# AdescoTechHub Online Academy Project

**By Angel**

## Project Overview

This project demonstrates the deployment of a Student Management Portal using Amazon Lightsail and the integration of AWS services for student records, attendance management, serverless functions, and monitoring.

## AWS Services Used

- **Amazon Lightsail:** Hosted the Ubuntu-based Student Management Portal.
- **Ubuntu:** Operating system used on the Lightsail instance.
- **Apache:** Web server used to serve the portal webpage.
- **Amazon DynamoDB:** Stored student records and attendance information.
- **AWS Lambda:** Created and tested a serverless function using Python 3.14.
- **Amazon CloudWatch:** Used to view Lambda execution logs and monitor function activity.

## Project Tasks

### Task 1: Student Management Portal Deployment

- Created and launched an Ubuntu Lightsail instance.
- Connected to the instance using the browser-based SSH terminal.
- Installed and verified the Apache web server.
- Created an `index.html` file for the Student Management Portal.
- Deployed and accessed the portal through a web browser.

### Task 2: DynamoDB Tables

**Students table**
- Created a DynamoDB table named `Students`.
- Configured `Student_ID` as the partition key.
- Added student records containing student and course information.

**Attendance table**
- Created a DynamoDB table named `Attendance`.
- Configured `Attendance_ID` as the partition key.
- Added attendance records to track student activities, courses, dates, and attendance status.

### Task 3: AWS Lambda

- Created a Lambda function named `AdescoTechHub-Online-Academy`.
- Selected Python 3.14 as the runtime.
- Deployed and tested the function.
- Verified a successful test response for the student registration event.

### Task 4: CloudWatch Monitoring and Logs

- Viewed Lambda execution logs in Amazon CloudWatch.
- Reviewed recorded function activity and execution details.

## Skills Demonstrated

- AWS Lightsail instance deployment
- Ubuntu server administration
- Apache web server installation
- Basic HTML website deployment
- Amazon DynamoDB table and item management
- AWS Lambda function creation and testing
- Amazon CloudWatch logs and monitoring
- Troubleshooting AWS services

## Project Documentation

The accompanying Word document contains screenshots showing the AWS console configuration, portal deployment, DynamoDB tables and records, Lambda function deployment and testing, and CloudWatch logs.

## Project Type

AWS Cloud Computing Training Assignment
