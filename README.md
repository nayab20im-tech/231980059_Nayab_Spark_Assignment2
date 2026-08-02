# NYC Taxi Trip Analytics using Apache Spark

## Course Information

- **University:** GIFT University
- **Course:** Big Data Analytics (DS-313)
- **Assignment:** Assignment #3
- **Instructor:** Zuhaib Hussain Butt

---

## Student Information

- **Name:** Nayab Nasir
- **Roll Number:** 231980059
- **Semester:** BS Data Science
- **Submission Date:** Aug-02-2026

---

# Project Overview

This project analyzes the **NYC Yellow Taxi Trip Records (January 2024)** dataset using **Apache Spark** running in **Local Mode**. The objective is to demonstrate the use of Spark for large-scale data processing, including data loading, cleaning, transformations, SQL analytics, window functions, and performance optimization.

---

# Dataset

**Dataset Used**

Yellow Taxi Trip Records – January 2024

Source:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

File:

```
yellow_tripdata_2024-01.parquet
```

---

# Development Environment

- Python 3
- Apache Spark 4.2.0
- Java 21
- Ubuntu Linux
- PySpark
- Jupyter Notebook

---

# Project Structure

```
RollNo_Name/
│
├── notebook.ipynb
├── notebook.py
├── report.pdf
├── README.md
├── execution_log.txt
│
├── output/
│   ├── query1.csv
│   ├── query2.csv
│   ├── query3.csv
│   ├── query4.csv
│   ├── query5.csv
│   ├── query6.csv
│   ├── query7.csv
│   ├── query8.csv
│   ├── query9.csv
│   └── query10.csv
│
└── screenshots/
    ├── spark_configuration.png
    ├── schema.png
    ├── eda.png
    ├── cleaning.png
    ├── filter.png
    ├── select.png
    ├── withColumn.png
    ├── orderBy.png
    ├── drop.png
    ├── distinct.png
    ├── groupBy.png
    ├── alias.png
    ├── join.png
    ├── repartition.png
    ├── sql_queries.png
    ├── window_functions.png
    ├── performance.png
    ├── jobs.png
    ├── stages.png
    ├── storage.png
    └── executors.png
```

---

# Features Implemented

## Part 1 – Environment Setup

- Spark Session Creation
- Spark Version
- Spark Master
- Application Name

---

## Part 2 – Dataset Loading

- Read Parquet File
- Display Schema
- Count Records
- Count Columns
- Display Sample Data

---

## Part 3 – Exploratory Data Analysis

The following statistics were computed:

- Total Trips
- Earliest Trip
- Latest Trip
- Unique Vendors
- Average Trip Distance
- Average Fare
- Maximum Fare
- Minimum Fare
- Average Passenger Count
- Number of Payment Methods

---

## Part 4 – Data Cleaning

Performed the following preprocessing steps:

- Removed Duplicate Records
- Removed Invalid Trip Distances
- Removed Negative Fare Values
- Removed Missing Values

---

## Part 5 – Spark Transformations

The following Spark transformations were demonstrated:

- filter()
- select()
- withColumn()
- orderBy()
- drop()
- distinct()
- groupBy()
- alias()
- join()
- repartition()

---

## Part 6 – Spark SQL

Ten SQL queries were implemented, including:

1. Top 10 Longest Trips
2. Top Pickup Locations
3. Average Fare by Payment Type
4. Peak Pickup Hour
5. Trips Over 20 Miles
6. Monthly Revenue
7. Average Tip by Vendor
8. Average Trip Distance by Vendor
9. Passenger Count Distribution
10. Highest Total Fare Trips

The output of each SQL query is available inside the **output/** directory.

---

## Part 7 – Window Functions

Implemented the following window functions:

- row_number()
- rank()
- dense_rank()

---

## Part 8 – Performance Optimization

Demonstrated:

- cache()
- repartition()
- explain()
- Execution Time Before Caching
- Execution Time After Caching

---

## Part 9 – Spark UI Analysis

Screenshots included:

- Jobs
- Stages
- Storage
- Executors

---

# How to Run

## Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebook.ipynb
```

Run all cells sequentially.

---

## Run Python Script

```bash
python3 notebook.py
```

---

## Generate Execution Log

```bash
python3 notebook.py > execution_log.txt
```

---

# Output Files

The SQL query outputs are automatically saved as CSV files inside:

```
output/
```

---

# Learning Outcomes

Through this project, the following Apache Spark concepts were implemented and understood:

- Spark DataFrames
- Spark SQL
- Lazy Evaluation
- Data Cleaning
- Data Transformations
- Window Functions
- Caching
- Repartitioning
- Spark UI Analysis
- Performance Optimization

---

# Author

**Name:** Nayab Nasir

**Roll Number:** 231980059

**Course:** Big Data Analytics (DS-313)

**University:** GIFT University
