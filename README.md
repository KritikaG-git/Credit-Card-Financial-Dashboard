# 🧾 Credit Card Report – Power BI

## 📌 Project Overview

This project was completed as part of a **Power BI course** focused on building business intelligence dashboards using real-world financial data.

The goal was to develop a **comprehensive weekly credit card performance dashboard** that provides **real-time insights** into key metrics and operational trends. The dashboard enables stakeholders to **monitor**, **analyze**, and **track** credit card operations effectively.

---

## 🎯 Primary Goal

> To design and implement a weekly credit card performance dashboard that delivers actionable insights into operational and financial metrics, empowering stakeholders to effectively monitor and evaluate credit card activity over time.

---

## 🛠 Tools & Technologies Used

- **Power BI** – Dashboard creation, data modeling, and visualization  
- **PostgreSQL (pgAdmin)** – Database setup and data storage  
- **SQL** – Data extraction and transformation  
- **DAX (Data Analysis Expressions)** – Calculated columns and measures  
- **CSV Files** – Source datasets

---

## 📂 Data Integration Workflow

1. **CSV files** were imported and used to populate tables in **PostgreSQL** using `pgAdmin`.
2. **Power BI** was connected to PostgreSQL for data modeling and dashboard creation.
3. Two additional data sources were appended to existing tables:
   - `cc_add.csv` → appended to `cc_detail`
   - `cust_add.csv` → appended to `cust_detail`

---

## 📊 Key Insights – Week 53 (Ending 31st Dec)

### 🔁 Week-over-Week (WoW) Changes

- 📈 **Revenue** increased by **28.8%**

### 📆 Year-to-Date (YTD) Overview

- 💰 **Total Revenue**: `$57M`
- 💵 **Total Interest Earned**: `$8M`
- 🧾 **Total Transaction Amount**: `$45.5M`
- 👨‍💼 **Male customers** contributed `$31M` vs 👩‍💼 **Female customers** with `$26M`
- 🗺 **Top-performing states**: **TX, NY, CA**
- ✅ **Activation Rate**: `57.46%`
- ⚠️ **Delinquency Rate**: `6.06%`

---

## 🧠 Key Learnings

- Combining **SQL**, **PostgreSQL**, and **DAX** enables powerful data modeling and insights.
- **Power BI's interactive visuals** greatly improve stakeholder communication.
- **Incremental data updates** (via CSVs) help simulate real-time dashboard refreshes.

---

> 💡 _This project was developed as part of a hands-on **Power BI course** to enhance my data visualization and business analytics skills._
