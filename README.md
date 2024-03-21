
# northsea_mpa_sust_fish

## The effects of marine protected areas on the sustainabillity of marine fish stocks under climate change

This repository contains the code for the project on the effects of Marine Protected Areas and sustainable fisheries in the north Sea published on the journal *NPJ Sustainabillity*.

Cheung, W. W. L., Palacios-Abrantes, J. and Roberts, S. M., 2024. Projecting contributions of marine protected areas to rebuild fish stocks under climate change. npj Ocean Sustainability, 3 (1), 11.

[![DOI](https://zenodo.org/badge/29789533.svg)](https://www.nature.com/articles/s44183-024-00046-w)


# Authors

- William W.L. Cheung^1^
- Juliano Palacios-Abrantes^1^
- Sarah Roberts^2^

# Affiliations

^1^Changing Oceans Research Unit, The University of British Columbia, Vancouver, BC, Canada  

^2^University of North Carolina at Chapel Hill, CITY, NC, United States

# Folder organization

- **Data**, this folder contains secondary data used in th project, it has three subfolders:
  - **mpa_scenarios**, these represent the random protection scenarios used in the project, 30% protected (`grid_30.csv`), 15% (`grid_15.csv`) and current protection (`grid_cm6point4.csv`)
  - **spatial**, any spatial data (i.e., shapefiles) needed for the research
  - **species**, species list analyized in this study
  - *Lon_Lat_DBEM.txt*, grid map of the world

- **Scrips**, this folder contains all scrips used in the present research
  - *pre_dbem.rmd*, this script was used to determine the MPA scenarios, the species to be analyzed and the re-allocation of fishing effort to surrounding protected cells
  - *post_dbem.rmd*, this script contains the post-modelling data analysis and production of project results

_This repository has been archived and is no longer updated. The master branch contains the most updated version_
