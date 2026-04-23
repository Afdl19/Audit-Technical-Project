# 🛡️ Global Financial Audit & Forensic System
**Automated Internal Controls for Multinational Freight Operations**

## 📌 Project Overview
This repository contains a full-population forensic audit tool designed for a London-headquartered logistics firm. Instead of traditional "sampling," this tool uses Python and SQL to analyze every transaction across UK, EU, and US entities to identify financial leakage and internal control failures.

## 🚀 Key Modules
- **Currency Normalization:** Automated FX conversion of EUR, USD, and SGD into GBP reporting currency.
- **Forensic Engine:** Implementation of **Benford's Law** to detect statistically unnatural financial patterns.
- **Threshold Audit:** SQL-driven identification of unauthorized expenditures exceeding managerial limits (£100k).
- **Split-Billing Detection:** Logic to catch vendors bypassing approval limits through fragmented invoicing.

## 🛠️ Technical Stack
- **Languages:** Python (Pandas, NumPy, Matplotlib)
- **Database:** SQL (SQLite3)
- **Methodology:** Forensic Accounting, Data Integrity Auditing, Risk Management.

## 📁 Repository Structure
- `/Forensic_Audit_Engine.ipynb`: Full code, calculations, and data processing.
- `/METHODOLOGY.md`: Detailed breakdown of the accounting logic and formulas used.
- `/reports/Final_Audit_Report.pdf`: Executive-level summary of findings and visualizations.
