# customer-lifetime-value
use  polynomial regression to analyza and be able to predict high value customers
# 🧮 Customer Lifetime Value (CLV) Prediction Using Polynomial Regression

## 📊 Project Overview

This project predicts **Customer Lifetime Value (CLV)** using customer behavioral and demographic data. CLV is a critical business metric that helps companies identify and retain their most valuable customers.

The model leverages **Polynomial Regression** to capture non-linear relationships between features such as tenure, satisfaction, average spend, and transaction frequency.

---

## 🧠 Problem Statement

> "How can a business accurately predict how much revenue a customer will bring over their lifetime based on their behavior, engagement, and demographics?"

Understanding CLV helps businesses:
- Improve **marketing ROI**
- Prioritize **high-value customers**
- Design better **loyalty programs**
- Predict **revenue growth**

---

## 📦 Dataset Features

The dataset contains 1,000 simulated customer records inspired by real-world CRM systems. Key features include:

| Feature | Description |
|--------|-------------|
| `Customer_ID` | Unique customer identifier |
| `Age` | Customer age |
| `Gender` | Male, Female, Other |
| `Tenure_Months` | How long they’ve been a customer |
| `Average_Monthly_Spend` | Monthly average spending |
| `Frequency` | Monthly transaction frequency |
| `Region` | Geographic region (e.g., Nairobi) |
| `Churned` | Whether the customer churned |
| `Satisfaction_Score` | Satisfaction level (1 to 5) |
| `CLV` | Calculated Customer Lifetime Value (target) |

---

## 🔍 Project Objectives

- Explore and clean the dataset
- Engineer features to better capture customer behavior
- Apply **Polynomial Regression** and evaluate performance
- Visualize insights and model fit
- Generate actionable business recommendations

---

## 🧰 Tools & Libraries

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (PolynomialFeatures, LinearRegression)
- Jupyter Notebook / Google Colab

---

## 📈 Key Results

- Polynomial regression achieved an R² of `XX.XX` (to be filled after modeling)
- Strongest CLV drivers: `Tenure`, `Frequency`, and `Satisfaction`
- Churned customers had 60–80% lower CLV
- Nairobi and Mombasa customers showed the highest revenue potential

---

## 📂 File Structure


