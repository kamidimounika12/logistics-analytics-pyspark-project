# Logistics Data Engineering Project using Databricks

## Project Overview

This project demonstrates an end-to-end Data Engineering pipeline built using Databricks, PySpark, SQL, and Delta Lake.

The project processes logistics and transportation data through a Medallion Architecture (Bronze, Silver, and Gold layers) to generate business insights related to fleet operations, delivery performance, maintenance, safety, fuel efficiency, and customer analytics.

---

## Technologies Used

- Databricks Free Edition
- PySpark
- Spark SQL
- Delta Lake
- Python
- Data Engineering Concepts

---

## Architecture

Bronze Layer → Raw Data Ingestion

Silver Layer → Data Cleaning and Transformation

Gold Layer → Business Analytics and Reporting

---

## Project Workflow

### 1. Data Loading
- Loaded raw logistics datasets into Databricks.
- Created Bronze Layer tables.

### 2. Data Cleaning
- Handled missing values.
- Removed duplicates.
- Standardized data formats.

### 3. Business Analytics

The following analyses were performed:

#### Driver Performance Analysis
- Driver ratings
- Delivery efficiency
- Performance comparison

#### Route Profitability Analysis
- Revenue by route
- Profitability trends
- High-performing routes

#### Fleet Utilization Analysis
- Vehicle usage tracking
- Fleet utilization percentage

#### Maintenance Analysis
- Maintenance costs
- Vehicle service trends

#### Fuel Efficiency Analysis
- Fuel consumption patterns
- Fuel cost optimization

#### Customer Analysis
- Customer behavior insights
- Revenue contribution

#### Safety Analysis
- Safety incidents
- Risk identification

#### Delivery Performance Analysis
- Delivery success rate
- On-time delivery metrics

---

## Project Structure

```
Logistics-Data-Engineering-Project
│
├── notebooks
│   ├── 01_Data_Loading.py
│   ├── 02_Data_Cleaning.py
│   ├── 03_Driver_Performance.py
│   ├── 04_Route_Profitability.py
│   ├── 05_Fleet_Utilization_Analysis.py
│   ├── 06_Maintenance_Analysis.py
│   ├── 07_Fuel_Efficiency_Analysis.py
│   ├── 08_Customer_Analysis.py
│   ├── 09_Safety_Analysis.py
│   └── 10_Delivery_Performance_Analysis.py
│__ Screenshots
|
├── README.md
```

---

## Key Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Data Cleaning and Transformation
- PySpark Data Processing
- SQL Analytics
- Delta Lake Architecture
- Business Intelligence Reporting

---

## Author

Mounika Kamidi

B.Tech Computer Science Engineering

Aspiring Data Engineer / Data Analyst
