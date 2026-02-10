# Medical-Insurance-cost-prediction-using-regression
Objective

The objective of this project is to implement, analyze, and compare various Linear Regression models to predict medical insurance charges based on personal and health-related attributes.
All regression models are implemented from scratch without using any pre-built machine learning algorithms.

Problem Statement

Given a dataset containing multiple input features such as age, BMI, number of children, and other attributes, the task is to predict the medical insurance cost (continuous target variable) using different linear regression techniques and evaluate their performance.

Dataset Description

Dataset Name: Medical Insurance Dataset

Source: Publicly available dataset (Kaggle)

Target Variable: charges (continuous)

Input Features Used:

age

bmi

children

(optional categorical features encoded numerically)

The dataset contains no missing values. Categorical variables were converted into numerical form using manual encoding.

Tools & Technologies Used

Python

Google Colab

NumPy (numerical computation)

Pandas (data handling)

Matplotlib & Seaborn (visualization)

No machine learning libraries (such as sklearn) were used for model implementation.

Methodology

The project follows a structured approach:

Part A: Exploratory Data Analysis (EDA)

Dataset loading and inspection

Summary statistics

Feature distribution plots

Correlation heatmap

Part B: Simple Linear Regression

Single feature used to predict insurance charges

Interpretation of slope and intercept

Part C: Multiple Linear Regression

Multiple input features used simultaneously

Model built using gradient descent

Part D: Polynomial Regression

Polynomial feature expansion to capture non-linear relationships

Performance comparison with linear regression

Part E: Regularization Techniques

Ridge Regression (L2 Regularization)

Lasso Regression (L1 Regularization)

Analysis of coefficient shrinkage and feature importance

Part F: Model Diagnostics

Residual vs predicted value plots

Validation of regression assumptions

Evaluation Metrics

The models were evaluated using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

All evaluation metrics were computed from scratch using NumPy.

Key Observations

Age and BMI show strong influence on insurance charges

Multiple linear regression performs better than simple linear regression

Polynomial regression improves model fit

Ridge regression stabilizes coefficients

Lasso regression helps identify less important features

Conclusion

This project demonstrates a complete end-to-end implementation of linear regression techniques without relying on pre-built machine learning algorithms. It provides a clear understanding of regression modeling, regularization, diagnostics, and performance evaluation.

Repository Contents

insurance_model.ipynb – Complete notebook with implementation

insurance.csv – Dataset used

README.md – Project documentation

Output plots and figures
