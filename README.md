# Retail Sales Performance Analysis

## Project Overview
An end-to-end data analysis project examining retail sales performance 
across products, regions and customers to identify profitability drivers 
and areas for improvement.

## Business Questions
1. Which product categories and sub-categories are most/least profitable?
2. Is discounting helping or hurting profit?
3. Which regions are underperforming and why?
4. Who are our most valuable customers?
5. Are there seasonal trends in sales?

## Key Findings
- **Furniture** generates £742k in sales but only £18k profit (3.9% margin)
- **Tables** alone lose £17,725 due to excessive discounting (avg 26%)
- Sub-categories with **discounts above 20%** are all loss-making
- **Central region** has the lowest margin (7.9%) despite 629 customers
- **Sales peak in September and November** — clear seasonal pattern
- **Tamara Chand** is the most profitable customer at £8,981 profit

## Tools Used
- **Python** (pandas, matplotlib, seaborn) — data cleaning & EDA
- **SQL** (SQLite) — business queries including CTEs and window functions
- **Power BI** (PL-300 certified) — interactive 3-page dashboard

## Dashboard Pages
| Page | Content |
|------|---------|
| Executive Summary | KPI cards, sales trend, category performance |
| Product Analysis | Sub-category profit, discount vs margin scatter |
| Regional & Customer | Regional comparison, top 10 customers |

## Dataset
- Source: Superstore Sales Dataset (Kaggle)
- 9,994 rows, 21 columns
- Years: 2014–2017

## Files
| File | Description |
|------|-------------|
| `project1.ipynb` | Python analysis notebook |
| `superstore_cleaned.csv` | Cleaned dataset |
| `dashboard_page1.png` | Executive Summary |
| `dashboard_page2.png` | Product Analysis |
| `dashboard_page3.png` | Regional & Customer Analysis |

## Recommendations
1. Cap discounts at 15% across all sub-categories
2. Review Tables pricing strategy — currently losing £17k
3. Investigate Central region's low margin (7.9% vs West's 14.9%)
4. Launch VIP retention programme for top 10 customers
5. Plan promotions around February dip and maximise stock for Sep/Nov peaks
