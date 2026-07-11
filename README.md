# Bahadır Köksal - Behavioural & Data Research Portfolio

## About

Hi, I'm Bahadır. This is where I share personal research and analytical projects exploring human behaviour, markets, and organisations through data.

Behavioural Insights · Consumer Research · Data Analytics · Business Intelligence · Mixed Methods Research · Data Visualisation

## Tools & Technologies

| Category | Tools |
|---|---|
| **Query & Transformation** | SQL, BigQuery, DBT |
| **Programming** | Python |
| **Statistical Analysis** | A/B Testing, Hypothesis Testing, Correlation Analysis |
| **Machine Learning** | Scikit-learn, Supervised & Unsupervised Learning |
| **Spreadsheets** | Excel, Google Sheets |
| **BI & Visualisation** | Power BI, Looker Studio |
| **Data Integration & Automation** | Fivetran, Zapier, Google Tag Manager |
| **APIs** | Borsa (financial data), NewsAPI, Mapbox |

---

## Table of Contents

- [About](#about)
- [Tools & Technologies](#tools--technologies)
- [Portfolio Projects](#portfolio-projects)
  - [SQL / BigQuery](#sql--bigquery)
    - [Greenweez E-Commerce Suite](#greenweez-e-commerce-suite)
    - [Circle Sportswear Analysis](#circle-sportswear-analysis)
    - [Olist E-Commerce Analysis](#olist-e-commerce-analysis)
    - [Olist E-Commerce Data Analysis & Business Insights](#olist-e-commerce-data-analysis--business-insights)
    - [Other SQL Projects](#other-sql-projects)
  - [Power BI](#power-bi)
    - [TheLook E-Commerce Power BI Dashboard](#thelook-e-commerce-power-bi-dashboard)
    - [DAX Film Analysis](#dax-film-analysis)
    - [Billionaire Sector Analysis](#billionaire-sector-analysis)
    - [Top Websites Visualization](#top-websites-visualization)
    - [Tallest Buildings Visualization](#tallest-buildings-visualization)
    - [Regional Population Analysis](#regional-population-analysis)
  - [Looker Studio](#looker-studio)
    - [TechShop BI Dashboard](#techshop-bi-dashboard)
  - [Google Sheets](#google-sheets)
    - [Greenweez Google Sheets Suite](#greenweez-google-sheets-suite)
    - [Digital Ads Performance](#digital-ads-performance)
    - [B2B Sales Funnel Visualization](#b2b-sales-funnel-visualization)
  - [Instacart Behavioral Analysis (SQL)](#instacart-behavioral-analysis)
  - [Python](#python)
    - [Travel Agency Database Challenge](#travel-agency-database-challenge)
    - [Sumup Orders Analysis](#sumup-orders-analysis)
- [Certificates](#certificates)
- [Contact](#contact)

---

## Portfolio Projects

In this section I list data analytics projects briefly describing the technology stack and business problem solved.

---

### SQL / BigQuery

#### Greenweez E-Commerce Suite

A multi-project deep dive into Greenweez, a French organic e-commerce platform. Each repo covers a different business domain:

| Project | Description | Tools |
|---|---|---|
| [greenweez-sales-analysis](https://github.com/BahadirKoksal/greenweez-sales-analysis) | Category performance, repeat purchase rates, and subcategory deep-dive into top revenue category | BigQuery SQL |
| [greenweez-sales-operations](https://github.com/BahadirKoksal/greenweez-sales-operations) | Sales, margin, and operational performance | BigQuery SQL |
| [greenweez-sales-operations-analysis](https://github.com/BahadirKoksal/greenweez-sales-operations-analysis) | Operational profitability — revenue, margin, shipping costs, ad spend, and promotion breakdown | BigQuery SQL |
| [greenweez-finance-join-analysis](https://github.com/BahadirKoksal/greenweez-finance-join-analysis) | Joining sales, product, and shipping tables to calculate operational margin per order | BigQuery SQL |
| [greenweez-nps-analysis](https://github.com/BahadirKoksal/-greenweez-nps-analysis) | NPS data cleaning, deduplication, and transporter performance breakdown | BigQuery SQL |
| [greenweez-crm-mail-analysis](https://github.com/BahadirKoksal/greenweez-crm-mail-analysis) | Email marketing campaign KPIs — opening rate, CTR, turnover per mille | BigQuery SQL |
| [greenweez-sql-functions](https://github.com/BahadirKoksal/greenweez-sql-functions) | BigQuery UDF practice — reusable SQL functions for mail segmentation, NPS scoring, and transporter classification | BigQuery SQL |

#### Circle Sportswear Analysis

Two-part analysis of Circle, a sportswear brand:

| Project | Description | Tools |
|---|---|---|
| [circle-b2b-sales-analysis](https://github.com/BahadirKoksal/circle-b2b-sales-analysis) | B2B sales funnel conversion rates and KPI calculation | SQL, BigQuery |
| [circle-stock-analysis](https://github.com/BahadirKoksal/circle-stock-analysis) | Inventory health — stock KPIs, category shortage rates, and critical restock alerts | BigQuery SQL |
| [circle-delivery-analysis](https://github.com/BahadirKoksal/circle-delivery-analysis) | Parcel delivery performance — data quality checks, KPI calculations, delivery time by transporter, priority, and month | BigQuery SQL |

#### Olist E-Commerce Analysis

**Repo:** [olist-ecommerce-analysis](https://github.com/BahadirKoksal/olist-ecommerce-analysis)

**Goal:** Analyze customer behavior, product performance, and revenue trends for Olist, Brazil's largest e-commerce marketplace.

**Tools:** BigQuery SQL

#### Olist E-Commerce Data Analysis & Business Insights

**Repo:** [olist-ecommerce-analysis2](https://github.com/BahadirKoksal/olist-ecommerce-analysis2)

**Goal:** Comprehensive business analysis of the Olist Brazilian E-Commerce Dataset — covering regional performance, financial KPIs, customer retention, payment behavior, and seller insights across 27 states (2016–2018).

**Skills:** Data cleaning, multi-table joins, KPI calculation, geographic analysis, business recommendations

**Technology:** BigQuery SQL

**Results:** Identified SP dominates with 45% of all orders but low AOV; AL/MA have 20%+ late delivery rates correlated with lowest review scores; 97% of customers purchase only once — returning customers spend 2x more.

#### Other SQL Projects

| Project | Description | Tools |
|---|---|---|
| [bigquery-nps-analysis](https://github.com/BahadirKoksal/bigquery-nps-analysis) | Customer satisfaction scoring, segmentation, and transporter performance tracking | BigQuery SQL |
| [bigquery-window-functions](https://github.com/BahadirKoksal/bigquery-window-functions) | Exploring ROW_NUMBER, RANK, DENSE_RANK — includes a pipeline to identify first-ever customer purchases | BigQuery SQL |
| [bigquery-financial-analysis](https://github.com/BahadirKoksal/bigquery-financial-analysis) | Joining financial tables to track daily business profitability | BigQuery SQL |
| [carrefour-crm-email-analysis](https://github.com/BahadirKoksal/carrefour-crm-email-analysis) | CRM email campaign KPI tracking for Carrefour France newsletter segment | BigQuery SQL |

---

### Power BI

#### TheLook E-Commerce Power BI Dashboard

**Repo:** [thelook-ecommerce-powerbi](https://github.com/BahadirKoksal/thelook-ecommerce-powerbi)

**Goal:** Sales performance analysis of The Look e-commerce dataset.

**Tools:** Power BI, BigQuery

#### DAX Film Analysis

**Repo:** [power-bi-dax-film-analysis](https://github.com/BahadirKoksal/power-bi-dax-film-analysis)

**Goal:** Practice DAX measures and film data visualization.

**Tools:** Power BI, DAX

#### Billionaire Sector Analysis

**Repo:** [power-bi-billionaire-analysis](https://github.com/BahadirKoksal/power-bi-billionaire-analysis)

**Goal:** Data cleaning and sector-level analysis of global billionaires dataset.

**Tools:** Power BI

#### Top Websites Visualization

**Repo:** [power-bi-top-websites](https://github.com/BahadirKoksal/power-bi-top-websites)

**Goal:** Data cleaning and visualization of the world's most visited websites.

**Tools:** Power BI

#### Tallest Buildings Visualization

**Repo:** [powerbi-tallest-buildings](https://github.com/BahadirKoksal/powerbi-tallest-buildings)

**Goal:** Data cleaning and visualization of the world's tallest buildings.

**Tools:** Power BI

#### Regional Population Analysis

**Repo:** [Power-BI-Regional-Population-Analysis](https://github.com/BahadirKoksal/Power-BI-Regional-Population-Analysis)

**Goal:** Population distribution by world region using a Power BI donut chart.

**Tools:** Power BI

---

### Looker Studio

#### TechShop BI Dashboard

**Repo:** [techshop-bi-dashboard](https://github.com/BahadirKoksal/techshop-bi-dashboard)

**Goal:** Drill-down & breakdown analysis on TechShop e-commerce data.

**Tools:** Looker Studio

---

### Google Sheets

#### Greenweez Google Sheets Suite

| Project | Description | Tools |
|---|---|---|
| [greenweez-crm-email-analysis](https://github.com/BahadirKoksal/greenweez-crm-email-analysis) | Email campaign performance analysis for Greenweez CRM team | Google Sheets |
| [greenweez-quality-products-analysis](https://github.com/BahadirKoksal/greenweez-quality-products-analysis) | Refund analysis and product quality insights for Greenweez e-commerce | Google Sheets |
| [greenweez-finance-analysis](https://github.com/BahadirKoksal/greenweez-finance-analysis) | Financial health and profitability analysis dashboard | Google Sheets |

#### Digital Ads Performance

| Project | Description | Tools |
|---|---|---|
| [google-ads-performance-analysis](https://github.com/BahadirKoksal/google-ads-performance-analysis) | Annual Google Ads performance — daily metrics, monthly breakdown, pivot tables, and summary dashboard | Google Sheets |
| [facebook-ads-performance-analysis](https://github.com/BahadirKoksal/facebook-ads-performance-analysis) | Annual Facebook Ads performance with comparison to Google Ads | Google Sheets |
| [ads-performance-visualizations](https://github.com/BahadirKoksal/ads-performance-visualizations) | Google Ads & Facebook Ads performance visualizations — monthly spend, ROAS, clicks, impressions, and revenue charts | Google Sheets |

#### B2B Sales Funnel Visualization

**Repo:** [b2b-sales-funnel-visualization](https://github.com/BahadirKoksal/b2b-sales-funnel-visualization)

**Goal:** 2B sales funnel analysis and KPI visualization using XLOOKUP, pivot tables, and charts.

**Tools:** Google Sheets

---

### Instacart Behavioral Analysis

**Repo:** [instacart-behavioral-analysis](https://github.com/BahadirKoksal/instacart-behavioral-analysis)

**Goal:** Analyze food ordering behavior using the Instacart public dataset.

**Tools:** SQL

---

### Python

#### Travel Agency Database Challenge

**Repo:** [travel-agency-python-analysis](https://github.com/BahadirKoksal/travel-agency-python-analysis)

**Goal:** Build a functional city database and search engine for a travel agency using core Python data structures and functions.

**Description:** Working with a dataset of cities stored as Python dictionaries (name, population, continent, coordinates, area), the project involved building reusable functions to retrieve, update, and query city data — culminating in a geolocation-based search engine that returns nearby cities within a given radius.

**Skills:** Python functions, dictionaries, lists, loops, conditional logic, geospatial distance calculation

**Technology:** Python, Geopy

**Results:** Delivered a working `get_cities_nearby()` function that takes a customer's coordinates and a radius (km) and returns all cities within range — a practical tool for travel destination recommendation.

#### Sumup Orders Analysis

**Repo:** [sumup-orders-analysis](https://github.com/BahadirKoksal/sumup-orders-analysis)

**Goal:** Explore, clean, and derive business insights from real transactional order data collected across 10 restaurants using Sumup's POS system.

**Description:** Worked with 3 joined CSV datasets (orders, order lines, store metadata) to analyze revenue distribution, order volume, average spend, order duration, and product-level performance. Included data cleaning (division-by-zero, invalid transactions), feature engineering, and multi-table joins.

**Skills:** Data loading, cleaning, aggregation, feature engineering, joins, exploratory data analysis

**Technology:** Python, Pandas, Google Colab

**Results:** Restaurant 7965 generates ~€1.1M revenue with only ~9K orders (highest AOV at ~€125/order) vs. restaurant 1796 with ~27K orders at ~€11.7/order — revealing fundamentally different restaurant categories. Paris's 2nd arrondissement alone accounts for 59,381 orders.

---

## Certificates

- [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) — Google / Coursera (Oct 2025)
- Data Analytics & AI — Workintech (Jan 2026 – ongoing)
- Computational Social Science & Data Methods — Marmara University, supported by Boğaziçi University & METU (Sep 2025 – ongoing)

---

## Contact

- **LinkedIn:** [Bahadır Köksal](https://www.linkedin.com/in/bahad%C4%B1r-k%C3%B6ksal-m-a-5806642a9/)
- **Email:** koksalbahadirakif@gmail.com
