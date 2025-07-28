# Retail Sales ETL Pipeline in Databricks

This project demonstrates a complete ELT pipeline using Databricks and Delta Lake, designed to process and analyze retail sales data.

## 💡 Features

- Medallion Architecture (Bronze → Silver → Gold)
- Data cleaning and validation in PySpark
- Aggregated sales KPIs (revenue, quantity sold per product/store)
- Delta Lake storage with history tracking
- Interactive Databricks SQL dashboard

## 📁 Project Structure

- `notebooks/`: Contains PySpark ETL logic
- `data/`: Sample raw sales data (CSV)
- `screenshots/`: Visual of dashboard for business insights

## 🔧 Tech Stack

- Databricks
- PySpark
- Delta Lake
- SQL Dashboards
- GitHub

## 🚀 How to Run

1. Upload CSV to Databricks FileStore
2. Run `Retail_etl_project` notebook
3. Explore Bronze, Silver, Gold tables
4. View SQL Dashboard

## 📌 Sample KPIs Tracked

- Total revenue per store
- Top-selling products
- Quantity sold by product category

