Boston Housing Dataset Analysis

This repository contains code and analysis for exploring the Boston Housing Dataset. The dataset contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.




Dataset Description

The dataset includes 506 samples and 14 attributes, including:

CRIM: per capita crime rate by town
ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: proportion of non-retail business acres per town
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX: nitric oxides concentration (parts per 10 million)
RM: average number of rooms per dwelling
AGE: proportion of owner-occupied units built prior to 1940
DIS: weighted distances to five Boston employment centers
RAD: index of accessibility to radial highways
TAX: full-value property-tax rate per $10,000
PTRATIO: pupil-teacher ratio by town
B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black people by town
LSTAT: % lower status of the population
MEDV: Median value of owner-occupied homes in $1000's
 


Analysis

Import Modules: Import necessary Python libraries including Pandas, NumPy, Seaborn, and Matplotlib.
Loading the Dataset: Load the Boston Housing Dataset from a CSV file and perform basic data exploration.
Preprocessing the Dataset: Check for and handle any missing values.
Exploratory Data Analysis: Visualize the dataset using box plots, distribution plots, and correlation matrices.
Data Normalization: Perform min-max normalization and standardization on selected columns.
Model Training: Train various regression models including Linear Regression, Decision Tree Regression, Random Forest Regression, Extra Trees Regression, and XGBoost Regression. Evaluate the models using mean squared error and cross-validation score.
Model Evaluation: Plot feature importance for tree-based models.
Conclusion: Summarize findings and discuss potential next steps or improvements.
Usage

You can run the Jupyter Notebook file Boston_Housing_Analysis.ipynb to reproduce the analysis.

Requirements

Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
