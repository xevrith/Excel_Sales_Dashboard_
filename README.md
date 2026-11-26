# Executive Summary & Profitability Dashboard

An interactive Excel dashboard built to monitor sales performance and profitability across products, sales channels, regions, countries, and time.

## Dashboard Preview

![Executive Summary & Profitability Dashboard](dashboard.png)

## Project Overview

This project analyzes a European sales dataset containing **2,707 sales records**. The Excel workbook is organized into three worksheets:

- **Data**: source sales records stored in an Excel table named `SalesDataTable`.
- **PivotTable**: supporting PivotTables and summarized metrics.
- **Dashboard**: visual summary of revenue, gross profit, sales volume, country performance, sales channels, and regions.

## Key Performance Indicators

The dashboard reports the following overall results from the workbook:

| KPI | Result |
|---|---:|
| Total Revenue | $645,223.18 |
| Gross Profit | $296,384.25 |
| Gross Profit Margin | 45.94% |
| Total Units Sold | 6,698 |
| Number of Sales Records | 2,707 |
| Total COGS | $348,838.93 |

## Dashboard Analysis

### 1. Monthly Revenue & Gross Profit
A monthly trend comparison of total revenue and gross profit from January to December.

### 2. Top 5 Countries
Compares revenue across the five highest-revenue countries. The United Kingdom leads the displayed ranking.

### 3. Revenue Share by Sales Channel
Shows how revenue is distributed across:
- Corporate
- Marketplace
- Online Store
- Retail Partners

### 4. Revenue by Region
A doughnut chart compares revenue across Central Europe, Northern Europe, Southern Europe, and Western Europe.

### 5. Country-wise Revenue Map
A geographic view of revenue distribution across the countries represented in the dataset.

## Interactive Filters

The dashboard includes slicers for:
- Product Category
- Country
- Quarter

These filters allow users to explore the dashboard by selected categories, markets, and quarters.

## Dataset Fields

The source data includes fields such as:

- ID and Order Date
- Region and Country
- Sales Channel and Customer Type
- Product Category and Product
- Units Sold, Unit Price, Discount %, and Unit Cost
- Revenue, COGS, and Gross Profit

Revenue, COGS, and Gross Profit are calculated in the source worksheet using Excel formulas.

## Tools & Excel Features

- Microsoft Excel
- Excel Tables
- PivotTables
- PivotCharts
- Slicers
- KPI reporting
- Dashboard visualization
- Formula-based sales and profitability calculations

## How to Use

1. Download and open `Excel Sales Dashboard.xlsx` in Microsoft Excel.
2. Open the **Dashboard** worksheet.
3. Use the Product Category, Country, and Quarter slicers to filter the report.
4. Review the KPI cards and charts to compare sales and profitability.

## Project Files

- `Excel Sales Dashboard.xlsx` — workbook containing the source data, PivotTables, and dashboard.
- `dashboard.png` — dashboard preview image.

---

*This dashboard is an Excel-based sales reporting project designed to summarize revenue, costs, gross profit, and sales performance.*
