# Azure Sales Data Engineering Project
End-to-end Azure Data Engineering project using ADF, ADLS,Blob,MySql,Mongo DB Cosmos DB, and Azure SQL

## Project Objective
Built a centralized Azure Data Warehouse to integrate sales data from CSV, Excel,
MySQL, and Azure Cosmos DB for analytics and reporting.

## Architecture

- Azure Blob Storage & ADLS Gen2
- Azure Data Factory (Pipelines & Data Flows)
- Medallion Architecture (Raw → Bronze → Silver → Gold)
- Azure SQL Database (Star Schema)

## Data Model
Fact: SalesFact  
Dimensions: Product, Category, SubCategory, Geography, SalesRep

## Key Transformations
- Data cleansing & standardization
- Deduplication using aggregates
- Date format conversion
- Surrogate key generation
- Revenue & profit calculations

## Outcome
Delivered a scalable, automated Azure data pipeline ready for BI reporting.

## Author
Varun Yaddanapalli
