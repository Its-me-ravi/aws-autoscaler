# AWS Auto Scaling Project

## Description
This project demonstrates AWS EC2 Auto Scaling using Launch Templates, Auto Scaling Groups (ASG), and CloudWatch Alarms — all configured through the AWS Console.

## Components Used
- EC2 Instances
- Launch Template
- Auto Scaling Group
- CloudWatch Alarm (CPU > 60%)
- Target Group (if load balancer used)

## Setup Process
1. Created Launch Template for EC2 with required AMI and User Data
2. Created Auto Scaling Group with min=1, max=3, desired=1
3. Added CloudWatch alarm to trigger scale-out and scale-in policies
4. Monitored scaling events in EC2 and CloudWatch

## Architecture
_A simple diagram can be added here later._

## Author
Ravi Kumar Choudhary
