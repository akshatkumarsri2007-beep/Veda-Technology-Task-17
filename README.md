# Veda-Technology-Task-17
#  Monthly Sales Trend Analysis

**Data Analytics Internship — Veda Technology**
Task 17 · Day 17 · Level 1
Author: **Akshat Srivastava**

---

##  Overview

This project summarizes retail order data by month and visualizes the resulting sales trend using the **Superstore dataset**. It was completed as part of the Data Analytics track of the Veda Technology internship program.

##  Objective

Summarize sales by month and visualize the trend — practicing date grouping and line chart creation.

##  Tools Used

- **Excel** — `SUMIF` formulas, native line chart
- **Python** — `pandas` for grouping/aggregation, `matplotlib` for visualization

##  Repository Contents

| File | Description |
|---|---|
| `Superstore_Dataset.xlsx` | Raw input dataset (300 orders) |
| `Monthly_Sales_Trend.xlsx` | Excel workbook with Year-Month helper column, monthly summary table, and line chart |
| `Monthly_Sales_Trend_Report.docx` / `.pdf` | Final formatted report with methodology, table, chart, and insights |
| `monthly_sales_chart.png` | Exported line chart image |

##  Methodology

1. Converted `Order Date` into a `Year-Month` format (e.g. `2024-01`) to enable monthly grouping.
2. Aggregated `Sales` for each month using `SUMIF` (Excel) / `groupby()` (Python).
3. Sorted monthly totals chronologically (Jan 2024 → Aug 2025).
4. Plotted a line chart with **Month** on the X-axis and **Total Sales** on the Y-axis.

##  Key Insights

- **Total sales** across the 20-month period: **₹1,79,436.02** (avg. **₹8,971.80**/month)
- **Highest** monthly sales: **June 2025** — ₹16,174.82
- **Lowest** monthly sales: **December 2024** — ₹4,707.18
- Sales show noticeable month-to-month fluctuation rather than one steady trend, suggesting seasonal or order-volume driven variation.
- April–June 2025 shows a strong upward spike compared to the same period in 2024.
