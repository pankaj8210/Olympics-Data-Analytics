# Tokyo-Olympic-Data-Analysis
### Data Engineering Project
The Tokyo Olympic Data Analysis on Azure project is a comprehensive solution for analyzing and visualizing Olympic Games data using various Azure services. This project aims to showcase how to leverage the power of cloud computing and Azure's data services to gain insights from historical Olympic data. By combining Azure Databricks, Azure Data Factory, and other Azure resources, this project provides a scalable and efficient way to process, transform, and analyze large volumes of Olympic data.

# Table of Contents
- [Introduction](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#introduction)
- [Architecture](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#architecture)
- [Technologies Used](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#technologies-used)
- [Getting Started](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#getting-started)
  - [Prerequisites](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#prerequisites)
- [Data Ingestion](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#data-ingestion)
- [Data Processing](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#datafactory)
- [Conclusion](https://github.com/pankaj8210/Olympics-Data-Analytics/blob/main/README.md#conclusion)

# Introduction
The Olympic Data Analysis on Azure project demonstrates how to build an end-to-end data analysis pipeline on the Azure cloud platform. This involves ingesting raw Olympic data, transforming it into a suitable format, performing analysis, and creating insightful visualizations. The project provides an example of how to integrate and utilize Azure Databricks, Azure Data Factory, and other Azure services to achieve these goals.

# Architecture
![arch](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/332dd635-c741-417a-b2de-bc525649052e)

The architecture of the project consists of the following components:
* Azure Databricks: Used for data processing, transformation, and analysis. It provides a collaborative and interactive environment for running Spark-based jobs.

* Azure Data Factory: Manages and orchestrates the data workflow. It is responsible for data ingestion from various sources, data transformation, and scheduling of jobs.

* Azure Storage: Serves as the data lake for storing raw and processed data. It can also host intermediate results generated during the analysis.

* Azure SQL Database: Stores the cleaned and transformed data, making it accessible for visualization and reporting.

* Power BI: Connects to the Azure SQL Database to create interactive and visually appealing dashboards for data exploration.

# Technologies Used
* Azure Databricks
* Azure Data Factory
* Azure Storage
* Azure SQL Database
* Azure Synapse Analytics
### Resource Group
![rsG](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/2f481de3-b486-46e4-b38b-80b4410d6d01)
## Getting Started
### Prerequisites
* Azure subscription
* Azure Databricks workspace
* Azure Data Factory instance


### Data Ingestion
![dIngestion](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/180d3f6a-5599-4c90-bdfc-b43dc1eef818)
### Data Transformation using DataBricks
![dataTransform](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/63c7a5c8-dc21-46c8-b36d-6e965666ffdd)
The data processing stage involves cleaning and transforming raw Olympic data into a structured format suitable for analysis. This step takes advantage of Azure Databricks' distributed computing capabilities for efficient processing.

### Data Warehousing using Synapse Analytics
![Screenshot (20)](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/c061d6ae-656f-4f3a-b991-cf87d069af66)

### OLYMPIC DATA ANALYSIS
![image](https://github.com/pankaj8210/Olympics-Data-Analytics/assets/60617234/9e2aef28-89f9-4f41-a12f-e933b77ef636)


# Conclusion

The Olympic Data Analysis on Azure project demonstrates how to leverage Azure services for processing, analyzing, and visualizing large-scale data. By following the setup and guides provided in this repository, you can adapt the project to other domains and expand its functionalities. Happy analyzing!

# Author
@pankaj8210
