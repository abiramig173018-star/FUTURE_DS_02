📊 SaaS Customer Churn & Retention Analysis (Power BI)
📌 Project Overview

This project analyzes customer churn patterns for a subscription-based SaaS company using Power BI.

The objective was to:

Identify churn drivers

Analyze retention trends

Segment customers by tenure and contract type

Estimate revenue impact of churn

Provide strategic recommendations as a business consultant

🗂 Dataset Description

The dataset contains customer-level subscription information including:

CustomerID

Tenure (months subscribed)

Contract Type (Month-to-month, One-year, Two-year)

Internet & Add-on Services

Payment Method

Monthly Charges

Total Charges

Churn (Yes/No)

🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (Data Cleaning & Transformation)

Data Modeling

Business KPI Design

📈 Key Business Metrics Created

Total Customers

Churned Customers

Churn Rate

Average Revenue per User (ARPU)

Average Tenure

Revenue Lost Due to Churn

Customer Lifetime Value (CLV – estimated)

🔍 Key Insights

1️⃣ Contract Type is the strongest churn driver
Month-to-month customers show significantly higher churn compared to annual contracts.

2️⃣ Early lifecycle churn is highest
Customers in the 0–12 month tenure group have the highest churn probability → indicates onboarding issues.

3️⃣ Service Add-ons influence retention
Customers without Tech Support or Online Security churn at a much higher rate.

4️⃣ Revenue Risk Concentration
A large portion of revenue loss comes from high-paying month-to-month customers.

📊 Dashboard Structure
Page 1 – Executive Overview

KPI Summary

Churn Rate by Tenure

Churn Rate by Contract

Revenue Overview

Page 2 – Retention Drivers

Churn by Service Add-ons

Churn by Payment Method

Customer Risk Segmentation

Decomposition Tree Analysis

Page 3 – Revenue & Lifetime Value

Revenue by Contract

Estimated CLV

Revenue Lost to Churn

🎯 Business Recommendations

Incentivize migration from month-to-month to annual contracts

Improve onboarding experience within first 12 months

Bundle Tech Support & Security services to reduce churn

Monitor high-risk customer segments using churn indicators

📂 Repository Contents

Task 2.pbix – Power BI dashboard file

dataset.csv – Raw dataset

README.md – Project documentation

dashboard_screenshots/ – Dashboard visuals

🚀 Future Improvements

Implement churn prediction using Machine Learning

Build a churn probability model in Python

Deploy dashboard to Power BI Service

Automate refresh using real-time data
