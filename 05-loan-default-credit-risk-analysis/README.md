# Project 5: Loan Default / Credit Risk Analysis

## Problem Statement

A lender wants to understand which borrower characteristics are most associated with loan default, so credit risk can be flagged earlier in the sanction process rather than discovered after disbursement. This project draws directly on housing finance/lending domain context from hands-on loan case processing experience — the BFSI differentiator angle for this portfolio.

## Dataset

- Suggested source: a public loan/credit risk dataset (e.g. Kaggle "Loan Default Prediction" or "Give Me Some Credit" style dataset), with borrower income, credit history, loan amount, tenure, and default flag
- `data/raw/` — Raw loan application/repayment data — kept intentionally unclean: missing income fields, inconsistent categorical labels, duplicate application IDs
- `data/cleaned/` — Cleaned, standardized version

## Key Business Questions

1. Which borrower segments (by income band, loan-to-value ratio, credit history, loan purpose) show the highest default rate?
2. Is default risk more strongly tied to loan size, tenure, or borrower credit history?
3. What early-warning signal in the sanction data would flag high-risk applications before disbursement?
4. What's the one specific underwriting recommendation this analysis supports (e.g. "applications with X characteristic default at 3x the base rate")?

## Approach by Tool

### Spreadsheets
- Clean loan/borrower records
- Default rate by segment via pivot tables
- Simple risk-scoring logic based on the strongest correlated factors

### SQL
*To add*

### Power BI
*To add — likely candidate for a credit risk segmentation dashboard*

### Python
*To add — logistic regression or decision tree for default prediction*

## Findings & Recommendation

*To be completed — should land on one clear, specific number or action.*

## Why this project matters for this portfolio

This is the project that most directly leverages BFSI/housing finance domain experience — it's the one where "understands lending operations, not just spreadsheets" comes through clearly to a reviewer.

## Files in this folder

- `spreadsheets/` — Excel/Sheets workbook
- `sql/` — SQL scripts
- `powerbi/` — .pbix file + dashboard screenshots
- `python/` — Notebook/scripts
- `assets/` — Screenshots used in this README
