# Hosptial_data_analysis
# Hospital  Analytics Dashboard – Power BI Project

This repository showcases an end-to-end Power BI project lifecycle — from requirement gathering to dashboard development, testing, and deployment preparation. It walks through building a financial analytics solution that turns raw financial data into interactive dashboards and standard financial statements for stakeholder decision-making.

🔗 **Live Report:** [View Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=25bfb271-1709-4563-8c5f-2981afb60309&autoAuth=true&ctid=8b0bd025-5185-40db-ba3c-d8fda52e6d2b)

## Project Overview

The goal of this project is to design and develop financial analytics dashboards that help stakeholders analyze company performance. The solution covers preparation of:

- Profit & Loss Statement (Income Statement)
- Balance Sheet
- Cash Flow Statement
- Statement of Changes in Equity
- Financial Ratios
- Financial Dashboards

## Project Workflow

1. **Requirement gathering & task tracking** using Jira
2. **Understanding business KPIs** and reporting needs
3. **Data extraction and validation** using SSMS
4. **Data transformation** using Power Query
5. **Data modeling** (Star Schema — Fact & Dimension tables)
6. **DAX measures** for financial calculations
7. **Dashboard development** in Power BI
8. **Testing** and **deployment preparation**

## Tech Stack

| Component | Tool |
|---|---|
| Data Visualization | Power BI |
| Data Preparation | Power Query |
| Data Modeling | Power BI Data Model |
| Calculations | DAX |
| Data Source | Excel / CSV / SQL Database |
| Publishing | Power BI Service |

## Data Model

Follows a **Star Schema** design:

- **Fact Table:** `Fact_Financials` (Transaction ID, Date, Account, Amount, Department, Type)
- **Dimension Tables:** `Dim_Account`, `Dim_Date`, `Dim_Department`

## Key DAX Measures

- Total Revenue
- Total Expenses
- Net Profit
- Profit Margin
- Financial Ratios (Gross Margin, Net Profit Margin, Current Ratio, Quick Ratio, Asset Turnover)

## Dashboard Pages

1. **Financial Overview** — KPI cards, revenue trend, expense breakdown, net profit chart
2. **Profit & Loss Statement** — matrix table, profit margin trend, revenue vs. expense comparison
3. **Balance Sheet** — asset/liability distribution, equity analysis
4. **Financial Ratios** — KPI indicators, ratio trends, year-over-year comparison

## Repository Contents

- `README.md` — project summary
- `Requirements-LLD (Low Level Design)` — detailed low-level design document covering architecture, data model, DAX logic, dashboard design, security (RLS), and deployment steps

## Deployment

1. Publish the report to Power BI Service
2. Configure the data refresh schedule
3. Assign user permissions
4. Share the dashboard with stakeholders
