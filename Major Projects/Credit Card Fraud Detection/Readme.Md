Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning algorithms. The dataset used contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions.


Table of Contents

Installation
Usage
Dataset
Preprocessing
Exploratory Data Analysis
Model Training
Class Imbalancement
Installation



Navigate to the project directory:
bash

cd credit-card-fraud-detection
Run the Jupyter Notebook:
bash

jupyter notebook
Open and execute the Credit_Card_Fraud_Detection.ipynb notebook.
Dataset

The dataset used in this project (creditcard.csv) contains the following columns:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.
V1-V28: Features obtained through PCA transformation.
Amount: Transaction amount.
Class: 1 for fraudulent transactions, 0 otherwise.
Preprocessing


The dataset is preprocessed as follows:


Null value check.

Standard scaling of numerical features.

Train-test split.

Exploratory Data Analysis



Exploratory data analysis includes:


Distribution of classes.

Distribution plots for each feature.

Correlation matrix heatmap.

Model Training


Three machine learning models are trained and evaluated:

Logistic Regression
Random Forest Classifier
XGBoost Classifier
Class Imbalancement

Class imbalancement is addressed using Synthetic Minority Over-sampling Technique (SMOTE). The models are trained and evaluated again after balancing the classes.

