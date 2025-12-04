# Titanic Survival Analysis – Exploratory Data Analysis and Logistic Regression
- Interactive EDA and logistic regression on the Kaggle Titanic dataset.

This notebook explores survival patterns by demographics, ticket class, family size, fare, and embarkation. It includes data cleaning (missing values), feature engineering (one-hot encoding), visualizations, and trains a logistic regression model (~78.7% accuracy).

## Installation instructions for users
- Clone/download this repository (includes code.ipynb and data.csv).
- Install dependencies:
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
- Launch and run notebook:
    jupyter notebook code.ipynb

## Installation instructions for developers
- Clone repository (includes dataset and notebook).
- Create/activate virtual environment:
    python -m venv .venv
    source .venv/bin/activate  # Linux/Mac
    .\.venv\Scripts\activate   # Windows
- Install dev dependencies:
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter black pytest
- Format: black . | Test: pytest
- Extend notebook with new models, cross-validation, or hyperparameter tuning tools.