# 🚀 Enterprise Budget vs Actual Sales & Profitability Analytics Platform

<p align="center">

![Power BI](https://img.shields.io/badge/PowerBI-Analytics-F2C811?logo=powerbi)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Validation-green?logo=microsoftexcel)
![GitHub](https://img.shields.io/badge/GitHub-Budget_Data-black?logo=github)
![Rows](https://img.shields.io/badge/Rows-500K+-orange)
![SKUs](https://img.shields.io/badge/SKUs-4000+-red)
![Years](https://img.shields.io/badge/History-5_Years-blue)
![KPIs](https://img.shields.io/badge/Business_Questions-38-success)

</p>

---

# 📖 Project Overview

Modern organizations often struggle with disconnected Actual and Budget data sources, manual reporting, inconsistent KPIs, and delayed decision-making.

This project delivers an **enterprise-grade Budget vs Actual Analytics Platform** capable of analyzing:

✅ 500K+ records
✅ 5 years of historical data
✅ 4000+ products
✅ Multiple locations, channels, and customer clusters
✅ 38 business questions across finance and profitability domains

The solution transforms raw business data into actionable financial intelligence.

---

# 🎯 Business Objective

Build a centralized analytics platform that enables stakeholders to:

* Monitor Budget vs Actual performance
* Identify revenue leakage
* Understand profitability drivers
* Detect cost leakage
* Improve strategic decision making

---

# ⚙️ Architecture Diagram

```text
┌─────────────────────┐
│  MySQL Actual Data  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ GitHub Budget Data  │
└──────────┬──────────┘
           │
           ▼
╔══════════════════════╗
║ Power Query ETL Layer║
║ • Cleaning           ║
║ • Validation         ║
║ • Standardization    ║
║ • Reconciliation     ║
╚══════════════════════╝
           │
           ▼
╔══════════════════════╗
║ Galaxy Schema Model  ║
║ • Actual Fact Table  ║
║ • Budget Fact Table  ║
║ • Shared Dimensions  ║
╚══════════════════════╝
           │
           ▼
╔══════════════════════╗
║ Advanced DAX Engine  ║
║ • Variance Analysis  ║
║ • EBITDA Analysis    ║
║ • Ranking            ║
║ • What-If Analysis   ║
║ • PVM Analysis       ║
╚══════════════════════╝
           │
           ▼
┌─────────────────────┐
│ Power BI Dashboard  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Power BI Service    │
│ Gateway + RLS       │
└─────────────────────┘
```

---

# ⭐ Problem Statement 1

# Data Consolidation & Reporting Automation

## Objective

Create a single source of truth for Actual and Budget reporting.

### Business Problems Solved

* Integrated MySQL Actual Sales and GitHub Budget datasets.
* Eliminated manual Excel reconciliation.
* Standardized and validated business data.
* Designed a scalable Galaxy Schema model.
* Automated reporting workflows.
* Implemented centralized KPI calculations.
* Enabled secure access using RLS.

### Business Impact

✅ Reduced manual reporting effort
✅ Improved trust in business numbers
✅ Faster reporting cycles
✅ Enterprise-ready reporting model

---

# 📈 Problem Statement 2

# Budget vs Actual Performance Analysis

## Objective

Determine whether business performance aligns with financial expectations.

### Questions Answered

✔ Are actual sales meeting budget targets?
✔ Which months overperformed or underperformed?
✔ Which products caused budget shortfalls?
✔ Which products exceeded expectations?
✔ Which channels are underperforming?
✔ Which locations are missing targets?
✔ What is the variance percentage?
✔ Is profit following the same trend as sales?

### Business Impact

📌 Improved forecasting accuracy
📌 Faster variance identification
📌 Better resource allocation

---

# 💰 Problem Statement 3

# Profitability Driver Analysis

## Objective

Understand what truly drives profitability.

### Questions Answered

✔ Highest net profit products
✔ High sales but low profit products
✔ Most profitable channels
✔ Most profitable locations
✔ Highest value customer clusters
✔ Top EBITDA products
✔ Volume vs profitability relationship
✔ Investment prioritization opportunities
✔ Weak product identification
✔ Best product-channel-location combinations

### Business Impact

📌 Improved product strategy
📌 Better investment decisions
📌 Higher profitability focus

---

# 📉 Problem Statement 4

# Cost Leakage Analysis

## Objective

Identify controllable costs reducing profitability.

### Questions Answered

✔ Largest profit leakage sources
✔ Discount impact analysis
✔ Highest discount products
✔ Discount effectiveness measurement
✔ Trade spend efficiency analysis
✔ COGS trend analysis
✔ Location cost burden analysis
✔ Lowest gross margin products
✔ EBITDA decline drivers
✔ Cost optimization opportunities
✔ Scenario analysis using What-If parameters

### Business Impact

📌 Improved pricing decisions
📌 Better cost control
📌 Trade spend optimization
📌 Stronger profitability management

---

# 🧠 Advanced Analytics Implemented

🔥 Variance Analysis
🔥 EBITDA Analysis
🔥 Profitability Ranking
🔥 Revenue Leakage Analysis
🔥 Cost Leakage Analysis
🔥 Growth Analysis
🔥 Dynamic Top N Analysis
🔥 What-If Analysis
🔥 Price Volume Mix Analysis
🔥 Scenario Planning

---

# 🏗 Data Model

### Model Type

**Galaxy Schema**

### Fact Tables

* Actual Sales Fact
* Budget Sales Fact

### Shared Dimensions

* Date
* Product
* Customer
* Channel
* Location
* Cluster

---

# 📊 Project Statistics

| Metric                    | Value                       |
| ------------------------- | --------------------------- |
| Total Records             | 500K+                       |
| Historical Data           | 5 Years                     |
| Products                  | 4000+                       |
| Business Questions Solved | 38                          |
| Problem Statements        | 4                           |
| Fact Tables               | 2                           |
| Reporting Platforms       | 4                           |
| Deployment                | Power BI Service            |
| Security                  | Row Level Security          |
| Refresh                   | Gateway + Scheduled Refresh |

---

# 🛠 Technology Stack

```text
Power BI
DAX
MySQL
Excel
GitHub
Power BI Service
Gateway
RLS
Looker Studio
Microsoft Fabric
```

---

# 🎬 Demo Assets

📹 Architecture Walkthrough
📹 Dashboard Demonstration
📹 PPT Presentation Video
📹 Business Insights Presentation
📹 Executive Summary Video

---

# 👨‍💻 Author

## Dayanand Nimbalkar

🏅 PL-300 — Power BI Data Analyst Associate
🏅 DP-600 — Fabric Analytics Engineer Associate
🏅 DP-700 — Fabric Data Engineer Associate

---

⭐ If you found this project useful, consider giving the repository a star.
