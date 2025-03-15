# Kafka-based Instagram Engagement Data Pipeline

This project demonstrates how to set up a Kafka-based data pipeline for processing Instagram engagement data (e.g., likes, shares, comments) from a local dataset. The dataset is then consumed from Kafka and stored in an AWS S3 bucket for further analysis using AWS Glue and Athena.

## Project Overview
The goal of this project is to simulate a real-time data pipeline using Apache Kafka to process Instagram engagement data. The data is ingested from a local dataset, processed through Kafka, and stored in an AWS S3 bucket. The stored data is later queried using AWS Athena for insights.

## Key Components:
* Kafka: Real-time message queue for ingesting Instagram engagement data.
* AWS EC2: Cloud-based compute instance to host Kafka.
* AWS S3: Storage for engagement data.
* AWS Glue: Used for crawling the data stored in S3.
* AWS Athena: Query tool to analyze the data stored in S3.
* Python: Scripts for creating Kafka producers and consumers, and for storing data in S3.

## Architecture Diagram
![Architecture Diagram](Architecture%20Diagram.png)

## Insights and Benefits
1. Data Simulation: Even though the data isn't real-time, we are simulating real-time data processing, which is useful for testing and creating scalable systems.
2. Batch Data Processing: If the dataset is large, Kafka can still handle periodic batches, making it scalable and more efficient for data processing.
3. S3 and Athena Integration: The project allows to upload processed data to S3 and query it with Athena, providing valuable insights from the dataset.

## Contributing
Feel free to fork the repository, create issues, or submit pull requests to improve the project. Contributions are always welcome!
