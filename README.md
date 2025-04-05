# SQL-data-warehouse-project
Building a modern warehouse with SQL server, Including ETL process, data modelling and analytics.
Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository!
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.
Data Architecture

The data architecture for this project follows the Medallion Architecture with Bronze, Silver, and Gold layers:
Data Architecture

    Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.

    Silver Layer: Includes data cleansing, standardization, and normalization processes to prepare data for analysis.

    Gold Layer: Houses business-ready data modeled into a star schema designed for reporting and analytics.

Project Overview

This project involves:

    Data Architecture: Designing a modern data warehouse using Medallion Architecture (Bronze, Silver, and Gold layers).

    ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.

    Data Modeling: Developing fact and dimension tables optimized for analytical queries.

    Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

This repository is an excellent resource for professionals and students looking to showcase expertise in:

    SQL Development

    Data Architecture

    Data Engineering

    ETL Pipeline Development

    Data Modeling

    Data Analytics

Important Links & Tools

All tools and resources used in this project are free and open-source or community-supported:

    Datasets: Access to the project datasets (CSV files).

    SQL Server Express: Lightweight server for hosting your SQL database.

    SQL Server Management Studio (SSMS): GUI for managing and interacting with databases.

    GitHub: Set up a repository to manage, version, and collaborate on your code efficiently.

    Draw.io: Design data architecture, models, flows, and diagrams.

    Notion: Use Notion templates to organize project steps, documentation, and tracking.

Project Requirements
Building the Data Warehouse (Data Engineering)
Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.
Specifications

    Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.

    Data Quality: Cleanse and resolve data quality issues before analysis.

    Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.

    Scope: Focus on the latest dataset only; historization of data is not required.

    Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

BI: Analytics & Reporting (Data Analysis)
Objective

Develop SQL-based analytics to deliver detailed insights into:

    Customer Behavior

    Product Performance

    Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.
Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing ETL techniques and methods
│   ├── data_architecture.drawio        # Draw.io file showing the project's architecture
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
├── tests/                              # Test scripts and quality assurance files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
About This Project

This repository serves as a complete, end-to-end data warehouse and analytics solution. It is designed to help learners, professionals, and enthusiasts to understand the process of building a modern data pipeline — from raw data ingestion to delivering meaningful insights for business decision-making.
