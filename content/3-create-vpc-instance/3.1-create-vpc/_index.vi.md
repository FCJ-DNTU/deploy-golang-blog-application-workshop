---
title : "Khởi tạo VPC Instance"
date :  "`r Sys.Date()`"
weight : 1
chapter : false
pre : "<b>3.1. </b>"
---

#### Khởi tạo VPC Instance
Ở section này chúng ta sẽ khởi tạo **VPC Instance**, bao gồm 2 **AZ**, 2 Public Subnets, 2 Private Subnets

#### 1. Tạo VPC Instance 
- Truy cập [Your VPCs](https://ap-southeast-1.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-1#vpcs:), Create VPC
- Tại **VPC Settings**, chọn option **VPC and more**


![create-vpc](/images/3-create-vpc-instance/create-vpc.png)
- Đặt tên **name tag** và để mặc định các field khác, chọn **Create VPC**
![create-vpc-done](/images/3-create-vpc-instance/create-vpc-done.png)
- Kết quả tạo VPC Instance thành công
![review-result](/images/3-create-vpc-instance/review-result.png)

#### 2. Tiếp theo chúng ta sẽ gán Public IP4 cho các public subnet
- Truy cập [Subnets](https://ap-southeast-1.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-1#subnets:)
- Chọn **Subnet ID** của public subnet e.g. **deploy-golang-workshop-subnet-public1-ap-southeast-1a**
![subnets](/images/3-create-vpc-instance/subnets.png)
- Chọn dropdown **Actions**, **Edit subnet settings**
![edit-subnet](/images/3-create-vpc-instance/edit-subnet.png)
- Tích vào **Enable auto-assign public IPv4 address**, Save
![enable-ipv4](/images/3-create-vpc-instance/enable-ipv4.png)
- Hoàn thành gán Public IPv4 cho một public subnet **deploy-golang-workshop-subnet-public1-ap-southeast-1a**
![complete](/images/3-create-vpc-instance/complete.png)
