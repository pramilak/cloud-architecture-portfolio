# Highly Available AWS Application Platform (Sanitized)

## Overview
This project represents a sanitized AWS architecture designed for client workloads, focusing on high availability, scalability, and security. Client-specific details are omitted due to NDAs.

## Architecture Components
- Amazon VPC with multi-AZ public and private subnets
- EC2 Auto Scaling Groups
- Application Load Balancer (HTTPS)
- Amazon RDS (Multi-AZ)
- IAM roles and policies
- AWS KMS and ACM
- Amazon CloudWatch

## Key Design Decisions
- Private subnets for application and database tiers
- Auto Scaling for fault tolerance and elasticity
- IAM role-based access (no static credentials)
- Encryption at rest and in transit

## Monitoring & Reliability
- CloudWatch metrics, logs, and alarms
- Health checks and automated instance replacement
