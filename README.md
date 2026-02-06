# Ecommerce Customer Churn Analysis & Prediction

This repository contains a Jupyter Notebook that demonstrates an end-to-end **Ecommerce Customer Churn Analysis** workflow. The notebook focuses on loading customer data, merging features with churn labels, and preparing a clean dataset for further analysis and modeling.

---

## 📁 Repository Structure

ecommerce_customer_churn/
├── ecommerce_customer_churn.ipynb # Main Jupyter Notebook
├── ecommerce_customer_features.csv # Customer feature dataset
├── ecommerce_customer_targets.csv # Churn labels
└── result.csv # Merged output dataset


---

## 🧠 Project Overview

Customer churn—when customers stop engaging or purchasing—is a critical metric for e-commerce businesses. This project aims to:

- Combine customer behavioral features with churn outcomes
- Inspect and clean the resulting dataset
- Prepare data for exploratory analysis and predictive modeling

---

## 🔍 What the Notebook Does

### 1. Load Data
- Reads customer features and churn target CSV files into Pandas DataFrames
- Displays sample rows for quick inspection

### 2. Merge Datasets
- Joins features and targets using `Customer_ID`
- Performs an inner merge to ensure data consistency
- Saves the merged dataset as `result.csv`

### 3. Clean & Prepare Data
- Removes unnecessary columns (e.g., index columns)
- Verifies final dataset structure and dimensions

---

## 🧩 Example Features

The dataset includes customer-level attributes such as:

- `account_age_months`
- `avg_order_value`
- `total_orders`
- `days_since_last_purchase`
- `discount_usage_rate`
- `return_rate`
- `customer_support_tickets`
- `loyalty_member`
- `browsing_frequency_per_week`
- `cart_abandonment_rate`
- `satisfaction_score`
- `price_sensitivity_index`
- `churned` (target variable)

---

## 🚀 Next Steps

Potential extensions to this project include:

- Exploratory Data Analysis (EDA)
- Feature engineering and encoding
- Training churn prediction models (e.g., Logistic Regression, Random Forest, XGBoost)
- Model evaluation using accuracy, ROC-AUC, and F1-score

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Jupyter Notebook

---

## 📌 License

Add a license here if applicable (e.g., MIT License).
