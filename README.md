# Abalone Age Classification using Logistic Regression

## Overview
This project builds a binary classification model to predict whether an
abalone is young or old based on physical measurements.

## Dataset
Abalone dataset containing physical attributes such as shell length,
diameter, weight, and type (M/F/I).

Target definition:
- 0 → Rings < 10 (young)
- 1 → Rings ≥ 10 (old)

## Methodology
- One-hot encoding for categorical feature (Type)
- Feature scaling using StandardScaler
- Logistic Regression with class balancing
- Threshold optimization based on F1-score
- ROC and Precision–Recall analysis

## Results
The optimal probability threshold is selected by maximizing the F1-score,
demonstrating improved performance compared to the default 0.5 threshold.

## Technologies
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
