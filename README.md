# Transportation Sales Performance Analysis

This project analyzes sales performance data in the transportation sector to provide actionable insights. Using Python and powerful visualization tools, the analysis identifies trends, evaluates product performance, and explores deal size contributions.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Tools Used](#tools-used)
- [Link to Google Colab and Slide](#link-to-google-colab-and-slide)

---

## Project Overview
The transportation industry generates vast amounts of sales data. This project leverages that data to uncover patterns, optimize strategies, and make data-driven decisions for improving revenue performance.

---

## Objectives
1. Analyze sales by product lines to identify high and low performers.
2. Uncover temporal trends in sales performance over time.
3. Investigate the correlation between deal size and total sales, and quantify contributions of small, medium, and large deals.

---

## Dataset
The dataset contains the following key fields:
- **ORDERNUMBER:** Unique identifier for each sales order.
- **QUANTITYORDERED:** Number of units ordered per product.
- **PRICEEACH:** Price per unit of the product.
- **ORDERDATE:** Date the order was placed.
- **STATUS:** Current order status (e.g., Shipped, Cancelled).
- **PRODUCTLINE:** Product category (e.g., Classic Cars, Trains).
- **DEALSIZE:** Size of the deal (Small, Medium, Large).

---

## Methodology
1. **Data Cleaning:** 
   - Removed duplicates and handled missing values.
   - Converted dates to proper datetime formats.
2. **Feature Engineering:** 
   - Created a `SALES` column (`QUANTITYORDERED * PRICEEACH`).
3. **Exploratory Data Analysis (EDA):** 
   - Visualized sales by product line, sales trends over time, and deal size contributions.
4. **Visualizations:**
   - Bar, line, scatter, and pie charts for key insights.

---

## Key Findings
- **Product Line Performance:** Classic Cars lead in sales, while Trains underperform.
- **Seasonal Trends:** Sales peak during November-December due to holiday demand.
- **Deal Size Contributions:** Medium deals contribute 59.8% of total revenue, highlighting their importance.

---

## Tools Used
- **Python Libraries:**
  - `Pandas` for data cleaning and manipulation.
  - `Matplotlib` and `Seaborn` for data visualization.
- **Environment:** Google Colab for an interactive and collaborative analysis workflow.

---

## Link to Google Colab and Slide
- [bit.ly/TransportSales](https://bit.ly/TransportSales)
- [bit.ly/Transportsales_slide](https://bit.ly/Transportsales_slide)
