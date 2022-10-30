README

In order to use this notebook you must download 3 different datasets, keeping their original names upon downloading and moving them into the same directory as the notebook:

The RAW_us_confirmed_cases.csv file from the Kaggle repository of John Hopkins University COVID-19 data. This data is updated daily. This version was Collected on 10/30/22.
https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university

The CDC dataset of masking mandates by county. Note that the CDC stopped collecting this policy information in September 2021.
https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i

The New York Times mask compliance survey data.
https://github.com/nytimes/covid-19-data/tree/master/mask-use 

Running the notebook with create a visualization showing the total case count, 7 day average moving derivative of cases, and the periods in which masking policies were imposed in Denver Colorado from 05-2020 to 09-2021.

The Raw_us_confirmed_cases.csv data file is not modified in any way other than to pivot the table and remove some data not needed for visualization. 