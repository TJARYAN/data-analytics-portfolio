# Project 4: Marketing Campaign Performance Analysis

## Problem Statement

A marketing team runs multiple campaigns across channels but isn't sure which ones are actually earning their spend back. This project analyzes campaign-level performance to identify which channels/campaigns deliver the best return, so future budget can shift toward what works.

## Dataset

- Suggested source: a public marketing campaign dataset (e.g. Kaggle "Marketing Campaign Performance" style dataset) with spend, impressions, clicks, conversions, and revenue by campaign/channel
- `data/raw/` — Raw campaign-level data — kept intentionally unclean: missing spend values, inconsistent channel naming, duplicate campaign rows
- `data/cleaned/` — Cleaned, standardized version

## Key Business Questions

1. Which channel/campaign has the best ROI (revenue generated per rupee spent), and which is actively losing money?
2. How does conversion rate vary by channel — is low ROI a spend problem or a conversion problem?
3. Is performance seasonal (specific months/campaigns spike), or consistent across the period?
4. What's the one specific budget reallocation this analysis supports (e.g. "shift ₹X from Channel A to Channel B for an estimated Y% revenue lift")?

## Approach by Tool

### Spreadsheets
- Clean campaign data
- ROI and conversion rate calculations by channel/campaign via pivot tables
- Identify top/bottom performers

### SQL
*To add*

### Power BI
*To add — likely candidate for a channel ROI comparison dashboard*

### Python
*To add — deeper trend/seasonality analysis*

## Findings & Recommendation

*To be completed — should land on one clear, specific number or action.*

## Files in this folder

- `spreadsheets/` — Excel/Sheets workbook
- `sql/` — SQL scripts
- `powerbi/` — .pbix file + dashboard screenshots
- `python/` — Notebook/scripts
- `assets/` — Screenshots used in this README
