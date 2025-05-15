Predict_customer_churn_risk_dashboard_analysis/
├── data/
│   └── customer_data.csv  # if allowed, otherwise use a sample or mention location
├── notebooks/
│   └── churn_analysis.ipynb
├── reports/
│   └── churn_dashboard_screenshots.png
├── dashboard/
│   └── churn_dashboard.pbix  # for Power BI or .twbx for Tableau
├── README.md



# Customer Churn Risk Prediction & Dashboard Analysis

This project focuses on predicting customer churn and visualizing churn risk through an interactive dashboard using Power BI.

## 📌 Objectives

- Identify factors contributing to customer churn.
- Predict which customers are at high risk of leaving.
- Create a dashboard for business stakeholders to monitor churn trends.

## 📊 Tools & Technologies

- Python (pandas, scikit-learn, matplotlib)
- Excel for preprocessing
- Power BI for dashboard creation

## 🧩 Data Description

The dataset contains customer information such as:

- Demographics (age, gender)
- Service usage (calls, internet)
- Subscription details (plan type, contract, tenure)
- Churn label (Yes/No)

> 📁 Sample dataset file: `data/customer_data.csv`

## ⚙️ Process Overview

1. **Data Cleaning & Preparation** (Python/Excel)
2. **Churn Prediction Model** (RandomForestClassifier)
3. **Feature Importance Analysis** (SHAP values)
4. **Customer Segmentation**
5. **Power BI Dashboard Development**

## 📈 Key Insights

- Longer tenure reduces churn probability.
- Month-to-month contracts have higher churn.
- Customers with multiple services churn less.

## 📊 Dashboard Preview

> ![Dashboard Screenshot](reports/churn_dashboard_screenshots.png)

## 💡 Future Improvements

- Use a larger dataset from a real telecom provider.
- Deploy the model in a web app using Streamlit.
- Add real-time data refresh to Power BI dashboard.

## 🧠 Author

Ramya Badathala  
[LinkedIn](#) | [GitHub](https://github.com/RamyaBadathala)

