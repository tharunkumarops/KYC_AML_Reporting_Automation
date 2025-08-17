# KYC / AML Reporting Automation

This project demonstrates how to automate **KYC completeness tracking** and **AML alert generation** with SQL, Python, and BI dashboards.  
It is designed as a portfolio case study for compliance and financial operations.

---

## 📊 Features

### 🔍 KYC Status Monitoring
- Tracks **Complete / Partial / Missing** status for customers based on verified, non-expired documents  
- Flags **expired** and **expiring soon** KYC documents  

### 🚨 AML Alert Rules Implemented
- **Structuring** → Sub-threshold cash > 500,000 within 7 days (≥3 events)  
- **Velocity** → >20 transactions and total > 2,000,000 in 24 hours  
- **High-Risk Geography** → Counterparty in NG / RU / PK with txn > 250,000  
- **PEP Large Transactions** → PEP with transaction > 1,000,000  
- **Rapid In–Out Flow** → Outflow >80% of recent inflow  

### 📈 Dashboards
- KYC Status Distribution  
- AML Alerts by Rule Type  
- High-Risk Geography Alerts  

---

## 📂 Project Structure
KYC_AML_Reporting_Automation/
│
├── data/ # Sample datasets
│ ├── customers.csv
│ ├── transactions.csv
│ ├── kyc_documents.csv
│ ├── aml_alerts.csv
│ └── watchlist_hits.csv
│
├── dashboards/ # Visuals & dashboards
│ ├── kyc_status.png
│ ├── aml_alerts_by_rule.png
│ └── hr_geo_alerts.png
│
├── docs/ # Project reports
│ ├── KYC_AML_Case_Study_OnePager.pdf
│ └── KYC_AML_Automation_PortfolioDeck.pptx
│
└── sql/ # SQL logic
└── kyc_aml_rules.sql

---

## 🛠️ Tools Used
- **Python** (Pandas, Matplotlib, ReportLab)  
- **SQL** (joins, rule logic)  
- **Excel** (data exploration)  
- **Tableau / Power BI** (for dashboards)  

---

## 🚀 How to Use
1. Clone this repo  
2. Explore datasets under `/data`  
3. Open dashboards in `/dashboards`  
4. Review case study in `/docs`  

---

## 📸 Sample Dashboard

![KYC Status Dashboard](dashboards/kyc_status.png)

---

## 📌 Portfolio
- 📄 [Case Study PDF](docs/KYC_AML_Case_Study_OnePager.pdf)  
- 📑 [Portfolio Deck (PPTX)](docs/KYC_AML_Automation_PortfolioDeck.pptx)

---
