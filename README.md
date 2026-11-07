# Personal Finance Ledger & Budget Dashboard (Excel)

## 📌 Project Overview
The Financial Expenses Ledger is a robust personal finance tracker and budget allocation engine developed entirely inside Microsoft Excel. Designed to replace static expense tables, this repository showcases two distinct data tracking architectures (`monthly_ledger_v1.xlsx` and `daily_budget_tracker_v2.xlsx`) built to ingest daily cash-flow items, parse categorical spending spreads, and optimize personal capital runway preservation.

---

## 📊 Comparative Sheet Architectures & Models

### 🗺️ Data Architecture 1: Macro Ledger (`monthly_ledger_v1.xlsx`)
This framework focuses on high-level parameter grouping, mapping cash-flow movements directly across core financial pillars: `FOOD`, `FUN`, `OFFICE`, and `INVESTMENT`.
* Leverages horizontal cross-binning to route row expenditures automatically from a master input column straight into individual asset category columns.
* Includes summary aggregation blocks tracking a **TOTAL COST** of `21,745` and an **AVERAGE COST** of `1,812.08` across all tables.

### 🗺️ Data Architecture 2: Micro Tracker (`daily_budget_tracker_v2.xlsx`)
This workbook introduces a highly granular reporting layer, expanding tracking boundaries to include academic expenses (`STUDIES`) alongside detailed daily threshold limits.
* Maps detailed daily item descriptions like Thali orders, Python study resources, and digital metro passes natively.
* Employs advanced functions to track localized metrics: a **Total for the Day** of `21,210`, **Highest Expense** (`10,000`), and **Lowest Expense** (`10`).

---

## ⚙️ Technical Excel Logic & Formula Design
Both workbooks leverage error-free structural programming rules to guarantee automation stability:
* **Strict Absolute Cell Anchoring ($):** Programmed background calculations using strict absolute references (`$A$1`, `$B$2`). This ensures that as transaction rows grow over time, the background formulas remain firmly locked onto target master cells without reference shifting or causing broken reference errors.
* **Nested Logical Loops:** Formulated multi-tiered nested `IF` loops to parse row variables automatically, sorting transaction targets into their correct category lanes based on metadata strings.
* **Automated Conditional Formatting Gradients:** Configured live visual rules to track spending thresholds. The system dynamically changes row colors on the screen—shifting from calm greens to high-alert red highlights the exact second a category breaches its maximum preset budget limit.
* **Dynamic Chart Profiles:** Engineered uniform, side-by-side multi-variable stacked column graphs and categorical pie charts to visualize asset allocations instantly for immediate review.
