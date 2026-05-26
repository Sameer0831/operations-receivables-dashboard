# Operations & Receivables Dashboard

A real-world Business Operations & Receivables Analytics project built using Power BI, Power Query, and DAX.

This project focuses on transforming fragmented operational ledger data from multiple business units into a centralized analytical reporting solution for monitoring revenue, collections, outstanding receivables, and depot-wise operational performance.

---

# Project Overview

Unlike traditional dashboard projects built on pre-cleaned datasets, this project involved working with raw operational financial ledger files containing:

- Debit/Credit transaction structures
- Opening & Closing balances
- Null voucher information
- Multi-year operational records
- Multiple business/depot datasets

The project demonstrates practical implementation of:

- ETL (Extract, Transform, Load)
- Data Cleaning & Transformation
- Data Modeling
- Basic Data Warehousing Concepts
- KPI Engineering
- Business Intelligence Reporting

---

# Business Objective

The primary objective was to centralize operational financial data across multiple depots/business units and create a scalable reporting solution to monitor:

- Revenue
- Collections
- Outstanding Receivables
- Collection Efficiency
- Depot Performance
- Financial Trends

---

# Technologies Used

- Power BI
- Power Query
- DAX
- Excel
- Data Modeling

---

# Concepts Applied

## ETL & Data Transformation

- Extracted data from multiple Excel ledger files
- Cleaned and transformed raw transactional data
- Removed unnecessary rows and null values
- Handled opening and closing balances
- Standardized column names and data types
- Derived analytical fields such as Year and Month

## Data Warehousing & Modeling Concepts

- Built a centralized analytical model
- Created a unified `Fact_Transactions` table
- Designed supporting dimension tables
- Applied basic Star Schema concepts
- Established one-to-many relationships
- Enabled scalable reporting and filtering

## Financial & Business Analytics

- Revenue vs Collection Analysis
- Outstanding Receivables Tracking
- Collection Efficiency Monitoring
- Depot-wise Performance Analysis
- Time-based Financial Trend Analysis

## KPI Engineering

- Total Revenue
- Total Collection
- Outstanding Receivables
- Collection Efficiency %
- Outstanding with and without Opening Balance

---

# Dashboard Features

- Interactive slicers for Year, Month, and Business Unit
- Revenue & Collection monitoring
- Outstanding analysis
- Depot-wise operational performance
- Financial KPI tracking
- Centralized reporting across multiple business units

---

# Data Model

The project follows a basic Star Schema structure.

## Fact Table

- `Fact_Transactions`

## Dimension Tables

- `Dim_Date`
- `Dim_Business`
- `Dim_Type`
- `Dim_RecordType`

---

# Key Learning Outcomes

This project provided practical exposure to:

- Real-world operational data handling
- Financial analytics
- ETL workflows using Power Query
- Centralized analytical modeling
- KPI engineering
- Power BI dashboard development
- Business intelligence reporting

---

# Screenshots

## Dashboard Overview

(Add dashboard screenshot here)

## Data Modeling

(Add dimensional modeling screenshot here)

---

# Future Improvements

- Aging Analysis for Receivables
- Drill-through Reporting
- Automated Data Refresh Pipelines
- SQL-based Data Warehouse Integration
- Advanced Financial Forecasting

---

# Author

Sameer Shaik

---

# Directory Structure

```bash
operations-receivables-dashboard/
│
├── datasets/
│   ├── depot_ledger_1.xlsx
│   ├── depot_ledger_2.xlsx
│   ├── depot_ledger_3.xlsx
│   ├── depot_ledger_4.xlsx
│   ├── depot_ledger_5.xlsx
│   ├── depot_ledger_6.xlsx
│   ├── depot_ledger_7.xlsx
│   └── depot_ledger_8.xlsx
│
├── screenshots/
│   ├── dashboard.png
│   └── dimensional_modeling.png
│
├── bi-reports/
│   └── operations_receivables_dashboard.pbix
│
└── README.md
```
