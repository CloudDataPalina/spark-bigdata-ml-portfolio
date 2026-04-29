# Apache Spark Big Data & ML Portfolio

This repository contains a collection of Apache Spark projects covering:

- Big Data processing (RDD, DataFrames)
- ETL pipelines
- Spark SQL analytics
- Machine Learning (classification, regression, clustering)
- ML pipelines and model persistence
- Structured Streaming

## Projects

### 1. Retail Big Data Analytics
- Distributed processing using Spark
- Sales and revenue aggregation
- ETL pipeline

### 2. Classification
- Spark ML classification models
- Evaluation metrics

### 3. Regression
- Regression models
- Model persistence

### 4. Clustering
- KMeans clustering

### 5. Streaming
- Real-time data processing using Spark Structured Streaming

### 📂 Project Structure
```
spark-bigdata-ml-portfolio/
│
├── 01_retail_big_data/
│
├── 02_spark_etl_data_integration/
│
├── 03_ml_regression/
│   └── airfoil_regression_pipeline.ipynb   
│
├── 04_ml_classification/
│   └── classification_sparkml.ipynb        
│
├── 05_clustering/
│   └── clustering_sparkml.ipynb            
│
├── 06_streaming/
│   └── structured_streaming.ipynb          
│
└── README.md
```
# Dataset

This project uses a retail sales dataset (Retailsales.csv).

Due to file size limitations, the dataset is not included in this repository.

## Dataset Description

The dataset contains:

- product_id
- store_id
- date
- sales
- revenue
- promotion types
- stock levels

The data was used for distributed processing and aggregation using Apache Spark (RDD and DataFrame APIs).
