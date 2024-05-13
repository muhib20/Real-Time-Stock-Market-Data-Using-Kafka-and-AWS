# Real-Time-Stock-Market-Data-Using-Kafka-and-AWS
## Description
This project demonstrates an end-to-end data engineering process for handling real-time stock market data using various technologies, including Python, Amazon Web Services (AWS), Apache Kafka, AWS Glue, AWS Athena, and SQL. The project involves streaming stock data into Kafka, storing it in Amazon S3, cataloging it using AWS Glue, and querying it with Amazon Athena using SQL.
## Installation
To run this project, follow these steps:

1. Set up an AWS account and create necessary resources like S3 buckets, Kafka clusters, Glue crawlers, and Athena databases.
2. Install Python and required libraries like boto3 and pandas for data processing and Kafka interaction.
3. Configure AWS credentials on your local machine for programmatic access to AWS services.
4. Set up JupyterLab or any other preferred IDE for running Python scripts.

## Project Details
- **Data Streaming with Kafka**:  Real-time stock market data is streamed into Kafka topics using Python scripts.
- **Data Storage in S3**: Streamed data is stored in Amazon S3 buckets for scalable and durable storage.
- **Data Cataloging with Glue**: AWS Glue crawlers are used to automatically catalog the data stored in S3, making it queryable by Athena.
- **Querying with Athena**: Amazon Athena is used to query the cataloged data using SQL queries, enabling easy analysis and visualization.

## Architecture Overview
![Real Time Stock Market Data Using Kafka and AWS](https://github.com/muhib20/Real-Time-Stock-Market-Data-Using-Kafka-and-AWS/blob/main/Real%20Time%20Stock%20Market%20Data%20Using%20Kafka%20and%20AWS.png)

## Usage
For usage instructions, please refer to the configuration files and scripts provided in the project repository.

## Contact
contact@muhibhafeez.com
