# AWS Static Website Deployment on EC2

## Overview

This project demonstrates the deployment of a secure static website on Amazon Web Services (AWS) using an Ubuntu Linux EC2 instance and Nginx as the web server.

The project showcases practical cloud engineering skills, including Linux server administration, AWS networking, SSH access, DNS configuration, and web server deployment.

---

## Project Architecture

> Insert your AWS architecture diagram here.

![Architecture](images/aws-architecture.png)

---

## Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2
- Ubuntu Linux
- Nginx
- Amazon VPC
- Route 53
- Security Groups
- SSH
- Git & GitHub

---

## Project Objectives

- Launch an EC2 instance
- Configure Ubuntu Linux
- Install and configure Nginx
- Deploy a static website
- Configure Security Groups
- Configure Route 53 DNS
- Verify successful deployment

---

## Architecture Components

- Internet
- Amazon Route 53
- Internet Gateway
- Amazon VPC
- Public Subnet
- Security Group
- Amazon EC2
- Ubuntu Linux
- Nginx Web Server
- Static Website

---

## Deployment Steps

### 1. Launch an EC2 Instance

- Selected Ubuntu Server
- Created a Key Pair
- Configured Security Groups
- Assigned a Public IP

---

### 2. Connect via SSH

```bash
ssh -i my-key.pem ubuntu@your-public-ip
