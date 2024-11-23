![Folie1](https://github.com/user-attachments/assets/a3e4a803-128c-467d-8299-83a5807ad906)

# Secure Cloud Infrastructure with High Availability and Security

## Overview

This project demonstrates the design and deployment of a highly available, secure, and scalable cloud infrastructure on AWS. The architecture follows industry best practices for security and availability, integrating multi-tier architecture with advanced security controls.

## Objectives

**The project focuses on the following security and availability goals:**

  - Network Segmentation: Separation of public and private subnets to protect sensitive data.
  - Multi-layered Security: Implementation of security groups and network ACLs for traffic control.
  - Access Control: Restricting access to resources via a bastion host.
  - Data Encryption: Ensuring secure data transmission and storage using SSL/TLS.
  - Monitoring: Utilizing AWS CloudWatch for activity monitoring and logging.

## High Availability

  - Auto Scaling & Load Balancing: Ensures fault tolerance and consistent availability of services.
  - Multi-AZ RDS Deployment: Provides database redundancy and automatic failover in case of failures.

## Security Aspects

  - VPC Isolation: Protects resources from direct exposure to the Internet.
  - Bastion Host: Limits SSH access to authorized users.
  - Encryption: Implements data encryption in transit (SSL/TLS) and at rest.
