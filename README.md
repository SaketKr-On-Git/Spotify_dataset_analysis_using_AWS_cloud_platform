Realtime Election Voting System
===============================

This repository contains the code for a realtime election voting system. The system is built using Python, Kafka, Spark Streaming, Postgres and Streamlit. The system is built using Docker Compose to easily spin up the required services in Docker containers.

## System Architecture
![system_architecture.jpg](https://github.com/SaketKr-On-Git/Spotify_dataset_analysis_using_AWS_cloud_platform/blob/main/System%20architecture.png)

The project is designed with the following components:

- **Data Source**: The pipeline retrieves random user data using the `randomuser.me` API.  
- **Apache Airflow**: Manages the orchestration of the pipeline and facilitates storing fetched data in a PostgreSQL database.  
- **Apache Kafka and Zookeeper**: Enable data streaming from PostgreSQL to the processing engine.  
- **Control Center and Schema Registry**: Provide tools for monitoring Kafka streams and managing schemas.  
- **Apache Spark**: Processes the data through its master and worker nodes.  
- **Cassandra**: Serves as the storage solution for the processed data.
  
## Technologies

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker
