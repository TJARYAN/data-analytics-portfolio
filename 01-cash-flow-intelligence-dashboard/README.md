# Project 1: Cash Flow Intelligence Dashboard

## Problem Statement

Personal finance across multiple bank accounts is hard to track in real time — spending patterns, irregular transactions, and true financial health get lost across statements. This project builds a Financial Health Score and cash flow analysis using real transaction data from three personal bank accounts.

## Dataset

- Source: Real transaction data, 3 personal bank accounts
- `data/raw/` — Raw_Transactions, left intentionally unclean (source of truth): duplicate rows, inconsistent formatting, blank cells
- `data/cleaned/` — Cleaned_Data scaffold, output of the cleaning process below

## Key Business Questions

1. Where is money leaking or being spent inefficiently across accounts?
2. What does a 0–100 Financial Health Score look like month over month?
3. Which anomalies (duplicate charges, unusual spikes) can be flagged automatically?
4. What's the one concrete recommendation this analysis supports?

## Approach by Tool

### Spreadsheets (Module 1 — Complete)
- Cleaned raw transaction data (deduplication, formatting standardization, handling blanks)
- Built the Financial Health Score formula logic
- Detected baked-in anomalies

### SQL (Module 2 — In Progress)
- Rebuild the cleaning + scoring logic as SQL queries
- *To add once complete*

### Power BI (Planned)
- Interactive dashboard version of the Financial Health Score
- *To add once complete*

### Python (Planned)
- Automated anomaly detection using pandas
- *To add once complete*

## Findings & Recommendation

*To be completed once the analysis across all tool layers is finalized — this should land on one clear, specific number or action.*

## Files in this folder

- `spreadsheets/` — Excel/Sheets workbook with Raw_Transactions, Cleaned_Data, Project_Brief tabs
- `sql/` — SQL scripts (once Module 2 is done)
- `powerbi/` — .pbix file + dashboard screenshots (once built)
- `python/` — Notebook for anomaly detection (once built)
- `assets/` — Screenshots used in this README
