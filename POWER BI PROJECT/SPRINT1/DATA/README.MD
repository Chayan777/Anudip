# Indian Banking Analytics Dataset

## Project Overview

This dataset is designed for data analytics, business intelligence, and dashboard development using the Indian banking sector. It contains synthetic data representing multiple banks, customers, accounts, branches, transactions, loans, and other banking-related information.

The dataset is suitable for building interactive dashboards using Power BI, Tableau, Excel, SQL, and Python.

> **Disclaimer:** This is a synthetic dataset created for educational, analytical, and portfolio-project purposes. It does not contain real customer information or represent actual financial records of banks.

---

## Dataset Features

- Multi-bank analysis
- Customer analytics
- Account analysis
- Branch performance
- Deposit analysis
- Loan analysis
- Transaction analytics
- Time-based analysis
- Geographic analysis
- Banking performance comparison

---

## Banks Included

The dataset covers 14 Indian banking institutions, including:

- State Bank of India (SBI)
- Punjab National Bank (PNB)
- Bank of Baroda (BOB)
- Canara Bank
- Union Bank of India
- Indian Bank
- Bank of India
- Central Bank of India
- HDFC Bank
- ICICI Bank
- Axis Bank
- Kotak Mahindra Bank
- IndusInd Bank
- IDFC First Bank

---

## Dataset Structure

The dataset is organized into multiple tables to support relational data modeling and analytical workflows.

### Dimension Tables

| Table | Description |
|---|---|
| Dim_Banks | Bank information and bank-level attributes |
| Dim_Customers | Customer demographic and profile information |
| Dim_Accounts | Account details, account types, balances, and status |
| Dim_Branches | Branch details and geographic information |
| Dim_Date | Calendar table for time-based analysis |
| Dim_Emolyees | Employee information of all banks |

### Fact Tables

| Table | Description |
|---|---|
| Fact_Transactions | Banking transaction records |
| Fact_Loans | Loan information and loan-related metrics |
| Fact_Credit_Cards | Credit card & related information of customers |

---

## Key Analysis Areas

### 1. Banking Performance

- Compare performance across different banks
- Analyze total deposits and loan portfolios
- Identify top-performing banks
- Compare transaction activity

### 2. Customer Analytics

- Customer distribution
- Customer demographics
- Customer segmentation
- Account ownership analysis

### 3. Account Analytics

- Account type distribution
- Active and inactive accounts
- Account balance analysis
- Deposit trends

### 4. Transaction Analytics

- Transaction volume
- Transaction value
- Transaction type analysis
- Monthly and yearly transaction trends
- Transaction status analysis

### 5. Loan Analytics

- Total sanctioned loan amount
- Loan distribution across banks
- Loan type analysis
- Loan status analysis
- Loan performance

### 6. Branch Analytics

- Branch distribution by location
- Branch performance
- Geographic banking analysis

---

## Recommended Power BI Data Model

The dataset can be modeled using a Star Schema.

### Recommended Relationships

- Dim_Banks → Dim_Branches
- Dim_Banks → Dim_Accounts
- Dim_Banks → Fact_Transactions
- Dim_Banks → Fact_Loans
- Dim_Customers → Dim_Accounts
- Dim_Customers → Fact_Transactions
- Dim_Accounts → Fact_Transactions
- Dim_Accounts → Fact_Loans
- Dim_Branches → Dim_Accounts
- Dim_Date → Fact_Transactions
- Dim_Date → Fact_Loans

Use one-to-many relationships wherever appropriate, with dimension tables filtering fact tables.

---

## Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Data Modeling
- DAX
- Data Visualization
- Business Intelligence

---

## How to Use

1. Download the dataset files.
2. Import the CSV files into Power BI.
3. Create relationships between the tables.
4. Build a Star Schema data model.
5. Create calculated measures using DAX.
6. Design interactive dashboards.
7. Use slicers and filters for dynamic analysis.

---

## Example KPIs

- Total Customers
- Total Accounts
- Active Accounts
- Total Deposits
- Total Loan Amount
- Total Transaction Value
- Total Transactions
- Average Account Balance
- Average Transaction Value
- Bank-wise Performance
- Monthly Transaction Growth

---

## Project Purpose

This dataset can be used to demonstrate skills in:

- Data Cleaning
- Data Analysis
- Data Modeling
- DAX Development
- Power BI Dashboard Development
- KPI Design
- Business Intelligence
- Data Visualization
- Analytical Storytelling

---

