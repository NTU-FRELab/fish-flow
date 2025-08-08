 # :tropical_fish: Data from: Patterns of reef fish energy flow in a transitional zone 

This README file was generated on 2025/07/31 by Chia-Hung Eric Liu (ericchiahungliu@gmail.com). Knit the fish_flow.Rmd to generate html and extract R code (Latest update on 2025/08/08)

1. **Author Information**
   * First author
      * Name: Chia-Hung Eric Liu
      * Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan
   * Second author
      * Name: Lauriane Ribas-Deulofeu
      * Affiliation 1: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan
      * Affiliation 2: Ocean Center, National Taiwan University, Taipei 10617, Taiwan
   * Third author
      * Name: Meng-Hsin Morris Wu
      * Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan
   * Fourth author 
      * Name: Yi-Jay Chang
      * Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan
   * Fifth & corresponding author
      * Name: Vianney Denis
      * Affiliation 1: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan
      * Affiliation 2: Ocean Center, National Taiwan University, Taipei 10617, Taiwan. Email: vianneydenis@ntu.edu.tw
      * Email: [vianneydenis@ntu.edu.tw](mailto:vianneydenis@ntu.edu.tw)

2. **Date of data collection:** 2023

3. **Geographic location of data collection:** southern, eastern, and northern Taiwan, West Pacific

4. **Funding sources that supported the collection of the data:** Ocean Conservation Administration of Taiwan, Ministry of Science and Technology of Taiwan

5. **Recommended citation for this dataset:** Liu CHE, Ribas-Deulofeu L, Wu MHM, Chang YJ, Denis V (Forthcoming 2025). Data from: Patterns of reef fish energy flow in a transitional zone [Dataset]. Zenodo. https://doi.org/XXXX.XXXX
   
6. **Associated manuscript:** Liu CHE, Ribas-Deulofeu L, Wu MHM, Chang YJ, Denis V (Forthcoming 2025). Patterns of reef fish energy flow in a transitional zone. Coral Reefs. https://doi.org/XXXX.XXXX

\[The data set and the R script are available through Zenodo (https://doi.org/XXXXXX.XXXX) and the GitHub repository (https://github.com/NTU-FRELab/fish-flow.git) in order to replicate our analyses]
   
## DESCRIPTION OF THE DATA AND FILE STRUCTURE

### DATA AND FILE OVERVIEW

1. **Description of the dataset**

This dataset is used to characterize fish energy flow in Taiwan. 

2. **File list**

There are four spreadsheets in the folder **Data**.

- File 1: *Abiotic variable.csv*; Description: Environmental conditions at each site.
- File 2: *Benthic composition.csv*; Description: Benthic composition at each study transect.
- File 3: *Global fish metric.csv*; Description: Global reef fish data from Reef Life Survey (site level). 
- File 4: *Taiwan fish metric.csv*; Description: Taiwan reef fish data from our survey (transect level).
  
### METHODOLOGICAL INFORMATION

A detailed description of data acquisition and processing can be found in the published manuscript in Coral Reefs (https://doi.org/XXXX.XXXX).

### DATA-FILE SPECIFIC INFORMATION

**File 1: *Abiotic variable.csv***

1. Number of variables/columns: 13

2. Number of cases/rows: 26

3. Missing data codes: None

4. Variable List

    * Site: Survey sites. Some site abbreviations are as follows:
      
      | Abbreviation   | Full name        |
      |----------------|------------------|
      | GreenGrassland | Green Grass Land |
      | LionRock       | Two Lion Rock    |
      | HenRock        | Hen Rock         |
      | 825K           | 82.5K            |
   
    * Human_pop: Human population. Unit: Inhabitants km<sup>-2</sup>. Data from *Center for International Earth Science Information Network - CIESIN - Columbia University (2018)*.
    * PP: Primary production. Unit: mg m<sup>-2</sup>day<sup>-1</sup>. Data from *European Union-Copernicus Marine Service (2022)*.
    * SST: Sea surface temperature. Unit: &deg;C. Data from *Liu et al. (2014)*.
    * SS: Stable substrate. Unit: Mean proportion of stable substrate at each site. Data from our survey using photo-qurat methods.
    * US: Unstable substrate. Unit: Mean proportion of unstable substrate at each site. Data from our survey using photo-qurat methods.
    * S4: Fine-scale slope. Value of slope at a 4 cm resolution at each site. Data from our survey using photogrammetry methods.
    * S32: Coarse-scale slope. Value of slope at a 32 cm resolution at each site. Data from our survey using photogrammetry methods.
    * PROC4: Fine-scale profile curvature. Value of profile curvature at a 4 cm resolution at each site. Data from our survey using photogrammetry methods.
    * PLC4: Fine-scale planform curvature. Value of planform curvature at a 4 cm resolution at each site. Data from our survey using photogrammetry methods.
    * PROC32: Coarse-scale profile curvature. Value of profile curvature at a 32 cm resolution at each site. Data from our survey using photogrammetry methods.
    * PLC32: Coarse-scale planform curvature. Value of profile curvature at a 32 cm resolution at each site. Data from our survey using photogrammetry methods.
    * SC: Surface complexity. Value of surface complexity at a 1 cm resolution at each site. Data from our survey using photogrammetry methods.


**File 2: *Benthic composition.csv***

1. Number of variables/columns: 36

2. Number of cases/rows: 126

3. Missing data codes: None

4. Variable List
    * Transect: Survey transects at each site. The first four characters represent the survey site, and the last two characters indicate the transect number (1 to 5) within the site. Site abbreviations are as follows:
      
      | Abbreviation | Full name       |
      |--------------|-----------------|
      | Fenn         | Fenniaolin      |
      | Jiam         | Jiamuzi         |
      | Jihu         | Jihui           |
      | Jiqi         | Jiqi            |
      | Xins         | Xinshe          |
      | Chai         | Chaikou         |
      | Daba         | Dabaisha        |
      | Gong         | Gongguan        |
      | Guiw         | Guiwan          |
      | Shil         | Shilang         |
      | Ding         | Dingbaisha      |
      | Houb         | Houbihu         |
      | Jial         | Jialeshui       |
      | Leid         | Leidashih       |
      | Tiao         | Tiaoshi         |
      | 825K         | 82.5 K          |
      | Bito         | Bitou           |
      | Chao         | Chaojing        |
      | Long         | Longdong        |
      | Meiy         | Meiyanshan      |
      | Dong         | Dongchin        |
      | HenR         | Hen Rock        |
      | Gree         | Green Grass Land|
      | Lion         | Two Lion Rock   |
      | Yayo         | Yayo            |
    
    * AL_artcal: Proportion of articulated calcareous algae at each transect.
    * AL_corfol: Proportion of corticated foliose algae at each transect.
    * AL_cormac: Proportion of corticated macrophyte algae at each transect.
    * AN_encrusting: Proportion of encrusting anemone at each transect.
    * AS_eresin: Proportion of erect single ascidian at each transect.
    * CB_filamentous: Proportion of filamentous cyanobacteria at each transect.
    * CCA: Proportion of crustose coralline algae at each transect.
    * HC_arborescent: Proportion of arborescent hard coral at each transect.
    * HC_bushy: Proportion of bushy hard coral at each transect.
    * HC_column: Proportion of column hard coral at each transect.
    * HC_encrusting: Proportion of encrusting hard coral at each transect.
    * HC_foliose: Proportion of foliose hard coral at each transect.
    * HC_massive: Proportion of massive hard coral at each transect.
    * HC_tabular: Proportion of tabular hard coral at each transect.
    * OC_arborescent: Proportion of arborescent octocoral at each transect.
    * OC_bushy: Proportion of bushy octocoral at each transect.
    * OC_clustered: Proportion of clustered octocoral at each transect.
    * OC_digitate: Proportion of digitate octocoral at each transect.
    * OC_encrusting: Proportion of encrusting octocoral at each transect.
    * OC_lobate: Proportion of lobate octocoral at each transect.
    * OC_massive: Proportion of massive octocoral at each transect.
    * SG: Proportion of seagrass at each transect.
    * SP_encrusting: Proportion of encrusting sponge at each transect.
    * SP_massive: Proportion of massive sponge at each transect.
    * SP_branching: Proportion of branching sponge at each transect.
    * Turf: Proportion of turf algae at each transect.
    * ZO_encrusting: Proportion of encrusting zoantharian at each transect.
    * boulss: Proportion of boulder (stable substrate) at each transect.
    * limess: Proportion of limestone (stable substrate) at each transect.
    * rockss: Proportion of rock (stable substrate) at each transect.
    * rubbus: Proportion of rubble (unstable substrate) at each transect.
    * sandus: Proportion of sand (unstable substrate) at each transect.
    * siltus: Proportion of silt (unstable substrate) at each transect.
    * other_life: Proportion of other life (e.g., sea urchin and sea star) at each transect.
    * other: Proportion of other non-living things (e.g., shadow and trash) at each transect.

**File 3: *Global fish metric.csv***

1. Number of variables/columns: 19

2. Number of cases/rows: 278863

3. Missing data codes: None

4. Variable List
    * SurveyID: Transect ID in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * SiteCode: Site code in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * Country: Survey countries in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * Depth: Survey depths. Unit: meter. Data from *Seguin et al. (2022)*.
    * Family: Fish family identified in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * Genus: Fish genus identified in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * Species: Fish species identified in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * Size: Observed fish total length in Reef Life Survey. Unit: Centimeter. Data from *Seguin et al. (2022)*.
    * Num: The number of observed fish in Reef Life Survey. Data from *Seguin et al. (2022)*.
    * sstmean: Mean sea surface temperature. Unit: &deg;C.
    * a: Bayesian length-weight growth coefficient obtained from FishBase (a) *(Froese and Pauly 2025)*.
    * b: Bayesian length-weight growth coefficient obtained from FishBase (b) *(Froese and Pauly 2025)*.
    * MaxSizeTL: Maximum recorded fish total length at which observation was made in Reef Life Survey. Unit: Centimeter. Data from *Seguin et al. (2022)*.
    * Area: Surveyed area of each transect. Unit: meter<sup>2</sup>. Data from *Seguin et al. (2022)*.
    * Biomass: Biomass of an fish individual, calculated from its observed fish total length (i.e., `column: Size`) using Bayesian length-weight regression model: Biomass = a &times; TL<sup>b</sup>. TL: Fish total length. Unit: Gram.
    * Kmax: The standardized fish growth coefficient represents a theoretical growth coefficient (K) when the asymptotic length of the population equals the maximum length of the species. It was caculated using the `calc_prod_rfishprod` function developed by *Seguin et al. (2022)*, based on the `rfishprod` package *(Morais and Bellwood 2018)*.
    * somatic_G: The daily growing biomass of a fish individual, which was estimated using the von Bertalanffy growth model. Calculations were conducted using the `calc_prod_rfishprod` function developed by *Seguin et al. (2022)*, based on the `rfishprod` package *(Morais and Bellwood 2018)*. Unit: Gram.
    * Md: The predicted natural mortality rate, estimated using the model proposed by *Gislason et al. (2010)*. This model incorporateds the `observed fish total length` (i.e., column: `Size`), `maximum recorded total legnth` (i.e., column: `MaxSizeTL`), and `Kmax` (i.e., column: `Kmax`). Calculations were conducted using the `calc_prod_rfishprod` function developed by *Seguin et al. (2022)*, based on the `rfishprod` package *(Morais and Bellwood 2018)*.
    * Growth_iter: The average somatic growth across 100 iterations following survival simulations. The survival simulation used the predicted natural mortality rate (i.e., column: `Md`) as the probability in a Bernouli distribution, producing binary outcomes of 0 (death) or 1 (survival). The fate of each individual was simulated across 100 iterations, and the somatic growth (i.e., column: `somatic_G`) was multiplied by the fate matrix and averaged over all iterations. Unit: Gram.

**File 4: *Taiwan fish metric.csv***

1. Number of variables/columns: 19

2. Number of cases/rows: 14497

3. Missing data codes: None
   
4. Variable List
    * Region: Survey regions. Regions are abbreviated as follows:
      
      | Abbreviation | Full name     |
      |--------------|---------------|
      | NT           | North Taiwan  |
      | ET           | East Taiwan   |
      | GI           | Green Island  |
      | OI           | Otchid Island |
      | KT           | Kenting       |
      
    * Site: Survey sites. Some sites are abbreviated as follows:
      
      | Abbreviation   | Full name        |
      |----------------|------------------|
      | GreenGrassland | Green Grass Land |
      | LionRock       | Two Lion Rock    |
      | HenRock        | Hen Rock         |
      | 825K           | 82.5K            |
   
    * Transect: Survey transects. T1 to T5 represent the five transects deployed at each site.
    * Family: Fish family identified in our survey.
    * Genus: Fish genus identified in our survey.
    * Species: Fish species identified in our survey. Due to limitations in identification from blurred images, some individuals were only identified to the genus level and labeled as *sp*. These individuals may share similar body structure, life history traits, and feeding behavior, leading to comparable energy flows when analyzed under an individual age framework. Their Bayesian length-weight growth coefficients and maximum total length were averaged to estimate the energy flows for the fish genera.
        *  *Stegastes sp.*: Average parameters of *S. nigricans*, *S. albifasciatus*, and *Plectroglyphidodon fasciolatus*.
        *  *Acanthurus sp.*: Average parameters of *A. nigrofuscus*, *Ctenochaetus binotus*, and *C. striatus*.
    * Length: Observed fish total length, measured using stereo video systems. Unit: Centimeter.
    * Comment: Notes recorded during fish labeling in stereo videos.
        * Cf: Fish species that is hard to be correctly identified to species level.
        * S: Fish schools. Five or six individuals were measured and averaged to represent the lengths of all individuals within the entire school. The number behind "S" denotes different fish schools in each transect, resetting to 1 at the start of each new transect.
    * a: Bayesian length-weight growth coefficient (a). Data from curated FishBase data *(Froese and Pauly 2025)*.
    * b: Bayesian length-weight growth coefficient (b). Data from curated FishBase data *(Froese and Pauly 2025)*.
    * MaxSizeTL: Maximum recorded fish total length. Unit: Centimeter. Data from curated FishBase data *(Froese and Pauly 2025)* and the National Taiwan University Museum specimens.
    * Diet: Fish diets were divided into seven categories based on FishBase *(Froese and Pauly 2025)* and the dataset compiled by *Morais and Bellwood (2018)*. The dietary groups are abbreviated as follows: 
      
      | Abbreviation | Full name                   |
      |--------------|-----------------------------|
      | HerDet       | Herbivorous detritivore     |
      | HerMac       | Macroalgae feeder           |
      | Plktiv       | Planktivore                 |
      | Omnivr       | Omnivore                    |
      | InvSes       | Sessile invertebrate feeder |
      | InvMob       | Mobile invertebrate feeder  |
      | FisCep       | Piscivore                   |
       
    * Position: Relative position in the reef was categorized into six groups considering vertical (pelagic, benthopelagic, and benthic) and horizontal (reef dwelling and reef associated) components based on FishBase *(Froese and Pauly 2025)* and the dataset compiled by *Morais and Bellwood (2018)*. The positions are abbreviated as follows:
      
      | Abbreviation | Full name       |
      |--------------|-----------------|
      | Bnth         | Benthic         |
      | BtPl         | Benthopelagic   |
      | Pelg         | Pelagic         |
      | Dw           | Reef-dwelling   |
      | As           | Reef-associated |
      
    * sstmean: Mean sea surface temperature. Unit: &deg;C. Data from *Liu et al. (2014)*.
    * Biomass: Biomass of an fish individual, calculated from its observed fish total length (i.e., `column: Length`) using Bayesian length-weight regression model: Biomass = a &times; TL<sup>b</sup>. TL: Fish total length. Unit: Gram.
    * Kmax: The standardized fish growth coefficient represents a theoretical growth coefficient (K) when the asymptotic length of the population equals the maximum length of the species. It was estimated from `sea surface temperature`, `fish total length`, `diet`, and `living position relative to reefs` and calculated using `rfishprod` packages *(Morais and Bellwood 2018)*.
    * somatic_G: The daily growing biomass of a fish individual, which was estimated using the von Bertalanffy growth model. Calculations were conducted using the `calc_prod_rfishprod` function developed by *Seguin et al. (2022)*, based on the `rfishprod` package *(Morais and Bellwood 2018)*. Unit: Gram.
    * Md: The predicted fish mortality rates were predicted using the natural mortality model proposed by *Gislason et al. (2010)*, which used `observed fish total length` (i.e., column: `Length`), `maximum recorded total legnth` (i.e., column: `MaxSizeTL`), and `Kmax` (i.e., column: `Kmax`) for estimation.
    * Growth_iter: The average somatic growth across 100 iterations following survival simulations. The survival simulation used the predicted natural mortality rate (i.e., column: `Md`) as the probability in a Bernouli distribution, producing binary outcomes of 0 (death) or 1 (survival). The fate of each individual was simulated across 100 iterations, and the somatic growth (i.e., column: `somatic_G`) was multiplied by the fate matrix and averaged over all iterations. Unit: Gram.

***

**Code/software**

The R software is required, along with the following packages to run the script: `tidyverse`, `vegan`, `glmmTMB`, `emmeans`, `ggpubr`, `DHARMa`, `performance`.

**Data sources and references**

Center for International Earth Science Information Network - CIESIN - Columbia University (2018) Gridded Population of the World, Version 4 (GPWv4): Population Count Adjusted to Match 2015 Revision of UN WPP Country Totals, Revision 11 *NASA Socioeconomic Data and Applications Center (SEDAC)*. https://doi.org/10.7927/H4PN93PB

European Union-Copernicus Marine Service (2022) Global Ocean Colour (Copernicus-GlobColour), Bio-Geo-Chemical, L4 (monthly and interpolated) from Satellite Observations (1997-ongoing) [dataset]. *Mercator Ocean International*. https://doi.org/10.48670/MOI-00281

Froese R, Pauly D (2025) FishBase. www.fishbase.org. Accessed 14 February 2025

Gislason H, Daan N, Rice JC, Pope JG (2010) Size, growth, temperature and the natural mortality of marine fish. *Fish and Fisheries*, *11*(2), 149–158. https://doi.org/10.1111/j.1467-2979.2009.00350.x 

Liu G, Heron SF, Eakin CM, Muller-Karger FE, Vega-Rodriguez M, Guild LS, De La Cour JL, Geiger EF, Skirving WJ, Burgess TF (2014) Reef-scale thermal stress monitoring of coral ecosystems: new 5-km global products from NOAA Coral Reef Watch. *Remote Sensing*, *6*(11), 11579–11606. https://doi.org/10.3390/rs61111579

Morais RA, Bellwood DR (2018) Global drivers of reef fish growth. *Fish and Fisheries*, *19*(5), 874–889. https://doi.org/10.1111/faf.12297 

Seguin R, Mouillot D, Cinner JE, Stuart Smith RD, Maire E, Graham NA, McLean M, Vigliola L, Loiseau N (2022) Towards process-oriented management of tropical reefs in the anthropocene. *Nature Sustainability*, *6*(2), 148–1571. https://doi.org/10.1038/s41893-022-00981-x

