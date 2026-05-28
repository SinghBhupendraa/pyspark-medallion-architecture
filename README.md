# PySpark Medallion Architecture

## Project Objective
Build an end-to-end data engineering pipeline using PySpark and Databricks following Medallion Architecture principles.

## Architecture
- Bronze Layer → Raw data ingestion
- Silver Layer → Cleaned and transformed data
- Gold Layer → Business-ready analytics tables

## Dataset
Brazilian Ecommerce Public Dataset by Olist

## Tools Used
- PySpark
- Databricks
- Delta Lake
- SQL
- GitHub

## Topics Covered
- Data Ingestion
- Schema Validation
- Data Cleaning
- ETL Pipelines
- Transformations
- Delta Tables
- Spark SQL
- Data Quality Checks

## Project Workflow
1. Ingest raw CSV files into bronze layer
2. Clean and standardize data in silver layer
3. Create analytical gold tables
4. Validate transformed outputs
5. Prepare data for analytics consumption

## Repository Structure
```plaintext
bronze/
silver/
gold/
notebooks/
transformations/
validation/
configs/
```

## Future Enhancements
- Incremental data loading
- Partitioning strategies
- API ingestion
- Workflow orchestration
- Azure Data Factory integration
