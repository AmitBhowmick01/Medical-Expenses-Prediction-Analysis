# **Medical Expenses Prediction**

This GitHub repository contains a Python implementation for predicting medical expenses using various regression models, including Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor. The goal is to provide a tool that can estimate medical costs based on certain attributes, helping individuals and healthcare providers plan and manage their expenses effectively.

## Introduction

Medical expenses can be a significant financial burden for individuals and families. This project aims to develop accurate prediction models that can estimate medical costs based on various factors such as age, BMI, smoker status, region, and number of children. By utilizing different regression algorithms, we provide users with multiple options to predict medical expenses and make informed decisions.


## Data

The data used for training and testing the prediction models is stored in the data directory. The dataset, named `medical_expenses.csv`, contains information about individuals' medical expenses and relevant attributes. It includes columns such as age, sex, BMI, number of children, smoker status, region, and medical charges.

## Models

This repository includes implementations of the following regression models:

- **Linear Regression:** This model fits a linear equation to the training data and predicts medical expenses based on the input attributes.

- **Random Forest Regressor:** This ensemble model combines multiple decision trees to make predictions. It can capture non-linear relationships and handle complex datasets.

- **Gradient Boosting Regressor:** This boosting algorithm builds an ensemble of weak prediction models in a sequential manner. It improves predictive accuracy by focusing on instances with larger errors.

## Results

After running the model scripts, the results will be displayed on the console. You can compare the performance of different models and evaluate their predictive capabilities based on relevant metrics such as `mean absolute error` (MAE), `mean squared error` (MSE), and `R-squared score`.