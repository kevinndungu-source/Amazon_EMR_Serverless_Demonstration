# Amazon Elastic Map Reduce (EMR) Serverless Demonstration

<img width="1180" alt="Amazon-EMR-Serverless" src="https://github.com/kevinndungu-source/EMR_Serverless_Demonstration_Resources/assets/114335263/0b67b0b1-eacc-4101-ba35-90e31b7d8fb9">



This project showcases the utilization of Amazon EMR Serverless for running a sample Spark job to process semi-structured review data. The goal is to demonstrate the capabilities of Amazon EMR Serverless in efficiently processing and analyzing big data workloads.
Overview
Amazon EMR (Elastic MapReduce) Serverless is a serverless big data processing service that enables you to run Apache Spark applications without managing clusters. In this demonstration, we leverage EMR Serverless to process semi-structured review data stored in JSON format and derive insights from the analysis.

## Project Structure
**1.	Scripts:**
 - **reviews.py**: Python script for processing the review data.
 - **script_arguments**: Additional script arguments used during the EMR Serverless application setup.

**2.	Sample Dataset:**
 - **dataset_en_dev.json**: Semi-structured review data in JSON format.

## How to Use
**1.	Setup Amazon EMR Serverless:**
 -	Configure an S3 bucket to store output files and logs.
 -	Create an IAM role with appropriate permissions for EMR Serverless.

**2.	Run Spark Job:**
 -	Execute the sample Spark job using Amazon EMR Serverless.
 -	Provide necessary script arguments during application setup.

**3.	Analyze Data with Amazon Athena:**
 -	Link Amazon Athena to the output folder in the S3 bucket containing processed Parquet data.
 -	Run SQL queries in Amazon Athena to analyze the processed data and derive insights.

## Additional Resources
1. For detailed documentation and insights, refer to this project's documentation document [link](https://drive.google.com/file/d/16BrMDEi1JACxEJZfeDUAg90ulZR1V2Ol/view?usp=drive_link).
2.	To replicate the project or explore the code, refer to this GitHub repository code section.


