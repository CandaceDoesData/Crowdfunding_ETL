# 📊 Crowdfunding ETL Pipeline (Python + SQL)

## 🧭 Project Overview

    This project is a collaborative data engineering pipeline designed to extract, transform, and load (ETL) crowdfunding data into a structured relational database for analysis.

    Working as part of a team, we built a full data pipeline using Python and PostgreSQL to clean raw datasets, normalize data structures, and load them into a SQL database optimized for querying and reporting.

    The goal of the project was to simulate a real-world data engineering workflow, where messy, multi-source data is transformed into a clean, analysis-ready format.

## 👥 Collaboration

    This was a group project completed in collaboration with other data team members.

    My role focused on:

    - Building and refining Python-based data transformation logic
    - Supporting data cleaning and restructuring processes
    - Assisting with database schema design and SQL table creation
    - Ensuring consistency between transformed datasets and SQL load structure
    - Participating in team debugging and workflow alignment

    This project reflects real-world collaborative data engineering practices, including shared codebases, version control, and coordinated pipeline development.

## 🔧 ETL Workflow   

    ### 🟢 Extract (Python / Pandas)
        - Imported raw crowdfunding datasets from CSV files
        - Inspected data structure and identified inconsistencies
        - Standardized column formats for downstream processing
    
    ### 🟡 Transform (Python / Pandas)
        - Cleaned and normalized nested and inconsistent data fields
        - Converted data types (dates, numeric values, categorical fields)
        - Split and structured complex fields into relational components
        - Created multiple structured DataFrames for database loading
    ### 🔵 Load (SQL / PostgreSQL)
        - Designed relational database schema
        - Created SQL tables with primary and foreign keys
        - Loaded cleaned datasets into PostgreSQL
        - Ensured referential integrity across all tables
        
## 🧱 Database Design

    The final database was structured to support relational querying across crowdfunding entities, including:

    - Campaigns
    - Categories
    - Subcategories
    - Contacts

    Key design considerations included:

    - Normalization to reduce redundancy
    - Primary and foreign key relationships
    - Data integrity enforcement through schema constraints
    
## 📊 Tools & Technologies
    - Python (Pandas)
    - SQL (PostgreSQL)
    - Jupyter Notebook
    - ETL pipeline design principles
    - Data cleaning and transformation
    - Relational database modeling
    - Git & GitHub (collaborative version control)
    
## 💡 Key Outcomes
    - Converted raw, unstructured crowdfunding data into a fully relational SQL database
    - Built a repeatable ETL pipeline using Python
    - Strengthened data integrity through schema design and validation
    - Demonstrated ability to work collaboratively on a shared data engineering project
    
## 📌 Business Value

    This pipeline demonstrates how raw transactional and campaign data can be transformed into structured datasets suitable for business intelligence, analytics, and reporting.

    The final database enables:

    - Campaign performance analysis
    - Category-based funding insights
    - Structured reporting for decision-making
    - Scalable querying using SQL

### Candace Stingley 
    - Category and Subcategory DataFrames

### Jessica Richter 
    - Campaign DataFrame

### Mark Meinhardt 
    - Contacts DataFrame

### Brenton Bethel 
    - Crowdfunding Database

