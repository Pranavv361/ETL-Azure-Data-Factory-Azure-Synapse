# End to End Azure Data Engineering Project

## Overview

This project is a complete end-to-end Azure Data Engineering solution. It has all aspects of data engineering, including Data Ingestion, Data Transformation, Data Loading, and Reporting, using various Azure tools and services.

## Tools and Services

Following Azure tools and services are used:

1. **Azure Data Factory**: For orchestrating data movement and transformation.
2. **Azure Data Lake Storage Gen2**: For scalable and secure data storage.
3. **Azure Databricks**: For data processing and transformation.
4. **Azure Synapse Analytics**: For data integration, big data, and data warehousing.
5. **Azure Key Vault**: For managing secrets and sensitive information.
6. **Azure Active Directory (AAD)**: For identity and access management.
7. **Microsoft Power BI**: For data visualization and reporting.

## Use Case

The use case for this project involves building an end-to-end data solution by following these steps:

1. **Data Ingestion**:
    - Ingest tables from an on-premises SQL Server database using Azure Data Factory.
    
2. **Data Storage**:
    - Store the ingested data in Azure Data Lake Storage Gen2.
    
3. **Data Transformation**:
    - Use Azure Databricks to transform the raw data into a clean and structured format.
    
4. **Data Loading**:
    - Load the transformed data into Azure Synapse Analytics for further analysis.
    
5. **Reporting**:
    - Integrate Microsoft Power BI with Azure Synapse Analytics to build interactive and insightful dashboards.
    
6. **Monitoring and Governance**:
    - Implement monitoring and governance using Azure Active Directory (AAD) and Azure Key Vault.

## Project Flow

1. **Ingestion**: 
    - Use Azure Data Factory to connect to the on-premises SQL Server database and ingest data into Azure Data Lake Storage Gen2.
    
2. **Transformation**:
    - Utilize Azure Databricks to process and transform the raw data into a clean and usable format.
    
3. **Loading**:
    - Load the clean data into Azure Synapse Analytics using data pipelines.
    
4. **Reporting**:
    - Create interactive dashboards and reports in Microsoft Power BI by connecting to Azure Synapse Analytics.
    
5. **Monitoring and Governance**:
    - Implement monitoring and access control mechanisms using Azure Active Directory and manage secrets with Azure Key Vault.


To follow along with this project, you will need:

- An Azure account with the necessary permissions to create and manage resources.
- Access to an on-premises SQL Server database.
- Basic knowledge of Azure services mentioned above.

