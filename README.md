# House-Price-Prediction

The aim of this project is to identify the suitable model to make the prediction for the house price with given significant predictor variables and used a supervised learning technique.

The data-set is available on Kaggle: https://www.kaggle.com/prasadperera/the-boston-housing-dataset/data

# Data-set examination
The Boston Housing Dataset

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

# Data-set pre-processing

The heat-map showed the correlation of each variable with another. The darker colour means the relationship between any two variables are strongly correlated and lighter colour means they have almost no relationship.

# Model training

The XGBoost model will be used in this project. XGBoost stands for eXtreme Gradient Boosting. XGBoost is fast and dominates structured or tabular datasets on classification and regression predictive modeling problems.

# Summary

After the result comparison, I still need to put more effort to improve the model. The result reflects that some of the valuable data might not yet to be discovered from the dataset. Probably need to review all the missing data, outliers, also, spend more time on data analysis and multicollinearity issue.

# Working enviroment
Google Colab
Python 3.8
xgboost
sklearn
XGBRFRegressor
