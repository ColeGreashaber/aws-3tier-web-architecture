# AWS 3-Tier Web Architecture

This project demonstrates a 3-tier web application deployed on AWS using EC2 and RDS.

## Architecture

Internet → Internet Gateway → VPC → Frontend EC2 → Backend EC2 → Amazon RDS

Frontend:
- EC2 instance
- Next.js application
- Port 3000

Backend:
- EC2 instance
- Node.js API
- Port 3001

Database:
- Amazon RDS MySQL
- Port 3306

## Architecture Diagram
![Architecture Diagram](diagrams/architecture-diagram.png)

## Infrastructure

### EC2 Instances
![EC2](screenshots/ec2-instance(b).png)
![EC2](screenshots/ec2instance(f).png)

### RDS Database
![RDS](screenshots/aws-rds-database-1.png)

### Security Groups
![Security Groups](
