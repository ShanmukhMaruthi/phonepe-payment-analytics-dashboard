# 📱 PhonePe Payment Analytics Dashboard

An end-to-end **Power BI** project that analyzes digital payment transactions using **Power Query**, **DAX**, and **Star Schema Data Modeling**. The dashboard provides interactive insights into transaction performance, payment success, user behavior, service utilization, and business trends through dynamic visualizations and KPI tracking.

---

## 🚀 Project Overview

This project demonstrates how Power BI can be used to transform raw payment data into meaningful business insights. The dashboard enables users to monitor transaction performance, analyze payment trends, evaluate service usage, and understand customer demographics through interactive reports.

---

## 🛠️ Tech Stack

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Star Schema
- Microsoft Excel

---

## 📂 Dataset

The project uses two datasets:

- **Transactions Dataset**
- **Users Dataset**

The datasets include information such as:

- Transaction ID
- User ID
- Transaction Amount
- Payment Status
- Service
- Service Type
- Transaction Date
- User Name
- Age
- Join Date

---

## 🔄 Data Preparation

Performed data transformation using **Power Query** by:

- Removing duplicate records
- Handling missing values
- Standardizing data types
- Replacing inconsistent values
- Creating Age Segment categories
- Preparing clean datasets for analysis

---

## 📊 Data Modeling

Implemented a **Star Schema** by creating relationships between:

- Fact Table
  - All_Transactions

- Dimension Tables
  - All_Users
  - Date_Table

Created a custom **Date Table** using DAX to support Time Intelligence calculations.

---

## 📈 DAX Measures

Created reusable DAX measures including:

- Total Transactions
- Total Transaction Value
- Total Users
- Successful Transactions
- Success Rate
- Previous Month Transactions
- Previous Month Transaction Value
- Transaction MoM %
- Transaction Value MoM %

---

## 📊 Dashboard Features

The interactive dashboard includes:

- KPI Cards
  - Total Transactions
  - Total Transaction Value
  - Total Users
  - Success Rate

- Transaction Trend Analysis

- Service-wise Transaction Analysis

- Age Segment Contribution

- Top Users by Transaction Value

- Weekday vs Weekend Transaction Analysis

- Payment Status Filter

- Month Filter

- Interactive Report Tooltips

---



## 💡 Key Business Insights

- Payment success rate remained consistently above 95%.
- Millennials generated the highest transaction value.
- Weekday transactions were significantly higher than weekend transactions.
- UPI-based services accounted for the majority of transactions.
- Transaction trends revealed monthly performance fluctuations.
- Service-wise analysis identified the most frequently used payment services.

---

## 📁 Repository Structure

```
phonepe-payment-analytics-dashboard
│
├── Dataset
├── PowerBI
│   └── PhonePe Dashboard.pbix
├── Dashboard Screenshots
├── README.md
└── LICENSE
---assest
```

---

## 🎯 Skills Demonstrated

- Power BI Dashboard Development
- Data Cleaning
- Data Transformation
- Power Query
- DAX
- Data Modeling
- Star Schema
- Time Intelligence
- Business Intelligence
- KPI Dashboard Design
- Interactive Data Visualization

---



---

⭐ If you found this project useful, consider giving it a star!
