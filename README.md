# 📱 PhonePe Transaction Insights

> End-to-end analytics pipeline on PhonePe's public transaction dataset — uncovering payment trends, user engagement patterns, and regional performance across India.

## 📌 Business Problem

With the rapid growth of digital payments in India, understanding transaction dynamics, user engagement, and regional adoption is critical for improving services and targeting users effectively. This project analyzes aggregated PhonePe transaction data to surface insights at state, district, and pin-code levels.

## 🎯 Objectives

- Analyze payment category volumes and trends over time
- Map transaction values at state and district levels
- Identify top-performing states, districts, and pin codes
- Provide insights on user engagement and insurance product adoption

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python (pandas, SQLAlchemy, mysql-connector) | JSON ingestion and pipeline automation |
| SQL (MySQL) | Data transformation, Window Functions, CTEs |
| Streamlit | Interactive web dashboard |
| Power BI | Business intelligence reporting |
| Google Colab | Exploratory analysis |
| Git & GitHub | Version control |

## 🔍 Approach

1. **Data Ingestion** — Extracted nested JSON data into MySQL using Python (`mysql.connector`, `SQLAlchemy`)
2. **Data Preprocessing** — Checked for nulls, validated data types, profiled distributions
3. **SQL Analysis** — Applied Window Functions and CTEs for regional ranking, trend analysis, and performance segmentation
4. **Visualization** — Built interactive Streamlit dashboard and Power BI reports for geographic and category-level insights

## 📊 Key Insights

- Regional transaction leaders by volume and value identified at state and district level
- Payment category breakdown revealing dominant transaction types
- Growth trends mapped across quarters for top-performing geographies
