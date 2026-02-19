# Dynamic Café Website on AWS (EC2, LAMP, AMI, Multi-Region)

## Project Overview
Deployed a dynamic café website on an Amazon EC2 instance using a LAMP stack.
The application allows customers to view a menu and place online orders.
Created an Amazon Machine Image (AMI) and deployed the same application in a second AWS Region for production.

## Architecture
- Development environment: EC2 instance (us-east-1)
- Production environment: EC2 instance (us-west-2)
- Web server: Apache
- Database: MariaDB
- Application language: PHP
- Secrets storage: AWS Secrets Manager

## Key Tasks Performed
- Connected to EC2 using VS Code IDE
- Configured Apache web server on port 8000
- Installed MariaDB database
- Deployed PHP café application
- Stored database credentials in AWS Secrets Manager
- Tested ordering functionality
- Created Amazon Machine Image (AMI)
- Launched second EC2 instance from AMI in another region

## Tools & Services Used
- AWS EC2
- AWS Secrets Manager
- Linux (Amazon Linux)
- Apache
- MariaDB (MySQL)
- PHP
- GitHub

## Outcome
Successfully deployed a dynamic website that supports online orders and runs in two AWS Regions (development and production).
