# 📊 Telco Customer Churn Analysis (Power BI Project)

## 🔹 Project Overview
This project analyzes customer churn for a telecom company using Power BI.  
The goal is to identify churn drivers, measure financial impact, and provide actionable insights for retention strategies.  

## 🔹 Dataset
- **Source**: Telco Customer Churn dataset (CSV)  
- **Rows**: ~7,043 customers  
- **Key fields**: tenure, contract type, monthly charges, internet services, payment method, churn flag.  

## 🔹 Data Preparation
- Cleaned nulls in `TotalCharges`.  
- Added calculated columns: `NumServices`, `LifetimeValue`, `TenureGroup`.  
- Built a **Star Schema** with FactCustomers + Dim tables.  

## 🔹 Dashboard Pages
1. **Overview** → KPIs (Total Customers, Churn Rate, Revenue Lost).  
2. **Demographics** → Churn by Gender, Senior Citizen, Dependents, Partner.  
3. **Tenure & Behavior** → Tenure distribution, Contract type churn, Billing impact.  
4. **Services & Contracts** → Internet type, Payment method, service add-ons.  
5. **Financial Impact** → Revenue lost, Lifetime value of churned customers.  

## 🔹 Key Insights
- Month-to-month contract customers churn at the highest rate.  
- Fiber Internet users show higher churn compared to DSL users.  
- Senior Citizens and customers without partners/dependents have higher churn.  
- High-value customers (high monthly charges) contribute disproportionately to revenue loss.  

## 🔹 Tools Used
- Power BI (DAX, Data Modeling, Interactive Visuals)  
- Power Query (Data cleaning & transformation)  

## 🔹 Files in Repo
- `Telco business analysis.pbix` → Power BI Dashboard file  
- `/screenshots` → PNG images of each dashboard page  
- `README.md` → Project documentation  

---

⭐ If you like this project, give it a star on GitHub!  
