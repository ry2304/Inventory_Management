# Inventory Management Analysis

## Project Background

This project simulates an Inventory Management System for a mid-sized consumer electronics retail company. 

The primary objective is to clean and analyze inventory data to:

- Identify stock trends
- Optimize inventory turnover
- Make informed restocking decisions

Insights and recommendations are provided on the following key areas:

- Inventory Valuation
- Stock Turnover Rates
- Restocking Costs
- Product Profitability

The SQL queries used for data cleaning and analysis are available [here](SQL).
The Power BI dashboard is available [here](Dashboard.png).
The dataset used for this project is available [here](Inventory_Records.xlsx).

---

## Dataset Information

**File Name**: `Inventory_Records.csv`

The dataset contains product inventory information, including:

- `product_id`: Unique identifier
- `product_name`: Description of the product
- `opening_stock`: Starting quantity at the beginning of the period
- `stock_in`: New stock added
- `units_sold`: Quantity sold
- `closing_stock`: Remaining stock
- `cost_per_unit`: Cost per item
- `total_closing_stock`: Total value of the remaining inventory

---

## Executive Summary

### Key Insights

- The total inventory value is approximately **$359,760** across over **2,000 units**.
- Smartphones and Laptops represent the largest portion of inventory value and have healthy turnover rates.
- Several items, such as Anti-Glare Screens and Gaming Desks, have low turnover rates, which could lead to higher holding costs.

---

## Deep Dive Analysis

### 1. Inventory Valuation

- Total Inventory Value: Approximately **$359,760**
- Top Categories by Value: **Smartphones, Laptops, Routers**

### 2. Stock Turnover Rates

- Highest Turnover: **Smartphones (~20%)**
- Lowest Turnover: **Anti-Glare Screens (~8%)**

### 3. Restocking Costs

- Estimated Restocking Cost Needed: Approximately **$125,000**
- Focus restocking on high-demand items like **Smartphones** and **Keyboards**.

### 4. Product Profitability

- Top Revenue Generators: **Smartphones, Laptops, Routers**
- Low-Performing Products: **Anti-Glare Screens, Gaming Desks**

---

## Recommendations

- Prioritize restocking products with high turnover to avoid stockouts.
- Promote or discount low-turnover products to recover costs.
- Monitor turnover rates monthly to dynamically adjust inventory.
- Reassess slow-moving stock and renegotiate supplier terms.
