# 📉 Customer Churn Risk Prediction & Dashboard Analysis

This project focuses on identifying high-risk customers likely to churn using data analysis and visual representation through a Power BI dashboard.

## 📌 Project Objective

To analyze customer behavior patterns and predict churn risk using Excel and Power BI. The dashboard enables business teams to track churn trends, identify at-risk customers, and make data-driven retention strategies.

---

## 🧰 Tools & Technologies Used

- **Excel** – Data cleaning and preprocessing
- **Power BI** – Dashboard development and data visualization
- **Python (Optional)** – Can be used for further machine learning model development

---

## 📊 Dataset

- **File**: `Customer analysis Dataset.xlsx`
- Contains customer demographics, service usage, subscription types, and churn status.
- Key columns: `Gender`, `SeniorCitizen`, `Partner`, `Dependents`, `Tenure`, `MonthlyCharges`, `Contract`, `PaymentMethod`, `Churn`, etc.

---

## 🧪 Workflow

1. **Data Cleaning**  
   Performed in Excel (handled nulls, formatted columns).

2. **Feature Understanding**  
   Explored patterns in tenure, payment method, contract type, etc.

3. **Churn Analysis**  
   Identified key churn indicators based on filters and charts.

4. **Dashboard Creation**  
   Built in Power BI with filters and visual elements like:
   - Pie charts for churn distribution
   - Bar graphs for contract types vs churn
   - Risk segments and key metrics

---

## 📸 Dashboard Preview

![Churn Dashboard](images/customer%20churn%20dashboard.png)  
![Risk Dashboard](images/customer%20risk%20dashboard.png)

---

## 📁 Project Structure

Predict_customer_churn_risk_dashboard_analysis/
├── data/
│ └── Customer analysis Dataset.xlsx
├── dashboard/
│ └── Customer Analysis Dashboard.pbix
├── images/
│ ├── customer churn dashboard.png
│ └── customer risk dashboard.png
└── README.md



---

## 📌 Key Insights

- Customers on **month-to-month** contracts have the **highest churn**.
- **Longer tenure** correlates with **lower churn probability**.
- Customers using **electronic checks** churn more frequently.
- **Senior citizens** have a slightly higher churn rate.

---

## 🌐 Future Enhancements

- Add a predictive machine learning model using Python (Random Forest or Logistic Regression).
- Integrate dashboard with real-time data using Power BI service.
- Build a web app using Streamlit or Flask for live predictions.

---

## 👩‍💻 Author

**Ramya Badathala**  
📧 [YourEmail@example.com]  
🔗 [GitHub Profile](https://github.com/RamyaBadathala)

---

## ⚖️ License

This project is open-source and available under the [MIT License](LICENSE).



