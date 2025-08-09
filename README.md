# Azure Data Factory - COVID-19 Reporting and Analytics Pipeline

This project demonstrates a real-world data engineering solution using **Azure Data Factory (ADF)** for reporting COVID-19 trends and building an analytics-ready data pipeline in the cloud. The goal of this project is to ingest, process, and transform COVID-19 datasets using ADF and other Azure services

## Technologies Used

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Azure Blob Storage
- Azure Databricks
  
## Key Features

### Data Ingestion
- Ingest data from:
  - HTTP endpoints
  - Azure Blob Storage
  - Azure Data Lake Gen2

### Data Transformation
- Mapping Data Flows: join, filter, aggregate, pivot, and conditional split
- Parameterized pipelines and datasets
- Use of **Databricks notebooks** for transformations

### Scheduling & Orchestration
- Event Trigger, Schedule Trigger, Tumbling Window Trigger
- Control flow activities: If Condition, ForEach, Wait, Validation
- Pipeline chaining and dependencies

