In this repository, aim is to perform the Exploratory Data Analysis (EDA) on ESG risk data and automate the data collection, preprocessing and conversion of data to approprate GEOJSON format.

## Purpose of the Exploratory Data Analysis

In this repository, I have performed exploratory data analysis on ESG risk variables to identify if the data fits the requirement mentioned below -
  1. Data needs to be geo-spatial and covering the European region.
  2. Data should have a time series and is a futuristic data (need to have projection for next 5, 10, 50 years)
  3. Identify the useful and redundant variables.
  4. Ensure that variables have S.I. units, if not perform the necessary transformation.
  5. Merge individual files to a one master file.

After, preocessing the data I have tried to convert the files in NetCDF format to GeoJSON format.

References -
- Temperature and Precipitation data - https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-hydrology-meteorology-derived-projections?tab=form
- Wildfire Data - https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-tourism-fire-danger-indicators?tab=overview
- Global Sea Level Change - https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-water-level-change-indicators-cmip6?tab=overview
