# NYC Airbnb Pricing and Reviews Analysis
## Project Overview
This project analyzes New York City Airbnb data to understand how pricing and reviews are shaped by host characteristics, property features, and booking policies. Using A/B testing and statistical methods on over 100,000 listings, the study examines two main areas:
- **Part I: Pricing Analysis** – Investigates whether location, room type, property age, and host attributes meaningfully influence rental rates/costs.
- **Part II: Reviews Analysis** – Explores how host portfolio size, property type, and booking policies affect both the volume and sentiment of guest reviews.

## Project Scope
- Statistical analysis with large-scale Airbnb listing data
- A/B testing for hypothesis-driven comparisons
- Examination of both economic (pricing) and guest engagement (reviews) outcomes
- Practical implications for Airbnb hosts and platform strategy

## Repo Contents
- NYC_airbnb_project_report.pdf – Full written project report summarizing methodology, findings, and implications; broken into 2 parts
- Dashboards
  - Pricing:
    - `airbnb_pricing_dashboard.pdf` – PDF export of Tableau pricing dashboard
    - `airbnb_pricing_dashboard_video.mov` – Walkthrough video of pricing dashboard
    - `airbnb_pricing_dashboards.twbx` – Tableau workbook for pricing dashboard
  - Reviews:
    - `airbnb_reviews_dashboard.pdf` – PDF export of Tableau reviews dashboard
    - `airbnb_reviews_dashboard_video.mov` – Walkthrough video of reviews dashboard
    - `airbnb_reviews_dashboards.twbx` – Tableau workbook for reviews dashboard
  - `airbnb_pricing_reviews_dashboards.twbx` – Combined Tableau workbook for both dashboards and all sheets
- Notebooks
  - `airbnb_sql_pricing_ab_testing.ipynb` – Jupyter notebook with SQL-based pricing A/B testing analysis
  - `airbnb_sql_reviews_analysis.ipynb` – Jupyter notebook with SQL-based reviews A/B testing analysis

## Limitations
- The analysis uses cross-sectional data representing a single snapshot in time. Thus, seasonal variations and longitudinal trends were not included.

## Data Source
This project uses the New York City Airbnb Data Cleaning dataset by Arian Azmoudeh, available on Kaggle:
https://www.kaggle.com/datasets/arianazmoudeh/new-york-city-airbnb-data-cleaning

The dataset is licensed under the Open Database License (ODbL v1.0). Original data was sourced from the Airbnb Inside project: http://insideairbnb.com/explore/
