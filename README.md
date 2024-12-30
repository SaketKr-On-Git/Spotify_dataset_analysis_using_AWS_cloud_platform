Spotify_dataset_analysis_on_AWS_cloud_platform
===============================

This repository contains the code for realtime Spotify 2023 dataset analysis. The system is built using Python, S3 bucket, Glue ETL, Crawler,Athena and Quicksight. The system is built on AWS cloud platform which is scalable, cost-efficient, serverless with integration of diverse services, high availability, robust security,.

## System Architecture
![system_architecture.jpg](https://github.com/SaketKr-On-Git/Spotify_dataset_analysis_using_AWS_cloud_platform/blob/main/System%20architecture.png)

The project is designed with the following components:

- **Data Source**: The pipeline retrieves data from spotify dataset 2023 from kaggle.
- **S3 bucket**: Used for scalable, secure, and durable storage of structured and unstructured data, enabling data lakes, ETL pipelines.
- **Glue ETL**:  Used to automate the process of discovering, preparing, and transforming data for analytics.
- **Crawler**: Used to automatically discover data schemas, populate the Glue Data Catalog, and make data queryable for analytics
- **Athena**: Used for serverless querying of data stored in S3 using SQL, enabling quick and cost-effective data analysis.
- **Quicksight**: QuickSight is used for creating interactive dashboards and visualizing data insights from various sources, including S3 and Athena.
  
## Technologies

- S3 bucket
- Glue ETL
- Crawler
- Athena
- Quicksight
