# 📊 Blinkit Last-Minute App: Sales Performance Dashboard

An end-to-end data analytics project using **Microsoft Excel** and **Power Query** to clean, analyze, and visualize $1.20M in grocery retail sales data.

## 📌 Project Overview
This project contains a comprehensive, unified Excel workbook containing both the structured source data and an interactive multi-metric sales dashboard. The system evaluates Blinkit's operational retail performance across diverse outlet categories, regional location tiers, and product item types.

## ⚙️ Data Pipeline Automation (The Power Query Fix)
During development, a routine data refresh completely overwrote hours of manual grid-level adjustments, reverting the source back to its raw, messy state. 

To resolve this permanently and build a production-grade data solution:
1. I established a dynamic ingestion architecture inside **Power Query**.
2. Hardcoded the ETL cleaning parameters (text replacements, empty row filtering, data-type casting) directly into the query steps.
3. Connected the automated clean output back into the dashboard's Pivot Tables.
Now, the data pipeline is 100% resilient and refreshes seamlessly in a single click.

## 🛠️ Technical Skills Demonstrated
* **Data Engineering (ETL):** Power Query (Inconsistent string resolution, handling null values, numeric formatting).
* **Data Modeling:** Pivot Tables, custom chronological sorting, and relational grouping.
* **UI/UX & Visualization:** Integrated corporate branding (Blinkit Yellow palette), dynamic KPIs, and cross-filtering interactive slicers.

## 💡 Key Business Insights Discovered
* **Revenue Drivers:** *Fruits & Vegetables* and *Snack Foods* represent the highest consumer demand, bringing in over $170K+ each.
* **Geographical Trends:** Tier 3 regional outlets heavily outperform Tier 1 and Tier 2 cities in overall revenue volume, showing incredible product-market fit in suburban clusters.
* **Structural Strategy:** *Supermarket Type 1* configurations account for the lion's share of revenue ($707.5K), making it the most viable commercial template for future expansions.
