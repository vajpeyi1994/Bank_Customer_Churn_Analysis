# 🏦 Bank Customer Churn Analysis

This project analyzes customer churn behavior for a fictional bank using historical customer data. The goal is to identify the key drivers of churn and provide actionable insights that can help reduce customer attrition.

## 📊 Project Overview

- **Objective:** Predict which customers are likely to leave the bank.
- **Tech Stack:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, statsmodels
- **Tools:** VS Code, Git, GitHub

## 📁 Folder Structure :

- Jupyter notebooks for analysis and modeling
- README.md -> Project overview
- requirements.txt -> Project dependencies
- Dataset


## 📌 Dataset

- **Source:** (willian oliveira gibin, and Kolli Sai Siddartha. (2024). Customer Churn [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/9626375)

- **Features:**
  - Customer demographics (Age, Gender)
  - Customer Identifiers ( Surname, Customer_ID)
  - Bank-related behavior (Balance, CreditScore, Tenure, EstimatedIncome)
  - Churn status (Exited = 1, Remained = 0)

## 🔍 Exploratory Data Analysis (EDA)

Initial analysis was  performed to identify:
- Demographic trends (Gender Churn rates)
- Geohraphical trends (Country churn rates)
- Churn correlations:
    - vis-à-vis CreditScore 
    - vis-à-vis EstimatedIncome

**Key Insights:**
- Older customers with higher balance and Estimated are more likely to churn. 
- Customers with longer tenure and higher credit scores are more likely to stay.
- Out of the geographies, the churn rate is relatively high in Germany warrenting more deeper analysis to identify the cause.
- Out of genders, the churn rate is relatively high in females and the cause could be further investigated. 

## 🧠 Modeling

A classification model was trained using:
- **Logistic Regression**

**Best performance:** `Logistic Regression with predictor varibales - EstimatedSalary','CreditScore','Age','Tenure','Balance'.
(Accuracy: 70%, with 80% true positives for No-Churn and 64% for Churn)`

---

