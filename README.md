# End-to-End Azure Data Engineering Pipeline

## Project Overview
This project demonstrates an end-to-end data engineering pipeline using Microsoft Azure services. It covers data ingestion, transformation, processing, storage, and analytics using Azure Data Factory, Azure Data Lake Gen2, Azure Databricks, PySpark, and Azure Synapse Analytics.

## Architecture
The project follows the Medallion Architecture:

- **Bronze Layer:** Raw data ingestion into Azure Data Lake Gen2 using Azure Data Factory.
- **Silver Layer:** Data cleaning and transformation using Azure Databricks and PySpark.
- **Gold Layer:** Processed data prepared for analytics using Azure Synapse Analytics.
- **Visualization:** Power BI integration for reporting and data visualization.

## Technologies Used
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark
- PySpark
- Azure Synapse Analytics
- SQL
- Power BI

## Project Workflow
1. Extract data from the source API.
2. Ingest raw data into Azure Data Lake Gen2.
3. Create ETL pipelines using Azure Data Factory.
4. Transform and clean data using Databricks and PySpark.
5. Organize processed data using the Medallion Architecture.
6. Query data using Azure Synapse Analytics.
7. Integrate the data warehouse with Power BI.

## Key Learnings
- Building ETL pipelines using Azure Data Factory.
- Working with Azure cloud storage.
- Data transformation using PySpark.
- Understanding the Medallion Architecture.
- Querying data using Azure Synapse Analytics.
- Integrating data pipelines with analytics tools.

## Data Source & Acknowledgment
- The Adventure Works datasets used in this project are sourced from a publicly available GitHub repository.

- Dataset Source: https://github.com/anshlambaoldgit/Adventure-Works-Data-Engineering-Project/tree/main/Data
- The datasets were used for learning and implementing the Azure Data Engineering pipeline. The pipeline development, data processing,          transformation, and analytics workflow were implemented as part of this project.

## Project Structure

## Project Structure

```text
Azure_First_Project/
│
├── Azure Data Factory/
│   ├── Datasets/
│   │   ├── ds_git_dynamic.json
│   │   ├── ds_git_parameters.json
│   │   ├── ds_http.json
│   │   ├── ds_raw.json
│   │   └── ds_sink_dynamic.json
│   │
│   ├── DynamicGitToRaw.json
│   └── GitToRaw.json
│
├── DATA/
│   ├── AdventureWorks_Calendar.csv
│   ├── AdventureWorks_Customers.csv
│   ├── AdventureWorks_Product_Categories.csv
│   ├── AdventureWorks_Product_Subcategories.csv
│   ├── AdventureWorks_Products.csv
│   ├── AdventureWorks_Returns.csv
│   ├── AdventureWorks_Sales_2015.csv
│   ├── AdventureWorks_Sales_2016.csv
│   ├── AdventureWorks_Sales_2017.csv
│   └── AdventureWorks_Territories.csv
│
├── Databricks/
│   └── silver_layer.ipynb
│
├── PowerBi/
│   └── azurefirstpro.pbix
│
├── Synapse/
│   └── Create Views Gold.sql
│
├── git.json
└── README.md
```






=======
# azure-data-engineering-pipeline
End-to-end Azure data engineering pipeline using Azure Data Factory, Azure Data Lake, Databricks, PySpark and Synapse Analytics.
>>>>>>> f99af8ce6ca4886a07f3c9dc90395285f470003f
