# Project 3: HR Attrition Analysis

## Problem Statement

A company's HR team wants to understand why employees are leaving — which departments, roles, or tenure bands have the highest attrition — so leadership can act before losing more people, instead of reacting after resignations pile up.

## Dataset

- Suggested source: a public HR analytics dataset (e.g. Kaggle "IBM HR Analytics Employee Attrition" or similar), which includes department, tenure, satisfaction, salary band, and attrition flag
- `data/raw/` — Raw employee records — kept intentionally unclean: missing satisfaction scores, inconsistent department naming, duplicate employee IDs
- `data/cleaned/` — Cleaned, standardized version

## Key Business Questions

1. Which department(s) and role(s) have the highest attrition rate, and how does that compare to headcount share?
2. Is attrition concentrated in a specific tenure band (e.g. within the first year) or salary band?
3. Which factors (overtime, distance from work, satisfaction score, years since last promotion) correlate most strongly with leaving?
4. What's the one specific intervention this analysis supports (e.g. "retention risk is concentrated in X, targeted at Y cost")?

## Approach by Tool

### Spreadsheets
- Clean employee records
- Attrition rate by department/role/tenure band via pivot tables
- Simple risk-flagging logic based on the strongest correlated factors

### SQL
*To add*

### Power BI
*To add — likely candidate for an attrition-by-segment dashboard*

### Python
*To add — correlation analysis, possibly a simple logistic regression for attrition risk*

## Findings & Recommendation

*To be completed — should land on one clear, specific number or action.*

## Files in this folder

- `spreadsheets/` — Excel/Sheets workbook
- `sql/` — SQL scripts
- `powerbi/` — .pbix file + dashboard screenshots
- `python/` — Notebook/scripts
- `assets/` — Screenshots used in this README
