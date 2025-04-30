# **Data Pipeline utilizing Databricks, Microsoft Azure, and Snowflake**

## **Final Project for the Information Management Course in the MS Business Analytics prgram at UT Austin.**
This repository highlights the code and process for completing my final project in this course.

:link: Watch the full breakdown here: [Youtube](https://youtu.be/wMmH8OzUQe0 'Information Management Capstone Project Video')

## **:rocket: Project Overview:**
For the capstone project in the Information Management course, I constructed a data pipeline utilizing software such as Databricks, Microsoft Azure Data Lake, and Snowflake.
Data for this project came from [Kaggle](https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset 'Ecommerce Order & Supply Chain Dataset')

The functions of the two files in this project were as follows: 
- SQL PDF: Constuction of an ETL pipeline to facilitate transfer of data originally stored in DBFS, then moved to Azure Data Lake, finally into Snowflake for constuction of warehouse and tables for analysis.
  - Additionally, data was combined in various ways to form a Medallion architecture (Raw, Silver layer schemas)
- Jupyter Notebook: Establishing a Snowpark session connected to the raw and silver layers to create dataframes and preform analysis to reupload to Snowflake as the Gold layer - ready to be utilized by top end business users for analysis.
  - Two analytical models to determine 'long term credit-card accounts' and products costing the most for the company to ship. I focused on pushing the long term credit-card account holders data back to Snowflake as a table      in the gold layer of the medallian architecture.
