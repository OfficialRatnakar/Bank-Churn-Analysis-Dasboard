# 🏦 Bank Customer Churn Analysis – SQL + Power BI

### **End-to-End Churn Analytics | Data Modeling + Dashboard Storytelling | By Vishal Ratnakar**

<p align="center">
  <img src="https://img.shields.io/badge/Skills-SQL-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tools-Power%20BI-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Banking%20Analytics-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Churn%20Prediction%20%7C%20Segmentation-purple?style=for-the-badge" />
</p>

---

## 📌 **Project Overview**

This project focuses on understanding **why bank customers churn** by leveraging SQL for **data modeling & metric building** and Power BI for **interactive dashboards**.
The goal is to uncover churn drivers, segment customers by risk level, and deliver insights that guide **customer retention strategies**.

### 🔥 Highlights

* Built a **fact table** using SQL from multiple source tables
* Designed a **star schema** for efficient querying
* Created **DAX measures** for KPIs such as *Churn Rate, Avg Balance, Avg Tenure*
* Developed a **4-page Power BI dashboard** for decision-makers
* Identified high-risk customer groups using SQL + BI

---

## 🗂 **Dataset Overview**

The project uses **7 relational tables**, enabling rich, multi-angle analytics:

| Table              | Description                                                      |
| ------------------ | ---------------------------------------------------------------- |
| **Bank_Churn**     | Core churn attributes: balance, credit score, tenure, churn flag |
| **CustomerInfo**   | Demographics: gender, age, salary, geography, DOJ                |
| **Gender**         | Gender categories                                                |
| **Geography**      | Regions: France, Spain, Germany                                  |
| **CreditCard**     | Card type information                                            |
| **ActiveCustomer** | Account activity levels                                          |
| **ExitCustomer**   | Reasons for customer churn                                       |

---

## 🏗 **Data Modeling**

### ⭐ Star Schema (Dimensional Model)

Built a consolidated fact table:

### **`fact_bank_churn`**

This fact table integrates:
✔ Customer demographics
✔ Geography
✔ Credit card info
✔ Churn reason
✔ Account activity
✔ Financial details

This schema enabled fast Power BI reporting and flexible KPI calculations.

---

## 📊 **Dashboard Pages**

### **1️⃣ Executive Overview**

* KPIs: **Avg Age**, **Avg Balance**, **Avg Tenure**, **Avg Salary**, **Churn Rate**
* High-level snapshot for leadership
  📸 Screenshot:
  [https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_index.png](https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_index.png)

---

### **2️⃣ Customer Behavior**

* Churn by **age group**, **tenure**, **products**, **activity status**
* Insight: Highest churn among **30–39 age group** & **multi-product customers**
  📸 Screenshot:
  [https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_customer_behavior.png](https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_customer_behavior.png)

---

### **3️⃣ Geography & Demographics**

* Churn segmented by **region** and **gender**
* Germany stands out as the **highest-risk market**
  📸 Screenshot:
  [https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_geography_and_demographic.png](https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_geography_and_demographic.png)

---

### **4️⃣ Risk & Predictions**

* Outlier analysis for **balance**, **credit score**, **tenure**
* High-risk customer groups identified using SQL logic
  📸 Screenshot:
  [https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_risk_and_predictions.png](https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_risk_and_predictions.png)

---

## 📌 **Key Insights**

* **Churn Rate:** **20.37%** across all customers
* **Germany** = highest churn geography
* **Low credit score** strongly correlates with churn
* **Female customers** churn slightly more than males
* Customers with **3–6 years tenure** are at highest churn risk
* Multiple products ≠ lower churn — in fact, churn increases
* Credit card ownership has **minimal influence** on churn

---

## 🚀 **Tools & Technologies**

* **SQL (MySQL Workbench)** → Data modeling, fact table creation, churn queries
* **Power BI** → Dashboard creation, DAX measures, KPI design
* **Excel** → Data preparation & validation

---

## 🎯 **Business Impact**

This project helps the bank:

* Identify **high-risk, high-value** customers
* Build **targeted retention campaigns**
* Reduce revenue leakage by addressing churn drivers
* Improve user experience through data-backed decisions
* Optimize marketing spend on the right customer segments

---
<img width="2372" height="1385" alt="image" src="https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_risk_and_predictions.png" />
<img width="2372" height="1385" alt="image" src="https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_geography_and_demographic.png" />
<img width="2372" height="1385" alt="image" src="https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_index.png" />
<img width="2372" height="1385" alt="image" src="https://github.com/OfficialRatnakar/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_customer_behavior.png" />




## 📦 **Repository Structure**

```
├── README.md
├── Bank-Churn-Analysis-Dasboard.pbix (if uploaded)
├── SQL Queries/
│   ├── data_modeling.sql
│   ├── churn_metrics.sql
│   ├── segmentation_queries.sql
│   ├── outlier_detection.sql
│   └── kpi_queries.sql
└── assets/
    ├── dashboard_screenshots/
```

---

## 👨‍💻 **Author**

**Vishal Ratnakar**
SQL Developer | Power BI Analyst | Data Storyteller

---

## ⭐ **If you found this project useful, please consider starring the repository!**


