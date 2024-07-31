# 📊 YouTube Statistics Data Engineering Project

## 📝 Overview
This project aims to securely manage, streamline, and analyze YouTube video data based on video categories and trending metrics. The focus is on building a scalable ETL system using AWS services to ingest, transform, and analyze data, with reporting capabilities through an interactive dashboard.

## 🛠️ Tools and Steps

### Tools:
- ☁️ AWS S3
- 🔒 AWS IAM
- 📊 AWS QuickSight
- 🛠️ AWS Glue
- 🖥️ AWS Lambda
- 🔍 AWS Athena

### Steps:
1. 📥 **Data Ingestion**:
   - Implemented mechanisms to ingest data from various sources.
   - Stored raw data in Amazon S3.

2. 🔄 **ETL System**:
   - Built ETL pipelines using AWS Glue to transform raw data into the required format.
   - Stored transformed data in a structured manner in S3.

3. 🗄️ **Data Lake**:
   - Centralized storage of data from multiple sources in Amazon S3 for seamless access and management.

4. 📈 **Scalability**:
   - Ensured the system is scalable to handle increasing data volumes by leveraging AWS services.

5. ☁️ **Cloud Integration**:
   - Utilized AWS cloud infrastructure to process and store large datasets efficiently.

6. 📊 **Reporting**:
   - Developed an interactive dashboard using Amazon QuickSight to visualize and analyze the data.

## 📥 Data Ingestion
### Data Source:
The Kaggle dataset contains statistics on daily popular YouTube videos over several months. Each region's data is in a separate file, with details including video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and a category_id field in the associated JSON file.

[YouTube Trending Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## 🔄 ETL System
### Data Transformation:
- Processed raw CSV files to extract relevant information.
- Transformed data into a structured format suitable for analysis.

### AWS Glue:
- Created and managed ETL jobs to automate data transformation.
- Cataloged data for easy querying using AWS Athena.

## 🗄️ Data Lake
### Centralized Repository:
- Used Amazon S3 to store raw and processed data, ensuring high availability and security.

## 📈 Scalability
### Scaling Solutions:
- Leveraged AWS services to ensure the system can scale as data volume grows.
- Employed serverless computing with AWS Lambda for efficient data processing.

## ☁️ Cloud Integration
### AWS Services:
- Implemented a cloud-based solution using AWS to handle large datasets and perform complex analyses without local infrastructure limitations.

## 📊 Reporting
### Interactive Dashboard:
- Utilized Amazon QuickSight to create visualizations and reports.
- Enabled stakeholders to gain insights from the data through an intuitive interface.

## 📈 Analysis and Insights
### Data Exploration:
- Analyzed video performance metrics such as views, likes, dislikes, and comment count.
- Categorized data by video categories and regions to identify trends.

### Reporting Metrics:
- Created visualizations for trends in video popularity.
- Provided insights into regional preferences and category-specific performance.

## 📝 Conclusion
The YouTube Analysis Project successfully ingested, transformed, and analyzed YouTube video data using AWS services. The project established a scalable ETL system and a centralized data lake, enabling comprehensive analysis and reporting through an interactive dashboard. This setup allows for continuous monitoring and insights into YouTube video trends and metrics.

## 📸 Screenshots
![architecture](https://github.com/user-attachments/assets/1a986834-4f0d-436b-a9e8-67bec339e6c7)


