# housing-price-prediction-ml
Machine learning regression project for predicting house prices using Python and scikit-learn.

# House Price Prediction using Machine Learning

## Project Overview

This project uses supervised machine learning regression models to predict house sale prices based on housing-related features such as house area, number of bedrooms, number of toilets, storeys, city, and renovation status.

The aim of this project was to build an end-to-end machine learning workflow, from data exploration and preprocessing to model training, model evaluation, hyperparameter tuning, and feature importance analysis.

## Dataset

The dataset contains housing records with features such as:

- House Area
- Number of Bedrooms
- Number of Toilets
- Storeys
- City
- Renovation Status
- Sale Price

## Machine Learning Workflow

The project followed these main steps:

1. Exploratory Data Analysis
2. Data Cleaning and Preprocessing
3. One-hot Encoding for Categorical Variables
4. Feature Scaling
5. Target Log Transformation
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning using Optuna
9. Feature Importance Analysis
10. Model Improvement

## Models Used

The following regression models were tested:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Final Model Performance

The improved Gradient Boosting Regressor achieved:

| Metric | Score |
|---|---:|
| MAE | 112,036 |
| RMSE | 155,817 |
| R² Score | 0.520 |

## Key Insights

- House area was the most influential predictor of house price.
- The number of toilets and renovation status also contributed meaningfully to price prediction.
- Gradient Boosting performed better than the simpler baseline regression models after tuning and feature refinement.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Optuna

## What I Learned

Through this project, I strengthened my understanding of regression modelling, feature engineering, model comparison, hyperparameter tuning, and interpreting machine learning results in a real-world pricing problem.
