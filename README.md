# Customer Churn Prediction

## 📌 Project Overview

Customer churn is a major challenge for banks and financial institutions. Losing existing customers can increase customer acquisition costs and affect business growth.

This project uses **Machine Learning** to predict whether a bank customer is likely to leave the service. By identifying customers who are at risk of churn, banks can take early actions to improve customer retention.

---

## 🎯 Problem Statement

The main objective of this project is to predict **customer churn** using historical customer data.

The model analyzes customer demographics, account information, and transaction behavior to identify customers who are more likely to discontinue their banking services.

---

## 📊 Dataset

The dataset contains **10,127 customer records** with demographic, banking, and transaction-related information.

### Target Variable

**Attrition_Flag**

* Existing Customer
* Attrited Customer

### Key Features

* Customer Age
* Gender
* Education Level
* Marital Status
* Income Category
* Card Category
* Months on Book
* Total Relationship Count
* Months Inactive in the Last 12 Months
* Contacts Count in the Last 12 Months
* Credit Limit
* Total Revolving Balance
* Average Open to Buy
* Total Transaction Amount
* Total Transaction Count
* Average Utilization Ratio

---

## 🔄 Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Understand the Dataset
4. Perform Exploratory Data Analysis
5. Preprocess the Data
6. Split Data into Training and Testing Sets
7. Build Machine Learning Models
8. Evaluate Model Performance
9. Analyze Feature Importance
10. Generate Business Insights

---

## 🔍 Exploratory Data Analysis

The dataset was analyzed using:

* Dataset summary
* Missing value analysis
* Statistical analysis
* Univariate analysis
* Bivariate analysis
* Distribution plots
* Count plots
* Correlation analysis

EDA helped identify important patterns and relationships between customer behavior and churn.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Handled categorical variables
* Encoded categorical features
* Selected relevant features
* Split the dataset into training and testing data
* Prepared the data for Machine Learning models

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

### 1. Decision Tree Classifier

Used to understand decision-based patterns in customer churn.

### 2. Random Forest Classifier

Used as an ensemble model to improve prediction performance and reduce overfitting.

### 3. Gradient Boosting Classifier

Used to build a strong predictive model by combining multiple weak learners.

### 4. Gradient Boosting Fine-Tuning

Hyperparameters were adjusted to improve the performance of the Gradient Boosting model.

---

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

The models were compared based on their overall performance, and the best-performing model was selected for customer churn prediction.

> **Note:** Actual model performance values can be added here after final model evaluation.

---

## ⭐ Feature Importance

Feature importance analysis was performed to identify the factors that have the greatest influence on customer churn.

This helps understand customer behavior and provides useful information for developing targeted retention strategies.

Some important factors include:

* Customer transaction activity
* Number of inactive months
* Total transaction count
* Credit-related information
* Customer relationship details

---

## 💡 Business Insights

The model can help banks identify customers who have a higher risk of leaving.

Based on the analysis, banks can:

* Identify high-risk customers early
* Provide personalized offers and rewards
* Improve customer support
* Increase engagement with inactive customers
* Monitor changes in transaction behavior
* Create targeted customer retention campaigns

---

## 🛠️ Technologies Used

* **Programming:** Python
* **Data Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Development Environment:** Jupyter Notebook

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Case_Study_Customer_Churn_Prediction.ipynb
├── README.md
│
├── data/
│   └── Customer_Churn.csv
│
└── images/
    ├── eda.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## 🚀 Future Improvements

* Perform advanced hyperparameter optimization
* Implement XGBoost and LightGBM
* Deploy the model using Streamlit
* Build a real-time churn prediction application
* Create a customer risk dashboard
* Develop a real-time churn prediction API

---

## 🏁 Conclusion

This project demonstrates how **Machine Learning can be used to predict customer churn in the banking sector**.

By identifying customers who are likely to leave, banks can take proactive steps to improve customer satisfaction, strengthen customer relationships, and increase long-term customer retention.

---
