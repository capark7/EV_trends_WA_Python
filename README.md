# EVCS Analysis Project

## Overview

Welcome to my Achievement 6 project for CareerFoundry's data analytics course. This repository showcases my journey through an advanced analytics project focused on Electric Vehicles (EV) and Electric Vehicle Charging Stations (EVCS) in Washington State.

The primary goal of this project was to explore the relationship between EV adoption and the growth of EVCS in different counties. While the main focus is on this analysis, it's important to note that some of the code and steps shared here may not directly relate to the core analysis project. This repository also served as a platform for me to practice my analytics skills and explore into machine learning techniques.

## Data

The analysis is based on the following datasets:
- `ev_PopHist.csv`: Dataset containing information about EV adoption and EVCS growth in different counties
- `WA_EVCS.csv`: Dataset containing information about EVCS in Washington State including opening dates.
- `wa PopCounty.csv`: Population data for each county used to estimate per capita values.

## Tools

The following Python libraries were used for this analysis:
- pandas: Data manipulation and analysis.
- numpy: Mathematical functions and array manipulation.
- matplotlib: Data visualization and plotting.
- seaborn: Data visualization with enhanced aesthetics.
- sklearn: Machine learning tools for regression analysis.
- pylab: Deprecated library for interactive scientific plotting.
- quandl: Library for financial, economic, and alternative data.
- statsmodels: Library for estimating and interpreting statistical models.
- scipy: Library for scientific and technical computing.
- folium: Library for interactive map visualizations.
- json: Library for working with JSON data.
- os: File and directory operations.
- warnings: Library for controlling warnings.

## Code

The main code files in this repository are:
- `6.1 Data Cleaning and Descriptive Analysis .ipynb`: Data cleaning, merging, and preparation.
- `6.2.1 Calculating new variables.ipynb`: Calculating new variables.
- `6.5 Unsupervised Machine Learning - Clustering.ipynb`: Unsupervised machine learning to cluster counties.
- `6.7 Statistical Hypothesis testing.ipynb`: Linear regresssion hypothesis testing and Linear regression modeling for High and Medium clusters.

## Resources

In addition to the code and data in this repository, the following resources were used for this analysis:
- [Alternative Fueling Station Locations](https://afdc.energy.gov/data_download): Source of EVCS data.
- [Electric Vehicle Population Size History By County](https://catalog.data.gov/dataset/electric-vehicle-population-size-history-by-county): Source of EV registration per county since 2017.
- [County-Level Data Set - Population Report](https://catalog.data.gov/dataset/county-level-data-sets): Source of county population data.
- [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data): Source of current information of EV registered in Washington State.
- [Rural Urban County Area Codes](https://www.ers.usda.gov/data-products/rural-urban-commuting-area-codes.aspx) : Source of county area.
- [Washington State County geoJSON data](https://cartographyvectors.com/map/1396-washington-state-counties): Source of GeoJSON infomations.

## Conclusion

The Tableau Story about this analysis can be found [here](https://public.tableau.com/app/profile/caroline.park/viz/WashingtonElectricVehicleAnalysis-final/Story).

This analysis explores the relationship between EV adoption and EVCS growth, clustering counties for further analysis, and developing predictive models for High and Medium clusters. Further analysis could include examining EV adopting and EVCS growth at a more detailed level then by county, and examining EVCS usage patterns to better understand factors affecting adoption.
