# Uber-ETL-Pipeline-DE-Project

Project Description
This project implements an end-to-end data engineering pipeline for analyzing Uber-style taxi trip data using Google Cloud Platform. The objective is to transform raw trip records into structured, analytics-ready datasets and generate insights through SQL queries and dashboards.
The pipeline follows a real-world data workflow: raw data ingestion, transformation, storage, and visualization. The focus is on data reliability, scalability, and clear separation between raw and processed data, rather than experimentation or machine learning.
________________________________________
Technologies Used
Programming
•	Python
Used for data ingestion, cleaning, and transformation logic within the pipeline.
Cloud Platform
•	Google Cloud Platform (GCP)
Provides scalable storage, compute, and analytics services for the entire pipeline.
GCP Services
•	Google Cloud Storage (GCS)
Stores raw taxi trip data as immutable source files.
•	Compute Engine
Runs the data pipeline and transformation workloads.
•	BigQuery
Acts as the analytical data warehouse for structured and optimized querying.
•	Looker Studio
Used to build interactive dashboards and visual reports on top of BigQuery tables.
Data Pipeline Tool
•	Mage (https://www.mage.ai/)
An open-source data pipeline orchestration tool used to manage ingestion, transformation, and scheduling of workflows.
________________________________________
Why This Stack
•	GCP enables serverless, scalable analytics without infrastructure overhead
•	BigQuery simplifies large-scale SQL analysis
•	Mage reduces orchestration complexity compared to heavier tools
•	Looker Studio allows quick insight generation without custom front-end work
________________________________________

