# On-Premises SQL Server to Azure Data Engineering Project

## Overview

This project is a comprehensive guide to building a real-time data engineering pipeline using Microsoft Azure. It covers the entire data engineering lifecycle, from data ingestion to transformation, storage, and analysis, providing practical, hands-on experience with Azure services.

## Project Architecture

![Arc](https://github.com/user-attachments/assets/5394aeff-2920-40dd-88b6-0c33d67e10b1)

## Project Steps

1. **Setting Up the Azure Environment**
   The project began with setting up the necessary Azure resources and services, including Azure Data Factory for orchestration, Azure Databricks for data transformation, and Azure key vault, ADLS. Ensuring these services were properly connected and configured was critical for the project's success.
   
   ![rg](https://github.com/user-attachments/assets/38c70311-66b5-4f4c-b99b-615f4a81e612)



2. **Data Ingestion**
   Azure Data Factory was used to ingest data from SQL server. By setting up linked services and pipelines, the data ingestion process was automated, making it seamless and efficient.
   
   <img width="830" alt="Pipeline" src="https://github.com/user-attachments/assets/6610bd50-bbd3-402b-8b91-a605938560c9">



3. **Data Transformation with Azure Databricks**
   Data transformation tasks were performed using Azure Databricks. Creating and managing Databricks notebooks facilitated the Extract, Transform, Load (ETL) processes, essential for cleaning, transforming, and aggregating data before storage in Azure Data Lake Storage.
   
   ![image](https://github.com/user-attachments/assets/7ac68899-28fa-4464-a4b1-78207f77458f)



4. **Data Storage in Azure Data Lake Storage**
   Best practices were implemented for storing both raw and processed data in Azure Data Lake Storage. This involved partitioning data to optimize performance and choosing the right file formats to balance between storage cost and query efficiency.
   
   ![image](https://github.com/user-attachments/assets/bee5e647-00aa-408b-be51-5c2a4d21f25b)



5. **Data Analysis with Azure Synapse Analytics**
   For advanced data analytics, transformed data from Azure Data Lake Storage was integrated into Azure Synapse Analytics. This enabled running complex queries and performing in-depth analysis, leveraging Synapse's powerful analytics capabilities.


   Loading Data in Synapse with the help of synapse pipeline with the store proceger
   
   <img width="956" alt="Load" src="https://github.com/user-attachments/assets/9478ec84-6670-4759-adfe-8d5ebcc173ae">
   
   <img width="952" alt="Load-data" src="https://github.com/user-attachments/assets/f176e83f-2422-438a-adbf-a1a9d6ee75eb">
   

   Store Proceger
   
   <img width="957" alt="StoreProceger" src="https://github.com/user-attachments/assets/6e69bb23-99fa-41f6-aa0e-64c1cac0ceab">


7. **Orchestrating Workflows with Azure Data Factory**
   Data pipelines were built and managed in Azure Data Factory to orchestrate the entire data workflow. This included scheduling pipelines to ensure timely data processing and monitoring them to maintain data flow continuity.

8. **Monitoring and Logging**
   Monitoring and logging strategies were implemented to track the performance of data pipelines. Azure Monitor and Log Analytics were used to gain insights and troubleshoot issues, ensuring the pipelines ran smoothly and efficiently.

9. **Real-Time Data Processing**
   To incorporate real-time data processing capabilities, Azure Stream Analytics was set up. This allowed handling streaming data pipelines, processing data in real time and enabling immediate insights and actions based on the incoming data.

10. **Deploying and Managing Solutions**
   Best practices were followed for deploying the data engineering solutions in a production environment. This included managing and scaling Azure resources to maintain efficient performance, ensuring the solution could handle increasing data volumes and complexity.

## Conclusion

This project provided a solid understanding of building robust and scalable data engineering solutions on Azure. The experience has equipped me with the skills needed to handle real-world data engineering challenges using Azure’s powerful tools and services.
