README

PROJECT DESCRIPTION:
------------------------------------------------------
For this capstone project Partly Parrots are building a predictive model to forecast the Zillow Rental Index (ZRI) with public data sets. 
The model is built on zipcode/monthly granularity. 
Feature selection was done with data sets looking at top 10 metro areas and later expanded the scope to all zipcodes of the United States.
The features are selected by running separate Lasso cross validation models with ACS and IRS data sets. 
Except for features from the two main data sets, monthly data was also dummified as well as metro areas.
The base model is built by multiple linear regression. 
Additionally, the team hopes to investigate the influence of wildfires on rental price. 
Initial data exploration suggests we use PM2.5, Ozone and the difference between the two metrics to predict the trend in rent after controlling the macro-economic aspects.


DATA SOURCE:
-------------------------------------------------------
ACS: Google Big Query
IRS: https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi
ZRI: https://www.zillow.com/research/data/
Air Quality Index: https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual


