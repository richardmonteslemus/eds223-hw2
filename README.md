# HOLC Grade Environmental and Socioecomoic Injustice Analysis

This repository contains scripts used to analyze how HOLC grades are associated with several socioeconomic and environmental injustices in LA county. Some of these injustices analyzed include expected low income average, exposure to particulate matter average, low life expectancy average, and unequal bird biodiversity rates. 

**Repository Structure:**
```
├── data
│   ├── ejscreen
│   │   ├── ~$EJSCREEN_2023_BG_Columns.xlsx
│   │   ├── EJSCREEN_2023_BG_Columns.xlsx
│   │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
│   │   └── ejscreen-tech-doc-version-2-2.pdf
│   ├── gbif-birds-LA
│   │   ├── gbif-birds-LA.dbf
│   │   ├── gbif-birds-LA.prj
│   │   ├── gbif-birds-LA.shp
│   │   └── gbif-birds-LA.shx
│   └── mapping-inequality
│       └── mapping-inequality-los-angeles.json
├── eds223-hw2.Rproj
├── hw2.qmd
├── hw2.pdf
└── README.md
```
**/data:**
  - ejscreen: Environmental screen justice data with geospatial column.
  - gbif-birds-LA: Geospatial points for bird observation data in LA county. 
  - mapping-inequality: LA county HOLC grade with geospatial column.
    
**/eds-223-hw2.Rproj:**
  - R project space for analysis
    
**/hw2.qmd:**
  - Quarto document containing code and scripts for analysis
    
**/hw2.pdf:**
  - Output pdf with code and figures
    
**/README.md:**
  - README file

**Author:** [Richard Montes Lemus](https://richardmonteslemus.github.io/)

**Acknowledgement:** Bren School Master of Environmental Data Science EDS 223 homework 2 coursework materials 

Data can be accessed [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view)

**Language: R**

**Data Citation:**

**ejscreen:**
Public Environmental Data Partners, (2025, Oct). EJ Screen. Environmental Justice Screening and Mapping Tool. https://pedp-ejscreen.azurewebsites.net/

**gbif-birds-LA**:
GBIF. (n.d.). https://www.gbif.org/

**Bird biodiversity study:**
Ellis-Soto, D., Chapman, M. & Locke, D.H. Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nat Hum Behav 7, 1869–1877 (2023). https://doi.org/10.1038/s41562-023-01688-5

**mapping-inequality:**
Mapping inequality. Digital Scholarship Lab. (n.d.). https://dsl.richmond.edu/panorama/redlining/data

