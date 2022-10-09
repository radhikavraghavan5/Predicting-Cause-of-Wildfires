# Analysis of Wildfire incidents from 2011 to 2015 in the US

## Abstract
This SQLite dataset includes Wildfires incident reports filed by various federal, state, and local fire organizations from period 2011 to 2015 obtained from [Kaggle - 1.88 Million US Wildfires](https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires) 


## Methods used

| Tools  |  Methodologies | 
| ------------- | ------------- | 
| Packages   |  `ggplot2`, `dplyr`, `readr`, `lubridate`,`tidygeocoder`, `forcats` |
| Tools  |  `relational data/joins`, `ggplot`, `data import`, `dates and times`, `geospatial vizualization`, `factors`|


## Data Description

The cleaned data set consists of 188,017 observations on the following 17 variables. 

| Column name     | Description      |   
| ------------- | ------------- | 
| `fire_year`    | Calendar year in which the fire was discovered or confirmed to exist.         | 
| `discovery_date`         |  Date on which the fire was discovered or confirmed to exist.        |
| `discovery_time`         |  Time of the day that the fire was discovered or confirmed to exist.        |
| `stat_cause_descr`        | Description of the (statistical) cause of the fire         | 
| `fire_size`         | Estimate of Acres of land burnt within the final perimeter of the fire  | 
| `fire_size_class`        | Code for fire size based on the number of acres within the final fire perimeter expenditures (A=greater than 0 but less than or equal to 0.25 acres, B=0.26-9.9 acres, C=10.0-99.9 acres, D=100-299 acres, E=300 to 999 acres, F=1000 to 4999 acres, and G=5000+ acres) 
| `latitude`  |  Latitude (NAD83) for point location of the fire (decimal degrees)  | 
| `longitude`   | Longitude (NAD83) for point location of the fire (decimal degrees)   | 
| `owner_descr`  |  Name of primary owner or entity responsible for managing the land at the point of origin of the fire at the time of the incident| 
| `cont_date`        | Date on which the fire was declared contained or otherwise controlled (mm/dd/yyyy where mm=month, dd=day, and yyyy=year)  | 
| `cont_time`         | Time of day that the fire was declared contained or otherwise controlled (hhmm where hh=hour, mm=minutes) | 
| `county`        | County, or equivalent, in which the fire burned (or originated), based on nominal designation in the fire report | 
| `state_abb`         | Two-letter code for the state in which the unit is located (or primarily affiliated) | 
| `disc_month`        | Month of the year   |
| `resolved_days`         | #Days taken to resolve the wildfire  | 
| `season`         | Season of the year - Summer, Spring, Fall, Winter   | 
| `state_name`         | Full name of the state  |
