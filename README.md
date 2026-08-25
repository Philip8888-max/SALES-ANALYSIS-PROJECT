# Sales Performance Dashboard (Excel)

## Overview
My first project on the Data Analytics track at TS Academy — an interactive 
Excel dashboard built from a raw sales transaction dataset, covering KPI 
calculation, PivotTable analysis, and dynamic data visualization.

## Dashboard

![Sales Data Analysis Dashboard](SALES_DATA_ANALYSIS.png)

## Objective
Analyze sales transactions across regions, cities, products, and sales reps 
to answer key business questions:
- What is the most profitable product?
- Which sales rep generates the highest revenue?
- Which city carries the highest cost of goods sold (COGS)?
- Which month had the weakest customer activity?

## Tools Used
- Microsoft Excel (PivotTables, PivotCharts, Slicers, Formulas)

## Process
1. **Data Cleaning** — Reviewed the raw dataset (Date, Region, City, Customer 
   Type, Channel, Product, Category, Unit Price, Quantity, Sales Rep, Cost 
   Price) for inconsistencies.
2. **KPI Calculation** — Derived Revenue, COGS, and Profit at the transaction 
   level using formulas, then aggregated totals.
3. **PivotTable Analysis** — Built four PivotTables:
   - Product by Profit
   - Sales Rep by Revenue
   - City by COGS
   - Monthly Customer Count
4. **Visualization** — Converted each PivotTable into a chart and combined 
   them into a single dashboard.
5. **Interactivity** — Added Region and Category slicers connected to all 
   four PivotTables for cross-filtering.

## Key Insights
- **Laptop A13** was the most profitable product overall (₦105.3M), well 
  ahead of the next closest product, Sofa Classic (₦69.2M).
- **Peter** generated the highest revenue among sales reps (₦434.8M), 
  slightly ahead of Musa (₦397.7M).
- **Kano** had the highest cost of goods sold (₦149.7M), ahead of Lagos, 
  Port Harcourt, and Abuja.
- **May** showed a sharp drop in transaction volume compared to Jan–Apr 
  (500+ each), flagging it as the weakest month for customer activity — 
  likely partial-month data, worth noting as a caveat in analysis.
- Overall profit margin sits at **20%** — ₦2.33B total revenue against 
  ₦1.86B COGS, netting ₦465.7M profit.

## File
📊 [PHILIP_OGUNDIRAN_-_Excel_Project.xlsx](PHILIP_OGUNDIRAN_-_Excel_Project.xlsx) 
— includes Data, Pivot Tables, and Dashboard sheets.

## Note
This is a beginner project completed as part of the TS Academy Data 
Analytics program. Feedback and suggestions are welcome as I continue 
building out my portfolio.
