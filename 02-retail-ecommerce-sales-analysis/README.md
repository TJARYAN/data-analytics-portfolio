# Project 2: Retail / E-commerce Sales Analysis

## Problem Statement

A retail/e-commerce business wants to understand what's actually driving revenue — which products, regions, and customer segments matter most — and where the biggest untapped opportunity sits, so they can decide where to focus limited marketing and inventory budget next quarter.

## Dataset

- Suggested source: a public retail/e-commerce transactions dataset (e.g. Kaggle "Online Retail" or "Superstore Sales" style dataset), sized to allow realistic messiness
- `data/raw/` — Raw transaction-level data (orders, products, customers, dates, revenue) — kept intentionally unclean: duplicate orders, missing categories, inconsistent date formats
- `data/cleaned/` — Cleaned, deduplicated, standardized version

## Key Business Questions

1. Which product categories/regions generate the most revenue, and which are underperforming relative to their potential?
2. Is revenue growth coming from more customers, or existing customers spending more (basket size vs. customer count)?
3. Which customer segment (by frequency/recency/value) is most at risk of churning, based on ordering patterns?
4. What's the one specific reallocation of budget or focus this analysis supports (e.g. "shift X% of ad spend from Category A to Category B")?

## Approach by Tool

### Spreadsheets
- Clean and deduplicate raw order data
- Pivot tables for revenue by category/region/month
- Build a basic RFM (Recency, Frequency, Monetary) customer segmentation

### SQL
*To add*

### Power BI
*To add — likely candidate for a sales trend + segmentation dashboard*

### Python
*To add — cohort analysis or basic churn flagging*

## Findings & Recommendation

*To be completed — should land on one clear, specific number or action.*

## Files in this folder

- `spreadsheets/` — Excel/Sheets workbook
- `sql/` — SQL scripts
- `powerbi/` — .pbix file + dashboard screenshots
- `python/` — Notebook/scripts
- `assets/` — Screenshots used in this README
