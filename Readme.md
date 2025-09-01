# AWS Cloud Project

## Overview
This project demonstrates a scalable web application deployed on AWS using cloud infrastructure:

- **Frontend:** Hosted on S3 (Static Website Hosting)
- **Auto Scaling Group (ASG):** Manages EC2 instances automatically
- **Application Load Balancer (ALB):** Distributes traffic across instances
- **EC2 Instances:** Run the application or demonstration content


## livefrontend 
 [Clicl here!] (http://s3demo.jesal.s3-website.ap-south-1.amazonaws.com/)

## Features
- Frontend served from S3 bucket
- EC2 instances automatically scaled using ASG
- ALB distributes traffic for high availability 
- Demonstrates scalable cloud architecture

## Deployment Steps
1. Create S3 bucket and upload frontend files
2. Launch EC2 instances using Launch Template or AMI
3. Create Application Load Balancer and register target group
4. Create Auto Scaling Group with desired capacity
5. Test the system end-to-end via S3 website

## Project Screenshots  

- **S3 Website**  
  [Static website stored in S3 bucket](screenshots/s3.png)  

- **ALB Targets**  
  [ALB name and details](screenshots/elb1.png)  
  [Show instance health status](screenshots/elb2.png)  

- **ASG Instances**  
  [ASG name & capacity overview](screenshots/asg1.png)  
  [Availability zones & Activity](screenshots/asg2.png)  

- **EC2 Instances**  
  [EC2 Instances](screenshots/ec2.png)  

- **EC2 Template**  
  [Launch Template](screenshots/temp1.png)  

## Notes
- Frontend stored in cloud storage
- ASG automatically scales EC2 instances based on load
- No backend code required — fully cloud-based infrastructure








