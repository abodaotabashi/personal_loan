# <div align="center">Personal Loan Prediction</div>

<p align="center"> 
    <a href="https://www.kaggle.com/code/odabashi/personal-loan-modelling-solving-data-imbalance" target="_blank"><img src="https://img.shields.io/badge/Kaggle-Notebook-blue.svg?logo=data:image/svg+xml;base64,PCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8vRFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQvc3ZnMTEuZHRkIj4KDTwhLS0gVXBsb2FkZWQgdG86IFNWRyBSZXBvLCB3d3cuc3ZncmVwby5jb20sIFRyYW5zZm9ybWVkIGJ5OiBTVkcgUmVwbyBNaXhlciBUb29scyAtLT4KPHN2ZyBmaWxsPSIjMjBiZWZmIiB3aWR0aD0iMjI2cHgiIGhlaWdodD0iMjI2cHgiIHZpZXdCb3g9IjAgMCAyNCAyNCIgcm9sZT0iaW1nIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0cm9rZT0iIzIwYmVmZiI+Cg08ZyBpZD0iU1ZHUmVwb19iZ0NhcnJpZXIiIHN0cm9rZS13aWR0aD0iMCIvPgoNPGcgaWQ9IlNWR1JlcG9fdHJhY2VyQ2FycmllciIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBzdHJva2U9IiNDQ0NDQ0MiIHN0cm9rZS13aWR0aD0iMC4wOTYiLz4KDTxnIGlkPSJTVkdSZXBvX2ljb25DYXJyaWVyIj4KDTx0aXRsZT5LYWdnbGUgaWNvbjwvdGl0bGU+Cg08cGF0aCBkPSJNMTguODI1IDIzLjg1OWMtLjAyMi4wOTItLjExNy4xNDEtLjI4MS4xNDFoLTMuMTM5Yy0uMTg3IDAtLjM1MS0uMDgyLS40OTItLjI0OGwtNS4xNzgtNi41ODktMS40NDggMS4zNzR2NS4xMTFjMCAuMjM1LS4xMTcuMzUyLS4zNTEuMzUySDUuNTA1Yy0uMjM2IDAtLjM1NC0uMTE3LS4zNTQtLjM1MlYuMzUzYzAtLjIzMy4xMTgtLjM1My4zNTQtLjM1M2gyLjQzMWMuMjM0IDAgLjM1MS4xMi4zNTEuMzUzdjE0LjM0M2w2LjIwMy02LjI3MmMuMTY1LS4xNjUuMzMtLjI0Ni40OTUtLjI0NmgzLjIzOWMuMTQ0IDAgLjIzNi4wNi4yODUuMTguMDQ2LjE0OS4wMzQuMjU1LS4wMzYuMzE1bC02LjU1NSA2LjM0NCA2LjgzNiA4LjUwN2MuMDk1LjEwNC4xMTcuMjA4LjA3LjM1OCIvPgoNPC9nPgoNPC9zdmc+"></a>
</p> 



## 📋 Project Overview

### Problem Statement
Thera Bank aims to convert liability customers to personal loan customers while maintaining their existing deposit relationships. The bank's previous campaign achieved a conversion rate of 9.6%, and our machine learning project seeks to improve target marketing strategies.

## 🎯 Project Objectives
- Predict customer likelihood of accepting a personal loan
- Develop a robust machine learning model to optimize marketing efforts
- Minimize marketing budget while maximizing loan conversions

## 🔍 Dataset Description

### Data Source
- Source: Bank.xls
- Total Customers: 5,000
- Positive Loan Responses: 480 (9.6%)

### Features
| Feature | Description | Type |
|---------|-------------|------|
| ID | Customer Unique Identifier | Numeric |
| Age | Customer's Age | Numeric |
| Experience | Years of Professional Experience | Numeric |
| Income | Annual Income (in 1000$) | Numeric |
| ZIP Code | Customer's Home Address ZIP Code | Categorical |
| Family | Family Size | Numeric |
| CCAvg | Average Credit Card Spending (in 1000$) | Numeric |
| Education Level | {1: Undergrad, 2: Graduate, 3: Advanced/Professional} | Categorical |
| Mortgage | House Mortgage Value (in 1000$) | Numeric |
| Securities Account | Account Ownership {1: Yes, 0: No} | Binary |
| CD Account | Certificate of Deposit Account {1: Yes, 0: No} | Binary |
| Online | Internet Banking Usage {1: Yes, 0: No} | Binary |
| CreditCard | Bank Credit Card Usage {1: Yes, 0: No} | Binary |
| Personal Loan (Label) | Loan Acceptance in Last Campaign {1: Yes, 0: No} | Binary |

## 🛠 Methodology

### Data Preprocessing
- Dealt with "Experience" feature anomalies
- Handled ZIP Code categorical data
- Identified and managed outliers
- Data splitting for training and testing
- Feature standardization
- Addressed class imbalance
- Applied dimensionality reduction techniques

### Machine Learning Models
Explored multiple classification algorithms:
- Logistic Regression
- Support Vector Machine
- K-Nearest Neighbors
- Stochastic Gradient Descent Classifier
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Extra Trees
- XGBoost
- Balanced Bagging Classifier

### Model Evaluation Techniques
- Classification Report (Precision, Recall, F1-score, Accuracy)
- Precision/Recall Curve
- Confusion Matrix
- Feature Importance Analysis

### Advanced Techniques
- Voting Classifier
- Hyperparameter Tuning
- Comparative Performance Analysis

## 🚀 Installation

### Prerequisites
- Python 3.8+
- Required libraries: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - uszipcode
  - scikit-learn
  - imblearn
  - xgboost

### Setup
```bash
git clone https://github.com/odabashi/Personal-Loan-Prediction.git
cd Personal-Loan-Prediction
```
<p align="center"> 
    Found value here? A quick upvote supports continued research and sharing! 👍
</p> 

