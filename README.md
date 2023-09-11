# House Price Prediction Project

## Overview

This project aims to predict house prices using a regression model trained on a house price dataset. The goal is to build a regression model that can accurately predict the price of a house based on various features. We will follow a structured pipeline, including data preprocessing, model selection, and evaluation.

## Dataset

The dataset used in this project is the House Price Dataset. It contains information about various houses, including features like square footage, number of bedrooms, number of bathrooms, and other relevant attributes. 

### Features

- `Square Footage`: Total square footage of the house.
- `Number of Bedrooms`: Number of bedrooms in the house.
- `Number of Bathrooms`: Number of bathrooms in the house.
- `Year Built`: Year the house was built.
- `Lot Size`: Size of the lot in square feet.
- ...

### Target Variable

- `Price`: Price of the house.

## Preprocessing

### Data Procuring

The dataset was obtained from [source] and consists of [format or structure]. It was loaded using [code snippet] and initial exploration was conducted to understand its structure.

### Data Cleaning

We performed data cleaning to handle missing values, outliers, and any anomalies that could affect the model's performance. 

### Feature Selection

After a careful analysis, we selected `Square Footage`, `Number of Bedrooms`, `Number of Bathrooms`, `Year Built`, and `Lot Size` as the most relevant features for building our regression model.

### Splitting Data

The dataset was split into training and testing sets using a random split with an 80% training and 20% testing ratio.

## Model Selection

We chose to use a Random Forest regressor for this regression problem due to its ability to handle non-linear relationships and robustness to overfitting.

## Cross-Validation

To ensure unbiased testing, we implemented k-fold cross-validation with 5 folds.

## Building the Regressor

The Random Forest regressor was implemented using the following hyperparameters:
- `n_estimators`: 100
- `max_depth`: 10
- `min_samples_split`: 2

## Evaluation

We evaluated the model's performance using the following metrics:

- Mean Absolute Error (MAE): 
- Mean Squared Error (MSE): 
- R-squared (R²): 

## Results and Conclusion 

In conclusion, we have successfully built a regression model using Random Forest to predict house prices. 
