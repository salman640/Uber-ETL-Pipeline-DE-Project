# Uber-ETL-Pipeline-DE-Project



# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction

This project implements an end-to-end data engineering pipeline for analyzing Uber-style taxi trip data using Google Cloud Platform. The objective is to transform raw trip records into structured, analytics-ready datasets and generate insights through SQL queries and dashboards.
The pipeline follows a real-world data workflow: raw data ingestion, transformation, storage, and visualization. The focus is on data reliability, scalability, and clear separation between raw and processed data, rather than experimentation or machine learning.


## Technology Used
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


Modern Data Pipeine Tool - https://www.mage.ai/



## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 


More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
