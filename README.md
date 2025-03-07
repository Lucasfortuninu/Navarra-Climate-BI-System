# BI System for Navarra's Climate

## 📌 Description
This repository contains the development of a **Business Intelligence (BI)** system to analyze the climate in Navarra, using an **ETL (Extract, Transform, Load)** process and storing data in a **Data Warehouse** in MySQL.

This project was developed as the final project for the **Business Applications Analysis** course in the third year of the **Computer Engineering** degree at the **Public University of Navarra (UPNA)**.

## 🏆 Project Objectives
- Develop an **ETL process** in Python to collect and transform weather data.
- Design a **Data Warehouse** with a star schema for structured storage.
- Implement **interactive reports and graphs** to visualize climate trends.
- Analyze **query performance** with load and concurrency testing.

## 🚀 Technologies Used
- **Python** 🐍 for implementing the ETL process and data analysis.
- **MySQL** for structured storage in the Data Warehouse.
- **Grafana** 📊 for visualizing data in interactive dashboards.
- **Jupyter Notebook** for documentation and experimentation.

## 📂 Project Content
1. **ETL Process**:
   - **Extraction**: Download weather data from external sources.
   - **Transformation**: Data normalization and cleaning.
   - **Loading**: Insert data into MySQL.
2. **Data Warehouse Design**:
   - Dimension tables (LK_comarcas, LK_pueblos, LK_tiempo).
   - Fact table (DT_temperaturas) with temperature and precipitation records.
3. **Report Generation**:
   - Graphs for precipitation and temperatures by year, month, and week.
   - Interactive dashboards in Grafana.
4. **Performance Testing**:
   - Evaluate SQL query response times.
   - Simulate concurrency with up to 100 users.

## 📊 Results and Conclusions
- An **efficient ETL** process was implemented for loading historical climate data.
- A **structured Data Warehouse** was designed to facilitate analysis.
- **Graphs and interactive dashboards** were created to visualize trends.
- Query times were analyzed with **concurrent user load**.
