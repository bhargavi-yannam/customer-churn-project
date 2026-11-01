Customer Churn Prediction

This project uses machine learning to predict whether a telecom customer may leave the service.

## What the notebook contains

The Jupyter notebook (`outputs/customer-churn-prediction_project.ipynb`) guides you through loading and exploring the Telco Customer Churn dataset, preparing the data, training Logistic Regression, Random Forest, and XGBoost models, and comparing their results. It also includes charts and feature explanations to show which factors may be related to churn.

## Project note

The data is split into training and test sets before SMOTE is used. SMOTE is applied only to the training data, so the test results provide a fairer check of how the models perform on unseen customers.
