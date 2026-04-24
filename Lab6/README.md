# Lab6 – House Price Prediction using Linear Regression

This project demonstrates a complete data analysis and machine learning workflow for predicting house prices using a Linear Regression model.

## Overview

In this lab, I performed data exploration, preprocessing, and model building on a housing dataset. The goal was to understand the data and build a model that can predict house prices based on numerical features.

## Steps Performed

### 1. Data Loading

* Imported the dataset from Kaggle
* Loaded it using pandas and explored its structure

### 2. Exploratory Data Analysis (EDA)

* Checked dataset info and summary statistics
* Visualized relationships using:

  * Pairplot
  * Distribution plots
  * Correlation heatmap
* Identified skewness in the price variable

### 3. Data Preprocessing

* Removed unnecessary categorical columns
* Applied log transformation (`log1p`) to handle skewed price values
* Selected relevant numerical features

### 4. Train-Test Split

* Split the dataset into training and testing sets (70% / 30%)

### 5. Model Building

* Trained a Linear Regression model using the training data

### 6. Prediction & Evaluation

* Generated predictions on the test set
* Evaluated the model using:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)
* Visualized:

  * Actual vs Predicted values
  * Residual distribution

### 7. Model Interpretation

* Examined the intercept and coefficients
* Interpreted how features like house size and number of bathrooms affect price

## Results

The model achieved moderate performance. It was able to capture general trends in the data, but its accuracy was affected by outliers and the variability in house prices.

## Conclusion

This lab provided a clear understanding of the full machine learning pipeline, including data exploration, preprocessing, model training, evaluation, and interpretation. The results show that while Linear Regression is effective for basic prediction, performance can be improved with better feature engineering or more advanced models.

## Dataset

* House Prices Dataset (Kaggle)
