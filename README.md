# data-pipeline
AWS Data Pipeline & Analytics Project 🚀

Welcome to the AWS Data Pipeline and Analytics Project!
This project demonstrates how to build a complete serverless data pipeline on AWS using Amazon S3, AWS Glue, AWS Athena, and QuickSight.
It is designed as a beginner-friendly, portfolio-ready project that follows modern data engineering architecture.

🏗️ Data Architecture

This project follows a lightweight version of the Medallion Architecture (Bronze → Silver → Gold) inside the AWS ecosystem.

Architecture Diagram (Draw.io provided below)

Raw Zone :
Raw CSV data is uploaded to Amazon S3.

Clean Zone :
AWS Glue cleans, transforms, and standardizes the data.

Analytics Zone :
Athena creates external tables from the processed data for business insights.

BI Layer:
Amazon QuickSight is used to create dashboards and reports.

📖 Project Overview

This project demonstrates:

1️⃣ AWS Cloud Architecture

S3 (data lake)

Glue Crawler

Glue ETL Job (PySpark)

Athena (SQL analytics)

QuickSight (dashboards)

2️⃣ ETL Pipeline

Extract data from local CSV

Upload into S3 

Clean & transform using AWS Glue 

Athena tables for analytics

3️⃣ Data Modeling

Flattened fact table design

Partitioning strategy used:
year, month, product_category (optional)

4️⃣ Analytics

Athena SQL queries to find:

Top-selling products

Monthly revenue

Customer purchase behavior

Region-wise performance

🎯 Skills Showcased

This project highlights your skills in:

✔️ AWS Data Engineering
✔️ ETL Development
✔️ Data Modeling
✔️ SQL Analytics
✔️ Cloud Architecture
✔️ Portfolio-building best practices
🛠️ Tools Used

All tools used in this project are free-tier compatible!

Tool	Purpose
AWS S3	Data storage (Bronze/Silver/Gold)
AWS Glue Crawler	Auto-discover schema
AWS Glue Job	ETL transformation
AWS Athena	SQL query engine
AWS IAM	Permissions
AWS CLI / Python boto3	S3 automation
Draw.io	Pipeline diagram
GitHub	Version control

📂 Repository Structure
/data-pipeline-project
    /bronze
    /silver
    /gold
    /scripts
        upload_to_s3.py
        glue_etl.py
    /athena
        queries.sql
    architecture.drawio
    README.md

🛡️ License

Open-source under MIT License. You may use or modify this project freely.

👨‍💻 About Me

Hi! I'm Arya Kurup.
I’m an aspiring Data Engineer passionate about building cloud-based data systems that are simple, scalable, and impactful.
