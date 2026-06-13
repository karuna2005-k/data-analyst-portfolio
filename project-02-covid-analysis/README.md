# COVID-19 Global Impact Analysis

## Problem Statement
COVID-19 affected every country differently. This analysis investigates why case fatality rates vary so dramatically across nations — and whether healthcare infrastructure quality is the real underlying driver, not just case count.

## Dataset
- **Source:** Johns Hopkins COVID-19 dataset (publicly available via Kaggle)
- **Size:** Data across 180+ countries
- **Domain:** Healthcare / Global Public Health
- **Columns:** Confirmed cases, deaths, recoveries, country, date

## Tools Used
- Python, Pandas, NumPy (data cleaning and analysis)
- Matplotlib, Seaborn (visualizations including correlation heatmap)

## What I Did
- **Cleaned data:** Handled missing values for smaller nations, standardized country names, calculated derived metrics (case fatality rate, recovery rate per country)
- **Analyzed:** Case fatality rate (CFR) across all 180+ countries, correlation between confirmed cases, deaths, and recoveries; country-level comparisons
- **Visualized:** Seaborn correlation heatmap between confirmed cases, deaths, and recoveries; country-level CFR bar chart; time-series of case growth by region

## Key Findings
1. **Yemen's case fatality rate is 28%** — the highest globally — versus the USA's 1.7%, a 16x difference between two countries with vastly different healthcare capacities
2. **CFR is strongly predicted by healthcare infrastructure quality**, not by case volume — countries with weak health systems show 10–20x higher fatality rates than high-income countries with similar case counts
3. **Strong positive correlation between confirmed cases and deaths** (r > 0.9), but recovery rates diverge sharply by region — indicating that detection and treatment capacity, not just exposure, determines outcomes

## Business / Policy Recommendations
1. **International health aid should prioritize countries with high CFR, not high case count** — Yemen, Syria, and similar fragile states need critical care infrastructure investment, not just testing kits
2. **Early detection programs reduce CFR** — countries that expanded testing early (South Korea, Germany) show CFR under 2% regardless of case volume; late-detection countries show 8–20% CFR
3. **Recovery rate, not case count, should be the primary public health KPI** — a country with 10,000 cases and 95% recovery rate is managing better than one with 1,000 cases and 60% recovery rate

## Files in This Project
- `covid_analysis.ipynb` — full analysis: data cleaning, CFR calculation by country, correlation heatmap, country-level comparisons
