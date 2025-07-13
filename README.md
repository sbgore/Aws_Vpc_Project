# Aws_Vpc_Project
Building  Architecture of AWS Public/Private Subnet
# 🏗️ Production-Ready VPC with ALB, Auto Scaling, and NAT Gateways

This project demonstrates how to create a highly available, secure, and scalable **Virtual Private Cloud (VPC)** architecture using AWS services. The setup is suitable for deploying web applications in a **production environment** across multiple **Availability Zones (AZs)**.

---

## 📦 Architecture Overview

- **VPC with public and private subnets**
- **Auto Scaling Group (ASG)** with EC2 instances in **private subnets**
- **Application Load Balancer (ALB)** in public subnets to receive incoming traffic
- **NAT Gateways in both AZs** to allow outbound internet access from private subnets
- **High Availability** and **fault tolerance** using multiple AZs

---

## ✅ Features

- Multi-AZ deployment for high availability
- EC2 instances in **private subnets** for improved security
- ALB to distribute incoming traffic across instances
- NAT gateways in **each AZ** to avoid single points of failure
- Uses **Auto Scaling** to adjust capacity based on demand
