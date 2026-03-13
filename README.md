**End-to-End Azure Data Pipeline using Medallion Architecture**

**Overview**
This project demonstrates an end-to-end modern data pipeline built on Microsoft Azure using Azure Data Factory, Azure SQL Database, Azure Data Lake Storage Gen2, and Databricks.
The pipeline is designed to support dynamic ingestion, incremental processing, and dimensional modeling using the Medallion Architecture (Bronze → Silver → Gold).

![Architecture Diagram](https://github.com/pkapoor1712/AZURE-DE-PROJECT/blob/main/pipeline_screenshot/project_architecture.png)

**Architecture**

The pipeline follows the Medallion Architecture pattern:
Bronze Layer → Raw Data
Silver Layer → Cleaned & Transformed Data
Gold Layer → Business-ready Fact & Dimension Tables

**Main Components Used:**

Azure Data Factory (ADF)
Azure SQL Database
Azure Data Lake Storage Gen2
Azure Databricks
Delta Lake
Unity Catalog
job & pipeline




