
# Project Overview
This end-to-end Azure analytics project was from Darshil Parmar in Youtube. We did raw data extraction, transformation, loading the data in SQL and dashboard creation.

## Personal Goal
I wanted to gain a comprehensive understanding of the Azure data pipeline, starting from the raw data ingestion stage to gaining insights in SQL and creating a usable dashboard.

### Data Sources

The data source used was the Tokyo Olympic Data of 2021 from Kaggle: https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

### Tools
- Azure Data Factory
- Azure Data Lake Gen 2
- Azure Databricks
- Azure Synpase Analytics
- SQL
- Power BI


## Process
Ingestion: We extract data from the API using Azure Data Factory
![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/16b387a1-81e4-471d-abe5-09063dee75b1)

Storage: The raw data is loaded into Azure Data Lake.

![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/15091bcf-3888-4a5b-8f5d-aa5d1bf58083)


Transformation: Azure Databricks is employed to write Spark code for data transformation.

![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/18780e9b-05c7-40a2-907a-041725c2d1e5)
![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/af63e39c-119f-467a-b192-05c505b3f1cd)
![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/6022b88e-37c9-4ac4-b561-f6b4f17399d1)
![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/2e60e27e-1542-4675-b586-3317eb609156)




Data Loading: The transformed data is then loaded back into Azure Data Lake.

Analytics: Finally, we leverage Synapse Analytics to execute SQL queries and extract valuable insights from the data.
![image](https://github.com/KarthikGowdaRamakrishna/Data-Engineering-with-Azure-Data-Factory-Data-Lake-Gen-2-Synapse-Analytics-and-Azure-Databricks./assets/144963620/c07ebfe7-24bf-46eb-917f-18aca3fef630)


