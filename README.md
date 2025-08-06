# Azure Data Factory - COVID-19 Reporting and Analytics Pipeline

This project demonstrates a real-world data engineering solution using **Azure Data Factory (ADF)** for reporting COVID-19 trends and building an analytics-ready data pipeline in the cloud. The goal of this project is to ingest, process, and transform COVID-19 datasets using ADF and other Azure services

## Technologies Used

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Azure Blob Storage
- Azure Databricks
- Azure DevOps (CI/CD)
- Azure Monitor & Log Analytics
- Power BI

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

### Monitoring
- Pipeline monitoring using Azure Data Factory Monitor
- Diagnostic logs forwarded to Log Analytics Workspace
- Custom dashboards and alerts via Azure Monitor

### CI/CD with Azure DevOps
- Source control using Azure DevOps Git Repos
- Build & release pipelines for deploying ADF artifacts
- Parameterized release to Test and Production environments

