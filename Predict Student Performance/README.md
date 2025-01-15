# Student Performance Prediction

This project aims to predict student performance using various machine learning models. The dataset contains student information and their corresponding grades.

## Project Overview

The main objectives of this project are:

1. Data preprocessing and exploration
2. Feature engineering and scaling
3. Model training and evaluation
4. Comparison of different machine learning algorithms

## Requirements

To run this project, you need the following libraries:

```
pandas
numpy
scikit-learn
xgboost
matplotlib
```

## Data

Dataset Link: [Predict Student Performance Dataset](https://www.kaggle.com/datasets/stealthtechnologies/predict-student-performance-dataset/data)

## Models

The following models are implemented and compared:

- Linear Regression
- Random Forest
- XGBoost
- Support Vector Regression (SVR)

## Evaluation Metrics

The models are evaluated using the following metrics:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R2) Score

## Usage

1. Load and preprocess the data
2. Split the data into training and testing sets
3. Scale the features using StandardScaler
4. Train and evaluate multiple models
5. Compare model performance using R2 scores
6. Identify the best performing model

## Results

The project includes a bar plot comparing the R2 scores of different models, allowing for easy visualization of model performance.

**Best Model:**

The Random Forest model performed the best for this dataset, achieving the highest R2 score compared to other models.

