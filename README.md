# 📊 Sales Performance & Market Trends Analysis Dashboard (Power BI)

##  Project Overview

This project is an **end-to-end Business Intelligence solution built using Power BI** to analyze sales performance and market trends across multiple dimensions (time, products, shipping, and operations).

The dashboard analyzes **$2.6B in total sales across 275K orders**, helping management:

* Identify growth peaks and early decline signals
* Understand product performance (value vs volume)
* Optimize pricing, operations, and workforce allocation
* Support strategic, data-driven decision making
The solution transforms complex raw sales data into **clear, actionable business insights** using interactive dashboards and a well-structured data model.
---
## Business Objectives
* Monitor overall sales performance and market trends
* Detect growth peaks and early decline signals
* Identify top-performing and underperforming products
* Compare **Revenue vs Order Volume** to support pricing strategy
* Improve operational planning and workforce distribution
* Provide executives with a single source of truth for decision-making
---
## Key KPIs Tracked
* Total Sales: **$2.6B**
* Total Orders: **275K**
* Sales Trend by Year
* Revenue by Product
* Orders by Product
* Orders by Ship Date
* Orders by Workday vs Weekend
---
## Analysis Sections
### Financial Overview
* **Total Sales & Total Orders** overview to track overall business size and performance.
* **Yearly Trend Analysis (Total Orders by Year):**

  * Strong growth from 2011 → peak in 2013 (~132K orders)
  * Noticeable decline in 2014, signaling a need for root-cause analysis.
* **Subtotals by Product:**

  * Top product generates **$44M** in revenue.
  * Helps identify “Golden Products” that drive most of the business value.
---
### Operational & Product Insights

* **Orders by Ship Date:**

  * Monthly fluctuations with recurring seasonal peaks.
* **Revenue vs Orders (Value vs Volume Analysis):**

  * *Mountain-200* dominates revenue.
  * Accessories and bottles dominate order count.
  * Supports pricing and product mix strategy decisions.
* **Orders by Workday:**

  * **87.5% of orders happen on workdays**
  * Insight used for workforce planning and promotional strategy on weekends.
---
## Data Model (Core of the Project)
* Implemented a **Star Schema** data model:
  * Central Fact Table: `SalesOrderHeader`
  * Connected to multiple Dimension tables (Products, Date, Territory, Employees, etc.)
* Relationships: **One-to-Many**
* Built a custom **Date Dimension Table** enabling:

  * Workday vs Weekend analysis
  * Month names, year filtering, and time intelligence calculations
* This design ensures:

  * High performance
  * Accurate cross-filtering
  * Scalable analytics
---
## Tools & Technologies

* Power BI Desktop**
* DAX (Measures, KPIs, Time Intelligence)**
* Power Query (ETL & Data Cleaning)**
* Star Schema Data Modeling**
* Interactive Visualizations & Drill-down Analysis**
---
## Business Impact
* Enabled leadership to **detect early sales decline trends** and react proactively
* Identified **high-impact products and revenue drivers**
* Supported **workforce optimization using operational insights**
---
## Deliverables
* Interactive Power BI Dashboard
* Cleaned & modeled dataset
* Executive-ready KPI views
* Drill-down and filtering capabilities
