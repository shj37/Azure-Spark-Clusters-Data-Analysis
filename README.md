# Harnessing Big Data Using Spark: Cloud-Based Analytics on Azure

![project overview](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*Y6sZtJh1CPIgRNp76QX5Ew.jpeg)

## Description

This repo houses the code and setup for a cloud-based data analytics pipeline built with **Apache Spark** on **Azure**. The project processes visa issuance data using a **Dockerized** Spark cluster and generates visualizations with Plotly. It’s a practical resource for anyone interested in scalable data engineering.


This project is fully documented in a [Medium article series](https://medium.com/@jushijun/harnessing-big-data-using-spark-cloud-based-analytics-on-azure-406f944e4e7b).

## Key Components

- `docker-compose.yml`: Configures the Spark cluster (1 master, 4 workers).
- `Dockerfile.spark`: Sets up the Spark environment with Python.
- `visualisation.py`: PySpark script for data processing and visualization.
- `requirements.txt`: Lists Python dependencies.
- `upload_files.sh` / `download_files.sh`: Scripts for file management between local and VM.

Usage: Clone the repo, set up an Azure VM with Docker, upload data/scripts, run the Spark job, and retrieve results.

Technologies: **Apache Spark**, **Docker**, **Azure**, **Python**, **Plotly**, **Spark SQL**, **PySpark**

## References

- YouTube CodeWithYu https://www.youtube.com/watch?v=f-IcM8mFmDc&ab_channel=CodeWithYu
- https://github.com/airscholar/Japan-visa-data-engineering