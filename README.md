# House Pricing Regression Analysis

## Overview

This project demonstrates the application of regression techniques to understand the correlation between various housing features and their impact on sale prices. Using a dataset (`HousePricingData.csv`), we analyze different factors like `GrLivArea`, `TotalBsmtSF`, `LotArea`, and others to predict house sale prices. The goal is to perform multiple regression analyses, interpret results (including R-squared, p-values, and coefficients), and evaluate model performance.

## Project Purpose

The purpose of this project is to apply regression techniques for:

- Identifying correlations between house features and sale prices.
- Creating models to predict sale prices and lot areas.
- Evaluating model effectiveness using statistical metrics like R-squared, p-values, and coefficients.
- Creating simplified models using regularization to improve prediction accuracy with fewer significant inputs.

## Deliverables

- A Jupyter Notebook (`ipynb`) containing all code, analysis, and explanations.
- A detailed interpretation of each regression model’s results, including the R-squared value, significance of inputs, and predictive performance.
- Generated plots (scatter plots with regression lines) to visually interpret relationships.
- A final regression model with reduced features based on significance testing.

## Tasks

1. **Regression between GrLivArea and SalePrice:**  
   Create a regression model to understand the relationship between `GrLivArea` and `SalePrice`. Analyze the model’s R-squared value and plot the data with the regression line.

2. **Regression between TotalBsmtSF and LotArea:**  
   Create a regression model for `TotalBsmtSF` and `LotArea`. Discuss the R-squared value and show the regression plot.

3. **Correlation Calculation:**  
   Calculate and interpret the correlation for the models created in tasks 1 and 2.

4. **Predicting SalePrice Using All Inputs:**  
   Build a regression model to predict `SalePrice` using all other features. Identify the three most and least significant inputs based on p-values.

5. **Predicting LotArea Using All Inputs:**  
   Build a regression model to predict `LotArea` and evaluate its effectiveness using R-squared. Identify significant and insignificant features.

6. **Simplified Model Using Regularization:**  
   Drop features with p-values greater than 0.05 and create a new model to predict `SalePrice`. Compare the performance with the original model and discuss which model you prefer.

7. **Prediction of SalePrice for New Data:**  
   Use the model from task 6 to predict `SalePrice` for three new data points and discuss if the predicted values make sense.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository to your local machine.
   
   ```bash
   git clone https://github.com/your-username/house-pricing-regression-analysis.git
