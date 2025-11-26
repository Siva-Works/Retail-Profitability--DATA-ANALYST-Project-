# Retail Business Performance & Profitability Analysis — Siva Sakthi R 

## Summary
Analyzed a public online retail transactions dataset to identify profit-draining categories, slow-moving SKUs, seasonality, and provide recommendations to improve profitability and inventory turnover.

## Tools
Google Sheets (cleaning), SQLite.com (SQL queries), Google Colab (analysis), Looker Studio (dashboard), GitHub (repo)

## Deliverables
- data/online_retail_cleaned.csv
- sql/*.sql (monthly_kpis.sql, category_performance.sql, slow_moving_skus.sql, ...)
- dashboards/ (Looker Studio share link in dashboards/README.txt)
- report/retail_analysis_report.pdf

## How to run (mobile)
1. Upload `online_retail_cleaned.csv` to SQLite.com as table `orders`.
2. Run SQL files in `/sql/` (open each .sql and paste into SQLite query editor).
3. Export result CSVs, upload to Google Sheets.
4. Connect Google Sheets to Looker Studio and build the visuals (or open provided report link).
