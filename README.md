# customer-churn_calculator

# 📉 Telco Customer Churn Prediction

This repository contains a full end-to-end data science project analyzing customer churn for a telecommunications company. Using real-world data, we built a machine learning model that predicts which customers are likely to cancel their service — a key insight that can help businesses reduce churn and protect recurring revenue.

---

## 🔍 Project Overview

**Churn** — when a customer leaves a service — is one of the most important metrics for subscription-based businesses. This project uses a dataset from a Telco provider to model churn risk based on customer demographics, billing data, and service usage.

### Goals:
- Understand which features are most predictive of churn
- Build and evaluate classification models
- Generate actionable business insights for retention strategies

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| [`data_wrangling.ipynb`](https://github.com/ovoarnav/customer-churn_calculator/blob/main/data_wrangling.ipynb) | Data cleaning and early exploration |
| [`eda.ipynb`](https://github.com/ovoarnav/customer-churn_calculator/blob/main/eda.ipynb) | Exploratory Data Analysis, feature distributions, statistical testing |
| [`Pre-processing Work and Model.ipynb`](https://github.com/ovoarnav/customer-churn_calculator/blob/main/Pre-processing%20Work%20and%20Model.ipynb) | Data prep, feature selection, model building & evaluation |
| `Cleansed_Telco_Customer_Churn.csv` | Final modeling dataset (7% rows removed for quality) |
| `README.md` | You're reading it :) |

---

## 📊 Key Techniques Used

- 🔹 **Data Cleaning**: Removed noisy or inconsistent records
- 🔹 **Statistical Testing**: Used t-tests to select significant features (p < 0.05)
- 🔹 **Feature Engineering**: Dropped multicollinear features using VIF
- 🔹 **Modeling**: Compared Logistic Regression, Random Forest, and SVC
- 🔹 **Evaluation**: ROC AUC, precision/recall, confusion matrix (percent-based)

---

## 🧠 Results

- **Top Predictors**: Tenure, MonthlyCharges, Contract type, and Security services
- **Best Model**: Random Forest with ROC AUC of **0.83**
- **Business Insight**: Customers with high bills and short tenure are most likely to churn

---

## 🛠️ Tech Stack

- Python 3.9+
- pandas, numpy, seaborn, matplotlib
- scikit-learn
- Jupyter Notebook

---

## 🚀 Future Work

- Deploy model as an API or live dashboard
- Collect time-series service usage data
- Apply retention strategies to high-risk flagged customers

---

## 📬 Contact

Made with ❤️ by Arnav Nambiar  
Feel free to connect or reach out if you're interested in collaborating or discussing the project.
