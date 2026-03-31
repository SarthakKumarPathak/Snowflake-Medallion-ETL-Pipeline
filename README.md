# Snowflake-Medallion-ETL-Pipeline
This project demonstrates an end-to-end data engineering pipeline in Snowflake using a Medallion Architecture (Bronze, Silver, Gold). It ingests, cleans, and transforms hotel booking data through SQL-based ETL, including MERGE operations for incremental processing, and delivers insights via a Snowsight dashboard.
Key Features:-
Native Ingestion: Uses Snowflake stages and file formats to efficiently load raw CSV data.
SQL-based ETL: Performs data cleaning, type casting, validation, and handles missing values, date standardization, and incremental processing using MERGE.
Medallion Architecture:
-Bronze: Raw data layer
-Silver: Cleaned and standardized data
-Gold: Aggregated, business-ready data
Business Analytics: Generates insights such as monthly revenue trends and top-performing cities.
Integrated Visualization: Builds interactive dashboards in Snowsight to display KPIs like total bookings, guest count, and average booking value.
