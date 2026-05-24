# Customer Churn Prediction using MLflow

An end-to-end Machine Learning project for predicting customer churn using the Telco Customer Churn dataset. This project demonstrates data preprocessing, exploratory data analysis (EDA), machine learning model building, hyperparameter experimentation, and experiment tracking using MLflow.

---

## Problem Statement

Customer churn is one of the biggest challenges for subscription-based businesses. The objective of this project is to predict whether a customer is likely to churn based on customer demographics, account information, and service usage patterns.

---

## Dataset

Dataset used:
- Telco Customer Churn Dataset from Kaggle

Features include:
- Customer demographics
- Internet services
- Contract details
- Payment methods
- Monthly and total charges
- Tenure information

Target Variable:
- `Churn`

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- MLflow

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
Performed detailed EDA to identify:
- Churn distribution
- Customer behavior patterns
- Correlation between features
- Important churn indicators

### 2. Data Preprocessing
- Handling missing values
- Label Encoding / One-Hot Encoding
- Feature scaling
- Train-test split

### 3. Model Building
Implemented and compared multiple models:
- Logistic Regression
- Naive Bayes
- Random Forest Classifier
- XGBoost Classifier

### 4. Experiment Tracking using MLflow
Tracked:
- Hyperparameters
- Model metrics
- Model artifacts
- Multiple experiment runs

Used MLflow UI for experiment comparison and model evaluation.

---

## MLflow Features Implemented

- Experiment tracking
- Parameter logging
- Metric logging
- Model logging
- Hyperparameter experimentation
- Run comparison

---

## Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Project Structure

```bash
customer-churn-mlflow/
│
├── data/
│   └── telco_churn.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   ├── evaluate.py
│   └── mlflow_tracking.py
│
├── models/
│
├── mlruns/
│
├── requirements.txt
│
├── README.md
│
└── .gitignore

