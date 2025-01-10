---
title : "Workshop Triển Khai Ứng Dụng Golang Trên EC2"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
---
# Workshop: Triển Khai Ứng Dụng Golang Trên EC2 Với MySQL RDS và S3

### Tổng quan

Trong workshop này, bạn sẽ học cách triển khai một ứng dụng Golang lên AWS EC2, sử dụng MySQL RDS làm cơ sở dữ liệu và S3 làm lưu trữ đối tượng.

![Workshop Architecture](/images/workshop_architecture.png)

### Mục tiêu:

- Hiểu cách tạo và cấu hình các dịch vụ AWS cơ bản.

- Kết nối và sử dụng MySQL RDS từ EC2.

- Tích hợp lưu trữ S3 vào ứng dụng Golang.

- Triển khai và chạy ứng dụng Golang trên môi trường AWS.

### Yêu cầu:

- Tài khoản AWS với quyền truy cập IAM.

- Kiến thức cơ bản về Golang và Linux command line.

- Một máy tính với SSH client (như Terminal hoặc PuTTY).

### Nội dung

 1. [Giới thiệu](1-introduce/)
 2. [Hạn chế quyền truy cập với IAM Service](2-restrict-access/)
 3. [Khởi tạo VPC](3-create-vpc-instance/)
 4. [Khởi tạo EC2 Instance](4-create-ec2-instance/)
 5. [Khởi tạo AWS Relational Database Service](5-create-rds-instance/)
 6. [Tạo S3 Bucket lưu trữ hình ảnh](6-create-s3-instance/)
 7. [Triển khai ứng dụng lên EC2](7-deploy-application-to-ec2/)
 8. [Dọn dẹp tài nguyên](8-clean-up/)



