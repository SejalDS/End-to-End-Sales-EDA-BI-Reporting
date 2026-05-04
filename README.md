# End-to-End-Sales-EDA-BI-Reporting
 
An end-to-end data analysis project exploring 5 years of U.S. sales data to uncover revenue drivers, seasonal patterns, and profitability insights — delivered via Python EDA and an interactive Power BI dashboard.
 
---
 
## Problem Statement
 
Acme Co.'s sales data was fragmented across 6 unlinked tables with no visibility into regional performance, seasonal swings, top SKUs, or channel profitability. This project aimed to clean, consolidate, and analyze the data to surface actionable business insights.
 
---
 
## Project Workflow
 
1. **Define Business Objective** — Identify core questions around revenue, margin, and regional growth
2. **Collect & Consolidate Data** — Load multi-sheet Excel workbook into Google Colab
3. **Pre-processing & Cleaning** — Merge 6 tables, handle nulls, standardize columns, fix data types
4. **Feature Engineering** — Derive `profit`, `profit_margin_pct`, and calendar fields
5. **Exploratory Data Analysis** — Visualize trends, distributions, correlations, and segment performance
6. **Dashboard & Recommendations** — Build Power BI dashboard and present strategic findings
---
 
## Tech Stack
 
| Layer | Tools |
|---|---|
| Language | Python 3 |
| Data Wrangling | pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Google Colab |
| BI Dashboard | Power BI |
| Data Source | Excel (.xlsx) — 6 sheets |
 
---
 
## Dataset
 
- **Company:** Acme Co.
- **Period:** 2014–2018
- **Tables:** Sales Orders, Customers, Products, Regions, State–Region mapping, Budgets (2017)
- **Key Fields:** `order_date`, `revenue`, `cost`, `profit`, `profit_margin_pct`, `channel`, `us_region`, `product_name`, `customer_name`
---
 
## Key Insights
 
- 📅 **Seasonality:** January revenue averages $124M, dropping to $95M in April — a $29M swing
- 📦 **SKU Concentration:** Products 25 & 26 together drive ~25% of total sales
- 🌍 **Geographic Dominance:** California alone accounts for 7.6K orders (~$230M); West region shows largest swings
- 🔄 **Channel Trade-off:** Wholesale captures 54% of volume; Export leads with ~38% average margin
- 👥 **Customer Concentration:** Top customers (e.g., Aibox Company) generate disproportionately high revenue vs. bottom tier
- 📈 **Pricing is Key:** Unit price correlates 0.91 with revenue and 0.94 with cost — volume plays a secondary role
---
 
## Recommendations
 
1. **Seasonal Promotions** — Launch recovery campaigns in April; amplify January offers
2. **SKU Optimization** — Double down on top products; phase out low-margin SKUs
3. **Channel Strategy** — Incentivize Export partnerships; introduce volume deals in Wholesale
4. **Regional Investment** — Replicate California's success in Northeast & Midwest markets
5. **Margin Monitoring** — Flag orders below 80% margin and investigate cost drivers
---
 
## Dashboard Preview
 
The Power BI dashboard includes 3 pages:
- **Page 1 — Performance Summary:** Revenue, orders, and margin trends by region and time
- **Page 2 — Customer Segmentation:** Revenue vs. margin scatter, top/bottom customer rankings
- **Page 3 — Revenue Scenarios:** Budget vs. actuals and what-if analysis
---
 
## Project Structure
 
```
├── EDA_Regional_Sales_Analysis.ipynb   # Full Python EDA notebook
├── PPT_Regional_Sales_Analysis.pptx    # Presentation with insights & recommendations
├── README.md                           # Project overview (this file)
```
 
---
 
## Author
 
Built as a personal analytics project to demonstrate end-to-end data analysis skills — from raw data wrangling to business storytelling.
