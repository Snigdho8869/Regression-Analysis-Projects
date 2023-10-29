# Salary Prediction Regression Analysis Project

This project is focused on predicting salaries using regression analysis. It involves cleaning and preprocessing data, exploring feature engineering, and building regression models. The dataset is split into a training set and a test set for model evaluation.

## Data Preprocessing

1. Handling missing values in the 'Rating', 'Founded', and 'Salary' columns.
2. Grouping job titles into broader categories.
3. Categorizing job seniority.
4. Converting salary data to a consistent format.
5. Feature engineering for company size, revenue, job location, and more.
6. Encoding categorical variables.

## Regression Models

Several regression models are implemented and evaluated, including:

- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression
- LightGBM Regression
- K-Nearest Neighbors (KNN) Regression
- Voting Regressor

## Neural Network Model

A neural network model is developed using Keras and TensorFlow for regression analysis.

## Model Evaluation

Models are evaluated using Mean Squared Error (MSE), Normalized Root Mean Squared Error (NRMSE), and R-squared (R2) scores.


## Requirements

- Python
- Libraries such as pandas, numpy, scikit-learn, matplotlib, Keras, TensorFlow, and more.


## Results

|  Model | Mean Squared Error (MSE) | Normalized Root Mean Squared Error (NRMSE) | R-squared (R2) Score |
|----------|----------|----------|----------|
| Logistic Regression | 683.02 | -26.135 | 0.275 | 
| RandomForest Regressor | 176.814 | -13.297 | 0.812 |
| GradientBoosting Regressor | 232.049 | -15.233 | 0.754 |
| XGBoost Regressor| 128.434 | -11.333 | 0.864 |
| LightGBM Regressor | 183.422 | -13.543 | 0.805 |
| K-Nearest Neighbors (KNN) Regression | 137.711 | -11.735 | 0.854 |
| Voting Regressor | 123.769 | -11.125 | 0.869 |
| DNN Model | 29.921 | -5.47 | 0.968 |


