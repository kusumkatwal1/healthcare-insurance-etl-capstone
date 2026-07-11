# healthcare-insurance-bigdata-capstone:
    This project implements an end-to-end Healthcare Insurance Big Data Analytics pipeline using AWS S3, Databricks,
    PySpark and Amazon Redshift. The pipeline ingests raw healthcare insurance datasets, performs data cleaning and 
    transformation,
    

## Project Workflow
    
    Healthcare Insurance CSV Files
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

## File Structure
  - "**README.md**": Guideline documents
  - "**data**": this is the folder containing all the CVS data files
  - 

@ 2026 Kusum Katwal
