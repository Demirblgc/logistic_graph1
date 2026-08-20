# 🚚 Trade, Logistics & Transport CO2 Emissions Analysis

This repository contains a comprehensive exploratory data analysis (EDA) and automated data preprocessing pipeline investigating the interplay between international trade openness, logistics infrastructure, high-technology exports, and transport-related CO2 emissions across selected economies (e.g., China, Turkey, Poland, Switzerland).

---

## 📌 Project Overview
The main objective of this study is to clean, transform, and analyze multi-country panel data to uncover relationships between commercial logistics indicators and environmental output. 

The project focuses on building an end-to-end Python workflow for:
* Data aggregation, cleaning, and structure validation.
* Exploratory analysis across country-level panel metrics.
* Interactive and static visualizations for trend and correlation diagnostics.
* Exporting formatted datasets ready for downstream econometric modeling.

---

## 📊 Key Variables
* `co2_transport`: CO2 emissions from transport sector
* `trade_pct_gdp`: Trade openness (% of GDP)
* `port_traffic_teu`: Container port traffic (TEU)
* `high_tech_exports_usd`: High-technology exports (current US$)
* `gdp_per_capita`: GDP per capita (current US$)
* `lpi_infrastructure` / `lpi_overall`: Logistics Performance Index scores

---

## 🛠️ Tech Stack & Methodology

### 🐍 Python (Data Pipeline & Visualization)
* **Data Manipulation**: `pandas`, `numpy` for data structure alignment, missing value management, and variable transformations.
* ** In this project the missingno library has been used to fix systematical missing values.
* **Exploratory Data Analysis (EDA)**: Correlation matrices, summary statistics, and multi-variable relationship inspection.
* **Data Visualization**: 
  * `plotly.express` / `plotly.graph_objects` for interactive web-ready figures.
  * `seaborn` & `matplotlib` for static diagnostic plots and heatmaps.
