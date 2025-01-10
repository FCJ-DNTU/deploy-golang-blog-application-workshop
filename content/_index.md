---
title: "Deploying Golang Application on EC2 Workshop"
date: "`r Sys.Date()`"
weight: 1
chapter: false
---
# Workshop: Deploying a Golang Application on EC2 with MySQL RDS and S3

### Overview

In this workshop, you will learn how to deploy a Golang application on AWS EC2, using MySQL RDS as the database and S3 for object storage.

![Workshop Architecture](/images/workshop_architecture.png)

### Objectives:

- Understand how to create and configure basic AWS services.
- Connect and use MySQL RDS from EC2.
- Integrate S3 storage into a Golang application.
- Deploy and run a Golang application in an AWS environment.

### Requirements:

- An AWS account with IAM access.
- Basic knowledge of Golang and Linux command line.
- A computer with an SSH client (e.g., Terminal or PuTTY).

### Contents

1. [Introduction](1-introduce/)
2. [Restrict Access with IAM Service](2-restrict-access/)
3. [Create a VPC](3-create-vpc-instance/)
4. [Set Up an EC2 Instance](4-create-ec2-instance/)
5. [Create AWS Relational Database Service (RDS)](5-create-rds-instance/)
6. [Set Up an S3 Bucket for Image Storage](6-create-s3-instance/)
7. [Deploy the Application to EC2](7-deploy-application-to-ec2/)
8. [Clean Up Resources](8-clean-up/)
