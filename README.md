# Vedant-Credit-Risk-Prediction
## Credit Risk Prediction with Python and Machine Learning
## Overview
This project builds a Credit Risk Model that predicts whether a person is likely to default on a loan based on their financial and personal information. The goal is to help banks and lenders make smart lending decisions, reducing the risk of bad loans.

We used XGBoost, a popular machine learning algorithm, for accurate predictions. To make it even easier to use, we created an interactive web app with Streamlit—a simple tool to input details and see the risk score in real-time.

## What This Project Contains
- Data cleaning and preparation
- Visual analysis of the data (charts and plots)
- Building and training the machine learning model
- Checking how well the model performs
- An easy-to-use web app for testing new data

## Technologies Used
- Python (programming language)
- pandas & numpy (data handling)
- scikit-learn (machine learning tools)
- imbalanced-learn (to handle unbalanced data)
- XGBoost (powerful prediction algorithm)
- matplotlib & seaborn (visualizations)
- Streamlit (interactive web app)

## How to Use the Project
1. Set up your environment
- Download the code from GitHub:
 < href ="https://github.com/Vedant2331/Vedant--Credit-Risk-Prediction/blob/main/code.ipynb"> Code link</a>

- Create a Python environment (optional):
#### python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
- Install the required packages:
#### pip install -r requirements.txt
2. Train the model
- Run this script to prepare data, train the model, and save it:
#### python train_model.py
3. Use the web app
- Launch the interactive prediction tool:
#### streamlit run app.py
- Open the link shown in your terminal or browser, and input the details of a loan applicant to see their default risk score instantly.

## Files in the Project
- train_model.py: Prepares data, trains the model, and saves it.
- app.py: The web app for easy risk prediction.
- credit_risk_data.csv: Sample dataset to train and test the model.
- xgb_model.pkl: The trained machine learning model.
- scaler.pkl: Data preprocessing tool to standardize inputs.
- requirements.txt: List of all needed packages to run the project.

## About the Data
Contains information about loan applicants such as:
- Credit Score
- Duration
- Risk
- Check Amount
- Saving Accounts
- Other Details

## Screenshots
- <a href= 
