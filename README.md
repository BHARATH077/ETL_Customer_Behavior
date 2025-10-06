# ETL_Customer_Behavior

# ETL Pipeline for Customer Behavior Analytics

## 📌 Project Overview
This project simulates an **ETL (Extract, Transform, Load) pipeline** that processes **clickstream, transaction, and CRM data** to build a **Customer 360 view**.  
The pipeline demonstrates how businesses can centralize raw data, transform it for analytics, and create BI-ready datasets for dashboards and personalization.

Built entirely in **Python (on Google Colab)** so it can be reproduced **without paid tools** like Airflow or managed warehouses.

---

## ⚙️ Features
- **Data Ingestion**: Simulated data sources (CSV, API, and SQL-like databases using DuckDB).  
- **Transformation**: Cleaning, aggregation, and enrichment of customer data with `pandas` and `DuckDB`.  
- **Customer 360 Table**: Unified dataset combining transactions, CRM, and clickstream behavior.  
- **Monitoring & Logging**: Pipeline logging for each step, with daily simulation of runs.  
- **Visualization**: Customer trends and pipeline health reports using `matplotlib` and `seaborn`.  
- **Scalable Simulation**: Multiple days of pipeline runs with evolving data.

---


Looker: https://lookerstudio.google.com/reporting/cc5e34e3-60dd-423d-989d-13788a396ebd
