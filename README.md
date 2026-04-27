# Residential Energy Forecasting Using Explainable AI

## Project Overview
This project develops a short-term residential energy forecasting framework using historical smart meter datasets. It applies machine learning models to predict household energy consumption and uses Explainable AI techniques to interpret the results.

## Objectives
1. Analyze residential energy consumption patterns using historical smart meter datasets.
2. Develop and evaluate a short-term energy forecasting framework using Linear Regression, Random Forest, and XGBoost.
3. Apply Explainable AI techniques, including SHAP and LIME, to identify key drivers of energy consumption.

## Datasets
This project uses three open-source datasets:
- Appliances Energy Prediction Dataset
- Individual Household Electric Power Consumption Dataset
- London Smart Meter Dataset

Due to memory limitations, the London dataset may be processed using a selected subset of CSV files.

## Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## Explainable AI
- SHAP for global feature importance
- LIME for local individual prediction explanations

## Evaluation Metrics
- MAE
- RMSE
- R² Score

## Execution Instructions
1. Install the required libraries:
```bash
pip install -r requirements.txt