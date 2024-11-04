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


#### File: Abiotic\_factor.csv

**Description:** 

##### Variables

* Site: Research site
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

**Description:** 

##### Variables

* Transect: Transect
* AL_artcal:Articulated calcareous algae
* AL_corfol: Corticated foliose algae
* AL_cormac: Corticated macrophyte algae
* AN_encrusting: Encrusting anemone
* AS_eresin: Erect single ascidian
* CB_filamentous: Filamentous cyanobacteria
* CCA: Crustose coralline algae
* HC_arborescent:Arborescent hard coral
* HC_bushy:Bushy hard coral
* HC_column:Column hard coral
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

**Description:** 

##### Variables

* Region: Region
* Site: Site
* Transect: Transect
* Family: Fish family
* Genus: Fish genus
* Species: Fish species
* Length: Observed fish total length
* Comment: Comments written while labeling fish in stereo videos. Cf: fish species that is hard to be correctly identified to species level. S: fish schools. Five or six individuals were measured and averaged to represent the lengths of all individuals within the entire school. The number behind S indicates different fish schools in each transect, and the number will restart in new transect.
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

#### File: Seguin\_world\_fish\_metric.csv

**Description:** 

##### Variables

* SurveyID: Transect ID in Reef Life Survey
* SiteCode: Site code in Reef Life Survey
* Country: Surveyed country
* Depth: Surveyed depth
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


Code/software
What free or open software is needed to view your data? Describe the software, including versions and loaded packages that you used to run files, and the workflow that you used if the relationship of files to software is not clear. If code or scripts are included with your submission, describe them here.



Other publicly accessible locations of the data:

*

Data was derived from the following sources:

*
