## Databricks Data Lakehouse Project

This project demonstrates the implementation of a modern Data Lakehouse solution on Databricks using the Medallion Architecture pattern. The pipeline ingests raw data, transforms and validates it through multiple processing stages, and delivers analytics-ready datasets optimized for business intelligence and reporting. The solution leverages Delta Lake for reliable data storage, Apache Spark for scalable data processing, and Unity Catalog for centralized governance and data management.

---

## Architecture

This project is built using the **Medallion Architecture** pattern, consisting of three processing layers:

### 🥉 Bronze Layer
- Ingests raw source data
- Performs schema discovery and stores data in Delta tables  

### 🥈 Silver Layer
- Cleanses and standardizes data
- Applies type conversions and data quality validations  

### 🥇 Gold Layer
- Dimensional Data Model (Business Transformation)
- Provides curated datasets optimized for reporting, analytics, and BI

---

## Technologies Used

- Databricks  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Unity Catalog  
