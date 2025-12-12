# data-pipeline
AWS Data Pipeline & Analytics Project 🚀

Welcome to the AWS Data Pipeline and Analytics Project!
This project demonstrates how to build a complete serverless data pipeline on AWS using Amazon S3, AWS Glue, AWS Athena, and QuickSight.
It is designed as a beginner-friendly, portfolio-ready project that follows modern data engineering architecture.

🏗️ Data Architecture

This project follows a lightweight version of the Medallion Architecture (Bronze → Silver → Gold) inside the AWS ecosystem.

Architecture Layers

Raw Zone (Bronze): Raw CSV data is uploaded to Amazon S3.

Clean Zone (Silver): AWS Glue cleans, transforms, and standardizes the data.

Analytics Zone (Gold): Athena creates external tables from the processed data for business insights.

BI Layer: Amazon QuickSight is used to create dashboards and reports.

📖 Project Overview
1️⃣ AWS Cloud Architecture Components

Amazon S3 (Data Lake)

AWS Glue Crawler

AWS Glue ETL Job (PySpark)

Amazon Athena (Serverless SQL Engine)

Amazon QuickSight (Dashboard & BI Layer)

2️⃣ ETL Pipeline

Extract data from local CSV

Upload into S3 (Bronze Zone)

Clean & transform using AWS Glue (Silver Zone)

Create Athena tables for analytics (Gold Zone)

3️⃣ Data Modeling

Flattened fact table design

Optional partitioning:

year

month

product_category

4️⃣ Analytics

Athena SQL queries help analyze:

Top-selling products

Monthly revenue

Customer purchase behavior

Region-wise performance

🎯 Skills Showcased

This project highlights your abilities in:

✔️ AWS Data Engineering

✔️ ETL Development

✔️ Data Modeling

✔️ SQL Analytics

✔️ Cloud Architecture

✔️ Portfolio-building best practices

🛠️ Tools Used

All tools used in this project are free-tier compatible!

Tool	Purpose
AWS S3	Data storage for Bronze/Silver/Gold zones
AWS Glue Crawler	Auto discovery of schema
AWS Glue Job	ETL transformation using PySpark
AWS Athena	SQL querying & analytics
AWS IAM	Access & permissions
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

This project is licensed under the MIT License.
You are free to use, modify, and share this project.

👨‍💻 About Me

Hi! I'm Arya Kurup.
I’m an aspiring Data Engineer passionate about building cloud-based data systems that are simple, scalable, and impactful.
