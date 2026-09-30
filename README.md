# 📊 Banking Transaction Analysis — Power BI

## 🔹 Project Overview

Banking Transaction Analysis is an interactive Power BI dashboard developed to analyze banking transaction data and identify important patterns in transaction values, transaction types, payment modes, and customer categories.

The dashboard transforms raw banking data into meaningful KPIs, visualizations, and business insights.

## 🎯 Business Problem

Banks generate large volumes of transactions through different channels and transaction types. Analyzing this data manually can make it difficult to identify important trends and patterns.

This project analyzes banking transactions to answer important business questions such as:

- What is the total transaction value?
- How many transactions were performed?
- How many customer accounts are involved?
- Which transaction mode has the highest transaction value?
- Which transaction types contribute the most?
- Which customer categories have higher transaction activity?
- How does transaction activity change over time?

## 🎯 Objectives

- Analyze overall banking transaction performance.
- Monitor important banking KPIs.
- Compare different transaction modes.
- Analyze transaction types and their values.
- Understand customer-category transaction activity.
- Identify transaction trends and patterns.
- Create an interactive Power BI dashboard.

## 📁 Dataset

The cleaned dataset contains:

- **20,999 transactions**
- **18,803 unique customer accounts**

### Important Columns

| Column | Description |
|---|---|
| `transaction_id` | Unique transaction ID |
| `account_id` | Customer account ID |
| `txn_date` | Transaction date |
| `txn_type` | Type of transaction |
| `amount` | Transaction amount |
| `Transaction_Mode` | Transaction channel |
| `Customer_category` | Customer category |

### Transaction Types

- Deposit
- Withdrawal
- Transfer In
- Transfer Out
- Interest Credit
- Fee Debit

### Transaction Modes

- UPI
- Mobile App
- POS
- Branch
- ATM
- Online Banking

## 🛠️ Tools Used

- **Microsoft Power BI**
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Visualization

## 📌 KPIs

| KPI | Value |
|---|---:|
| Total Transaction Value | ₹127.01M |
| Total Transaction Count | 20,999 |
| Active Customer Accounts | 18,803 |
| Average Transaction Amount | ₹6,048.24 |
| Total Deposits | ₹31.49M |
| Total Withdrawals | ₹31.28M |
| Total Transfer Amount | ₹38.17M |
| Average Spend per Category | ₹9.07M |

## 📊 Dashboard Features

### 1. Transaction Mode Analysis

Compares transaction values across:

- UPI
- Mobile App
- POS
- Branch
- ATM
- Online Banking

### 2. Transaction Type Analysis

Analyzes transaction values across deposits, withdrawals, transfers, interest credits, and fee debits.

### 3. Customer Category Analysis

Analyzes transaction values across different customer categories such as Travel, Rent, Entertainment, Dining, Shopping, Healthcare, Education, Utilities, Fuel, Insurance, Salary Credit, ATM Withdrawal, Fund Transfer, and Groceries.

### 4. Transfer Analysis

Analyzes transfer amounts across customer categories.

### 5. Yearly Transaction Analysis

Shows transaction activity over time.

### 6. KPI Monitoring

Provides important banking metrics through KPI cards.

## 🔍 Key Insights

- The dataset contains **20,999 transactions** across **18,803 unique customer accounts**.
- Total transaction value is approximately **₹127.01 million**.
- **Mobile App** records the highest transaction value among the transaction modes, at approximately **₹21.95M**.
- Total deposits are approximately **₹31.49M**.
- Total withdrawals are approximately **₹31.28M**.
- Transfer transactions account for approximately **₹38.17M**.
- **Travel** records the highest transaction value among the customer categories, at approximately **₹9.41M**.
- The average transaction amount is approximately **₹6,048**.

## 📷 Dashboard Preview

![Banking Transaction Analysis Dashboard](Dashboard_Screenshot.png)

## 📂 Project Structure

```text
Banking-Transaction-Analysis-PowerBI/
│
├── Final Dashboard Banking Analysis.pbix
├── cleaned banking dataset.xls
├── Dashboard_Screenshot.png
└── README.md
