<div align="center">
    
# 💳 Banking Transaction Analysis — Transactions, Customers & Risk Intelligence

### Power BI Dashboard | Retail & Commercial Banking Transaction Analytics

**Overview Analysis · Transaction Logs · Customer Segmentation · Status & Risk Monitoring**

📅 **Reporting Period:** January – December 2025 (with YoY Comparison)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Banking Analytics](https://img.shields.io/badge/Banking-Analytics-00529B?style=for-the-badge)
![Transaction Intelligence](https://img.shields.io/badge/Transaction-Intelligence-1E88E5?style=for-the-badge)

</div>


## 📌 Project Overview

This project presents an interactive **Banking Transaction Analysis Dashboard** developed using Microsoft Power BI to monitor real-time transaction flows, fee and tax generation, customer demographics, and transaction failure risk across India.

The dashboard provides a consolidated view of total transaction amount, transaction volume, average transaction value, total fees, total tax, monthly trends, transaction status distribution, customer segments, and granular transaction records.

Featuring dynamic metric switching (powered by Field Parameters) and interactive slicers, it simulates a real-world banking operations and risk monitoring environment—helping teams track payment success rates, identify regional transaction volume, and audit individual failed or high-value transactions.

---

## 🖼️ Dashboard Preview

### 01. Overview Analysis:

The Overview Analysis view provides management with a comprehensive view of banking transaction activity through interactive YoY KPI cards, monthly trend charts, transaction status splits, customer segment and gender breakdowns, state-level rankings, and a transaction type heatmap matrix[cite: 23].

<img src="assets/screenshots/01_overview_analysis.png" alt="Banking Transaction Analysis Overview Page" width="100%">

<br>

### 02. Transactions (Detailed Transaction Log):

The Transactions view provides operations and risk teams with a granular, searchable audit table of individual transactions—displaying Transaction ID, Customer Name, Date, Transaction Type, Status, Gender, Segment, State, Amount, Fees, and Tax alongside top-level KPIs[cite: 24].

<img src="assets/screenshots/02_transactions_details.png" alt="Transactions Detail Table Page" width="100%">

<br>


## 📊 Key Banking Transaction Indicators (FY 2025)

The dashboard tracks the following transaction and revenue KPIs:

| Transaction KPI | Dashboard Value | YoY Variance |
|---|---:|---:|
| Total Amount | ₹137.53M | ▲ +1.41% vs PY |
| Total Transactions | 14.94K | ▼ -0.57% vs PY |
| Avg Transaction Value | ₹9.20K | ▲ +1.98% vs PY |
| Total Fees | ₹216.94K | ▼ -0.17% vs PY |
| Total Tax | 39.04K | ▼ -0.26% vs PY[cite: 23, 24] |

*Monetary figures are reported in INR Millions (M) and Thousands (K) as displayed on the dashboard[cite: 23, 24].*

---

## 📈 Dashboard Features & Business Analysis

### 1️⃣ Overview Analysis & Dynamic Metric Switching

Provides a high-level view of payment volume, fee income, and monthly fluctuations across 2025:

- Dynamic KPI cards tracking Total Amount (₹137.53M), Total Transactions (14.94K), Avg Transaction Value (₹9.20K), Total Fees (₹216.94K), and Total Tax (39.04K) with Year-over-Year percentage comparisons.
- Interactive **Dynamic Metrics** selector allowing users to switch visuals dynamically (e.g., Total Amount) with live header badges displaying the active Year (`2025`) and selected metric (`Total Amount`).
- Monthly transaction volume trend peaking in July (₹12.5M+) and January/December, with a seasonal dip in September (₹10M).
- Transaction Type Analysis matrix with conditional heatmap formatting across 10 payment categories led by Loan EMI (₹40.0M / 2.8K transactions), Transfer (₹36.2M / 2.5K transactions), and Deposit (₹20.3M / 1.5K transactions)[cite: 23].

### 2️⃣ Customer Demographics, Segments & Regional Distribution

Analyzes where transactions originate and how different customer cohorts contribute to total volume:

- Customer Segment breakdown led by Retail (₹76M), Premium (₹26M), SME (₹21M), Corporate (₹9M), and Wealth (₹6M).
- Gender distribution showing Female customers contributing ₹72.6M (52.8%) and Male customers contributing ₹65.0M (47.2%).
- State-wise transaction volume led by Maharashtra (₹22M), Karnataka (₹16M), Gujarat (₹15M), Tamil Nadu (₹14M), and Uttar Pradesh (₹13M)[cite: 23].

### 3️⃣ Transaction Status & Granular Audit Logs

Monitors payment reliability, failure rates, and transaction-level audit records:

- Transaction Status distribution across ₹137.53M: Success at ₹117.4M (85.4%), Failed at ₹14.4M (10.4%), and Pending at ₹5.8M (4.2%).
- Dedicated **Transactions** view presenting an interactive tabular log (`Transaction ID`, `Customer_Name`, `Transaction Date`, `Transaction Type`, `Transaction Status`, `Gender`, `Customer Segment`, `State`, `Total Amount`, `Total Fees`, and `Total Tax`) for rapid auditing of failed or specific customer transactions[cite: 23, 24].

---

## 💡 Key Business Insights

Based on the Banking Transaction Analysis dashboard:

| Area | Business Insight |
|---|---|
| Volume & Ticket Size | Total transaction amount grew 1.41% YoY to ₹137.53M, driven by a 1.98% increase in average transaction value (₹9.20K) despite a slight 0.57% dip in transaction count. |
| Top Transaction Types | Loan EMI (₹40.0M, ₹64.0K fees) and Transfers (₹36.2M, ₹55.3K fees) generate over 55% of total transaction value and fee revenue. |
| Failure & Pending Risk | While 85.4% (₹117.4M) of transaction value succeeded, 10.4% (₹14.4M) failed and 4.2% (₹5.8M) remained pending—highlighting an opportunity to reduce payment failures. |
| Core Customer Segment | Retail banking dominates transaction volume at ₹76M (over 55% of total amount), followed by Premium (₹26M) and SME (₹21M). |
| Geographic Leaders | Maharashtra (₹22M), Karnataka (₹16M), and Gujarat (₹15M) represent the top three states by transaction amount. |
| Gender Split | Female account holders account for a slightly higher share of transaction value at 52.8% (₹72.6M) compared to Male account holders at 47.2% (₹65.0M)[cite: 23]. |

---

## 📊 Visualizations Used

The dashboard incorporates the following Power BI visuals:

- KPI Cards — Total Amount, Total Transactions, Avg Transaction Value, Total Fees, and Total Tax with YoY variance indicators[cite: 23, 24].
- Smooth Area / Line Chart — Monthly transaction trend across Jan–Dec[cite: 23].
- Doughnut Charts — Transaction Status (Success, Failed, Pending) and Gender distribution[cite: 23].
- Horizontal Bar Charts — Transaction amount ranked by Customer Segment and State[cite: 23].
- Conditional Formatted Matrix Table — Transaction Type Analysis comparing Amount, Fees, Tax, and Transactions with color-coded intensity scales[cite: 23].
- Detailed Transaction Log Table — Granular row-level audit table on the Transactions page[cite: 24].
- Navigation Buttons, Dynamic Title Cards & Slicers — Page-switching buttons (`Overview Analysis`, `Transactions`), dynamic selection badges (`2025`, `Total Amount`), and `Year`, `Dynamic Metrics`, `Occupation`, and `Category` filters[cite: 23, 24].

---

## 🎛️ Interactive Dashboard Filters

The dashboard includes multiple filtering options and dynamic parameters for targeted analysis:

| Filter | Purpose |
|---|---|
| Year | Compare annual transaction metrics and YoY growth (e.g., `2025`)[cite: 23, 24] |
| Dynamic Metrics | Dynamically switch the primary metric across charts (`Total Amount`, etc.)[cite: 23, 24] |
| Occupation | Filter transaction behavior across customer occupation groups[cite: 23, 24] |
| Category | Segment analysis across banking/transaction categories[cite: 23, 24] |

---

## 🛠️ Tools & Technologies

The project leverages the following tools and technologies:

| Technology | Application |
|---|---|
| Microsoft Power BI | Interactive multi-page banking transaction and risk dashboard[cite: 23, 24] |
| Power Query | Data cleaning, formatting, and transformation |
| DAX & Field Parameters | YoY variance calculations, dynamic metric switching, and KPI measures[cite: 23, 24] |
| Microsoft Excel | Source banking transaction and customer data preparation |
| Data Visualization | Conditional heatmap matrices, custom icons, and executive reporting[cite: 23] |

---

## 📂 Repository Structure

```text
Banking-Transaction-Analysis-Dashboard/
│
├── README.md
│
├── assets/
│   └── screenshots/
│       ├── 01_overview_analysis.png
│       └── 02_transactions_details.png
│
├── dataset/
│   └── Banking_Transactions_Dataset.xlsx
│
└── dashboard/
    ├── Banking_Transaction_Analysis.pbix
    └── Banking_Transaction_Analysis.pdf
