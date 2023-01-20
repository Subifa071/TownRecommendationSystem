## Town Recommendation System

A basic town recommendation project for module **ST5014CEM Data Science For Developers**. 
>Year II Sem II Data Science Assignment

### Prerequisite
These are some main components required to run the project
1. The <a href="#download">Dataset</a>
2. [The Unarchiver](https://theunarchiver.com/) file archiver
3. [R](https://cran.r-project.org/bin/) and [RStudio](https://www.rstudio.com/products/rstudio/download/)

### Dependencies
You may need to install these dependencies in order to run the code.
```R
> install.packages("tidyverse")
> install.packages("lubridate")
> install.packages("ggthemes")
> install.packages("scales")
> install.packages("ggdark")
> install.packages("ragg")
> install.packages("fmsb")
```

### Instructions

1. Extract zip data inside the main project folder
2. Open the <b>Coursework.R</b> project file in RStudio
3. Install dependencies mentioned <a href="#dependencies">above</a>
4. Run src/00 Setup/00 Setup.R
5. Run src/00 Setup/01 Functions.R
6. Run all file consecutively inside src/01 Cleaning
7. You may run any other afterwards. :)

### Folder Structure
```
📁 HouseRecommendation
    - 📁 src
        - 📁 00 Setup
        - 📁 01 Clean
        - 📁 02 Graph
        - 📁 03 Model
        - 📁 04 Recom
        - 📁 99 Trash
    - 📁 data (after extraction)
        - 📁 clean
        - 📁 mydata
        - 📁 raw
    - 📄 .gitignore
    - 📄 Coursework.Rproj
```    

### Used Datasets Info
Dataset used or considered for this project
<details><summary>SHOW ME!</summary>
    
#### Core datasets
- [x] Houseprice (2019-2022)
- [x] Population (2011)
- [x] Crime (2019-2022)
- [x] School (2019-2021)
- [x] Broadband (2018)

    
#### Helper datasets
- [x] Postcode to LSOA(custom)
- [x] [Population](https://api.schoolworkspro.com/uploads/files/Population2011_1656567141570.csv) <i>accessible for SchoolWorksPro users only.</i>

 
> The tick signifies that the dataset is in use
 
</details>

### Datasets License Information ⚖
Many core datasets, such as crime, housing price, and school are 
provided under Open Government License. The bandwidth dataset is provided under the Ofcom 
license, and some helper data, such as Postalcode and Population.

