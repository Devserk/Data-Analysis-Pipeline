# Data-Analysis-Pipeline

A setup of worflow and services for handle analysis and statics data based on apache suit as nifi, kafka , spark and tensorflow for IA interpretation. Alll ofnthis achieve by an visualization with superset.

### API Endpoints

Differents access points to drive data from them

### Apache Kafka

is event streaming platform and used for data ingestion, Kafka is set up with 3 brokers to ensure high availability and scalability. Topics are created to organize incoming data streams.

### Apache Nifi

for drive and do a small treatment on data and manage road of driving data for differents sources, is an ETL(Extract, Transform, and Load) tool to automate dataflows. This platform is easy to use through its user interface UI. It supports multiples sources to extract and load data like Elasticsearch, Redis, Snowflake, PostgreSQL, Amazon S3, Spark, Twitter, and many others.

### Apache Spark

A distributed processing framework that processes large-scale data streams. Saprk, particularly Spark Structured Streaming, will be used for consuming data from Kafka, performing necessary transformations, and preparing the data for storage in Minio S3.

### MinIO S3

A high-performance, S3-compatible object store used as the final destination for storing processed data streams. The data is organized in the S3 bucket with appropriate folder structures and naming conventions.

### Superset  

allows you to create and share dashboards and explore data with SQL

### Metabase

is an open source business intelligence tool. It lets you ask questions about your data, and displays answers in formats that make sense, whether that’s a bar graph or a detailed table.

### Docker

Docker provides a way to run applications in isolated environments, allowing for greater flexibility and efficiency in software development and deployment.
