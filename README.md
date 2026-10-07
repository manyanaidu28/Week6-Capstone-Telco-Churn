# Week 6 Capstone – Telco Customer Churn Prediction & Customer Segmentation

## 📌 Project Overview

This capstone project demonstrates an end-to-end Data Science workflow using Python and the IBM Telco Customer Churn dataset.

The project combines:

- Data acquisition
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Supervised Machine Learning
- Unsupervised Machine Learning
- Model evaluation
- Customer segmentation
- Business insights and recommendations

## 🎯 Objectives

1. Analyze customer churn patterns.
2. Build a Logistic Regression model to predict customer churn.
3. Segment customers using K-Means clustering.
4. Identify high-risk customer segments.
5. Provide actionable business recommendations.

## 📊 Dataset

**Dataset:** IBM Telco Customer Churn

- Customers: 7,043
- Features: 21
- Target variable: Churn

Overall churn rate: **26.54%**

## 🧹 Data Preprocessing

The dataset was inspected and cleaned before analysis.

Steps included:

- Missing-value detection
- Conversion of `TotalCharges` to numeric format
- Median imputation for missing `TotalCharges`
- Duplicate-row checking
- Feature preparation
- Target encoding

## 📈 Exploratory Data Analysis

The analysis examined:

- Overall churn distribution
- Churn by contract type
- Monthly charges
- Customer tenure
- Customer spending patterns

Important finding:

Customers with **month-to-month contracts** showed substantially higher churn than customers with one-year or two-year contracts.

## 🤖 Supervised Learning – Logistic Regression

Logistic Regression was used to predict customer churn.

### Model Result

**Accuracy: 78.42%**

Confusion Matrix:

- True Negatives: 935
- False Positives: 100
- False Negatives: 204
- True Positives: 170

## 🔵 Unsupervised Learning – K-Means

K-Means clustering was used to segment customers based on customer characteristics.

The analysis considered different values of K using:

- Elbow method
- Silhouette score

Four clusters were selected to provide useful customer segmentation.

### Cluster Churn Rates

| Cluster | Churn Rate |
|--------:|-----------:|
| 0 | 5.00% |
| 1 | 15.39% |
| 2 | 24.65% |
| 3 | 48.24% |

## 💡 Key Insights

- Cluster 0 represents
