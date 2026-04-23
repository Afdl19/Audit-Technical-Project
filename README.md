# 🛡️ Global Financial Audit & Forensic System
A Python-SQL framework for automated internal controls in multinational freight operations.

## 📊 Business Context
In global logistics, fragmented systems across different regions (UK, EU, US) often lead to "Financial Leakage." This project simulates a London-based HQ auditing its global entities to detect:
* **Currency Inconsistencies:** Normalizing USD/EUR to GBP.
* **Internal Control Gaps:** Flagging unauthorized spends >£100k.
* **Fraudulent Patterns:** Using Benford's Law to detect unnatural ledger entries.

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy)
* **Database:** SQL (SQLite)
* **Visuals:** Matplotlib, Seaborn
* **Environment:** Google Colab / ChromeOS

## 🔍 Audit Logic
1. **Benford's Law:** P(d) = log10(1 + 1/d) to catch fictitious invoicing.
2. **Split-Billing Detection:** SQL grouping to find threshold circumvention.
3. **Temporal Analysis:** Isolating high-risk weekend transactions.
