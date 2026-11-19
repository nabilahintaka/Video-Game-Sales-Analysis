
# E-Commerce Sales Performance Analysis

## Overview

This project analyzes simulated e-commerce sales transactions from **Shopee and TikTok Shop** using Microsoft Excel to evaluate **marketplace performance, revenue, order status, and product sales.** The analysis combines **data cleaning, transaction validation, Excel formulas, and dashboard reporting** to generate actionable insights for sales monitoring and operational decision-making.

The goal is to demonstrate how structured Excel-based reporting can support **accurate sales tracking, marketplace comparison, and SKU performance analysis.**

## Summary

This analysis covers **500 synthetic transactions from July to September 2026** across Shopee and TikTok Shop. The workbook reports **Rp55,339,000 in net revenue** from **414 valid completed orders**, with an Average Order Value (AOV) of **Rp133,669**.

Shopee contributes more revenue than TikTok Shop, while September records the highest monthly sales. The validation process also identifies **7 flagged records**, highlighting the importance of data quality in reliable sales reporting.

These findings demonstrate how **transaction validation, clearly defined KPIs, and marketplace-level analysis** can support more consistent business reporting.

---

## Data Processing

* Organized 500 synthetic sales transactions into structured Excel worksheets
* Used VLOOKUP to retrieve product information from the Product Master
* Identified duplicate order IDs and unknown product references
* Applied validation rules to flag transactions requiring review
* Excluded invalid, cancelled, and refunded transactions from eligible net revenue
* Used SUMIFS and COUNTIFS to calculate sales performance metrics

---

## Sales Performance Analysis

* Analyzed net revenue and completed orders across Shopee and TikTok Shop
* Calculated Average Order Value (AOV) from valid completed transactions
* Compared monthly revenue performance from July to September 2026
* Evaluated SKU-level revenue contribution and units sold
* Monitored transaction validation results to support reporting accuracy

---

## Key Insights

01 Shopee generates higher net revenue than TikTok Shop, contributing approximately 57.3% of total revenue

02 September records the highest monthly net revenue at Rp22,055,000

03 A total of 414 valid completed orders generate Rp55,339,000 in net revenue

04 Seven transactions are flagged for validation, demonstrating the importance of data quality in sales reporting

---

## Dashboard

The Excel dashboard provides an overview of e-commerce sales performance across Shopee and TikTok Shop, highlighting key metrics such as **Net Revenue, Completed Orders, Average Order Value, and Flagged Records.**

The dashboard also supports monitoring monthly sales trends and comparing marketplace performance.

The dashboard is available directly in the Excel workbook included in this repository.

---

## Tools

* Microsoft Excel
* VLOOKUP
* IF, AND, OR, IFERROR
* COUNTIF & COUNTIFS
* SUMIFS
* Excel Charts & Dashboard

---

## Project Structure

* Raw transaction data → Raw Sales Data worksheet
* Product reference → Product Master worksheet
* Data cleaning & validation → Data Cleaning worksheet
* Sales reporting & SKU analysis → Sales Analysis worksheet
* Visualization → Excel Dashboard worksheet
* Insights → Business recommendations

**Repository Files**

```text
E-Commerce-Sales-Performance-Analysis/
├── README.md
└── Ecommerce_Sales_Analysis_Portfolio.xlsx
```

---

## Business Recommendations

**Marketplace Performance Monitoring**

Regularly compare sales revenue and completed orders across Shopee and TikTok Shop to identify differences in channel performance and support marketplace planning.

**SKU Performance Optimization**

Use product-level revenue and units-sold analysis to identify high-performing SKUs and support inventory allocation and promotional decisions.

**Order Status Monitoring**

Track cancelled and refunded orders separately from completed transactions to improve sales reporting accuracy and identify potential operational issues.

**Data Quality Improvement**

Implement consistent transaction validation procedures to detect duplicate records, invalid product references, and other data quality issues before generating sales reports.

---

## Limitations

* The dataset contains synthetic transactions and does not represent actual Shopee or TikTok Shop sales
* The analysis covers only three months of sales activity
* Marketplace commissions, shipping fees, advertising costs, and product costs are not included
* Net revenue should not be interpreted as business profit or official marketplace GMV
* Flagged transactions require additional review before being treated as verified records

---

## Future Work

* Automate sales data imports and cleaning using Power Query
* Develop Pivot Tables and interactive slicers for more flexible reporting
* Analyze cancellation and refund rates across marketplaces
* Integrate product costs and marketplace fees for profitability analysis
* Automate recurring sales performance reports

---

## Dataset

Source: **Synthetic E-Commerce Sales Dataset**

The dataset consists of 500 simulated transactions from Shopee and TikTok Shop covering July–September 2026, created for portfolio and educational purposes.

The complete dataset, analysis, and dashboard are included in the Excel workbook available in this repository.
