# goodcabs-databricks-data-engineering
Project Overview

Designed and implemented an end-to-end cloud-based data engineering pipeline using Databricks, AWS S3, PySpark, and Lakeflow Declarative Pipelines. The project follows the Medallion Architecture (Bronze, Silver, Gold) to ingest raw transportation datasets, transform them into curated Delta tables, and prepare analytics-ready data for downstream reporting.

Problem Statement

GoodCabs, a ride-hailing company operating across Tier-2 cities in India, generates large volumes of trip and city data that must be processed efficiently for business analytics. The challenge is to build a scalable and reliable data pipeline capable of ingesting raw data from cloud storage, transforming it through multiple processing layers, and producing clean, analytics-ready datasets while maintaining data governance and quality.

Solution

This project implements a modern Lakehouse architecture using Databricks and AWS.

The pipeline:

Reads raw CSV files stored in Amazon S3
Loads raw datasets into the Bronze layer
Cleanses and transforms data in the Silver layer
Produces business-ready Gold tables
Stores processed data as Delta Tables
Uses Unity Catalog for centralized governance
Uses Lakeflow Declarative Pipelines for automated ETL

Tech Stack :
Databricks
AWS S3
PySpark
SQL
Delta Lake
Unity Catalog
Lakeflow Declarative Pipelines
Medallion Architecture
