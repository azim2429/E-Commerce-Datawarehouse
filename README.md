# E-Commerce-Datawarehouse Using Databricks 🛒
The "E-Commerce Data Warehouse Using Databricks" project involves the design and implementation of a robust data warehouse solution tailored for e-commerce data. Utilizing Databricks, the project focuses on ingesting and organizing data into a series of medallion tables, which are structured to enhance data quality and facilitate efficient analytics. The medallion architecture consists of bronze, silver, and gold layers, progressively refining raw data into curated, high-value insights. This structured approach supports scalable data processing and analytics, enabling in-depth business intelligence and reporting for e-commerce operations.

## Architecrure Diagrma

<p><img src="Resource/Architecture diagram.png" width="60%"></p>

## Tech Stack
The "E-Commerce Data Warehouse Using Databricks" project leverages a suite of Azure services to build a comprehensive data solution. Key components include:

- **Databricks**: Serves as the primary platform for building, managing, and optimizing the data warehouse, integrating seamlessly with Spark for advanced analytics and data engineering.
- **Data Factory**: Orchestrates and automates data ingestion, movement, and transformation workflows, ensuring a smooth pipeline from source systems to the medallion tables.
- **Azure Key Vault**: Ensures secure management of secrets, keys, and certificates used throughout the data processing pipeline.
- **Azure Data Lake Storage**: Provides scalable and secure storage for large volumes of raw e-commerce data, forming the foundation for the medallion table architecture.

## Dataset
The "E-Commerce Data Warehouse Using Databricks" project utilized the dataset from [this source](https://data.world/jfreex/e-commerce-users-of-a-french-c2c-fashion-store), which provides detailed records of users from a French C2C (consumer-to-consumer) fashion store. This dataset includes various attributes related to user interactions, transactions, and behavior on the platform. By ingesting and processing this dataset within the data warehouse, the project aims to create a comprehensive view of e-commerce activities, enabling advanced analytics and insights for business intelligence.

