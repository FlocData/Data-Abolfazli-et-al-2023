# Data-Abolfazli-et-al-Mississippi

## Overview

This repository holds data associated with the paper by Abolfazli et al. on *Flocculation Characteristics of Suspended Mississippi River Mud Under Variable Turbulence, Water and Salt Sources, and Salinity: A Laboratory Study* currently in review at *Frontiers in Earth Science*.

The repository contains data and Jupyter notebook to explore the data and reproduce the plots presented in the paper.

## Data

The data is grouped into the following three folders:
1. *Data_01_Time_Series:* contains time series data for turbulent shear rate, salinity, concentration, and suspended particle size distribution statistics grouped by experiment number. The Jupyter notebook ```1_Data_TimeSeries_Explore.ipynb``` can be used to explore the data found in this folder.
2. *Data_02_Equilibrium:* Data contained in this folder pertains to individual size measurements and size statistics at equilibrium. The data can be explored with the notebook ```2_Data_Equilibrium_Explore.ipynb```
	- ```Equilibrium_Data.csv``` contains the tabulated equilibrium data extracted from the time series and used in many of the scatter plots in the paper.
	- ```d_mu_ASTM_seasalt.csv``` and ```d_mu_GoM_water.csv``` contain particle size distributions for individual minutes in the time series that were used produce the particle size distribution plots of floc sizes with ASTM sea salt and Gulf of Mexico water.
	- ```MS_insitu_withG.csv``` provides tabulated in situ data from Osborn et al. (2023).
3. *Data_03_NTU_SSC:* Contains average OBS recorded NTU values and corresponding suspended solids concentration measurements obtained through filtration, drying, and weighing.

## Figures 

All data figures from the paper can be reproduced using the data in the repository and the Jupyter notebooks:

1. ```3_PaperFigures_Timeseires.ipynb```(Figures 3 and 10)
2. ```4_PaperFigures_Equilibrium.ipynb``` (Figures 4, 6-9)

## References

Osborn, R., Dunne, K. B. J., Ashley, T., Nittrouer, J. A., and Strom, K. (2023). The flocculation state of mud in the lowermost freshwater reaches of the mississippi river: Spatial distribution of sizes, seasonal changes, and their impact on vertical concentration profiles. *Journal of Geophysical Research: Earth Surface*, 128(7):e2022JF006975.
