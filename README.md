# sql-datawarehouse-project
# Data Warehouse and Analytics Project 🚀

This project focuses on building a **data warehouse** and analyzing data to find useful insights. It covers data cleaning, warehousing, analytics, and data mining.

🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
<img width="637" height="317" alt="image" src="https://github.com/user-attachments/assets/f47e28ce-ad0c-47ec-9d09-6342f0ac8b0f" />
Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

Tools:
Datasets:  the project dataset (csv files).
SQL Server Express: Lightweight server for hosting your SQL database.
SQL Server Management Studio (SSMS): GUI for managing and interacting with databases.
Git Repository: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
DrawIO: Design data architecture, models, flows, and diagrams.
Notion Project Steps: Access to All Project Phases and Tasks.

## 🚀 Project Requirements
### Data Warehouse

**Objective:**
Build a data warehouse using SQL Server to organize sales data and make it easier to analyze.

**Main Requirements:**

* Import data from ERP and CRM CSV files.
* Clean and fix the data before using it.
* Combine data from both sources.
* Create a simple data model for analysis.
* Focus only on the latest data.
* Document the data model clearly.

### 📊 Analytics & Reporting

**Objective:**
Use SQL to analyze the data and find useful insights about:

* Customer Behavior
* Product Performance
* Sales Trends

📂 Repository Structure:

![Uploading image.png…]()


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

🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
