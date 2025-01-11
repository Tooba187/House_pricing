Predicting House Prices Using the Boston Housing Dataset
Overview
This project involves building a regression model from scratch to predict house prices using the Boston Housing Dataset. The dataset includes various features such as crime rate, average number of rooms per dwelling, property tax rate, and others, to predict the median house price in the area.

The project implements three regression models:

Linear Regression
Random Forest
XGBoost
Each model is compared based on Root Mean Squared Error (RMSE) and R² metrics. Additionally, the importance of features for tree-based models is visualized.
Dataset
The California Housing Dataset is used, which is available from sklearn's datasets module. It contains 506 samples with 13 features for predicting housing prices.

Steps
1. Data Preprocessing
Normalization: All numerical features are normalized to bring them to the same scale.
Handling Categorical Variables: (In case of any categorical data present in real scenarios, but this dataset doesn't have them).
2. Model Implementation
a) Linear Regression (From Scratch)
Linear regression is implemented using the closed-form solution (Normal Equation).
b) Random Forest (From Scratch)
A custom implementation of the Random Forest algorithm using bootstrapping and decision trees. It uses an ensemble of decision trees to improve prediction accuracy.
c) XGBoost (From Scratch)
A basic version of the XGBoost algorithm is implemented using gradient boosting with decision trees.
3. Performance Comparison
The models are evaluated using two metrics:

Root Mean Squared Error (RMSE): Measures the difference between predicted and actual house prices.
R² (Coefficient of Determination): Indicates how well the model explains the variance of the target variable.
4. Feature Importance
For tree-based models (Random Forest and XGBoost), feature importance is visualized to show which features contribute the most to the prediction.
Results
The models will be compared using the following metrics:

Linear Regression: Provides a baseline for prediction accuracy.
Random Forest: Tends to perform better with nonlinear relationships and feature interactions.
XGBoost: Expected to yield the best performance due to its gradient boosting technique.
