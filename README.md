📊 Bank Customer Churn Analysis – SQL + Power BI

A complete end-to-end churn analytics project combining SQL data modeling and Power BI dashboarding to identify churn drivers, high-risk customers, and retention opportunities.

📌 Project Overview

This project analyzes bank customer churn using SQL for data preparation and Power BI for visual storytelling.
The objective is to understand why customers leave, segment high-risk groups, and provide data-driven recommendations for customer retention.

🔥 Project Workflow

Designed a fact table and star schema using SQL.

Built SQL queries to calculate churn metrics, customer segmentation, and outlier detection.

Created DAX measures for KPIs such as Churn Rate, Avg Balance, Avg Tenure, and Active Customer Rate.

Built a 4-page interactive Power BI dashboard to present insights.

🗂 Dataset

The dataset is composed of 7 tables, used to build dimensional modeling:

Table Name	Description
Bank_Churn	Core customer attributes (tenure, balance, churn flag).
CustomerInfo	Customer demographics – age, salary, DOJ, gender ID, geography ID.
Gender	Gender categories.
Geography	Regions (France, Spain, Germany).
CreditCard	Credit card type details.
ActiveCustomer	Account activity status.
ExitCustomer	Churn reasons.
🏗 Data Modeling

Designed a star schema centered around a consolidated fact table:
fact_bank_churn

Merged customer demographics, geography, gender, credit card, and churn details.

Ensured optimized relational joins for efficient Power BI querying.

📊 Dashboard Pages
1️⃣ Executive Overview

KPIs: Avg Age, Avg Balance, Avg Tenure, Salary, Churn Rate

High-level insights for stakeholders
Screenshot:
https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_index.png

2️⃣ Customer Behavior

Churn by age group, tenure, products, and account activity

Key Insight: Highest churn among customers aged 30–39 and those holding multiple products
Screenshot:
https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_customer_behavior.png

3️⃣ Geography & Demographics

Churn by country, gender, and customer profile segments

Insight: Germany shows the highest churn rate
Screenshot:
https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_geography_and_demographic.png

4️⃣ Risk & Predictions

Outlier detection in balance, credit score, and tenure

High-risk customer segmentation for targeted retention
Screenshot:
https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_risk_and_predictions.png

📌 Key Insights

Overall Churn Rate: 20.37%

Germany has the highest churn rate among all regions.

Customers with low credit scores are more likely to churn.

Credit card ownership does not significantly affect churn.

Female customers churn slightly more than male customers.

Customers with 3–6 years tenure are at the highest churn risk.

🚀 Tools & Technologies Used

SQL (MySQL Workbench) → star schema, fact table creation, data modeling

Power BI → interactive dashboard, DAX measures, KPI design

Excel → initial data cleaning and preparation

🎯 Business Impact

This churn analysis helps the bank to:

Identify high-value at-risk customers

Detect behavioral churn patterns

Build targeted retention campaigns

Improve customer satisfaction & reduce potential revenue loss

Prioritize product improvements, customer support interventions, and risk management strategies
