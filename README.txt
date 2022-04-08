Predicting California's Wildfires
By Janzen Hui
April 2022

Purpose: Utilizing machine learning models to classify California's wildfire - Supplementary documentation information
Files uploaded to Google Drive can be accessed here: https://drive.google.com/drive/folders/1d4INYMjh01rvRdqlNtB5A5Ilv9zFw_3q?usp=sharing

__________
Technical Report: 
Uploaded to GitHub

"Capstone Report - Janzen Hui.pdf"

__________
Submission Datasets:
This includes the unprocessed data, scrapped data and cleaned datasets. 
The 'Submission Datasets' Zip folder was uploaded to Google drive and contain the followin files: 

Unprocessed weather station data: "df_stations.csv"
Unprocessed weather station API information: https://et.water.ca.gov/Rest/Index

Unprocessed wildfire data: "USA_Forest_Fires.csv"
Unprocessed Wildfire data can be found here: https://www.fs.usda.gov/rds/archive/Catalog/RDS-2013-0009.5
Wildfire column attributes: https://www.fs.usda.gov/rds/archive/products/RDS-2013-0009.5/_metadata_RDS-2013-0009.5.html

Unprocessed scrapped weather data:https://cimis.water.ca.gov/Default.aspx
Weather data: "Daily Weather 1992-2018.zip"

__________
Jupyter Notebooks (in order of opening):
Uploaded to GitHub

"Capstone 1 - Data Wrangling.ipynb"
"Capstone 2 - Modeling.ipynb"

_________
Fitted Models:
The 'Fitted Models' Zip folder was uploaded to Google drive with the following .pkl files

Logistic Regression Model, F1 Scoring: "LR_f1_grid.pkl"
Logistic Regression Model with PCA, F1 Scoring: "LR_PCA_f1_grid.pkl"
Decision Tree Model, F1 Scoring: "DT_f1_grid.pkl"
Random Forest, Randomized Search Model, F1 Scoring: "RF_f1_grid.pkl"
Random Forest, Grid Search Optimized Model, F1 Scoring: "RF_f1_best_grid.pkl"
XGBoost, Randomized Search Model, F1 Scoring: "XG_f1_grid.pkl"
XGBoost, Grid Search Optimized Model, F1 Scoring: "XG_f1_best_grid.pkl"
__________
Jupyter Notebook Environments:
The 'Environments' zip folder was was uploaded to Google drive with the following text files

Boosting environment: 'boosting_requirements.txt'
Timeseries ennvironment: 'timeseries_requirements.txt'

__________
Miscellaneous Files: 
The following miscellaneous was uploaded to Google drive with the following files:

Tableau files containing wildfire locations in California:
"Capstone Graphs - Janzen Hui.twb"

Exported image of wildfire locations in California from Tableau:
"Location of California's Largest Wildfires.png"
