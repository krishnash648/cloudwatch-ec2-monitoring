# EC2 Monitoring & Alerts using AWS CloudWatch

This project demonstrates how to monitor an Amazon EC2 instance using AWS CloudWatch and configure automated alerts using SNS.

## 🔧 Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- Amazon Linux 2023

## 📌 What I Implemented
- Launched an EC2 instance
- Monitored CPU utilization using CloudWatch metrics
- Created a threshold-based alarm (CPU > 70%)
- Configured SNS email notifications
- Tested the alarm by generating CPU load
- Cleaned up resources to avoid unnecessary costs

## 📊 Monitoring
The CPUUtilization metric was tracked in CloudWatch using a 5-minute average period.

## 🚨 Alerts
An alarm was configured to trigger when CPU usage exceeded 70%, sending an email notification via SNS.

## 🧠 Key Learnings
- Understanding EC2 performance metrics
- Real-time monitoring using CloudWatch
- Alerting and notification workflows
- Safe AWS resource cleanup

## 📷 Screenshots
Screenshots of the EC2 instance, CloudWatch metrics, and alarm configuration are included in the repository.
