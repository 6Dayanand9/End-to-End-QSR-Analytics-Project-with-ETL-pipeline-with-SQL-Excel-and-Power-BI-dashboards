# 🚀 End-to-End QSR Analytics Project with ETL Pipeline using SQL, Excel and Power BI

## 📌 Project Overview

This project demonstrates an end-to-end enterprise analytics solution designed to solve business problems related to sales performance, profitability analysis, and cost leakage monitoring.

The project integrates multiple technologies including:

- MySQL
- Excel
- Power BI
- DAX
- Power Query
- Power BI Service
- Gateway Refresh
- Row Level Security (RLS)

The solution analyzes more than **500,000+ records**, **5 years of historical data**, and solves **38 business questions** across multiple business domains.

---

# 🏗 Architecture

```text
MySQL Actual Sales Data
            │
            │
            ▼
      Power Query ETL
            │
            ▼
GitHub Budget Data Source
            │
            ▼
     Galaxy Schema Model
            │
            ▼
      Advanced DAX Layer
            │
            ▼
      Power BI Dashboard
            │
            ▼
 Power BI Service Deployment
            │
            ├── Scheduled Refresh
            ├── Gateway Configuration
            └── Row Level Security
```
## 🏗️ Solution Architecture

```mermaid
flowchart TD

    A[MySQL Database<br>Actual Sales Data]
    B[GitHub Repository<br>Budget Data]

    A --> C[Power Query ETL Layer]
    B --> C

    C --> D[Data Cleaning]
    D --> E[Data Validation]
    E --> F[Data Transformation]
    F --> G[Galaxy Schema Data Model]

    G --> H1[Actual Fact Sales]
    G --> H2[Budget Fact Sales]

    G --> I1[Dim Date]
    G --> I2[Dim Product]
    G --> I3[Dim Channel]
    G --> I4[Dim Location]
    G --> I5[Dim Cluster]

    H1 --> J[Advanced DAX Layer]
    H2 --> J

    I1 --> J
    I2 --> J
    I3 --> J
    I4 --> J
    I5 --> J

    J --> K1[Budget vs Actual Analysis]
    J --> K2[Profitability Analysis]
    J --> K3[Cost Leakage Analysis]
    J --> K4[What If Analysis]
    J --> K5[PVM Analysis]
    J --> K6[Ranking Analysis]

    K1 --> L[Power BI Dashboard]
    K2 --> L
    K3 --> L
    K4 --> L
    K5 --> L
    K6 --> L

    L --> M[Power BI Service]

    M --> N1[Scheduled Refresh]
    M --> N2[Gateway Configuration]
    M --> N3[Row Level Security]
    M --> N4[Workspace Sharing]

```
---

# ⚙️ Technology Stack

| Component | Technology |
|-----------|------------|
| Database | MySQL |
| Budget Source | GitHub |
| Validation | Excel |
| ETL | Power Query |
| Analytics | DAX |
| Visualization | Power BI |
| Deployment | Power BI Service |
| Security | RLS |
| Refresh | Gateway |

---

# 📊 Dataset Information

| Metric | Value |
|--------|-------|
| Total Rows | 500,000+ |
| Historical Data | 5 Years |
| Products | 4,000+ |
| Channels | Multiple |
| Locations | Multiple |
| Business Questions Solved | 38 |
| Problem Statements | 4 |

---

# 🎯 Problem Statement 1
# Data Consolidation and Reporting Automation

## Objective

Create a centralized reporting solution by integrating Actual and Budget data from multiple sources.

## Questions Solved

- How can Actual and Budget data be consolidated?
- How can reporting be automated?
- How can data quality be improved?
- How can manual reporting efforts be reduced?
- How can business users access a single source of truth?

## Business Impact

✅ Reduced manual reporting effort  
✅ Improved reporting consistency  
✅ Centralized data model  
✅ Faster business decisions  

---

# 📈 Problem Statement 2
# Budget vs Actual Performance Analysis

## Objective

Identify revenue gaps and measure business performance against targets.

## Questions Solved

✅ Are actual sales meeting budget targets?  
✅ Which months overperformed or underperformed?  
✅ Which products caused budget shortfalls?  
✅ Which products exceeded expectations?  
✅ Which channels are underperforming?  
✅ Which locations are missing targets?  
✅ What is the variance percentage?  
✅ Is profit following the same trend as sales?

## Business Impact

📌 Improved forecasting accuracy  
📌 Faster variance identification  
📌 Better resource allocation  

---

## Dashboard Page 1
### Executive Budget Performance Dashboard

![](./Images/Page-1.png)

---

## Dashboard Page 2
### Variance Analysis Dashboard

![](./Images/Page-2.png)

---

# 💰 Problem Statement 3
# Profitability Driver Analysis

## Objective

Understand what truly drives profitability.

## Questions Solved

✅ Highest net profit products  
✅ High sales but low profit products  
✅ Most profitable channels  
✅ Most profitable locations  
✅ Best product-channel combinations  
✅ Highest EBITDA contributors  
✅ Investment worthy products  

## Business Impact

📌 Improved investment decisions  
📌 Better pricing strategies  
📌 Increased profit optimization  

---

## Dashboard Page 3
### Profitability Analysis Dashboard

![](./Images/Page-3.png)

---

## Dashboard Page 4
### Advanced Profitability Dashboard

![](./Images/Page-4.png)

---

# 💸 Problem Statement 4
# Cost Leakage Analysis

## Objective

Identify cost drivers reducing profitability.

## Questions Solved

✅ Largest cost leakage component  
✅ Profit lost due to discounts  
✅ Products receiving highest discounts  
✅ Trade spend efficiency analysis  
✅ COGS growth vs Revenue growth  
✅ Location cost burden analysis  
✅ Lowest gross margin products  
✅ EBITDA decline drivers  
✅ Cost reduction opportunities  
✅ What-if scenario analysis

## Business Impact

📌 Reduced operational cost  
📌 Improved pricing strategy  
📌 Increased EBITDA visibility  
📌 Better cost control decisions  

---

## Dashboard Page 5
### Cost Leakage Dashboard

![](./Images/Page-5.png)

---

# 📊 Advanced Analytics Implemented

- Budget vs Actual Analysis
- Revenue Variance Analysis
- Profitability Analysis
- Cost Leakage Analysis
- EBITDA Bridge Analysis
- Gross Margin Analysis
- Dynamic Ranking
- Top N Analysis
- Trade Spend Analysis
- Discount Analysis
- Growth Analysis
- What-if Analysis
- PVM Analysis

---

# 🚀 Deployment Features

## Power BI Service

✅ Published to Power BI Service  
✅ Scheduled Refresh Enabled  
✅ Gateway Configured  
✅ Demo Row Level Security Implemented  

---

# 📈 Additional Validation

The complete business logic was validated using:

- MySQL Queries
- Excel Validation Models
- Power BI Measures

---

# 🏆 Certifications Applied During Development

- Microsoft PL-300 — Power BI Data Analyst Associate
- Microsoft DP-600 — Fabric Analytics Engineer Associate
- Microsoft DP-700 — Fabric Data Engineer Associate

---

# 👨‍💻 Author

## Dayanand Nimbalkar

Data Analyst | Power BI Developer | Microsoft Fabric Engineer

---

# ⭐ If you found this project useful, consider giving it a star.
