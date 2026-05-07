# Secure Highly Available Web Application on AWS with WAF, Auto Scaling, and Monitoring

## 📌 Project Overview
This project demonstrates a secure and highly available AWS cloud architecture using load balancing, private subnet deployment, monitoring, and web application firewall protection.

The architecture is designed to simulate a production-style environment with scalability, security, and observability.

---

## 🏗️ Architecture

[Insert Architecture Diagram Here]

---

## 🚀 Technologies Used

- Amazon VPC
- Public & Private Subnets
- EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- AWS WAF
- Amazon CloudWatch
- Amazon S3
- IAM Roles

---

## 🔐 Key Features

- EC2 instances deployed inside private subnets
- Traffic routed through Application Load Balancer
- Auto Scaling Group for scalability and high availability
- AWS WAF protection against:
  - SQL Injection
  - XSS attacks
  - High-rate requests
- CloudWatch monitoring and alarms
- WAF logging stored in S3

---

## 🧠 Security Concepts Implemented

- Network isolation using private subnets
- Controlled traffic flow via ALB
- Web application firewall protection
- Monitoring and logging for visibility
- Rate limiting and malicious request filtering

---

## 📊 Monitoring & Logging

- CloudWatch metrics and alarms
- WAF request monitoring
- S3-based WAF log storage

---

## 🧪 Security Testing

The following attack simulations were tested:

### SQL Injection Test
```bash
?id=1' OR '1'='1