# ☕ Coffee Sales Dashboard

An interactive Excel dashboard that analyzes coffee order data — sales trends, top customers, and revenue by country — built entirely with native Excel features (PivotTables, PivotCharts, and Slicers). No add-ins or macros required.

![Dashboard Screenshot](<img width="1920" height="1080" alt="Screenshot 2026-09-05 101422" src="https://github.com/user-attachments/assets/e65a42d5-afbe-40c6-baf2-eebd38405798" />
)

---

## 📊 Overview

This project turns a raw coffee-order transaction log (1,000 orders) into a single-page executive dashboard, answering:

- How are sales trending over time, broken down by coffee type?
- Which countries generate the most revenue?
- Who are the top 5 customers by spend?

## 🗂️ Workbook Structure

| Sheet | Purpose |
|---|---|
| `Dashboard` | The final visual report — combines all charts below into one view |
| `TotalSales` | PivotTable + line chart: monthly sales (2019–2022) by coffee type (Arabica, Excelsa, Liberica, Robusta) |
| `CountryBarChart` | PivotTable + bar chart: total sales by country (US, UK, Ireland) |
| `Top5Customers` | PivotTable + bar chart: top 5 customers ranked by total spend |
| `orders` | Raw transaction data — order ID, date, customer, product, quantity, unit price, sales value |
| `customers` | Customer master data referenced by the orders table |
| `products` | Product catalog (coffee type, roast, size, pricing) referenced by the orders table |

## ✨ Features

- **Dynamic PivotTables** driving every chart, so the whole dashboard updates from one data refresh
- **Time-series analysis** of sales by year and month, segmented by coffee type
- **Geographic breakdown** of revenue across the US, UK, and Ireland
- **Customer ranking** to quickly surface the highest-value customers
- Built for **Excel 2013 or later** — no macros, no external add-ins

## 🚀 Getting Started

1. Download `coffeeOrdersProject.xlsx`.
2. Open it in Microsoft Excel (2013+) or Excel Online.
3. Go to the **Data** tab → **Refresh All** to recalculate all PivotTables and charts.
4. Explore the `Dashboard` sheet, or dig into the individual PivotTable sheets for more detail.

## 🛠️ Built With

- Microsoft Excel — PivotTables, PivotCharts, formulas
- Raw order-level data (Order ID, Customer, Product, Quantity, Sales)



