# House Prices - Advanced Regression Techniques

This repository contains a solution for the Kaggle competition **[House Prices - Advanced Regression Techniques]([https://www.kaggle.com/c/house-prices-advanced-regression-techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/))**. The goal is to predict the final sale price of homes using various features of the property.

## Project Overview

The dataset includes 79 explanatory variables that describe almost every aspect of residential homes in Ames, Iowa. The task is to predict the price of each house using regression techniques and various machine learning models.

### Key Features:
- Data preprocessing and feature engineering to clean and optimize the dataset.
- Exploratory Data Analysis (EDA) to gain insights into the relationship between features and the target variable (`SalePrice`).
- Implementation of multiple machine learning models, including:
  - Linear Regression
  - Ridge Regression
  - RandomForestRegressor
  - GradientBoostingRegressor
  - XGBRegressor (XGBoost)
  - CatBoostRegressor (CatBoost)
  - LightGBM (Light Gradient Boosting Machine)
- Model evaluation using metrics such as Mean Squared Error (MSE) and cross-validation to find the best-performing model.

---

## Dataset

- **Training Data**: `train.csv`
- **Test Data**: `test.csv`

---

## Feature Engineering

To enhance model performance, the following features were engineered:

- **houseage**: Years since the house was built (`YrSold - YearBuilt`).
- **houseremodelage**: Years since the house was remodeled (`YrSold - YearRemodAdd`).
- **totalsf**: Total square footage (`1stFlrSF + 2ndFlrSF + BsmtFinSF1 + BsmtFinSF2`).
- **totalarea**: Living area + Basement area (`GrLivArea + TotalBsmtSF`).
- **totalbaths**: Combined bathroom count.
- **totalporchsf**: Combined porch areas.

---

## Exploratory Data Analysis

- Various visualizations (scatter plots, heatmaps) were used to understand relationships between features and `SalePrice`.
- Outliers were identified and removed based on certain feature thresholds to improve model accuracy.

---

## Models

Several machine learning models were implemented and compared to predict house prices. The top models used include:

- **Linear Regression**
- **Ridge Regression**
- **RandomForestRegressor**
- **GradientBoostingRegressor**
- **XGBRegressor** (XGBoost)
- **CatBoostRegressor** (CatBoost)
- **LightGBM**

Each model was fine-tuned using hyperparameter optimization and evaluated using cross-validation and mean squared error (MSE).

---

## Results

- **Log Transformation**: The target variable (`SalePrice`) was transformed using the natural log to handle skewness.
- The best-performing model was found to be [insert your best-performing model], which achieved an MSE of [your result] on the training data.

---

## Acknowledgements

- The dataset is provided by the Ames Housing dataset from Kaggle.
- Thanks to the contributors of the various libraries used in this project such as `scikit-learn`, `XGBoost`, `CatBoost`, and `LightGBM`.

---

## Contact

For any questions, feel free to reach out at irukaict@gmail.com.
