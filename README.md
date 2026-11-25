# AWS-Cloud-File-Storage
AWS EC2, S3, IAM and RDS Hands-on Project
# AWS Cloud File Storage & Database Integration

## Project Overview
This project demonstrates an AWS cloud infrastructure setup using EC2, IAM, Amazon S3, and Amazon RDS. It focuses on secure access, cloud storage, server configuration, and database connectivity.

## Architecture
- **Amazon EC2:** Hosts the Linux server and application environment.
- **AWS IAM Role:** Allows EC2 to access AWS services without hardcoded access keys.
- **Amazon S3:** Stores files and images.
- **Amazon RDS (MySQL):** Managed relational database service.

## Technologies Used
- AWS EC2
- Amazon S3
- AWS IAM
- Amazon RDS (MySQL)
- Linux / Ubuntu
- Java
- Git & GitHub

## Implementation Plan
1. Launch and configure an Ubuntu EC2 instance.
2. Create and attach an IAM role to EC2.
3. Configure S3 bucket access through IAM role permissions.
4. Upload and manage files in Amazon S3.
5. Create an Amazon RDS MySQL database.
6. Configure secure connectivity between EC2 and RDS.
7. Integrate file upload using AWS SDK for Java.
8. Document deployment and configuration steps.

## Security
- IAM roles instead of hardcoded AWS access keys.
- Restricted inbound access using security groups.
- RDS access limited to the EC2 security group.
- No credentials stored in GitHub.

## Project Status
🚧 In Progress

## Author
Dileep
