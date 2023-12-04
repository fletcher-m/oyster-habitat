# Finding Suitable Oyster Habitat in U.S. west coast EEZ zones. 
This repository analyzes suitable oyster habitat among EEZ regions of the US west coast

## About
This repository contains one R markdown file, 'oyster_habitat.Rmd' that analyzes the area of each of the 5 west coast EEZ regions that would be considered suitable habitat for oysters. The idea would be to find the EEZ containing the most amount of suitable space and prioritize that zone for oyster fishing. 

## Visualization
After some raster wrangling, during which I took a series of steps in order to make both rasters compatible and able to be used together, I plotted the area along the west coast that fit my parameters for water temperature and depth. 

## Highlights
 
  - Data wrangling and exploration with `tidyverse`
  - Geospatial data wrangling with `sf` and `terra`
  - Map making with `Tmap` and `GGPlot`
  - Creating and customizing spatial plot

## Data
The sea surface temperature data can be accessed here (I used data from 2008 through 2012: https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php
The water depth data can be accessed here: https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area
EEZ zone data can be accessed here https://www.marineregions.org/eez.php. All data was accessed on December 1, 2023.
