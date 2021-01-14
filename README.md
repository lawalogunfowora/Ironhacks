# COVID-19 Data Science Challenge Fall 2020: Protect Purdue
## _Predicting the foot traffic at core places in Tippecanoe county_
In this project, the aim is to make a prediction of foot traffic for week 44 (Since Indiana recorded first COVID-19 case) in 1804 Point of Interests (POIs) in Tippecanoe County in Indiana, United States of America (a regression task). The data that is being used has been collected from the week 1 to week 43 and has is available as a BIgQuery project file. The schema of the tables that will be used for this project can be found here.

To start with, the six tables would be imported from the BigQuery project and stored as a pandas DataFrame. Then, Exploratory Data Analysis (EDA) would be carried out on the data to better understand their relationships for feature selection for the modeling task. For this challenge, some of the various models I used were:

Arima
Random Forest
LightGBM
Catboost
The result presented in this report was obtained using catboost. This report visualized the effectiveness of the policies taken during the fall in five poi locations that reported the highest cases of the virus.
