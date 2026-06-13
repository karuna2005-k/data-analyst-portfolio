# Zomato Restaurant Intelligence

## Problem Statement
Restaurant owners on Zomato want to know what actually drives higher customer ratings. Is it cuisine type? Location? Whether they offer online delivery? This analysis answers those questions with data from 9,551 restaurants.

## Dataset
- **Source:** Zomato Restaurant Dataset (Kaggle)
- **Size:** 9,551 restaurants
- **Domain:** Food & Beverage / Consumer Apps
- **Columns:** Restaurant name, location, cuisines, average cost, online delivery availability, aggregate rating, votes

## Tools Used
- Python, Pandas, NumPy (data cleaning and EDA)
- Matplotlib, Seaborn (visualizations)

## What I Did
- **Cleaned data:** Removed duplicates, handled missing rating values, standardized cuisine category strings, converted cost columns to numeric
- **Analyzed:** Rating distribution across delivery vs. non-delivery restaurants, cuisine-level performance, city-tier comparisons, feature correlation with rating
- **Visualized:** Rating distribution histograms, delivery vs. non-delivery rating comparison, top cuisine types by avg rating, city-wise restaurant density

## Key Findings
1. **Online delivery restaurants score +0.4 rating points higher on average** — restaurants offering delivery have a mean rating of 3.9 vs. 3.5 for dine-only, a statistically significant gap across all cuisine types
2. **North Indian and Chinese cuisines dominate in volume** but specialty/fusion restaurants have higher per-restaurant avg ratings — volume does not equal quality perception
3. **City-tier matters significantly** — Metro city restaurants (Delhi, Mumbai, Bangalore) have 23% more votes on average, but Tier-2 city restaurants often have higher ratings despite lower engagement

## Business Recommendations
1. **Enable online delivery if not already active** — the +0.4 rating uplift is consistent across cuisine types. For restaurants currently rated 3.5–3.8, adding delivery could push them into the high-visibility 4.0+ band on the app.
2. **Focus on vote accumulation in early months** — Zomato's ranking algorithm favors restaurants with more votes. New restaurants should run promotions specifically to drive reviews, not just footfall.
3. **Tier-2 city restaurant chains should maintain premium quality positioning** — data shows Tier-2 restaurants can compete on rating quality; the differentiation opportunity is in converting local high ratings into broader brand recognition.

## Files in This Project
- `zomato_analysis.ipynb` — full analysis: data cleaning, delivery vs. non-delivery comparison, cuisine analysis, city-tier breakdown