# Superstore Power BI Sales Analysis

An interactive Power BI dashboard built to analyze sales, profit, quantity, customer segments, categories, and regional performance using the Superstore dataset.

## 📊 Dashboard

![Superstore Power BI Dashboard](Screenshot%202026-10-08%20121345.png)

## 🎯 Project Objective

The objective of this project is to analyze Superstore sales data and build an interactive Power BI dashboard that provides insights into:

- Sales and profitability
- Monthly profit trends
- Customer segment performance
- Product category performance
- Regional profitability
- Year-wise performance
- Geographic profit distribution

## 🛠️ Tools Used

- Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization

## 📈 Key KPIs

| KPI | Value |
|---|---:|
| Total Revenue | 2.30M |
| Total Profit | 286.40K |
| Profit Margin | 0.12 |
| Total Quantity | 38K |

## 📊 Dashboard Analysis

### Sales & Profitability
The dashboard provides an overview of total revenue, total profit, profit margin, and quantity.

### Time Analysis
A Year slicer allows users to analyze performance across 2014–2017, while the monthly trend visual shows changes in profit throughout the year.

### Segment Analysis
Profit is analyzed across:

- Consumer
- Corporate
- Home Office

### Category Analysis
The dashboard analyzes quantity, sales, and profitability across different product categories.

### Regional Analysis
Profit is analyzed across different regions using interactive charts and a geographic map.

## 🧮 DAX Measures

```DAX
Total Profit = SUM(Fact_sales[Profit])

Total Revenue = SUM(Fact_sales[Sales])

Total Quantity = SUM(Fact_sales[Quantity])

Profit Margin = DIVIDE([Total Profit], [Total Revenue])
