# California Housing Price Prediction

![Housing Price Prediction](https://miro.medium.com/v2/resize:fit:1200/0*NCO1DF14J42HEQWR.jpg)

## Overview

This project focuses on predicting housing prices in California using machine learning regression models. It includes data preprocessing, exploratory data analysis (EDA), model development, and evaluation.

## Steps

### 1. Import the Main Libraries

We start by importing the necessary libraries for data analysis and visualization:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Missingno
- os

### 2. Load the Dataset

We read the housing dataset from a CSV file and create a Pandas DataFrame for further analysis.

### 3. Exploratory Data Analysis (EDA)

- We inspect the dataset using head(), info(), and describe() to get an understanding of its structure and contents.

- EDA visualizations are performed to explore key features:
  - Distribution of ocean proximity categories.
  - Histograms for various features.
  - Scatter plot between median income and median house value.

- The project highlights potential issues, such as skewed data distributions and the importance of the "median income" feature.

### 4. Data Preprocessing

We address data issues and outliers:

- Handling missing values in the "total bedrooms" feature.
- Removing outliers from features like "total bedrooms," "households," and "population."
- Converting the "ocean proximity" column into numeric values using label encoding.

### 5. Model Development

Three regression models are implemented:

- **Linear Regression**: A basic linear regression model is trained on the preprocessed data.

- **Ridge Regression**: Ridge regression is applied with alpha = 0.9 for regularization.

- **Lasso Regression**: Lasso regression is applied with alpha = 0.9 for regularization.

### 6. Model Evaluation

For each model, we calculate the following evaluation metrics:

- **R-squared (r2_score)**: A measure of the model's performance.
- **Root Mean Squared Error (RMSE)**: A measure of the model's accuracy.
- **Mean Absolute Error (MAE)**: A measure of the average error.
- **Mean Absolute Percentage Error (MAPE)**: A measure of prediction accuracy.

### 7. Comparing Models

We compare the three regression models based on their r-squared scores and RMSE to assess their performance.

## Conclusion

This project provides insights into predicting California housing prices using various regression models. The detailed steps for data preprocessing, model development, and evaluation are outlined. The project can be used as a starting point for real estate price prediction tasks.
