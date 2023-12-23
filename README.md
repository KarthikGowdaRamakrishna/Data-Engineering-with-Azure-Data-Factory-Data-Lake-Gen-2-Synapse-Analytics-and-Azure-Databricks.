
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

![image](https://github.com/stephechanova19/OlympicsDataAnalytics/assets/63657996/144cb9b2-d12d-44ed-8e35-9dfaf17b27fa)

Storage: The raw data is loaded into Azure Data Lake.

![image](https://github.com/stephechanova19/OlympicsDataAnalytics/assets/63657996/6d835d92-ab60-4cea-90ef-ec71a448ed44)

Transformation: Azure Databricks is employed to write Spark code for data transformation.

![image](https://github.com/stephechanova19/OlympicsDataAnalytics/assets/63657996/5286bb5c-ba51-43bf-8d97-3c33e53a0bf4)

![image](https://github.com/stephechanova19/OlympicsDataAnalytics/assets/63657996/f35b1efe-d520-4f77-9db1-6babda6f9f14)

Data Loading: The transformed data is then loaded back into Azure Data Lake.

Analytics: Finally, we leverage Synapse Analytics to execute SQL queries and extract valuable insights from the data.

![image](https://github.com/stephechanova19/OlympicsDataAnalytics/assets/63657996/aa40ccc0-8b03-4028-866c-883a9191819d)

