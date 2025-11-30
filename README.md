# EDS-223: [Homework 4]([https://eds-223-geospatial.github.io/assignments/HW3.html](https://eds-223-geospatial.github.io/assignments/HW4.html))

### Suitable Aquaculture Zones by West Coast EEZ

This repository contains the analyses and visual outputs from three data sources to evaluate site suitability for species specific aquaculture on the U.S. West Coast. NOAA's Coral Reef Watch data was used to determine sea surface temperature suitability. Gridded bathymetry data from the General Bathymetric Chart (GEBCO) of the Oceans were used to determine depth suitability. Marine EEZ data categorized zonal grouping in analysis.

## Data Access

Data was publicly available and accessed from NOAA, GEBCO, and Marineregions.org

## Author: Nathalie Bonnet

Instructor: Annie Adams

Teaching Assistant: Ale Vidal Meza

## Folders and Files
.gitignore: contains instructions for the IDE to not track data folder

aquaculture_analysis.html: web page output of quarto document

aquaculture_analysis.qmd: quarto file with all scripting 

README.md: project and setup information
## Contents
```
│   .gitignore
│   .Rhistory
│   aquaculture_analysis.html
│   aquaculture_analysis.qmd
│   eds-223-aquaculture.Rproj
│   README.md
├───aquaculture_analysis_files
│   
└───data
```
## References

| Data | Citation | Sources |
|-------------------------------|-------------------|---------------------------|
| Coral Reef Watch: National Environmental Satellite, Data, and Information Service | *NOAA Coral Reef Watch*. NOAA Coral Reef Watch Daily 5km satellite coral bleaching heat stress SST anomaly product (version 3.1). https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php | <https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php> |
| General Bathymetric Chart of the Oceans: Global ocean and land terrain models | *Gridded bathymetry data*. GEBCO. https://www.gebco.net/data-products/gridded-bathymetry-data#area | <https://www.gebco.net/data-products/gridded-bathymetry-data#area> |
| Marineregions.org: EEZ boundaries | *EEZ boundaries.* Marine regions. https://www.marineregions.org/eez.php | <https://www.marineregions.org/eez.php> |
