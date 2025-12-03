# Databricks-SparkSQL-DeltaLake-ETL
## Introduction

This repository showcases a complete **end-to-end data engineering project** built using **Databricks, Spark SQL, and Delta Lake**. It demonstrates how raw data can be ingested, transformed, stored, and queried efficiently using modern big data technologies and the **Lakehouse architecture**.

The main purpose of this project is to provide a **practical, hands-on learning experience** for engineers, students, and professionals who want to build expertise in:

- Big Data Processing  
- Distributed Computing with Spark  
- SQL-based ETL Pipelines  
- Working with real-world datasets  

The project uses the **NYC Taxi dataset**, which is widely used in industry and academia for benchmarking, analytics, and ETL workflows. By following the notebooks provided in this repository, users can learn how to:

- Ingest large datasets into Databricks  
- Clean and process data using SQL  
- Store data in the Delta Lake format with ACID transactions  
- Run analytical queries to extract insights  

Whether you're preparing for a **data engineering job**, building a **portfolio project**, or simply exploring Databricks and Spark, this project offers a valuable opportunity to gain **hands-on experience with modern industry tools and workflows**.

## About the Datasets

There are two types of taxis commonly operating in **New York City (NYC)**: **Yellow Taxis** and **Green Taxis**.  
Both datasets are used in this project.

---

### Yellow Taxi Dataset — Attributes

- `VendorID`
- `tpep_pickup_datetime`
- `tpep_dropoff_datetime`
- `passenger_count`
- `trip_distance`
- `RateCodeID`
- `store_and_fwd_flag`
- `PULocationID`
- `DOLocationID`
- `payment_type`
- `fare_amount`
- `extra`
- `mta_tax`
- `tip_amount`
- `tolls_amount`
- `improvement_surcharge`
- `total_amount`
- `congestion_surcharge`

---

### Green Taxi Dataset — Attributes

- `VendorID`
- `lpep_pickup_datetime`
- `lpep_dropoff_datetime`
- `passenger_count`
- `trip_distance`
- `RateCodeID`
- `store_and_fwd_flag`
- `PULocationID`
- `DOLocationID`
- `fare_amount`
- `extra`
- `mta_tax`
- `tip_amount`
- `tolls_amount`
- `ehail_fee`
- `improvement_surcharge`
- `total_amount`
- `payment_type`
- `trip_type`
- `congestion_surcharge`
