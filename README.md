# 📊 Telecom Customer Analytics Dashboard

## 📌 Project Overview

This project presents an end-to-end Telecom Customer Analytics Dashboard developed using **Power BI** to transform raw telecom customer data into actionable business insights. The dashboard focuses on customer acquisition, revenue performance, subscription plans, churn behaviour, payment trends, and data quality assessment.

The objective of this project is to help business stakeholders monitor KPIs, identify customer trends, understand churn behaviour, and make data-driven decisions through interactive visualizations.

---

# 🎯 Business Objectives

- Monitor overall business performance using KPIs.
- Analyze customer acquisition trends.
- Identify high-performing cities and regions.
- Compare revenue across subscription plans.
- Analyze customer churn behaviour.
- Evaluate payment behaviour over time.
- Detect data quality issues affecting reporting.
- Generate business recommendations from analytical findings.

---

# 📂 Dataset

The dashboard is built using a telecom customer dataset containing approximately **10,000 customer records**.

### Dataset includes:

- Customer Information
- Region
- City
- Subscription Plan
- Signup Date
- Monthly Charges
- Call Minutes
- Total Revenue
- Payment Status
- Last Payment Date
- Churn Status

---

# 🧹 Data Cleaning

Data preparation involved:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Date formatting
- Standardizing categorical values
- Exploratory Data Analysis (EDA)
- Data validation
- Data quality assessment

## Data Quality-

- The dataset contains approximately 5,000 missing values in the `last_payment_date` column.
- These values were preserved rather than imputed because they may represent customers with no recorded payment activity or inactive accounts.
- Date-based analyses were performed only on records with valid payment dates.
- The dashboard includes a data quality analysis page to highlight this limitation and ensure transparent reporting.



---

# 📊 Dashboard Pages

## 1️⃣ Executive Dashboard

Provides an overall business summary through KPIs including:

- Total Customers
- Total Revenue
- Average Monthly Charges
- Churn Rate
- Top Revenue Cities
- Revenue by Region
- Revenue by Plan Type
- Payment Status Overview

---

## 2️⃣ Customer & Churn Analysis

Focuses on customer retention and churn behaviour.

Visualizations include:

- Churn Rate by City
- Churn Rate by Region
- Churn Trend by Year
- Churn Trend by Plan Type
- Revenue vs Churn Analysis

---

## 3️⃣ Revenue & Customer Behaviour

Analyzes revenue generation and customer performance.

Includes:

- Monthly Revenue Trend
- Revenue Contribution by Customer Segment
- Sales Agent Performance
- Monthly Charges vs Total Revenue
- Customer Count by Year
- Average Revenue Trend

---

## 4️⃣ Payment Analysis

Analyzes payment behaviour across customers.

Includes:

- Payment Behaviour Over Time
- Payment Status Distribution
- Monthly Payment Activity
- Payment Date Availability

---

## 5️⃣ Data Quality Assessment

A dedicated page evaluating dataset quality.

This analysis identified:

- Missing values in `last_payment_date`
- Distribution of missing records
- Impact on date-based analysis
- Data completeness assessment

Instead of replacing missing dates with artificial values, the project preserved the original records, created data quality flags, excluded affected rows from date-based calculations where appropriate, and documented the limitation for stakeholders. :contentReference[oaicite:2]{index=2}

---

# 📈 Key KPIs

- Total Customers
- Total Revenue
- Average Revenue
- Average Monthly Charges
- Revenue Growth
- Churn Rate
- Customer Growth
- Payment Status
- Revenue by Plan
- Revenue by Region

---

# 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- SQL
- Microsoft Excel
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence

---

# 💡 Key Insights

- Lucknow generated the highest overall revenue among the analyzed cities.
- Basic and Premium subscription plans contributed the majority of total revenue.
- Customer count dropped significantly in 2025, affecting average revenue calculations for that year.
- High-value customers generated a disproportionately large share of total revenue.
- Payment behaviour remained relatively stable across years.
- Data quality analysis identified missing payment dates and documented their impact on reporting rather than masking the issue. 

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- KPI Development
- Dashboard Design
- Business Intelligence
- Exploratory Data Analysis
- Data Quality Assessment
- Business Storytelling
- Analytical Thinking

---

# 📷 Dashboard Preview

Dashboard Pages

- Executive Dashboard
<img width="1346" height="732" alt="Screenshot 2026-07-08 230214" src="https://github.com/user-attachments/assets/1828bbbb-a450-4898-b78b-80946f9e5e74" />
- Customer & Churn Analysis
<img width="1313" height="552" alt="Screenshot 2026-07-08 230230" src="https://github.com/user-attachments/assets/cf131a78-29e3-4f36-a7e1-d7b95aaa355f" />
- Revenue & Customer Behaviour
<img width="1336" height="712" alt="Screenshot 2026-07-08 230625" src="https://github.com/user-attachments/assets/d9327d0c-c3f5-4fa1-8fe2-b26697faca45" />
- Data quality assessment 
<img width="1370" height="727" alt="Screenshot 2026-07-10 145145" src="https://github.com/user-attachments/assets/f5a3ff5c-6a8b-449d-b44a-465ebb2d8308" />





































---

# 🔮 Future Enhancements

- Customer Lifetime Value (CLV) Analysis
- Revenue Forecasting
- Predictive Churn Modeling
- Power BI Service Deployment
- Automated Data Refresh

---

# 👨‍💻 Author

**Yash Shukla**

Data Analyst | SQL | Python | Power BI

If you found this project useful, consider giving it a ⭐.

## ⭐ If you found this project helpful, please consider giving it a star!
