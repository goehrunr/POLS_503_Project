# Final Project Women Combatants

This contains replication materials for the POLS 503 project of Ryan Goehrung.


## Organization

In this repository is all necessry files to reproduce the development and analysis of a predictive model using an original data set on women's roles in 170 non-state armed groups engaged in civil war against state governments across the globe from 1947 to 2016. Most importantly is the original dataset itself as a csv file and an r-markdown document containing all necessary instructions for reproduction as well as interpretation and analysis of the data and results.

- `README.md`: This file, describing the content project.
- `Final_Project_Women_Combatants_503.Rmd`: The primary computational narrative for this project.
- `doc`: An R markdown analyses other than the primary computational narrative.
- `src`: Any R scripts (`.R`).
- `data`: This folder contains the original data set used in the analysis.
- `results`: Any outputs produced by scripts, e.g., datasets, tables, plots.


## Install

In order to rund this analysis, several r packages are required. Instructions to run the libraries are included in the r-markdown document, but they should be installed beforehand. The following code can be used to do so:

```
packages_used <- c("tidyverse", "readr", "broom", "texreg", "leaps")
install.packages(packages_used)
```

The necessary data set is included in this repository. No other data is necessary to download. Instructions for loading and preparing the data are found in the r-Markdown file.



## Build

The most important file for replication in this repository is the r-markdown file titled Final_Project_Women_Combatants_503. This r-markdown document contains all necesary instructions and documentation for replication. The original data set used for this analysis is found in the folder entitled data. The relevant csv file is titled Women_Combtantas_Data_r_503.

In order to replicate this analysis, simply open the r-markdown file titled `Final_Project_Women_Combatants_503.Rmd` and knit the file.
