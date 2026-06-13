# Social Media Intelligence Dashboard

## Problem Statement
Brands running multi-platform social media campaigns need to know where their budget produces the most engagement. This dashboard analyzes performance across Instagram, Twitter, and Facebook to identify which platforms, regions, and content types generate the highest return on engagement.

## Dataset
- **Source:** Social Media Engagement Dataset (Kaggle)
- **Domain:** Digital Marketing / Social Media Analytics
- **Platforms covered:** Instagram, Twitter, Facebook
- **Columns:** Platform, country, post type, likes, shares, comments, reach, engagement rate

## Tools Used
- Power BI Desktop (dashboard design, DAX measures, cross-filtering slicers)
- DAX (calculated columns and measures for engagement rate, avg likes, platform benchmarks)

## What I Did
- **Loaded data:** Connected CSV to Power BI, defined data types and relationships
- **Built DAX measures:** Average likes per post, engagement rate (likes+comments+shares / reach), platform-level benchmarks, country-level aggregations
- **Designed dashboard:** Dark-themed interactive dashboard with 5 chart types — bar chart, donut chart, line chart, map visual, and KPI cards — with cross-filtering slicers for platform, country, and post type

## Key Findings
1. **USA generates 6,000+ average likes per post vs. a 2,000 global average** — a 3x engagement differential that clearly identifies the USA as the highest-value market for social content investment
2. **Instagram outperforms Twitter and Facebook in average engagement rate** across all regions — consistent across post types (image, video, carousel)
3. **Video content generates 2.4x higher engagement than static image posts** across all three platforms — the gap is widest on Instagram (3.1x) and smallest on Twitter (1.6x)

## Business Recommendations
1. **Reallocate social media budget toward USA-targeted content** — at 3x the global avg engagement, USA-focused campaigns produce measurably better ROI. Brands currently spreading budget equally across regions are leaving significant engagement on the table.
2. **Prioritize video content production, especially for Instagram** — the 3.1x video engagement premium on Instagram means that shifting even 30% of static image budget to short video would substantially increase overall campaign performance.
3. **Use platform-specific strategies, not one-size-fits-all** — this dashboard demonstrates that Twitter, Instagram, and Facebook respond differently to the same content. Brands should build platform-native content calendars rather than cross-posting identical material.

## Dashboard Preview
> Dark-themed Power BI dashboard with 5 interactive charts and cross-filtering slicers. See screenshots below.

![Dashboard Overview](dashboard-overview.png)
![Dashboard Filtered View](dashboard-filtered.png)

*(Add your screenshots to this folder and they will render here)*

## Files in This Project
- `social_media_dashboard.pbix` — Power BI dashboard file (open with Power BI Desktop)
- `dashboard-overview.png` — Full dashboard screenshot
- `dashboard-filtered.png` — Dashboard with filters applied