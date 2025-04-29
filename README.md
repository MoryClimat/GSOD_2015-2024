# GSOD_2015-2024 – Daily Meteorological Data for Senegal

**Description:**  
This repository contains a `.RData` file named `data2.RData`, which aggregates daily meteorological observations from **12 synoptic stations across Senegal** for the period **2015–2024**.  
The data were collected from the **Global Surface Summary of the Day (GSOD)** database, managed by the **National Centers for Environmental Information (NCEI)**: [www.ncei.noaa.gov](https://www.ncei.noaa.gov).

**Dataset content:**
- **Period:** 2015–2024
- **Coverage:** Senegal (12 synoptic stations nationwide)
- **Meteorological variables:**
  - Daily maximum temperature (**TMAX**)
  - Daily minimum temperature (**TMIN**)
  - Dew point temperature (**DEWP**)
  - Relative humidity (**RH**)
  - Daily precipitation (**PRCP**)
  - Mean wind speed (**WDSP**)

**Data format:**
- R object: **data2** stored in a `.RData` file
- Type: `data.frame`
- Each row represents one date-station pair
- Columns include: Station, Date, DEWP, PRCP, RH, TMAX, TMIN, WDSP

**Usage example:**
```r
load("data/data2.RData")
head(data2)
