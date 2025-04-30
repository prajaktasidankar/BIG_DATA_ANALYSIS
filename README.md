# BIG_DATA_ANALYSIS

COMPANY : CODTECH IT SOLUTIONS

NAME : PRAJAKTA SIDANKAR

DOMAIN : DATA ANALYSIS

DURATION : 4 WEEKS

Task 1: Big Data Analysis Using PySpark

Python Apache Spark Jupyter Notebook Status

Project Overview

As part of my data analysis internship, this project involved performing big data analysis using PySpark inside a Jupyter Notebook. The dataset used—NYC Yellow Taxi Trips (January 2023)—contains millions of records, ideal for demonstrating scalable data processing.

Using PySpark, I explored, cleaned, and analyzed this large dataset interactively. The goal was to extract business insights efficiently using distributed computing, even on a local machine.

Dataset Information

📁 Dataset: NYC Yellow Taxi Trip Records (Jan 2023)
📄 Format: Parquet (.parquet)
📊 Rows: ~10 million
🔗 NYC TLC Open Data

📁 Dataset Access

This project uses the **NYC Yellow Taxi Trip dataset** for January 2023, which is publicly available from the NYC Taxi & Limousine Commission.

Since the file size exceeds GitHub's 100MB upload limit, it is not included directly in this repository.

📥Download it here:  
[➡️ yellow_tripdata_2023-01.parquet (Direct Link)](https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2023-01.parquet)

To use the dataset, download and place it in the same folder as the notebook:



✅ Key Features:

Pickup and dropoff timestamps
Trip distance
Fare, tips, and total amount
Passenger count
Payment type
Location IDs
🛠️ Tools & Technologies Used

Apache Spark (PySpark)
Python 3.10
Jupyter Notebook
Pandas (for light comparisons)
Parquet file format
📈 Insights Derived

The dataset includes over 10 million taxi trips in January 2023
Pickup Location ID 138 was the most frequently used
The average trip distance was ~2.98 miles
Credit card users tipped more generously (~1.87 USD) than cash-paying customers (~0.65 USD)
Minor missing values were found in passenger_count and tip_amount
