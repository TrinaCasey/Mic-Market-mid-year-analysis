# MIC-Market Mid-Year Profit Analysis 2026

## Problem Statement
MIC Market recorded a $200,000 profit decline in H1 2026 vs H1 2025.

## Objective
Identify root causes of the profit drop using the transactional and operational data, and recommend data-driven actions to recover losses in H2 2026.

## Data Sources
**Till Transactions**: Voids, returns, no-sale events by staff/register
**POS Machines**: Transaction level sales, price, cost, discounts
**Stock Control**: Breakage, Shrinkage, Stock adjustments
**Procurement**: Supplier Invoices, Purchasee Orders, Cost price changes
**CCTV Reports**: Incident logs for theft, queue times, staff buying and staff presence

## Key Metrics Tracked
1. SAles Volume vs Basket size
2. Gross margin % by department
3. Shrinkage rate: voids + breakages + theft
4. Customer churn: spend by loyalty segment

## Tools Used
Excel, SQL, Python, Matplotlib, Seaborn, PowerBI, Pandas, Jupyter

## How to Run
1. Clone Repo
2. Run 'notebooks/01_eda_profit_drop.ipynb' top to bottom
3. See 'charts/' for exported visuals
