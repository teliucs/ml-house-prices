# House Price Prediction

This project focuses on predicting house sale prices using machine learning techniques. It is based on the Kaggle dataset [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) and showcases data preprocessing, modeling, and model evaluation.

## Project Overview

The goal of this project is to build predictive models for house prices and evaluate their performance using regression metrics. Both numeric-only features and categorical features (via encoding) are considered. Multiple models are compared to highlight differences in accuracy and robustness.

## Features

- **Data Exploration:** Distribution analysis, correlation heatmaps, feature importance.
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature selection.
- **Models Implemented:**
  - Linear Regression
  - Random Forest Regression
  - K-Nearest Neighbors Regression
  - Support Vector Regression
  - Gradient Boosting Regression
- **Model Evaluation:** RMSE, MAE, R² metrics; scatter plots of Actual vs Predicted; residual analysis.
- **Advanced Evaluation:** Binned error matrix to visualize under/overestimations in price ranges.

## Repository Structure
house-price-prediction/
│
├── data/ # Original datasets (train.csv, test.csv)
├── notebooks/ # Jupyter notebooks with analysis and models
├── requirements.txt # Python libraries required
├── .gitignore # Ignored files/folders (venv, pycache, etc.)
└── README.md # Project description
