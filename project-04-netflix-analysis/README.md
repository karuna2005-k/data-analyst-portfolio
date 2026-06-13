# Netflix Content Growth Analysis

## Problem Statement
Netflix grew from a DVD rental service to the world's largest streaming platform. This analysis examines how the content library evolved between 2008–2021 — which countries contributed most, how genre mix shifted, and what the content strategy signals about future direction.

## Dataset
- **Source:** Netflix Movies and TV Shows dataset (Kaggle)
- **Size:** 8,807 titles
- **Domain:** Media & Entertainment / Streaming
- **Columns:** Title, type (Movie/TV Show), director, cast, country, date added, release year, rating, duration, genre

## Tools Used
- Python, Pandas, NumPy (data cleaning and analysis)
- Matplotlib, Seaborn (country-level and genre-level visualizations)

## What I Did
- **Cleaned data:** Parsed date columns, handled multi-value genre and country fields (split and exploded for accurate counting), handled ~10% missing director values
- **Analyzed:** Content volume growth by year, country contribution to library, genre distribution shifts over time, Movies vs. TV Shows ratio changes
- **Visualized:** Year-over-year content growth line chart, country contribution bar chart, genre heatmap by year, Movies vs. TV Shows trend

## Key Findings
1. **10x content volume growth between 2015 and 2019** — Netflix added more content in those 4 years than in the entire preceding decade, peaking at 1,500+ titles added in 2019 alone
2. **USA contributes 36% of all content** — the next largest contributors are India (8%), UK (6%), and Canada (4%). No other single country exceeds 5%.
3. **TV Show proportion has been rising since 2018** — Movies still dominate (69% of library) but TV Shows grew from 24% of additions in 2016 to 38% in 2020, signaling a strategy shift toward serialized content
4. **Dramas and International Movies are the two largest genre categories**, while Stand-Up Comedy has grown 4x since 2016

## Business Recommendations
1. **Content partners in India and UK should be prioritized for expansion deals** — these markets are already the #2 and #3 contributors and have audiences with strong global demand on the platform
2. **Invest further in TV Show originals** — the rising TV Show proportion reflects viewer retention strategy (binge-watching keeps subscribers longer). The data supports accelerating this shift.
3. **International content outside USA/India/UK is underrepresented relative to global subscriber base** — Korean, Spanish-language, and Nigerian content are breakout categories that still have small library shares despite high viewer engagement (based on the rating distributions in this dataset)

## Files in This Project
- `netflix_analysis.ipynb` — full analysis: data cleaning, multi-value field parsing, year-over-year growth, country contribution, genre evolution, Movies vs. TV Shows trend