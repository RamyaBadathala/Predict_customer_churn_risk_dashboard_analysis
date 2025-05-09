# Predict_customer_churn_risk_dashboard_analysis
This is my project which analyzes customer data to predict churn and identify high-risk customers using basic data analysis and techniques.
# 📊 Predicting Customer Churn and Risk Analysis for future business with Excel and Power BI

This project analyzes telecom customer data to identify churn patterns and high-risk segments. It uses **Excel** for data preprocessing and **Power BI** for interactive dashboards.

---

## 📁 Dataset Overview

**Sheet**: `01 Churn-Dataset`  
**Rows**: ~7,000  
**Columns**: 23  
Includes customer demographics, service usage, support tickets, billing, and churn labels.

### Key Columns:
- `customerID`: Unique customer identifier  
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`: Demographics  
- `tenure`: Number of months as a customer  
- `PhoneService`, `InternetService`, `StreamingTV`: Services subscribed  
- `Contract`, `PaperlessBilling`, `PaymentMethod`: Account & billing  
- `MonthlyCharges`, `TotalCharges`: Financial metrics  
- `numAdminTickets`, `numTechTickets`: Support interaction frequency  
- `Churn`: Target column (Yes/No)

---

## 🛠 Steps for Analysis

### 1. **Excel – Data Preprocessing**
- **Remove Duplicates**: Ensure `customerID` is unique
- **Handle Missing Values**: Especially in `TotalCharges` (may be blanks)
- **Transform Columns**:
  - Convert categorical columns to consistent labels (e.g., Yes/No → 1/0)
  - Create new columns (e.g., `AverageCharges = TotalCharges / tenure`)
- **Save Clean File**: Save as `cleaned_customer_churn.xlsx`

### 2. **Power BI – Dashboard Creation**
- **Import Cleaned Excel File**
- **Create Visuals**:
  - **KPI Cards**: Churn rate, Avg Monthly Charges, Avg Tenure
  - **Pie Charts**: Churn % by gender, contract type
  - **Bar Charts**: MonthlyCharges by Churn, numTechTickets vs Churn
  - **Slicers**: Gender, Contract, InternetService
- **Add Filters & Tooltips** for interactivity
- **Create a Summary Page**:
  - Key insights from churn trends
  - Recommendations to reduce churn

---

## 🔍 Example Questions to Explore
- Which service types correlate with higher churn?
- Do customers with more tech support tickets churn more?
- How does contract type (e.g., Month-to-month vs. One year) affect churn?

---

## ✅ Outcome
A fully interactive Power BI dashboard highlighting:
- Churn drivers  
- High-risk customer segments  
- Actionable retention insights
