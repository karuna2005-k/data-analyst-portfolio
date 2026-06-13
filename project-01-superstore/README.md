# Superstore Sales Analysis

## Problem Statement
A retail superstore is losing profit despite growing sales. This analysis identifies which discounting patterns, product categories, and regions are destroying margins — and what pricing strategy changes would reverse the trend.

## Dataset
- **Source:** Sample Superstore dataset (publicly available)
- **Size:** 9,994 retail transactions
- **Domain:** Retail / E-commerce
- **Period:** Multi-year sales data across USA regions

## Tools Used
- Python, Pandas, NumPy (data cleaning and analysis)
- Matplotlib, Seaborn (visualizations)
- Tableau (interactive dashboard with calculated fields)

## What I Did
- **Cleaned data:** Checked for nulls, standardized category and region labels, parsed date columns for time-series analysis
- **Analyzed:** Profit margins across product categories, discount ranges, regions, and customer segments
- **Visualized:** Built a 5-chart Tableau dashboard with calculated fields segmenting profit by category and region
- **Referenced in:** Deloitte Forage Data Analytics Job Simulation — adopted as a reference dashboard

## Key Findings
1. **Discounts above 40% are the primary profit loss driver** — orders with 40%+ discounts have a negative average profit margin across all categories
2. **Furniture category loses money at scale** — despite being high in sales volume, Furniture has the lowest profit margin of all categories
3. **Technology has the highest profit margin** — even at moderate discount levels, Technology products remain profitable
4. **The West region outperforms all others** in both sales volume and profit margin

## Business Recommendations
1. **Cap discounts at 30% maximum** across all product lines — discounts beyond this threshold consistently produce negative margins. Implement a discount approval process for orders requiring >30% reduction.
2. **Re-evaluate Furniture pricing strategy** — either raise base prices to absorb discount impact or reduce discount frequency for low-margin Furniture sub-categories (Tables in particular).
3. **Replicate West region sales strategy** in the Central and South regions — analyze what pricing, product mix, and customer acquisition tactics are working in the West and systematically apply them elsewhere.

## Dashboard
> Built in Tableau with calculated fields for profit ratio, regional segmentation, and category-level filtering. Used in Deloitte Forage job simulation.

## Files in This Project
- `superstore_analysis.ipynb` — full analysis: data cleaning, EDA, profit margin breakdown, regional comparison