# Loan Default Prediction – Machine Learning Project

## Project Overview

Banks earn significant revenue from lending, but loans carry the risk of borrower default. Using historical borrower data, I aim to build a machine learning classifier that predicts whether a new applicant is likely to default.

## Dataset

Source: Loan Default Dataset (Kaggle – yasserh)[https://www.kaggle.com/datasets/yasserh/loan-default-dataset/data]<br>

Type: Tabular data with borrower demographics and loan attributes (income, gender, loan purpose, loan amount, etc.)<br>

Target: default → 1 = Default, 0 = No Default<br>

Challenges: Missing values, multicollinearity, and potential class imbalance<br>

## Tech Stack

Languages: Python<br>

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost, LightGBM<br>

Deployment: Streamlit (to be added in later phase)<br>

Version Control: GitHub<br>

## Objectives

Explore and understand the dataset (EDA)<br>

Clean and preprocess the data (handle missing values, encode categoricals, scale numerics)<br>

Train baseline models (Logistic Regression, Decision Tree)<br>

Build advanced models (Random Forest, XGBoost, LightGBM)<br>

Fine-tune hyperparameters and compare performance<br>

Deploy a simple Streamlit app for interactive predictions<br>

## Project Structure

loan_default_project/
│── notebooks/
│   ├── 01_load_data.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_preprocessing.ipynb
│   ├── 04_modeling.ipynb
│── app.py              # Streamlit app (Day 6–7)
│── data/               # Dataset (not uploaded due to Kaggle license)
│── README.md           # Documentation

## Results (to be updated)

Model	Accuracy	Precision	Recall	F1 Score	ROC-AUC <br>
Logistic Regression	–	–	–	–	– <br>
Random Forest	–	–	–	–	– <br>
XGBoost	–	–	–	–	– <br>

## Deployment (Planned)

I will build a Streamlit web app where users can input borrower details and get a predicted default risk.

## 👤 Author

Kavya Kasthuri Dodle [https://www.linkedin.com/in/kavya942/]

📩 Connect with me on LinkedIn
