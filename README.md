# 🧩 Product Analytics Pipeline

## 📘 Overview  
The **Product Analytics Pipeline** project simulates a real-world SaaS analytics system. It generates synthetic user, event, and subscription data to calculate key product performance metrics such as **MAU**, **WAU**, and **ARR**.  
This project demonstrates an **end-to-end data analytics workflow** — from data generation and storage to querying and visualization — using **Python, SQL, Amazon Redshift, and Tableau**.

---

## 🎯 Objectives  
- Simulate user behavior data for a SaaS-like product.  
- Store and process data in a scalable cloud environment (Amazon S3 + Redshift).  
- Compute essential product KPIs:  
  - Daily/Weekly/Monthly Active Users (DAU, WAU, MAU)  
  - Gross and Cancelled Annual Recurring Revenue (ARR)  
  - User retention and engagement metrics  
- Build interactive dashboards for business insights.

---

## 🗂️ Project Structure  
```
product-analytics-project/
│
├── product_data.ipynb # Data generation and exploration
├── daily_dump.csv # Synthetic user interaction data
├── mapping_sheet.csv # Date mapping for weekly/quarterly aggregation
├── subscription_data.csv # Subscription and revenue data
│
├── DAU.sql # Query for Daily Active Users
├── WAU.sql # Query for Weekly Active Users
├── MAU.sql # Query for Monthly Active Users
├── Gross_ARR.sql # Query for Gross ARR
├── Tall_table.sql # Combined data table query
│
└── README.md # Project documentation
```

---

## ⚙️ Tools & Technologies  
- **Python** – Data generation and preprocessing  
- **Amazon S3** – Data storage  
- **Amazon Redshift** – Data warehouse and SQL analytics  
- **Tableau** – Visualization and dashboard creation  
- **SQL** – KPI computation queries  

---

## 📊 Key Metrics Calculated  
- **DAU / WAU / MAU:** Active user metrics to track engagement  
- **Gross ARR / Cancelled ARR:** Revenue and churn insights  
- **Project creation & export counts:** Product usage trends  
- **Retention metrics:** New vs. returning users  

---

## 🚀 Workflow  
1. **Data Generation** – Synthetic datasets created in Python.  
2. **Data Storage** – Uploaded to Amazon S3 for scalability.  
3. **Data Processing** – Redshift queries compute core KPIs.  
4. **Visualization** – Tableau dashboards display interactive insights.  

---

## 💡 Insights & Outcomes  
- Built a comprehensive view of product performance and user engagement.  
- Enabled data-driven decision-making via KPI tracking and dashboards.  
- Demonstrated cloud-based analytics and business intelligence integration.  


