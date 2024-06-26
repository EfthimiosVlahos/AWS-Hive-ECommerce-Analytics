# Hive Analytics in AWS for E-commerce

## Prerequisites
Before beginning this project, you should have:
- Basic knowledge of AWS services and how to create an EC2 instance on AWS
- Proficiency in Hive, Spark, SQL, shell scripting, and Docker
- Strong foundation in databases and relational modeling with an eagerness to learn new techniques

## Project Motivation
This project was developed to gain practical experience in performing Hive analytics using Docker containers on an AWS EC2 instance. The process involved setting up the environment, data ingestion and transformation with Sqoop, Hive, and Spark, and conducting complex data analysis using Hive queries.

## Dataset
The dataset used is the AdventureWorks dataset, which is designed for a fictitious bicycle manufacturer and includes diverse components like Manufacturing, Sales, Purchasing, and Human Resources. The project focuses on the Sales and Customer Demographics data. The complete schema can be viewed [here](part0dataset/AdvWorksOLTP_DB_Diagram.png).

## Problem Statement
The analysis aims to address several business questions using Hive, such as:
- Determining the discount limits for products
- Identifying the top 10 customers by sales contribution
- Analyzing purchase patterns by salary, education, and gender
- Calculating sales contribution percentages by customer and demographics
- Evaluating top performing territories and their adherence to sales quotas

## Project Workflow
- **Project Setup in AWS**: Configured and prepared the AWS environment for the project. [Details](part1projectsetupinaws/)
- **Creating Hive Data Warehouse**: Constructed a data warehouse to facilitate efficient data analysis. [Details](part2hivedatawarehouse/)
- **Performing Hive Analytics**: Executed complex analytical queries to derive insights from the data. [Details](part3hiveanalytics/)
