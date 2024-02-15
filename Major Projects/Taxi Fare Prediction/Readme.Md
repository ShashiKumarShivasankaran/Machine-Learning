Problem Statement
This case study is to predict the taxi fare for a taxi ride in New York City from a given pickup point to the dropoff location. Try Building Predictive Model Using various algorithm like Decision tree and Random Forest.
Data Definition
unique_id: Unique identifier - (string)
date_time_of_pickup: time when the ride started - (timestamp)
longitude_of_pickup: Longitude of the taxi ride from pickup point - (float) - (Numerical)
latitude_of_pickup: Latitude of the taxi ride from pickup point - (float) - (Numerical)
longitude_of_dropoff: Longitude of the taxi ride dropoff point - (float) - (Numerical)
latitude_of_dropoff: Latitude of the taxi ride dropoff point - (float) - (Numerical)
no_of_passenger: count of the passengers during the ride - (integer) - (Numerical)
amount: Fair for the taxi ride in dollar(target variable)
Table of Contents
Import Libraries
Set Options
Read Data
Prepare and Analyze the Data
4.1 - Understand the Data
4.1.1 - Data Type
4.1.2 - Feature Engineering
4.1.3 - Summary Statistics
4.1.4 - Missing Values
4.2 - Exploratory Data Analysis
4.2.1 - Peak hours
4.2.2 - Mean fare for each hour during weekdays and weekends
4.2.3 - Distribution of key numerical variables
Random Forest
5.1 - Random Forest Model
5.2 - Random Forest with GridSearchCV
Conclusion and Interpretation
