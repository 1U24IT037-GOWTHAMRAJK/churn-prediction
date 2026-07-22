# churn-prediction

# Customer Churn Prediction

## Project Overview

Customer churn is one of the biggest challenges faced by banks and financial institutions. Losing existing customers increases customer acquisition costs and reduces overall profitability.

This project aims to build a Machine Learning model that predicts whether a customer is likely to leave the bank (churn) based on demographic information, account details, and transaction behavior. By identifying customers at risk, banks can take proactive measures such as personalized offers and improved customer support to increase customer retention.

---

## Problem Statement

The objective of this project is to predict customer churn using historical customer data. The prediction helps the bank identify customers who are likely to discontinue their services, enabling timely retention strategies.

---

## Dataset

The dataset contains **10,127 customer records** with demographic, banking, and transaction-related information.

### Target Variable

- **Attrition_Flag**
  - Existing Customer
  - Attrited Customer

### Important Features

- Customer_Age
- Gender
- Education_Level
- Marital_Status
- Income_Category
- Card_Category
- Months_on_book
- Total_Relationship_Count
- Months_Inactive_12_mon
- Contacts_Count_12_mon
- Credit_Limit
- Total_Revolving_Bal
- Avg_Open_To_Buy
- Total_Trans_Amt
- Total_Trans_Ct
- Avg_Utilization_Ratio

---

## Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Data Overview
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Train-Test Split
7. Model Building
8. Model Evaluation
9. Feature Importance Analysis
10. Business Insights & Recommendations

---

## Exploratory Data Analysis

The dataset was explored using:

- Summary Statistics
- Missing Value Check
- Univariate Analysis
- Bivariate Analysis
- Distribution Plots
- Count Plots
- Correlation Analysis

---

## Data Preprocessing

The preprocessing steps include:

- Handling categorical variables
- Encoding categorical features
- Train-Test Split
- Preparing data for Machine Learning models

---

## Machine Learning Models

The following classification models were trained and evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

Gradient Boosting Fine-Tuning was also performed to improve model performance.

---

## Model Evaluation

Models were compared using standard classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC (if applicable)
- Confusion Matrix

The best-performing model was selected based on overall predictive performance.

---

## Feature Importance

Feature importance analysis was performed to identify the most influential factors contributing to customer churn. These insights help businesses understand customer behavior and design effective retention strategies.

---

## Business Recommendations

Based on the model findings, banks can:

- Identify high-risk customers early.
- Offer personalized promotions and rewards.
- Improve customer service for inactive customers.
- Increase engagement with customers showing reduced transaction activity.
- Design targeted retention campaigns.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
Customer-Churn-Prediction/
│
├── Case_Study_Customer_Churn_Prediction.ipynb
├── README.md
├── data/
│   └── Customer_Churn.csv
└── images/ (optional)
```

---

## Future Improvements

- Hyperparameter Optimization
- XGBoost / LightGBM Implementation
- Model Deployment using Streamlit or Flask
- Real-time Customer Churn Prediction API

---

## Conclusion

This project demonstrates how Machine Learning can be used to predict customer churn in the banking sector. Accurate churn prediction enables organizations to proactively retain valuable customers, improve customer satisfaction, and increase long-term profitability.

---
