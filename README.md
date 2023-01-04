# Project name - 

Heart Failure Prediction 

# Background - 

Cardiovascular diseases (CVDs) accounts for 31% of all deaths worldwide. Four out of five CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under the age of 70 years. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease. People with CVDs or at high risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management, wherein a machine learning model can be very helpful. 
This is a pipeline written in Jupyter notebook to understand and compare the best prediction model of heart diseases. The heart disease dataset is obtained from the following website - https://www.kaggle.com/fedesoriano/heart-failure-prediction. This dataset was created by combining five different independent heart datasets over 11 common features. It is the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:
- Cleveland: 303 observations
- Hungarian: 294 observations
- Switzerland: 123 observations
- Long Beach VA: 200 observations
- Stalog (Heart) Data Set: 270 observations

Total: **1190 observations, Duplicated: 272 observations

Thus, the final dataset used in this project has **918 observations. 

# Running the code - 

Within the Zip file, the "heart.csv" file contains the final dataset. 
The Jupyter notebook "Heart Failure Prediction.ipynb" contains the code for dataset analysis and prediction models. It has the following list of contents - 

1. Importing packages
2. Loading data
3. Data Cleaning and Wrangling
4. Exploratory Data Analysis (EDA)
  - Analysis of categorical columns
  - Analysis of numerical columns
  - Analysis of the target column – HeartDisease
5. Prediction of Heart Disease using K-nearest neighbours (KNN) model
6. Prediction of Heart Disease using Logistic Regression model
7. Comparing models
8. Conclusion 

Note: The Jupyter notebook itself further contains various headings, subheadings, notes, and comments (followed by #) to help navigate and run the code in order, without errors. 


# Future work - 

The prediction models used is in this project are K-nearest neighbours (KNN) and Logistic Regression model. A comparison of these with other models such as Random Forest Classifier, Gradient boosting Classifier, Decision Tree Classifier, and SVC, might be able to provide a better heart disease prediction accuracy score. 

