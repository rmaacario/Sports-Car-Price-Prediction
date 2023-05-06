# Sports Car Price Prediction
This repository contains the code for the Sports Car Price Prediction project. The aim of this project is to build a machine learning model that predicts the price of sports cars based on various features such as engine size, horsepower, torque, and 0-60 MPH time.

# Data Preprocessing

The first step in any machine learning project is to prepare the data for analysis. In the Data Preprocessing section of the notebook, we perform the following tasks:

Remove commas from the Price (in USD) column and convert it to an integer.
Remove commas from the 0-60 MPH Time (seconds) column and convert it to a float.
Remove non-numeric characters from the Horsepower, Torque (lb-ft), and 0-60 MPH Time (seconds) columns and convert them to integers.
Segment the Engine Size (L) column into categories such as small, medium, and large.
Segment the Car Make column into categories such as luxury and non-luxury.
Remove the Car Model column as it is irrelevant for our analysis.
Exploratory Data Analysis

After the data preprocessing step, we perform some exploratory data analysis to gain insights into the data. We analyze the distribution of the target variable Price (in USD) and the relationship between the target variable and the other features.

Feature Engineering

In the Feature Engineering section of the notebook, we create some new features such as Horsepower per Liter, Torque per Liter, and Power to Weight Ratio. These features are calculated based on the existing features in the dataset and are expected to improve the performance of our machine learning model.

Machine Learning

In the Machine Learning section of the notebook, we train several machine learning models such as linear regression, decision tree regression, random forest regression, and gradient boosting regression. We evaluate the performance of each model using various metrics such as mean squared error, mean absolute error, and R-squared.

Conclusion

In conclusion, we were able to build a machine learning model that predicts the price of sports cars with a high degree of accuracy. We also gained some valuable insights into the relationship between the features and the target variable.
