# ENVS-193DS_spring-2025_final
Final exam for Data Science in Environmental Studies (ENVS193DS) - Spring 2025 


### General Information 

This project showcases the skills and methods developed in the Data Science in Environmental Studies course. Through four key problems, we critically evaluate how studies use statistics to communicate findings, practice data wrangling on large datasets, and recreate a graph from a past study. We also test generalized linear models in a study examining how distance from the forest edge influences Swift Parrot occupancy in nesting boxes.

Additionally, the project includes a reflection on an affective visualization that we refined based on feedback from peers during the workshop in Week 9. These insights were incorporated into the final version, which was presented during the Week 10 workshop.


### Packages 

```

library(tidyverse) # general use 

library(gt) # for summary table

library(janitor) # cleaning data frames 

library(here) # file organization 

library(readxl) # reading excel files 

library(MuMIn) # model selection

library(DHARMa) # to check diagnostics from the model

library(fs) # allows you to make a tree of the data structure

```

### Data and File Information 

**Problem 1** uses examples from the paper:

Saleh, D., & Joseph D. (2021). Concentrations, Loads, and Associated Trends of Nutrients Entering the Sacramento–San Joaquin Delta, California. *San Francisco Estuary and Watershed Science.* 10.15447/sfews.2021v19iss4art6.

**Problem 2** uses the dataset:

Kui, L. (2024). Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3 [Dataset]. *Environmental Data Initiative,* https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84.

**Problem 3** uses the dataset:

Stojanovic, Dejan et al. (2021). Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird [Dataset]. *Dryad,* https://doi.org/10.5061/dryad.83bk3j9sb

**and article:** 

Stojanovic, D., Owens, G., Young, C.M., Alves, F. and Heinsohn, R. (2021). “Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird.” *Restoration Ecology,* 29(3), https://doi.org/10.1111/rec.13319



File Structure: 

```
├── ENVS-193DS_spring-2025_final.Rproj
├── README.md
├── code
│   ├── ENVS-193DS_spring-2025_final.html
│   ├── ENVS-193DS_spring-2025_final.qmd
│   └── ENVS-193DS_spring-2025_final_files
│       ├── figure-html
│       └── libs
│           ├── bootstrap
│           │   ├── bootstrap-icons.css
│           │   ├── bootstrap-icons.woff
│           │   ├── bootstrap.min.css
│           │   └── bootstrap.min.js
│           ├── clipboard
│           │   └── clipboard.min.js
│           └── quarto-html
└── data
    ├── SST_update.csv
    └── occdist.csv

```


### Rendered Output 
The rendered output is [here](https://ethan-mathews24.github.io/ENVS-193DS_spring-2025_final/code/ENVS-193DS_spring-2025_final.html)









