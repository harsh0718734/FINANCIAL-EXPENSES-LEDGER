# Personal Finance Ledger & Budget Dashboard

## 📌 Project Overview
This personal finance project focuses on the structured tracking, categorization, and visual analysis of daily and monthly expenses within Microsoft Excel. The primary objective was to replace static expense lists with an automated, formula-driven ledger system that calculates real-time spending totals and category averages.

By applying nested logical formulas, strict cell anchoring, and visual formatting rules across two complementary workbooks (`MINI PROJECT - MONTHLY LEDGER V1.xlsx` and `MINI PROJECT - DAILY BUDGET TRACKER.xlsx`), this project isolates key spending indicators to monitor cash outflows, separate essential expenses from investments, and highlight high-cost categories at a glance.

---

## 🛠️ Data Structuring, Validation & Formula Logic
To ensure calculation accuracy as new expense entries are added, the following spreadsheet rules and formula structures were implemented across both workbooks:

* **Automated Category Routing (`IF` Logic):** Built nested `IF` formulas across the category columns (`Food`, `Fun`, `Office`, `Studies`, and `Investment`) to automatically route each transaction amount into its matching category lane based on the `Type` label.
* **Strict Absolute Cell Anchoring (`$`):** Programmed summary formulas using fixed cell references (`$A$1` style anchoring) so totals, averages, and thresholds stay locked onto target ranges without reference shifting.
* **Uniform Numeric Formatting:** Standardized all transaction amounts, category subtotals, and summary metrics into clean numeric fields to support accurate `SUM`, `AVERAGE`, `MAX`, and `MIN` aggregations.
* **Color-Coded Conditional Formatting:** Applied dynamic color scales and highlight rules across the summary tables to separate low, moderate, and high spending totals visually.

---

## 📊 Comparative Workbook Architecture & KPI Formulation
The repository houses two distinct Excel tracking architectures tailored to monthly and daily expense monitoring:

### 1. Macro Monthly Ledger (`MINI PROJECT - MONTHLY LEDGER V1.xlsx`)
* **Primary Category Pillars:** Tracks monthly cash-flow entries across `FOOD`, `FUN`, `OFFICE`, and `INVESTMENT`.
* **Executive KPI Summary Block:** Calculates a **Total Cost** of `21,745`, an **Average Cost** of `1,812.08`, **Investment Total** of `18,400`, **Office Expenses** of `900` (average `75`), and **Food Expenses** of `615` (average `51.25`).

### 2. Micro Daily Budget Tracker (`MINI PROJECT - DAILY BUDGET TRACKER.xlsx`)
* **Granular Expense Tracking:** Expands tracking to include `STUDIES` alongside `Food`, `Fun`, and `Office`, logging everyday items such as meals, tuition classes, study books, and metro passes.
* **Daily Threshold KPI Block:** Calculates a **Total for the Day** of `21,210`, **Highest Expense** (`10,000`), **Lowest Expense** (`10`), **Average Transaction Value** (`1,427.67`), **Studies Expenses** (`10,640`), **Food Expenses** (`420`), **Fun Expenses** (`200`), and **Office Expenses** (`105`).

---

## 🎛️ Visual Charts & Dashboard Enhancements
To make spending patterns easy to review without scanning row by row, custom charts and visual cues were integrated beside each ledger table:

* **Monthly Amount Distribution Pie Chart:** Built a 3D Pie Chart (`AMOUNT`) with a color-coded itemized legend in the Monthly Ledger, removing crowded slice labels to show major capital allocations clearly.
* **Daily Budget Clustered Column Chart:** Built a side-by-side column chart (`DAILY BUDGET TRACKER`) comparing spending levels across `Food`, `Fun`, `Investment`, `Office`, and `Studies`.
* **Summary Table Color Gradients:** Highlighted peak expenses in red/orange and lowest expenses in green for instant visual prioritization.

---

## 📈 Key Financial Insights Uncovered
* **Capital Allocation vs. Everyday Spending:** In the Monthly Ledger, long-term investments (`18,400` across HDFC and ICICI) account for **84.6%** of the total `21,745` outflow, while routine food and office costs remain tightly controlled.
* **High-Impact Academic & Investment Outlays:** In the Daily Budget Tracker, single milestone payments such as Tuition Classes (`10,000`) and HDFC Investment (`10,000`) drive over **94%** of total daily volume (`21,210`), while everyday food and transit transactions stay between `10` and `150`.
