Wine Quality Prediction

Overview

This project aims to predict the quality of wine based on various features such as acidity, residual sugar, chlorides, and more. It involves data preprocessing, exploratory data analysis, handling class imbalance, and training different machine learning models to make predictions.

Dataset

The dataset used in this project is winequality.csv, containing information about different types of wine and their respective quality ratings.

Requirements

Python 3.x
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn
Imbalanced-learn
Usage

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/wine-quality-prediction.git
Navigate to the project directory:
bash
Copy code
cd wine-quality-prediction
Install the required dependencies:
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:
Copy code
jupyter notebook wine_quality_prediction.ipynb
Workflow

Data Loading: Load the dataset winequality.csv.
Data Preprocessing: Handle missing values, encode categorical features, and perform feature scaling if necessary.
Exploratory Data Analysis: Visualize the data using box plots and distribution plots to understand the distribution and relationship between variables.
Correlation Analysis: Generate a correlation matrix heatmap to identify the relationships between features.
Input Split: Split the data into input features (X) and target variable (y).
Class Imbalance Handling: Use SMOTE to address class imbalance in the target variable.
Model Training: Train various machine learning models such as Logistic Regression, Decision Tree, Random Forest, and Extra Trees Classifier.
Model Evaluation: Evaluate the performance of each model using accuracy and cross-validation score.
Results

Logistic Regression: Accuracy - 33.23%, CV Score - 33.10%
Decision Tree: Accuracy - 80.17%, CV Score - 75.34%
Random Forest: Accuracy - 87.63%, CV Score - 82.61%
Extra Trees Classifier: Accuracy - 89.30%, CV Score - 83.63%
