# Data Engineering Labs with Apache Spark and Structured Streaming

## Overview
This repository contains three lab notebooks that demonstrate key concepts in 
**Apache Spark** and **Structured Streaming**. 
These labs cover essential topics such as data processing, transformations, and real-time streaming using Spark.

## Prerequisites
Before running the notebooks, ensure you have the following installed:

- Python 3.7+
- Apache Spark (latest version)
- PySpark
- Jupyter Notebook or JupyterLab
- Kafka (for structured streaming)
- Required Python libraries:  
  ```bash
  pip install pyspark pandas numpy matplotlib
1. Lab 1: Apache Spark Basics (lab1_spark.ipynb)
Topics Covered:

Introduction to Apache Spark
Setting up SparkContext and SparkSession
Basic RDD operations (map, filter, reduce)
Working with DataFrames and SparkSQL

Run notebook to explore the content 
#### lab1_spark.ipynb ####

2. Lab 2: Advanced Spark Transformations (lab2_spark.ipynb)
Topics Covered:

DataFrame transformations and actions
Aggregations and GroupBy operations
Handling missing data and performance optimizations
Writing and reading data in different formats (Parquet, JSON, CSV)

Run notebook to explore the content 
#### lab2_spark.ipynb ####


3. Lab 3: Structured Streaming with Spark (Lab3_StructuredStreaming-2.ipynb)
Topics Covered:

Real-time data ingestion using Structured Streaming
Streaming data sources (Kafka, socket, file-based)
Windowing operations and stateful processing
Writing streaming results to sinks (console, files, Kafka)

Run Notebook to explore the content
#### Lab3_StructuredStreaming-2.ipynb ####

Note: Start a streaming source (e.g., socket or Kafka broker).





