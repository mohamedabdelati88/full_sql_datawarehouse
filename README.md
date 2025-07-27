# full_sql_datawarehouse
Data Warehouse and Analytics Project – ERP &amp; CRM Integration

This project showcases a full-stack data engineering workflow: from ingesting raw business data to delivering clean, structured insights for analytics and reporting. Designed as a portfolio-level project, it follows modern best practices using the Medallion Architecture approach (Bronze, Silver, Gold).

🏗️ Data Architecture
The project uses a Medallion Architecture consisting of three layers:

Bronze Layer:
Raw ERP and CRM data is ingested from CSV files directly into a SQL Server database with minimal processing.

Silver Layer:
This layer handles data cleaning, deduplication, formatting (e.g. date/time, casing), and joining reference data (e.g. customer location, product category).

Gold Layer:
Final business-ready star schema including fact tables (e.g. sales) and dimension tables (e.g. customer, product, region) used for BI reporting and deep analytics.

📖 Project Overview
This project includes:

ETL Pipeline Development: Automated scripts using SQL to ingest, transform, and load ERP & CRM data.

Data Modeling: Star schema designed for business performance analysis.

Analytics Reporting: SQL queries and views provide actionable insights.

Data Documentation: Clear definitions for all entities, fields, and transformations.

🗃️ Source Data Overview
We work with 6 key tables from two systems:

📦 ERP System:
erp_sales_header: Sales transaction headers

erp_sales_details: Sales line items

erp_px_cat: Product and category data

erp_cust_az12: Customer master data

erp_loc: Customer region and location mapping

🧑 CRM System:
crm_cust_info: Customer activity and interaction data

🎯 Key Learning Areas
This project is ideal for learning or showcasing skills in:

SQL Development

Data Modeling & Star Schema Design

Data Warehousing Concepts

ETL Development (Bronze → Silver → Gold)

Analytics & BI Reporting

🧰 Tools & Technologies
SQL Server Express – Lightweight DB engine for local development

SSMS – SQL Server Management Studio for managing data pipelines

Draw.io – For architecture, data models, and flow diagrams

CSV Files – Used to simulate real-world ERP and CRM systems

GitHub – Version control and collaboration


🚀 Project Goals
Build a Modern Data Warehouse that integrates ERP and CRM data to enable analytics on:

Sales trends

Customer segmentation

Product performance

Regional analysis

All while following clean data engineering and architecture principles.
