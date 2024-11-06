# Data from: Contrasting energy flow associated with tropical and subtropical reef fish assemblages

---

This README file was generated on 2024/10/30 by Chia-Hung Eric Liu(ericchiahungliu@gmail.com). Knit Data_Analysis_Script.Rmd to generate html and extract R code. (Latest update on 2024/10/30)

1. Author Information

First author name: Mr. Chia-Hung Eric Liu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan.

Second author name: Dr. Lauriane Ribas-Deulofeu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan; Ocean Center, National Taiwan University, Taipei 10617, Taiwan.

Third author name: Mr. Meng-Hsin Morris Wu. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan

Four author name: Prof. Yi-Jay Chang. Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan

Fifth & corresponding author name: Prof. Vianney Denis Affiliation: Institute of Oceanography, National Taiwan University, Taipei 10617, Taiwan; Ocean Center, National Taiwan University, Taipei 10617, Taiwan. Email: vianneydenis@ntu.edu.tw

[UNDER REVIEW]
***

### File List
#### File: Abiotic\_factor.csv

**Description: The data were used to present the environmental conditions of each research site and analyze the extrinsic drivers of fish energy flows. The data of Human_pop, PP, PAR and SST were from different online database (see data sources), while the data of remained variables were obtained from field survey.** 

##### Variables

* Site: Survey sites
* Human_pop: Human population
* PP: Primary production
* PAR: Photosynthetically active radiation
* SST: Sea surface temperature
* SS: Stable substrate
* US: Unstable substrate
* S4: Fine scale slope
* S32: Rough scale slope
* PROC4: Fine scale profile curvature
* PLC4: Fine scale planform curvature
* PROC32: Rough scale profile curvature
* PLC32: Rough scale planform curvature
* SC: Surface complexity

#### File: Biotic\_factor.csv

**Description: The data were used to analyze the intrinsic drivers of fish energy flows. All the data were obtained from field surveys using photo-quadrat methods.** 

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
* SP_branching: Repent branching sponge
* Turf: Turf algae
* ZO_encrusting: Encrusting zoantharian

#### File: Taiwan\_fish\_metric.csv

**Description: The data were used to evaluate fish energy flow metrics.** 

##### Variables

* Region: Survey regions
* Site: Survey sites
* Transect: Survey transects
* Family: Fish family
* Genus: Fish genus
* Species: Fish species
* Length: Observed fish total length
* Comment: Comments written while labeling fish in stereo videos. Cf: fish species that is hard to be correctly identified to species level. S: fish schools. Five or six individuals were measured and averaged to represent the lengths of all individuals within the entire school. The number behind S indicates different fish schools in each transect, and the number will reorder from 1 in new transect.
* a: Fish bayesian length-weight growth coefficient
* b: Fish bayesian length-weight growth coefficient
* MaxSizeTL: Maximum recorded fish total length
* Diet: Fsih diet
* Position: Fish living position relative to reefs
* sstmean: Mean sea surface temperature
* Biomass: Fish biomass
* Kmax: The standardized fish growth coefficient 
* somatic_G: The somatic growth of fish biomass
* Md: The predicted fish mortality rates
* Fate: The predicted tomorrow's destiny of the fish. True indicates the fish will survive, while false indicates the fish will die. 

#### File: Seguin\_world\_fish\_metric.zip

**Description: The data were obtained from Reef Life Survey database in Seguin R. et al. (2022) and used as a global standard for comparison with our data. The data were compressed into a zip file and would automatically unzipped in the R script. The variables were extracted from the `RLS_transect_info.text` and evaluated using the `raw_data.Rdata`, `traits.RData` and `calc_prod_rfishprod.R script`.** 

##### Variables

* SurveyID: Transect ID in Reef Life Survey
* SiteCode: Site code in Reef Life Survey
* Country: Survey countries
* Depth: Survey depths
* Family: Fish family
* Genus: Fish genus
* Species: Fish species
* Size: Observed fish total length
* sstmean: mean sea surface temperature
* a: Fish bayesian length-weight growth coefficient
* b: Fish bayesian length-weight growth coefficient
* MaxSizeTL: Maximum recorded fish total length
* Area: Surveyed area of each transect (500 m^2)
* Kmax: The standardized fish growth coefficient 
* Md: The predicted fish mortality rates
* Fate: The predicted tomorrow's destiny of the fish. True indicates the fish will survive, while false indicates the fish will die. 
* Biom: Total fish biomass in each transect
* Prod: Productivity (i.e. total fish somatic growth in each transect). If the fish species was predicted to be dead tomorrow, the productivity is zero.

***

**Code/software**

R software is required, and the packages `tidyverse`, `vegan`, `ggpubr`, `multcompView`, `rstatix`, `glmmTMB`, `DHARMa`, `gridExtra`, `usdm`, `conflicted` need to be installed to run the script.

**Data sources**

* Seguin\_world\_fish\_metric.zip: Seguin, R., Mouillot, D., Cinner, J. E., Stuart Smith, R. D., Maire, E., Graham, N. A., McLean, M., Vigliola, L., & Loiseau, N. (2023). Towards process-oriented management of tropical reefs in the anthropocene. Nat SustainNature Sustainability, 6:148–1571-10. https://doi.org/10.1038/s41893-022-00981-x
*  Abiotic\_factor.csv
    + human_pop (human population): Center for International Earth Science Information Network - CIESIN - Columbia University. (2018). Gridded Population of the World, Version 4 (GPWv4): Population Count Adjusted to Match 2015 Revision of UN WPP Country Totals, Revision 11 NASA Socioeconomic Data and Applications Center (SEDAC). https://doi.org/10.7927/H4PN93PB
    + PP (primary production): European Union-Copernicus Marine Service. (2022). Global Ocean Colour (Copernicus-GlobColour), Bio-Geo-Chemical, L4 (monthly and interpolated) from Satellite Observations (1997-ongoing) [dataset]. Mercator Ocean International. https://doi.org/10.48670/MOI-00281
    + PAR (photosynthetically active radiation): NASA Goddard Space Flight Center, O. E. L., Ocean Biology Processing Group. (2017). MODIS-Aqua Level 3 Mapped Photosynthetically Available Radiation Data Version R2018.0 [dataset]. NASA Ocean Biology Distributed Active Archive Center. https://doi.org/10.5067/AQUA/MODIS/L3M/PAR/2018
    + SST (sea surface temperature): Liu, G., Heron, S. F., Eakin, C. M., Muller-Karger, F. E., Vega-Rodriguez, M., Guild, L. S., De La Cour, J. L., Geiger , E. F., Skirving, W. J., & Burgess, T. F. (2014). Reef-scale thermal stress monitoring of coral ecosystems: new 5-km global products from NOAA Coral Reef Watch. Remote Sensing, 6:(11), 11579–-11606. https://doi.org/10.3390/rs61111579
