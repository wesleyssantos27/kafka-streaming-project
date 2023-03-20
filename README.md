# Getting News - Kafka Real Time Data Engineering Project
## Introduction
In this project, I execute an end-to-end data engineering project on real-time API global news using Kafka.

For this I use different technologies such as Python, Linux, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, SQL and API consumption.

## Architecture

![image](https://user-images.githubusercontent.com/49647094/226472962-eb3e821d-21e4-4338-9160-270e26c5cae4.png)

## Technologies

- Rest API
- Programming Language - Python
- Linux (infra settings)
- Amazon Web Service (AWS)

  - S3 (Simple Storage Service)

  - Athena

  - Glue Crawler

  - Glue Catalog

  - EC2

- Apache Kafka

## Dataset

It comes from XXX API.
Documentation of bellow:

## Pipeline

The data is:
1. gotted from API service
2. transformed using python script
3. streamed using kafka over an EC2 instance in AWS service
4. saved in S3 Amazon data store
5. crawled and cataloged using Amazon Glue
6. delivered as structered data to be queried using Amazon Athena.

I believe this pipeline could be used as a basis to solve problems in many companies and deliver information to data or business teams.


## Sources

This flow was based on Darshil Parmar video: https://www.youtube.com/watch?v=KerNf0NANMo&t=1148s

I invite you to subscribe to his channel.
