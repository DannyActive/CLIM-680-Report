# Assessing Rainfall Variability and ENSO Influence on African Precipitation

by: Daniel A. Adjei
---


Introduction
---

The variability of rainfall exhibited on both spatial and temporal scales (Ball et al., 2019) is of interest to farmers and water resource managers in Africa. As the most discriminant climatic parameter in the tropics, rainfall is used in determining climatic changes in a geographical area by determining long time series in precipitation variability (Sadiq et al., 2020). Many studies over the years have employed various approaches in estimating rainfall variability including the use of the Rainfall Anomaly Index, a method known for its unique ability in describing drought incidence in the African Sahel since the end of the 1960s. Developed by Van Rooy (1965), RAI employs a ranking procedure to assign magnitudes of positive and negative precipitation anomalies (Keyantash and Dracup, 2002), making use of a simple normalization procedure. While precipitation in Africa is known to be driven by local-scale phenomena, including the monsoonal flow associated with the movement of the Intertropical Convergence Zone (ITCZ), global-scale phenomena such as the El-Niño Southern Oscillation (ENSO), a quasi-periodic warming of the sea surface waters in the central and eastern tropical Pacific Ocean influence precipitation in Africa. In this study, the variability of rainfall in Africa will be assessed in addition to investigating the impact of the ñino3.4 index on the rainfall. Analysis conducted in the study include but not limited to monthly averaged precipitation climatology, annual averaged precipitation climatology spanning the temporal domain (1990-2019), anomaly computation and composites.

Data
---

The dataset used in this project:

### Cru TS Precipitation Dataset 

The Climate Research Unit Time Series (CRU TS) dataset is a gridded dataset with a spatial resolution of 0.5 by 0.5 degree based on a spatially complete analysis of records of more than 4000 individual weather stations. Variables included in this dataset are monthly fields of precipitation, daily maximum and minimum temperatures, and cloud cover for 1901-2022. In this report, the monthly precipitation variable is used to compute the monthly and annual average climatology and the annual anomaly. 

[Link to dataset description](https://climatedataguide.ucar.edu/climate-data/cru-ts-gridded-precipitation-and-other-meteorological-variables-1901)

### El Niño Southern Oscillation (Niño3.4) Index 

Monthly mean sea surface temperature dataset computed as the Niño3.4 index, spanning 1990 to 2019, is used to calculate composites for El-Niño, La Nina, and Neutral phases, evaluating the impact of each phase on precipitation in Africa. 

![Niño3.4 index (with warming & cooling signals)](figures/Niño3.4 phases.png)


[Link to NCAR niño indices description](https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni)

Results and Analysis
---

### Project Notebook on Github

A collection of jupyter notebooks used for this analysis can be be found in my CLIM680-Report directory via [Analysis:](https://github.com/DannyActive/CLIM680-Report) . The python notebook [RAI](https://github.com/DannyActive/CLIM680-Report/blob/main/RAI.ipynb) includes a manual function for computing the Rainfall Anomaly Index (RAI). All notebooks are labeled and commented.

# Conda environment 
The [climate.yml](climate.yml) file provides the conda environment for the successful execution codes used in this study.




