# Bank Transaction Data Analysis

**One-line idea:** We turned two years of raw bank records into a clean data model, a set of KPIs, and a 3-page Power BI dashboard. The dashboard shows how the bank is performing, where operations fail, and who the customers are.

## 1. Background
Banks record every deposit, withdrawal, transfer, and payment. These records hold the answers to management's daily questions, but only if the data is cleaned, linked, and measured.

## 2. Problem
Raw transaction records don't show:
- Which channels fail the most.
- When the peak load happens.
- Which branches and customer segments bring in the highest value.

Without structured analysis, decisions are made by intuition.

## 3. Objectives
- Build a clean, connected data model from 5 tables.
- Define clear KPIs: transaction count, transaction value, success rate, net flow, and account closure rate.
- Track performance over time and by transaction type, channel, and branch.
- Find where and why transactions fail.
- Analyze customers and account status.
- Deliver an interactive dashboard with practical recommendations.

## 4. Source Data
A single Excel file with 5 sheets:
- **Transactions:** 210,994 records.
- **Customers:** 2,940.
- **Accounts:** 117.
- **Branches:** 12 branches across 5 regions.
- **Channels:** 5 (Branch, ATM, Mobile App, Internet Banking, POS).

**Period:** November 2024 to October 2026.

## 5. Tools
- **Excel:** raw data source.
- **MySQL:** storage and validation using SQL.
- **Power BI:** cleaning, modeling, DAX, and the dashboard.
