
# 📊 FinSight – Financial Analysis Dashboard

## 📌 Project Overview

FinSight is an interactive **Financial Analysis Dashboard** built using Microsoft Power BI.

This project provides insights into financial transactions, customers, transaction status, customer segments, transaction types, fees,
taxes, and regional performance.

The dashboard uses a **Customers Table, Finance_Transactions Table, and Calendar Date Table**, along with a **Dynamic Matrix** for flexible financial
analysis.

---

## 🎯 Problem Statement

Financial transaction data is often stored across multiple tables, making it difficult to monitor performance, analyze customer behavior,
and track financial metrics.

The objective of this project is to develop an interactive Power BI dashboard that helps users:

- Monitor financial transaction performance.
- Analyze transaction amounts over time.
- Understand successful, failed, and pending transactions.
- Compare customer segments and states.
- Analyze transaction types, fees, and taxes.
- Explore financial metrics using a dynamic matrix.

---

## 🗂️ Data Model

### 1. Customers Table

Contains customer-related information:

- Customer ID
- Customer Name
- Gender
- Customer Segment
- State
- Occupation
- Category

### 2. Finance_Transactions Table

Contains transaction-related information:

- Transaction ID
- Transaction Date
- Transaction Type
- Transaction Status
- Total Amount
- Total Fees
- Total Tax
- Customer-related transaction details

### 3. Calendar Date Table

A dedicated Calendar Table was created for time-based analysis.

It supports:

- Year-wise analysis
- Monthly analysis
- Date filtering
- Year-over-year comparisons

---

## ⚙️ Power BI Features Used

- Power Query for data transformation
- Data modeling and relationships
- DAX measures
- Calendar Date Table
- KPI Cards
- Slicers
- Dynamic Matrix
- Line Charts
- Donut Charts
- Bar Charts
- Conditional Formatting
- Year-wise Filtering

---

## 📊 Dashboard Components

### 🔹 KPI Cards

The dashboard includes the following key performance indicators:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Year-over-Year Percentage Comparison

### 🔹 Visualizations

The dashboard provides:

- Total Amount by Month
- Total Amount by Transaction Status
- Total Amount by Customer Segment
- Total Amount by State
- Transaction Type Analysis
- Total Amount by Gender
- Transaction-Level Details Table

---

## 🔄 Dynamic Matrix

A Dynamic Matrix was created using the Finance_Transactions Table.

It allows users to analyze different financial measures dynamically, such as:

- Total Amount
- Total Fees
- Total Tax
- Transaction Count
- Other financial measures

This improves dashboard flexibility and allows users to switch between different metrics without creating separate visuals for every 
measure.

---

## 📈 Key Insights

Based on the dashboard:

- **Retail customers** contribute the highest transaction amount among the displayed customer segments.
- **Successful transactions** represent the largest share of total transaction value.
- Transaction amounts vary across states, providing insights into regional financial performance.
- Different transaction types contribute varying amounts of fees, taxes, and transaction volumes.
- Monthly transaction values fluctuate throughout the year.
- Gender-based analysis provides a comparison of transaction value between male and female customers.
- The dynamic matrix enables flexible analysis of financial metrics.

> Note: These insights are based on the dashboard visuals. Detailed business conclusions should be validated using the complete dataset.

---

## 💼 Business Value

This dashboard can help businesses:

- Monitor financial performance.
- Analyze customer transaction behavior.
- Compare regional performance.
- Track transaction fees and taxes.
- Identify monthly transaction trends.
- Analyze transaction success and failure.
- Support data-driven decision-making.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & Calculations |
| Data Modeling | Table Relationships |
| Calendar Table | Time Intelligence |
| GitHub | Project Documentation |

---

## 🚀 Future Improvements

- Customer Lifetime Value Analysis
- Fraud and Anomaly Detection
- Risk Scoring
- Customer-Level Drill-Through
- Advanced Year-over-Year Analysis
- Monthly Transaction Forecasting
- Automated Data Refresh
- Customer Retention Analysis

---


## 👤 Author

**Shalu Songara**

📊 Data Analytics | Microsoft Power BI | SQL

**Project:** FinSight – Financial Analysis Dashboard

**Tool:** Microsoft Power BI

---

## ⭐ Project Highlights

- Interactive Financial Dashboard
- Customer & Finance Data Analysis
- Dynamic Matrix
- Calendar Date Table
- DAX-Based KPI Analysis
- Transaction Performance Insights

---

⭐ If you find this project useful, feel free to explore the repository and connect with me for collaboration and data analytics 
discussions.
