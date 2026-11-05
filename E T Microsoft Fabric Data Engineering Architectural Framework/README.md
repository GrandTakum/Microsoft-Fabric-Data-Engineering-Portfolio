## Architecture Documentation

The complete Microsoft Fabric Data Engineering
Architectural Framework is available below.

[View Microsoft Fabric Architecture PDF](./Microsoft-Fabric-Architecture.pdf)

Data Engineering architecture designed to support scalable,
secure and reliable enterprise analytics solutions.

The framework illustrates how Microsoft Fabric integrates
data ingestion, transformation, storage, modelling and
business intelligence into a unified analytics platform.

## Technologies Used

- Microsoft Fabric
- Fabric Data Pipelines
- Dataflows Gen2
- Microsoft OneLake
- Fabric Lakehouse
- Fabric Data Warehouse
- Delta Lake / Delta Tables
- Python and PySpark
- Spark SQL
- T-SQL
- Fabric Notebooks
- SQL Analytics Endpoint
- Power BI Semantic Models
- Power BI Dashboards
- CI/CD and Deployment Pipelines

## Architecture Components

### 1. Data Ingestion

Data is ingested from multiple enterprise systems using:

- Fabric Data Pipelines
- Dataflows Gen2
- Copy Jobs
- SQL Server connections
- APIs and external data sources

### 2. Data Engineering

Data transformation and processing are performed using:

- PySpark
- Spark SQL
- Fabric Notebooks
- T-SQL

### 3. Medallion Architecture

The solution follows a Bronze, Silver and Gold
Medallion Architecture.

**Bronze Layer**
- Raw source data ingestion
- Data preservation
- Initial storage in Lakehouse Delta tables

**Silver Layer**
- Data cleansing
- Deduplication
- Data validation
- Standardisation
- Business rule transformations

**Gold Layer**
- Curated business-ready datasets
- Fact and dimension tables
- Star-schema modelling
- Aggregated reporting tables
- Optimised analytical datasets

### 4. Data Storage

The architecture uses:

- Microsoft OneLake
- Fabric Lakehouses
- Delta Tables
- Fabric Data Warehouse
- SQL Analytics Endpoints

### 5. Semantic Modelling

Power BI semantic models provide:

- Relationships between fact and dimension tables
- DAX calculations and KPIs
- Row-Level Security
- Standardised business definitions
- Reusable analytical measures

### 6. Business Intelligence

The final analytical layer supports:

- Power BI dashboards
- Operational reporting
- Regulatory compliance reporting
- Self-service analytics
- Automated data refresh

## Data Quality and Governance

The framework incorporates:

- Data quality validation
- Source-to-target reconciliation
- Pipeline monitoring
- Error handling
- Role-based access controls
- Development, UAT and Production environments
- CI/CD and deployment processes

## Project Objective

To demonstrate how Microsoft Fabric can be used to
design and deliver a modern enterprise data platform,
from data ingestion and transformation to semantic
modelling and business intelligence.

## Author

GrandTakum

Microsoft Fabric Data Engineer / Developer
Senior Power BI and Analytics Consultant
