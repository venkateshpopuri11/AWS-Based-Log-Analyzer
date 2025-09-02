# AWS-Based-Log-Analyzer
AWS-Based Log Analyzer is a serverless Python application designed to automate log processing and deliver real-time insights through interactive dashboards. The solution is deployed on AWS Lambda and triggered by S3 events whenever new log files are uploaded.
# AWS-Based Log Analyzer

## Overview
A serverless Python application deployed on **AWS Lambda** that processes log files stored in **S3** and generates analytics dashboards using **Amazon QuickSight**.  

## Features
- Event-driven pipeline triggered by S3 upload  
- Parses application log files and extracts metrics  
- Stores structured data in DynamoDB / RDS  
- Visualizes data with QuickSight dashboards  
- Fully serverless using AWS Lambda + CloudWatch  

## Architecture
S3 → Lambda (Python) → DynamoDB/SQL → QuickSight Dashboard  

## Tech Stack
- Python 3.x  
- AWS Lambda  
- Amazon S3  
- DynamoDB / RDS  
- Amazon QuickSight  
- CloudWatch  

## Getting Started
1. Upload log files to the configured S3 bucket.  
2. Lambda function automatically processes and stores structured data.  
3. View metrics and charts in the QuickSight dashboard.  

## Repo Structure
- `lambda_function.py` → Main Lambda handler  
- `requirements.txt` → Dependencies  
- `README.md` → Documentation  

## Screenshot
![QuickSight Dashboard](quicksight_dashboard.png)
