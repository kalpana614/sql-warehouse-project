# 📊 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics Project** repository! 🚀  
This project is a comprehensive demonstration of designing, building, and analyzing a modern data warehouse using industry-standard best practices. It serves as a robust portfolio piece for data professionals aspiring to showcase skills in data engineering and analytics.

---

## 🏗️ Modern Data Architecture (Medallion Architecture)
![image](https://github.com/user-attachments/assets/53d704ac-f527-4498-88bf-52bc4d9af891)


This project adopts the **Medallion Architecture** pattern with clearly defined **Bronze**, **Silver**, and **Gold** layers:

- **🔹 Bronze Layer**: Ingests raw data directly from CSV files into a SQL Server database (no transformation applied).
- **⚙️ Silver Layer**: Cleanses, standardizes, and integrates the data, making it analysis-ready.
- **🌟 Gold Layer**: Presents business-friendly, analytics-optimized data in a star schema format to support reporting and BI use cases.

---

## 📖 Project Scope & Objectives

### 🔧 Data Engineering

**Objective**  
Build a scalable and clean data warehouse using SQL Server to centralize ERP and CRM data for business analysis.

**Key Deliverables**
- **Data Integration**: Merge and harmonize data from two distinct source systems.
- **ETL Pipelines**: Develop efficient SQL-based extract-transform-load scripts for each layer.
- **Data Modeling**: Design dimension and fact tables using star schema.
- **Data Quality**: Address missing, inconsistent, or duplicate data issues.

### 📈 Data Analytics

**Objective**  
Enable strategic decision-making through insights derived from structured data.

**Focus Areas**
- Customer Behavior
- Product & Sales Performance
- Trend Analysis

**Deliverables**
- Insightful SQL queries
- BI-ready tables
- Reporting dashboards (optional/future scope)

---

## 👨‍💻 Target Audience

Ideal for professionals and learners pursuing roles in:
- SQL Development  
- Data Engineering  
- ETL Pipeline Development  
- Data Analytics  
- Data Architecture

---

## 🛠️ Tools & Resources

- **SQL Server Express** – Lightweight relational database engine  
- **SQL Server Management Studio (SSMS)** – GUI for database development and management  
- **Draw.io** – For creating architecture diagrams, data flows, and schemas  
- **Notion** – Project management and documentation template  
- **GitHub** – Version control and project collaboration  
- **Datasets** – Raw ERP and CRM CSV files (available in `/datasets`)

---

## 🚀 Project Requirements

This project is divided into two main phases: **Data Engineering** and **Data Analysis**, aligned with industry practices for building and utilizing a modern data warehouse.

---

### 🏗️ Building the Data Warehouse (Data Engineering)

**🎯 Objective**  
Develop a modern data warehouse using **SQL Server** to consolidate and manage sales data, enabling robust analytical reporting and strategic decision-making.

#### 📋 Specifications
- **Data Sources**: Import data from two source systems—**ERP** and **CRM**—provided in CSV format.
- **Data Quality**: Cleanse and resolve any quality issues such as missing, duplicate, or inconsistent values.
- **Integration**: Combine both data sources into a unified, user-friendly data model optimized for analytical workloads.
- **Scope**: Use only the latest snapshot of data (no historical tracking required).
- **Documentation**: Maintain clear and complete documentation of the data model to assist both business stakeholders and analytics teams.

---

### 📊 BI: Analytics & Reporting (Data Analysis)

**🎯 Objective**  
Deliver SQL-based analytics to extract actionable insights and drive business decisions.

#### 📌 Focus Areas
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key metrics and help shape strategic business directions.

📄 _For complete technical specifications, refer to [`docs/requirements.md`](docs/requirements.md)._

---

## 📂 Repository Structure

```data-warehouse-project/
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
```

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

---

> 💡 *Feel free to fork this project, contribute improvements, or use it as a base for your own analytics portfolio!*

