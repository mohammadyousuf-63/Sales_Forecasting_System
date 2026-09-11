# Sales Forecasting System

A machine learning-based Sales Forecasting System developed using historical Superstore sales data to analyze sales trends and predict future monthly sales.

## 📌 Project Overview

This project was developed as part of my Data Science Internship at **Sqrock IT Solutions**.

The system analyzes historical sales data, performs data preprocessing and exploratory data analysis, creates time-based features, trains machine learning models, evaluates their performance, and forecasts future monthly sales.

## 🎯 Objectives

- Analyze historical sales data
- Identify sales trends and seasonal patterns
- Perform data preprocessing and exploratory data analysis
- Create time-based features for forecasting
- Train and compare machine learning models
- Forecast future monthly sales
- Provide business-oriented insights from the predictions

## 📊 Dataset

**Dataset:** Sample - Superstore

- Records: 9,994
- Features: 21
- Time Period: January 2014 – December 2017
- Target Variable: Sales

The dataset contains information related to orders, customers, products, categories, regions, sales, discounts, and profits.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

## 🔄 Project Workflow

1. Data Loading
2. Data Understanding
3. Data Preprocessing
4. Feature Engineering
5. Exploratory Data Analysis (EDA)
6. Monthly Sales Aggregation
7. Time-Based Feature Creation
8. Model Building
9. Model Training
10. Model Evaluation
11. Model Selection
12. Future Sales Forecasting
13. Business Interpretation
14. Project Conclusion

## 📈 Feature Engineering

Time-based features were created to improve the forecasting process:

- Year
- Month
- Day
- Month Number
- Time Index

Monthly sales were aggregated from the historical transaction-level data.

## 🤖 Machine Learning Models

Two machine learning models were trained and evaluated:

### 1. Linear Regression

Used as a baseline model for predicting monthly sales based on time-based features.

### 2. Random Forest

Used to capture non-linear relationships between the time-based features and sales.

## 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 12180.97 | 16833.86 | 0.5734 |
| Random Forest | 12052.30 | 14152.52 | 0.6985 |

### 🏆 Best Model

**Random Forest**

- MAE: 12052.30
- RMSE: 14152.52
- R² Score: 0.6985

Random Forest performed better than Linear Regression based on the evaluation metrics and was selected as the final forecasting model.

## 🔮 2018 Sales Forecast

The selected Random Forest model was used to forecast monthly sales from **January 2018 to December 2018**.

- **Total Predicted Sales:** 649377.38
- **Average Monthly Predicted Sales:** 54114.78
- **Highest Predicted Sales:** December 2018 — 90579.05
- **Lowest Predicted Sales:** February 2018 — 27382.06

## 💼 Business Use

The forecasting system can help businesses with:

- Inventory planning
- Revenue planning
- Resource allocation
- Seasonal demand planning
- Sales strategy
- Future business decision-making

## 📁 Project Structure

```text
Sales_Forecasting_System/
│
├── data/
│   └── Sample - Superstore.csv
│
├── notebooks/
│   └── sales_forecasting.ipynb
│
├── .gitignore
├── requirements.txt
└── README.md