# Customer Churn Prediction (Telecommunications)

## Overview
This project focuses on predicting customer churn for a telecommunications company using historical customer data, including service usage, subscribed products, and customer characteristics. The objective is to build and evaluate classification models capable of identifying customers with a high probability of cancelling the service, supporting data-driven retention strategies.

This project was developed as part of a formal Data Science training program and represents a complete end-to-end machine learning workflow.

---

## Problem Statement
Customer churn is a critical business problem in the telecommunications industry, as acquiring new customers is often significantly more expensive than retaining existing ones. Being able to proactively identify customers who are likely to cancel allows the company to take preventive actions such as targeted offers or personalized support.

The challenge is framed as a **binary classification problem**, where the goal is to predict whether a customer will churn based on historical data.

---

## Dataset
The dataset contains historical information about customers, including:
- Customer demographics
- Contract and billing details
- Subscribed services
- Usage-related features

The data used in this project comes from a private academic environment. For this reason, the raw dataset is **not publicly available**. However, the full methodology, feature engineering process, and modeling approach are documented in the notebook.

---

## Methodology

### 1. Data Preparation
- Data cleaning and type correction
- Handling missing values based on feature semantics
- Encoding categorical variables
- Scaling numerical features when required

### 2. Exploratory Data Analysis (EDA)
- Analysis of churn distribution
- Identification of patterns related to customer behavior and service usage
- Visualization of key relationships between features and churn

### 3. Feature Engineering
- Creation of derived features to better capture customer behavior
- Removal of features that could introduce data leakage
- Selection of relevant features for modeling

### 4. Modeling
Multiple classification models were trained and compared, including:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting (scikit-learn)
- K-Nearest Neighbors (KNN)
- XGBoost
- LightGBM
- CatBoost

All models were evaluated using consistent preprocessing pipelines to ensure fair comparison.

---

## Evaluation Metric
Because customer churn is a **class-imbalanced problem**, **ROC-AUC** was selected as the primary evaluation metric. This metric provides a robust measure of a model’s ability to distinguish between churned and non-churned customers across different decision thresholds.

---

## Results
The final selected model achieved:

- **ROC-AUC = 0.939 on the test dataset** (CatBoost)

This result demonstrated strong predictive performance, making the model suitable for supporting churn reduction initiatives.

---

## Conclusions
- Machine learning models can effectively identify customers at high risk of churn using historical behavioral data.
- Proper feature engineering and evaluation strategies are critical in class-imbalanced business problems.
- The resulting model can be used as a decision-support tool for retention-focused business actions.

---

## Technologies Used
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Notes
This repository contains the final cleaned notebook used for analysis and modeling. Intermediate experiments and private datasets were excluded to maintain clarity and data privacy.
