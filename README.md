# House Price Prediction - Boston Housing Dataset

## Overview
This project implements a machine learning model to predict house prices using the Boston Housing Dataset. The implementation is done in Python using a Jupyter notebook, leveraging popular data science libraries.

## Dataset
The project uses the Boston Housing dataset which contains information about various features of houses in Boston. Key features include:
- rm: Average number of rooms per dwelling
- lstat: Percentage of lower status population
- ptratio: Pupil-teacher ratio by town
- medv: Median value of owner-occupied homes (target variable)

## Project Structure
- `housePricePred.ipynb`: Main Jupyter notebook containing the analysis
- `BostonHousing.csv`: Dataset file

## Implementation Steps
1. Data Loading and Preprocessing
    - Loading the dataset using pandas
    - Checking for missing values
    - Handling null values
2. Exploratory Data Analysis (EDA)
    - Distribution analysis of target variable
    - Feature distributions visualization
    - Feature correlation with house prices
    - Outlier detection and removal using boxplots
3. Model Development
    - Feature selection
    - Train-test split
    - Linear Regression implementation
    - Model evaluation using multiple metrics

## Technologies Used
- Python 3.x
- Libraries:
    - pandas - Data manipulation and analysis
    - numpy - Numerical operations
    - matplotlib - Data visualization
    - seaborn - Statistical data visualization
    - scikit-learn - Machine learning implementation

## Model Evaluation
The model's performance is evaluated using multiple metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

