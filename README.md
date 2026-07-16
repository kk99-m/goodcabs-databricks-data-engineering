# goodcabs-databricks-data-engineering
<h5>Project Overview</h5>

Designed and implemented an end-to-end cloud-based data engineering pipeline using Databricks, AWS S3, PySpark, and Lakeflow Declarative Pipelines. The project follows the Medallion Architecture (Bronze, Silver, Gold) to ingest raw transportation datasets, transform them into curated Delta tables, and prepare analytics-ready data for downstream reporting.

<h5>Problem Statement</h5>

GoodCabs, a ride-hailing company operating across Tier-2 cities in India, generates large volumes of trip and city data that must be processed efficiently for business analytics. The challenge is to build a scalable and reliable data pipeline capable of ingesting raw data from cloud storage, transforming it through multiple processing layers, and producing clean, analytics-ready datasets while maintaining data governance and quality.

<h5>Solution</h5>

This project implements a modern Lakehouse architecture using Databricks and AWS.

<h5>The pipeline:</h5>

<li>Reads raw CSV files stored in Amazon S3</li>
<li>Loads raw datasets into the Bronze layer</li>
<li>Cleanses and transforms data in the Silver layer</li>
<li>Produces business-ready Gold tables</li>
<li>Stores processed data as Delta Tables</li>
<li>Uses Unity Catalog for centralized governance</li>
<li>Uses Lakeflow Declarative Pipelines for automated ETL</li>

<h5>Tech Stack :</h5>
<li>Databricks</li>
<li>AWS S3</li>
<li>PySpark</li>
<li>SQL</li>
<li>Delta Lake</li>
<li>Unity Catalog</li>
<li>Lakeflow Declarative Pipelines</li>
<li>Medallion Architecture</li>
