 # :tropical_fish: Data from: Patterns of reef fish energy flow in a transitional zone 

This README file was generated on 2025/07/31 by Chia-Hung Eric Liu(ericchiahungliu@gmail.com). Knit the fish_flow.Rmd to generate html and extract R code (Latest update on 2025/08/5)

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
   
-------------------------------------------------------------

## DESCRIPTION OF THE DATA AND FILE STRUCTURE

### DATA AND FILE OVERVIEW

1. **Description of the dataset**

This dataset is used to characterize fish energy flow in Taiwan. 

2. **File list**

There are four spreadsheets in the folder **Data**.

- File 1: Abiotic variable.csv; Description: Environmental conditions at each site.
- File 2: Benthic composition.csv; Description: Benthic composition at each study site

### METHODOLOGICAL INFORMATION

A detailed description of data acquisition and processing can be found in the published manuscript in Coral Reefs (https://doi.org/XXXX.XXXX).

### DATA-FILE SPECIFIC INFORMATION





---------------------------------


#### File: Abiotic variable.csv

##### Variables
The data of `Human_pop`, `PP`, and `SST` were from  online databases (see data sources), while the data of other variables were obtained from field survey.** 

* Site: Survey sites
* Human_pop: Human population
* PP: Primary production
* SST: Sea surface temperature
* SS: Stable substrate
* US: Unstable substrate
* S4: Fine-scale slope
* S32: Coarse-scale slope
* PROC4: Fine-scale profile curvature
* PLC4: Fine-scale planform curvature
* PROC32: Coarse-scale profile curvature
* PLC32: Coarse-scale planform curvature
* SC: Surface complexity

#### File: Benthic composition.csv

**Description: The data were used to analyze the biotic drivers of fish energy flows. All the data were obtained from field surveys using photo-quadrat methods.** 

##### Variables

* Transect: survey transects
* AL_artcal: Articulated calcareous algae
* AL_corfol: Corticated foliose algae
* AL_cormac: Corticated macrophyte algae
* AN_encrusting: Encrusting anemone
* AS_eresin: Erect single ascidian
* CB_filamentous: Filamentous cyanobacteria
* CCA: Crustose coralline algae
* HC_arborescent: Arborescent hard coral
* HC_bushy: Bushy hard coral
* HC_column: Column hard coral
* HC_encrusting: Encrusting hard coral
* HC_foliose: Foliose hard coral
* HC_massive: Massive hard coral
* HC_tabular: Tabular hard coral
* OC_arborescent: Arborescent octocoral
* OC_bushy: Bushy octocoral
* OC_clustered: Clustered octocoral
* OC_digitate: Digitate octocoral
* OC_encrusting: Encrusting octocoral
* OC_lobate: Lobate octocoral
* OC_massive: Massive octocoral
* SG: Seagrass
* SP_encrusting: Encrusting sponge
* SP_massive: Massive sponge
* SP_branching: branching sponge
* Turf: Turf algae
* ZO_encrusting: Encrusting zoantharian
* boulss: Boulder (stable substrate)
* limess: Limestone (stable substrate)
* rockss: Rock (stable substrate)
* rubbus: Rubble (unstable substrate)
* sandus: Sand (unstable substrate)
* siltus: Silt (unstable substrate)
* other_life: Other life
* other: Other non-living things

#### File: Global fish metric.csv

**Description: The data were obtained from Reef Life Survey database in Seguin R. et al. (2022) and used as a global standard for comparison with our data. The variables were extracted from the `RLS_transect_info.text` and evaluated using the `raw_data.Rdata`, `traits.RData` and `calc_prod_rfishprod.R script`.** 

##### Variables

* SurveyID: Transect ID in Reef Life Survey
* SiteCode: Site code in Reef Life Survey
* Country: Survey countries
* Depth: Survey depths
* Family: Fish family
* Genus: Fish genus
* Species: Fish species
* Size: Observed fish total length
* Num: The number of fish
* sstmean: Mean sea surface temperature
* a: Fish bayesian length-weight growth coefficient
* b: Fish bayesian length-weight growth coefficient
* MaxSizeTL: Maximum recorded fish total length
* Area: Surveyed area of each transect (500 m^2)
* Biomass: Fish biomass of one corresponding individual 
* Kmax: The standardized fish growth coefficient
* somatic_G: The somatic biomass growth of one corresponding individual
* Md: The predicted fish mortality rates
* Growth_iter: The average somatic growth of one corresponding individual across 100 iterations following survival simulations

#### File: Taiwan fish metric.csv

**Description: The data were used to evaluate fish energy flow metrics.** 

##### Variables

* Region: Survey regions
* Site: Survey sites
* Transect: Survey transects
* Family: Fish family
* Genus: Fish genus
* Species: Fish species
* Length: Observed fish total length
* Comment: Comments written while labeling fish in stereo videos. Cf: fish species that is hard to be correctly identified to species level. S: fish schools. Five or six individuals were measured and averaged to represent the lengths of all individuals within the entire school. The number behind "S" denotes different fish schools in each transect, resetting to 1 at the start of each new transect.
* a: Fish bayesian length-weight growth coefficient
* b: Fish bayesian length-weight growth coefficient
* MaxSizeTL: Maximum recorded fish total length
* Diet: Fish diet. HerDet: herbivorous detritivore; HerMac: macroalgae feeder; Plktiv: planktivore; Omnivr: omnivore; InvSes: sessile invertebrate feeder; InvMob: mobile invertebrate feeder; FisCep: piscivore. 
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

**Data sources**

*  Global fish metric.csv: Seguin, R., Mouillot, D., Cinner, J. E., Stuart Smith, R. D., Maire, E., Graham, N. A., McLean, M., Vigliola, L., & Loiseau, N. (2022). Towards process-oriented management of tropical reefs in the anthropocene. *Nature Sustainability*, *6*(2), 148–1571. https://doi.org/10.1038/s41893-022-00981-x
*  Abiotic variable.csv
    + Human_pop (human population): Center for International Earth Science Information Network - CIESIN - Columbia University. (2018). Gridded Population of the World, Version 4 (GPWv4): Population Count Adjusted to Match 2015 Revision of UN WPP Country Totals, Revision 11 *NASA Socioeconomic Data and Applications Center (SEDAC)*. https://doi.org/10.7927/H4PN93PB
    + PP (primary production): European Union-Copernicus Marine Service. (2022). Global Ocean Colour (Copernicus-GlobColour), Bio-Geo-Chemical, L4 (monthly and interpolated) from Satellite Observations (1997-ongoing) [dataset]. *Mercator Ocean International*. https://doi.org/10.48670/MOI-00281
    + SST (sea surface temperature): Liu, G., Heron, S. F., Eakin, C. M., Muller-Karger, F. E., Vega-Rodriguez, M., Guild, L. S., De La Cour, J. L., Geiger , E. F., Skirving, W. J., & Burgess, T. F. (2014). Reef-scale thermal stress monitoring of coral ecosystems: new 5-km global products from NOAA Coral Reef Watch. *Remote Sensing*, *6*(11), 11579–11606. https://doi.org/10.3390/rs61111579
