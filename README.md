# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  

This project demonstrates a comprehensive end-to-end data warehousing and analytics solution — from building a structured data warehouse to generating actionable business insights.

Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** pattern with three structured layers:

### 🥉 Bronze Layer (Raw Data)
- Stores raw data as-is from source systems  
- Data is ingested from CSV files into SQL Server  
- No transformations applied  
- Source-aligned schema  

### 🥈 Silver Layer (Clean & Standardized Data)
- Data cleansing and validation  
- Standardization and normalization  
- Deduplication and null handling  
- Derived columns and enrichment  

### 🥇 Gold Layer (Business-Ready Data)
- Data modeled into a **Star Schema**  
- Fact and Dimension tables  
- Aggregations and business logic  
- Optimized for reporting and analytics  

---

## 📖 Project Overview

This project includes:

### 🔹 Data Architecture
Designing a modern data warehouse using Medallion Architecture (Bronze, Silver, Gold).

### 🔹 ETL Pipelines
Extracting, transforming, and loading data from ERP and CRM systems into SQL Server.

### 🔹 Data Modeling
Developing fact and dimension tables optimized for analytical queries.

### 🔹 Analytics & Reporting
Creating SQL-based reports and dashboards to generate actionable insights.

---

## 🎯 Skills Demonstrated

This repository showcases expertise in:

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Technologies Used

- SQL Server Express  
- SQL Server Management Studio (SSMS)  
- Git & GitHub  
- Draw.io (Architecture & Data Modeling Diagrams)  
- CSV Datasets  

All tools used in this project are completely free.

---

## 🚀 Project Requirements

### 🏗️ Building the Data Warehouse (Data Engineering)

**Objective:**  
Develop a modern SQL Server data warehouse to consolidate ERP and CRM sales data for analytical reporting and informed decision-making.

### Specifications

- Import data from ERP and CRM (CSV files)  
- Cleanse and resolve data quality issues  
- Integrate both sources into a unified analytical model  
- Focus on the latest dataset only (no historization required)  
- Provide documentation to support business stakeholders and analytics teams  

---

## 📊 BI: Analytics & Reporting (Data Analysis)

**Objective:**  
Develop SQL-based analytics to deliver detailed insights into:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights empower stakeholders with key business metrics for strategic decision-making.

For more details, refer to:

docs/requirements.md

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

---

## 🛡️ License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project with proper attribution.

---

## 🌟 About Me

Hi there! I'm Ankita Banubakode, an aspiring Data Analyst with a strong interest in data warehousing, ETL pipelines, and business analytics. I’m passionate about building scalable data solutions and turning complex datasets into actionable insights.


