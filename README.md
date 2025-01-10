# Blog Application

This is a simple blog application built using **Go (Golang)** and deployed on **AWS EC2** with **AWS RDS** for **MySQL** and **S3** for storage.

## Features
- Create, Edit, and Delete blog posts
- Store images in AWS S3
- MySQL database for storing blog content

## Tech Stack
- Go (Golang)
- AWS EC2
- AWS RDS (MySQL)
- AWS S3

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/minhnghia2k3/workshop-01.git
   cd workshop-01
   ```

2. Set environment variables:
   ```bash
   export DATABASE_URL="admin:Admin123@tcp(<YOUR_DB_ENDPOINT>:3306)/blog_db"
   export AWS_REGION="ap-southeast-1"
   export S3_BUCKET_NAME="your-s3-bucket-name"
   ```

3. Build and run the application:
   ```bash
   go build -o ./bin/main .
   ./bin/main
   ```

4. Access the app via EC2 instance's IP:
   ```
   http://<your-ec2-public-ip>:3000/
   ```

## Cleanup

After use, make sure to clean up AWS resources such as EC2, RDS, and S3 to avoid extra charges.