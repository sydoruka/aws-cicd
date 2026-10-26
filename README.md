## Project Overview

This project demonstrates the usage of GitHub Actions CI/CD pipeline. When changes to the `/backend_rds`, `/backend_redis` or `/frontend` are made, the respective docker images are automatically created, uploaded to the ECR and deployed on EC2 instance.

## AWS Architecture

![Architecture Diagram](/images/Architecture.png)
