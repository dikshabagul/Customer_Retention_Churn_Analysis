📊 Customer Retention & Churn Analysis

Python · SQL · Power BI

An end-to-end data analytics project focused on understanding customer churn and improving retention strategies in the telecom domain. This project uses Python for data cleaning and analysis, SQL for business insights, and Power BI for interactive dashboard reporting.

🔍 Project Overview

Customer retention is critical for telecom businesses. This project analyzes customer behavior and service usage to identify churn patterns and key factors affecting customer retention.

Objectives:

Analyze customer churn trends

Identify high-risk customer segments

Support retention decisions using data-driven insights

Present findings through an interactive Power BI dashboard

🧰 Tools & Technologies

Python: Pandas, NumPy

Visualization (Python): Matplotlib, Seaborn

SQL: Business analysis and churn queries

BI Tool: Power BI

Environment: Jupyter Notebook

📁 Project Structure
Customer-Retention-and-Churn-Analysis/
│
├── data/
│   ├── Telco_Customer_Churn.csv
|   ├── Telco_churn_clean_for_powerBi
|   └── Wa_fn_usesC_-Telco-Customer-churn
│
├── Jupyter otebook/
│   ├── 01_data_cleaning.ipynb
│   └── dataset loading into mysql.ipynb
│
├── powerbi/
│   └──Customer_Retention_&_Churn_Analysis.pbix
│
├── outputs/
│   └── charts/
│
└── README.md

🧹 Data Cleaning & Preparation (Python)

Removed missing and invalid values

Converted numerical columns (MonthlyCharges, TotalCharges)

Encoded categorical variables

Created churn-related metrics

Prepared clean datasets for SQL and Power BI

📈 Exploratory Data Analysis (Python)

Key insights identified:

Customers with Month-to-Month contracts have higher churn

Electronic Check payment method shows higher churn rates

Customers with short tenure are more likely to churn

Higher Monthly Charges increase churn probability

Customers without support services churn more frequently

🗄️ SQL Analysis

SQL queries were used to:

Analyze churn distribution across customer segments

Identify high-churn contract and payment types

Calculate churn rate and retention metrics

Support business-level reporting

📊 Power BI Dashboard

The interactive dashboard provides a business-ready view of churn and retention performance.

Key KPIs

Total Customers

Total Churned Customers

Churn Rate (%)

Average Monthly Charges

Average Tenure

Average Total Charges

Dashboard Insights

Churn by Contract Type

Churn by Payment Method

Churn by Internet Service

Churn by Tenure Group

Revenue impact of churn

📁 File: powerbi/churn_dashboard.pbix

🎯 Business Impact

Helps businesses identify high-risk churn segments

Supports customer retention strategies

Enables data-driven decision-making

Translates raw data into actionable insights
