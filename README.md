# Data-migration-from-S3-to-Documentdb

# Overview
This project aims to use a URL that points to a zip file containing multiple JSON files. These JSON files contain various data structures with multiple documents. The goal is to download the zip file from the URL, extract the data from the JSON files, store it in Amazon S3, and load it into Amazon DocumentDB

# Project Goals
1.Use the requests library to download the zip file from the URL.
2.Use the zipfile module to extract the data from the zip file.
3.Use the boto3 library to store the data in Amazon S3.
4.Create a DocumentDB instance and connect it with an EC2 instance in the same VPC. Also, create a SageMaker instance to connect with DocumentDB.
5.Load the data from S3 into Amazon DocumentDB (MongoDB).

# Services we will be using
1.Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2.AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3.AWS DocumentDB: AWS DocumentDB is a fully managed, non-relational database service that is compatible with MongoDB workloads
4.AWS EC2: Enables you to launch and manage virtual machines, known as instances.
4.Amazon SageMaker: An AWS SageMaker Notebook is essentially a Jupyter Notebook in which you can run Python code.
