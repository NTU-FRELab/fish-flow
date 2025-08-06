 # :tropical_fish: Data from: Patterns of reef fish energy flow in a transitional zone 

This README file was generated on 2025/07/31 by Chia-Hung Eric Liu (ericchiahungliu@gmail.com). Knit the fish_flow.Rmd to generate html and extract R code (Latest update on 2025/08/5)

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

    * Site: Survey sites. Some sites are abbreviated as follows:
      
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
    * Transect: Survey transects at each site. The first four characters represented the survey sites, while the last two characters represented the transect 1 to 5 at the corresponding sites. The abbreviations of sites:
      
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
    * SurveyID: Transect ID in Reef Life Survey
    * SiteCode: Site code in Reef Life Survey
    * Country: Survey countries
    * Depth: Survey depths. Unit: meter.
    * Family: Fish family
    * Genus: Fish genus
    * Species: Fish species
    * Size: Observed fish total length. Unit: Centimeter.
    * Num: The number of observed fish
    * sstmean: Mean sea surface temperature: Unit: &deg;C.
    * a: Fish bayesian length-weight growth coefficient
    * b: Fish bayesian length-weight growth coefficient
    * MaxSizeTL: Maximum recorded fish total length. Unit: Centimeter.
    * Area: Surveyed area of each transect. Unit: m<sup>2</sup>.
    * Biomass: Fish biomass of one corresponding individual 
    * Kmax: The standardized fish growth coefficient
    * somatic_G: The somatic biomass growth of one corresponding individual. Unit: Gram.
    * Md: The predicted fish mortality rates
    * Growth_iter: The average somatic growth of one corresponding individual across 100 iterations following survival simulations. Unit: Gram.

**File 4: *Taiwan fish metric.csv***

1. Number of variables/columns: 19

2. Number of cases/rows: 14497

3. Missing data codes: None
   
4. Variable List
    * Region: Survey regions
    * Site: Survey sites
    * Transect: Survey transects
    * Family: Fish family
    * Genus: Fish genus
    * Species: Fish species
    * Length: Observed fish total length. Unit: Centimeter.
    * Comment: Comments written while labeling fish in stereo videos. Cf: fish species that is hard to be correctly identified to species level. S: fish schools. Five or six individuals were measured and averaged to represent the lengths of all individuals within the entire school. The number behind "S" denotes different fish schools in each transect, resetting to 1 at the start of each new transect.
    * a: Fish bayesian length-weight growth coefficient
    * b: Fish bayesian length-weight growth coefficient
    * MaxSizeTL: Maximum recorded fish total length. Unit: Centimeter.
    * Diet: Fish diet. HerDet: Herbivorous detritivore; HerMac: Macroalgae feeder; Plktiv: Planktivore; Omnivr: Omnivore; InvSes: Sessile invertebrate feeder; InvMob: Mobile invertebrate feeder; FisCep: Piscivore. 
    * Position: Fish living position relative to reefs. Bnth: benthic; BtPl: benthopelagic; Pelg: pelagic; Dw: reef-dewelling; As: reef-associated
    * sstmean: Mean sea surface temperature
    * Biomass: Fish biomass
    * Kmax: The standardized fish growth coefficient 
    * somatic_G: The somatic growth of fish biomass
    * Md: The predicted fish mortality rates
    * Growth_iter: The average somatic growth across 100 iterations following survival simulations

***

**Code/software**

The R software is required, along with the following packages to run the script: `tidyverse`, `vegan`, `glmmTMB`, `emmeans`, `ggpubr`, `DHARMa`, `performance`.

**Data sources and references**

Center for International Earth Science Information Network - CIESIN - Columbia University (2018) Gridded Population of the World, Version 4 (GPWv4): Population Count Adjusted to Match 2015 Revision of UN WPP Country Totals, Revision 11 *NASA Socioeconomic Data and Applications Center (SEDAC)*. https://doi.org/10.7927/H4PN93PB

European Union-Copernicus Marine Service (2022) Global Ocean Colour (Copernicus-GlobColour), Bio-Geo-Chemical, L4 (monthly and interpolated) from Satellite Observations (1997-ongoing) [dataset]. *Mercator Ocean International*. https://doi.org/10.48670/MOI-00281

Liu G, Heron SF, Eakin CM, Muller-Karger FE, Vega-Rodriguez M, Guild LS, De La Cour JL, Geiger EF, Skirving WJ, Burgess TF (2014) Reef-scale thermal stress monitoring of coral ecosystems: new 5-km global products from NOAA Coral Reef Watch. *Remote Sensing*, *6*(11), 11579–11606. https://doi.org/10.3390/rs61111579

Seguin R, Mouillot D, Cinner JE, Stuart Smith RD, Maire E, Graham NA, McLean M, Vigliola L, Loiseau N (2022) Towards process-oriented management of tropical reefs in the anthropocene. *Nature Sustainability*, *6*(2), 148–1571. https://doi.org/10.1038/s41893-022-00981-x

