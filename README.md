# healthcare-insurance-bigdata-capstone:
    - This project implements an end-to-end Healthcare Insurance Big Data Analytics pipeline using AWS S3, Databricks,
    PySpark and Amazon Redshift. The pipeline ingests raw healthcare insurance datasets, performs data cleaning and 
    transformation, and generates analytical reports to support business decision-making.
    

## Project Workflow
    
    Healthcare Insurance CSV Data Files
                │
                ▼
    Amazon S3 (input-data)
                │
                ▼
    Databricks (PySpark)
                │
         Bronze Layer
                │
                ▼
         Silver Layer
                │
                ▼
    Amazon S3 (Silver)
                │
                ▼
    Amazon Redshift
                │
                ▼
    healthcare_clean Schema
                │
                ▼
    project_output Schema
                │
                ▼
    SQL Business Analytics

## Technology Stack
    - AWS S3
    - Databricks
    - PySpark
    - Amazon Redshift Serverless
    - SQL
    - GitHub
    - Jira

## File Structure
  - "**README.md**": Guideline documents, Project overview, objectives, technology stack, workflow, and setup instructions.
  - "**data**": This is the folder containing all the Raw data files
  - "**data_cleaning.ipynb**": This file contains the Python code for 
  - "**02_Result_generation.ipynb**": This file contains Python code for loading the cleaned datasets and implementing all 13 use cases on them.
  - "**Kusum_Katwal_Capstone_Project_Screenshot_Documentation.pdf**": This file contains the overall overview process and details about the project.

@ 2026 Kusum Katwal
