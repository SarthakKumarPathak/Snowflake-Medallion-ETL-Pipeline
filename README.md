# Snowflake Medallion ETL Pipeline

This project demonstrates an end-to-end data engineering pipeline in Snowflake using the **Medallion Architecture (Bronze, Silver, Gold)**. It ingests, cleans, and transforms hotel booking data using SQL-based ETL (including MERGE for incremental processing) and delivers insights through a Snowsight dashboard.

---

## Key Features

### Native Ingestion
- Uses Snowflake stages and file formats  
- Efficiently loads raw CSV data  

### SQL-based ETL
- Data cleaning and validation  
- Type casting and schema standardization  
- Handles missing values and date formatting  
- Incremental processing using `MERGE`  

### Medallion Architecture
- **Bronze:** Raw data layer  
- **Silver:** Cleaned and standardized data  
- **Gold:** Aggregated, business-ready data  

### Business Analytics
- Monthly revenue trends  
- Top-performing cities  
- Key business insights  

### Integrated Visualization
- Interactive dashboards using Snowsight  
- KPIs include:
  - Total bookings  
  - Guest count  
  - Average booking value  

---

## Project Workflow

1. Data Ingestion (Bronze Layer)  
2. Data Transformation (Silver Layer)  
3. Data Aggregation (Gold Layer)  
4. Visualization using Snowsight  

---

## Getting Started

### Prerequisites
- Snowflake account (Free Trial recommended)

### Setup
- Run SQL scripts to create:
  - Database and schemas  
  - File formats  
  - Stages  

### Execution
- Execute ETL pipeline from **Bronze → Silver → Gold**

### Visualization
- Connect Gold tables to Snowsight dashboards  
