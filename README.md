# Stock Market Real-Time Streaming Pipeline

 ## Introduction
This project implements a real-time stock market data pipeline using Python. Apache Kafka and Zookeeper, hosted on an Amazon EC2 instance, handle data streaming. Stock data is ingested into S3, processed with AWS Glue, and made accessible via AWS Athena for querying and analysis. This setup ensures efficient and scalable stock data processing.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. Programming Language - Python
2. IDE used - Jupyter Notebook
3. AWS Services
   - AWS EC2
   - Amazon S3
   - AWS Glue
   - Amazon Athena

## Dataset Used
The dataset used in this project contains historical stock market data, which serves as the producer for the streaming pipeline. The data is read from the dataset and sent through Apache Kafka, simulating real-time stock market events. This approach allows for testing and validating the pipeline’s functionality before integrating with live stock market feeds.<br />
**Stock Market Data Used:** - https://github.com/Delmas-code/Stock-Market-Real-Time-Streaming-Pipeline/blob/main/stock_market_dataset.csv

## Project Scripts
1. [Producer File](Kafka_producer.ipynb)
2. [Consumer File](Kafka_consumer.ipynb)
