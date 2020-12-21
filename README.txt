README

PROJECT DESCRIPTION:
------------------------------------------------------
In the capstone project we are trying to bulid a predictive model to forecast the Zillow Rental Index(ZRI) with public data sets. 
The model is built on zipcode/monthly granularity. 
We started our feature selection with data set of top metro areas and expand the scope to all zipcodes of the United States.
The features are selected by running separate Lasso cross validation models with ACS and IRS data sets. 
Except for features from the two main data sets, we also used dummified month information plus dummified metro areas.
The base model is built by multiple linear regression. 
We also hope to investigate the influence from wildfires on rental price. 
The initial data exploration suggests we use PM2.5, Ozone and the difference between the two metrics to predict the trend in rent after controlling the macro-economic aspects.


DATA SOURCE:
-------------------------------------------------------
ACS: Google Big Query
IRS: https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi
ZRI: https://www.zillow.com/research/data/
Air Quality Index: https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual


