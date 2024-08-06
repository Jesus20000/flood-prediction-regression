# Flood Prediction Regression

Welcome to the **flood-prediction-regression** repository! This project focuses on predicting the probability of flooding in a region based on various factors using regression models. The dataset is provided by the 2024 Kaggle Playground Series.

## Overview

The main goal of this project is to build and evaluate regression models to forecast flood probabilities. The workflow includes data exploration, preprocessing, and model training with XGBoost, CatBoost, and Linear Regression.

## Project Structure

- **`flood_prediction_regression.ipynb`**: Jupyter Notebook containing the complete workflow for data analysis, feature engineering, model training, and evaluation.

## Key Features

- **Data Loading and Exploration**: Load and explore training, testing, and sample submission datasets. Visualize and analyze the distribution of numerical features and detect outliers.
- **Data Preprocessing**: Handle missing values, check for multicollinearity, and perform feature engineering.
- **Model Training and Evaluation**: Train and evaluate XGBoost, CatBoost, and Linear Regression models. Visualize feature importance and assess model performance with various plots.
- **Submission Preparation**: Make predictions on the test dataset and prepare the final submission file.

## Requirements

Ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `xgboost`
- `catboost`
- `matplotlib`
- `seaborn`
- `statsmodels`

You can install the required libraries using `pip`:

```bash
pip install numpy pandas scikit-learn xgboost catboost matplotlib seaborn statsmodels
