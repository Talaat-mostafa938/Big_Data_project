# Big Data ETL Pipeline using Spark, Hadoop, Airflow, and Snowflake

This project demonstrates an end-to-end Big Data ETL Pipeline for processing large-scale e-commerce data using modern Data Engineering tools.
The pipeline automates the complete workflow from data generation to cloud data warehousing using a Medallion Architecture (Bronze, Silver, Gold).

## Tech Stack
| Technology | Purpose |
| :--- | :--- |
| **Python** | Main programming language |
| **Apache Spark** | Distributed data processing |
| **Hadoop HDFS** | Distributed storage |
| **Apache Airflow** | Workflow orchestration |
| **Snowflake** | Cloud data warehouse |
| **Docker** | Containerization |
| **PySpark** | Spark API for Python |
| **YARN** | Cluster resource management |

## Airflow DAG Workflow
The pipeline is orchestrated using Apache Airflow with the following tasks:  
1. Read Data From HDFS
2. Clean , Transformation Data
3. Load To SnowFlake

## Final Validation
. All Airflow tasks completed successfully.

## Data Validation
. Data successfully stored in HDFS.
. loaded into Snowflake successfully.
. Data quality checks completed successfully.

## 1. Airflow DAG Execution
<img width="1897" height="896" alt="Screenshot 2026-07-12 042833" src="https://github.com/user-attachments/assets/a848ab68-b956-4839-84e1-b6b486bfa922" />



