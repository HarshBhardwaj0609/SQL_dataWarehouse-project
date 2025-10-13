# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  

This project demonstrates a comprehensive **data warehousing and analytics solution**,  
from building a data warehouse to generating actionable insights.  

Designed as a **portfolio project**, it highlights **industry best practices**  
in data engineering and analytics.
---------------------
## 🧩 Data Architecture

The data architecture for this project follows the **Medallion Architecture** with three key layers — **Bronze**, **Silver**, and **Gold**.

### 🥉 Bronze Layer
- Stores **raw data** as-is from the source systems.  
- Data is ingested from **CSV files** into the SQL Server database.  
- No transformations are applied at this stage.

### 🥈 Silver Layer
- Performs **data cleansing, standardization, and normalization**.  
- Transformed data is stored in clean, structured tables ready for analytics processing.

### 🥇 Gold Layer
- Contains **business-ready data** modeled into a **Star Schema** or **Flat Table**.  
- Optimized for **reporting, analytics, and visualization** in BI tools.
-----------------------
## 📖 Project Overview

This project demonstrates a complete **end-to-end data warehousing and analytics solution**, showcasing modern best practices used in enterprise data engineering.

---

### 🧩 Key Components

#### 🏗️ Data Architecture  
Designing a **Modern Data Warehouse** using the **Medallion Architecture** — consisting of **Bronze**, **Silver**, and **Gold** layers.  

#### ⚙️ ETL Pipelines  
Implementing **Extract, Transform, Load (ETL)** workflows to ingest raw data from source systems into the warehouse efficiently.  

#### 🧮 Data Modeling  
Developing optimized **fact** and **dimension tables** to support analytical queries and reporting.  

#### 📊 Analytics & Reporting  
Creating **SQL-based reports** and interactive **dashboards** that deliver actionable business insights.

---

## 🎯 Ideal For

This repository is an excellent resource for professionals and students aiming to build or demonstrate expertise in:

- 🧠 **SQL Development**  
- 🏗️ **Data Architecture**  
- ⚙️ **Data Engineering**  
- 🚀 **ETL Pipeline Development**  
- 🧮 **Data Modeling**  
- 📈 **Data Analytics**

---
# 🚀 Building the Data Warehouse (Data Engineering)

## Objective
Develop a modern data warehouse using **SQL Server** to consolidate sales data, enabling **analytical reporting** and **informed decision-making**.

## Project Specifications

### Data Sources
- Import data from **two source systems**:
  - **ERP**
  - **CRM**  
  Both provided as **CSV files**.

### Data Quality
- Cleanse and resolve **data quality issues** before analysis.

### Integration
- Combine both sources into a **single, user-friendly data model** optimized for **analytical queries**.

### Scope
- Focus on the **latest dataset only**.
- **Historization of data** is not required.

### Documentation
- Provide **clear documentation** of the data model to support:
  - Business stakeholders
  - Analytics teams
-------------------
## 📊 BI: Analytics & Reporting (Data Analysis)

### Objective
Develop **SQL-based analytics** to deliver detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with **key business metrics**, enabling **strategic decision-making**.
----------------------------
## 📁 Repository Structure

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
