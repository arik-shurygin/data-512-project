README

In order to use this notebook you must download 3 different datasets, keeping their original names upon downloading and moving them into the same directory as the notebook:

The RAW_us_confirmed_cases.csv file from the Kaggle repository of John Hopkins University COVID-19 data. This data is updated daily. This version was Collected on 10/30/22.
https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university

Note: This dataset is too large to push to the repository, so it is not included at initial pull!

The CDC dataset of masking mandates by county. Note that the CDC stopped collecting this policy information in September 2021.
https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i

The New York Times mask compliance survey data.
https://github.com/nytimes/covid-19-data/tree/master/mask-use 

Running the project_part_1_visualization notebook with create a visualization showing the total case count, 7 day average moving derivative of cases, and the periods in which masking policies were imposed in Denver Colorado from 05-2020 to 09-2021.

Running the project_part_2_crime notebook will generate insights about how crime changed in response to different measures implemented during the epedemic. In particular it looks at 3 hypothesis:
1) The introduction of mask mandates increased public disorder crime by 15%, as those who actively broke masking mandates put strain on police forces
2) Lock down increased domestic abuse by 20% as victims no longer could avoid their abusive partners and were more likely to be stuck in the home with them.
3) Stimulus checks reduced robbery and financial crimes by up to 10%, as people could finally put food on their tables, even for a week or two

We consider the "begining" of the pandemic to be January 10th 2020 according to the CDC covid museum: https://www.cdc.gov/museum/timeline/covid19.html#:~:text=January%2010%2C%202020,%2DnCoV)%20on%20its%20website. 

Mask Mandate implementation dates were sourced from from: https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i

Lock Down orders were sourced from: https://covid19.colorado.gov/public-health-orders-and-executive-orders 

Stimulus check rollout dates were sourced from: https://www.fool.com/the-ascent/personal-finance/stimulus-checks/#:~:text=March%2027%3A%20The%20CARES%20Act,around%205%20million%20per%20week.

Crime data was pulled from the City of Denver Open Data Catalog which is a part of the NIBRS FBI reporting system. All data should be interpretted as research, and should not be taken as 100% accurate. This project was an exercise in using statistical thinking on a human centered data science project, it was limited in scope and therefore may not have fully correct insights or assumptions.