# Azure End-to-End Data Engineering Project
This repository showcases a complete end-to-end data engineering project leveraging Azure services, including data ingestion, transformation, storage, analytics, and visualization. The project demonstrates real-world use cases and best practices for modern data engineering workflows.

---

## **Architecture Diagram**
![image](https://github.com/user-attachments/assets/d3cb6d8f-506b-4d94-8511-ed3db9334018)



## **Project Overview**
### **Objective**  
The goal of this project is to build a scalable, secure, and efficient data pipeline to process, analyze, and visualize data.

### **Key Features**
- Automated data ingestion using **Azure Data Factory**.
- Secure access management with **Azure Key Vault**.
- Data transformation and processing with **Azure Databricks** using PySpark.
- Data storage and management in **Azure Data Lake Storage** and **Azure Synapse Analytics**.
- Business intelligence and visualization with **Power BI**.

---

## **Technologies Used**
- **Azure Data Factory**: For data ingestion and pipeline orchestration.
- **Azure Key Vault**: To securely store secrets and credentials.
- **Azure Data Lake Storage**: To store raw and processed data.
- **Azure Databricks**: For scalable data transformations using PySpark.
- **Azure Synapse Analytics**: For data warehousing and analytics.
- **Power BI**: To create interactive dashboards.
- **Azure Monitor**: For monitoring pipeline execution and system performance.

---

## **Data Flow**
1. **Data Ingestion**: Azure Data Factory ingests data from multiple source systems (databases, APIs, and cloud storage) into Azure Data Lake Storage (Raw Layer).
2. **Data Transformation**: Azure Databricks processes raw data, performing cleaning and transformation, and writes the transformed data back to Azure Data Lake Storage (Processed Layer).
3. **Data Warehousing**: Processed data is loaded into Azure Synapse Analytics for analytics and reporting.
4. **Data Visualization**: Power BI connects to Synapse Analytics to create dashboards for business insights.

---

## **Project Workflow**
### **Step 1: Data Ingestion**
- Configured pipelines in Azure Data Factory to extract data from source systems.
- Stored data in the **Raw Layer** of Azure Data Lake Storage.

### **Step 2: Data Transformation**
- Built notebooks in Azure Databricks to process raw data using **PySpark**.
- Transformed and enriched data is written to the **Processed Layer** of Azure Data Lake Storage.

### **Step 3: Data Warehousing**
- Synapse Pipelines loaded processed data from Azure Data Lake Storage into Azure Synapse Analytics.
- Implemented SQL scripts for aggregations and analytics.

### **Step 4: Data Visualization**
- Designed interactive Power BI dashboards connected to Azure Synapse Analytics for real-time reporting.

## **Screenshots**
### 1. Azure Data Factory Pipeline
![image](https://github.com/user-attachments/assets/2c6ac973-865d-4df3-973d-2d6e532845fb)


### 2. Databricks Notebook
![image](https://github.com/user-attachments/assets/dbd9cb4f-8773-4385-a59f-b473d87060df)


### 3. Azure Synapse Analytics 
![image](https://github.com/user-attachments/assets/aa0a15df-6943-4f03-bb4c-4aec4e77c6a9)


### 4. Power BI Dashboard
![image](https://github.com/user-attachments/assets/e2c82b29-473c-4d83-a13c-158bfb7b3541)



## **How to Run This Project**
### **Prerequisites**
- Azure subscription
- Access to Azure services: Data Factory, Databricks, Data Lake Storage, Synapse Analytics, and Power BI
- Basic knowledge of PySpark, SQL, and ETL processes

---

## **Reference**
Luke J Byrne video on End to End Azure Data Engineering Project[https://www.youtube.com/watch?v=ygJ11fzq_ik] 
