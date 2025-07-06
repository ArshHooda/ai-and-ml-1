# Titanic Dataset Cleaning and Prediction

This Jupyter notebook performs data cleaning, preprocessing, and logistic regression modeling on the Titanic dataset to predict passenger survival.

## Features

- Loads and explores the Titanic dataset
- Handles missing values (Age, Embarked)
- Drops irrelevant columns (Name, Ticket, Cabin)
- Converts categorical variables to dummy variables (Sex, Cabin_initial, Embarked)
- Splits data into training and test sets
- Trains a logistic regression model
- Evaluates model accuracy
- Generates submission file with predictions

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

## Installation

```bash
pip install pandas numpy scikit-learn
