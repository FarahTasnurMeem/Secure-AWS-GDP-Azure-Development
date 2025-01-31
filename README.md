# Secure AWS/GCP/Azure Deployment

## Overview
Securing cloud deployments is crucial to protect data and services from unauthorized access and cyber threats. This guide walks you through setting up a secure cloud deployment on **AWS, GCP, and Azure**, implementing best security practices and essential configurations.

## Prerequisites
Before you begin, ensure you have:
- Basic knowledge of cloud computing
- An AWS, GCP, or Azure account
- A computer with internet access

---
## Step-by-Step Deployment Guide

### **Step 1: Secure AWS Deployment**

1. **Create an AWS Account**
   - Sign up at [AWS](https://aws.amazon.com/)

2. **Set Up IAM Users and Roles**
   - Navigate to IAM in the AWS Management Console
   - Create IAM users and assign appropriate group permissions
   - Enable **Multi-Factor Authentication (MFA)** for all users

3. **Secure S3 Buckets**
   - Create an S3 bucket
   - Configure bucket policies to restrict access
   - Enable **versioning**, **logging**, and **server-side encryption**

4. **Set Up VPC (Virtual Private Cloud)**
   - Create a VPC with subnets, route tables, and an internet gateway
   - Configure **security groups** and **network ACLs**

5. **Launch an EC2 Instance**
   - Choose an instance type and configure security groups
   - Enable **EBS volume encryption**
   - Use **SSH key pairs** for secure access

6. **Enable Cloud Monitoring & Logging**
   - Activate **CloudTrail** to log all API activity
   - Set up **CloudWatch** for monitoring and alerts

![AWS Screenshot 1](https://github.com/user-attachments/assets/4be04aa0-21cc-4e15-a878-3f7f963824fe)
![AWS Screenshot 2](https://github.com/user-attachments/assets/9c6d49cf-04e0-4202-a681-25c0c498e4f7)

---
### **Step 2: Secure GCP Deployment**

1. **Create a GCP Account**
   - Sign up at [Google Cloud](https://cloud.google.com/)

2. **Set Up IAM Users and Roles**
   - Navigate to IAM & Admin in Google Cloud Console
   - Assign roles following **least privilege principles**
   - Enable **MFA** for all users

3. **Secure Cloud Storage Buckets**
   - Create a bucket with **restricted permissions**
   - Enable **logging, versioning, and encryption**

4. **Set Up VPC**
   - Configure a **VPC Network** with subnets and firewall rules

5. **Launch a VM Instance**
   - Choose a machine type and configure firewall rules
   - Enable **disk encryption**

6. **Enable Cloud Audit Logs & Monitoring**
   - Activate **Cloud Audit Logs**
   - Use **Stackdriver Monitoring** for alerts

![GCP Screenshot 1](https://github.com/user-attachments/assets/b983ffda-4e3a-4034-a955-b5ca61b76dd5)
![GCP Screenshot 2](https://github.com/user-attachments/assets/864c1210-e058-4b95-9746-c17e70cde57f)

---
### **Step 3: Secure Azure Deployment**

1. **Create an Azure Account**
   - Sign up at [Azure](https://azure.microsoft.com/)

2. **Set Up IAM Users and Roles**
   - Use **Azure Active Directory** to create users and groups
   - Assign appropriate roles and enable **MFA**

3. **Secure Blob Storage**
   - Create a storage account with restricted access policies
   - Enable **logging, versioning, and encryption**

4. **Set Up Virtual Network (VNet)**
   - Configure **subnets, route tables, and network security groups**

5. **Launch a Virtual Machine**
   - Configure an Azure VM with network security rules
   - Enable **disk encryption**

6. **Enable Monitoring & Security**
   - Use **Azure Monitor** to track resources
   - Activate **Azure Security Center** for security posture assessment

![Azure Screenshot 1](https://github.com/user-attachments/assets/6a711e02-5807-450f-b9c7-86b71fa8698e)
![Azure Screenshot 2](https://github.com/user-attachments/assets/6d59f3ab-090a-493a-b1e1-37a5d1901724)

---
### **Step 4: Documentation**

- **Configuration Details:** Document IAM roles, VPC/VNet settings, and security policies
- **Security Measures:** List encryption settings, access controls, and monitoring setups
- **Usage Instructions:** Include steps for accessing and maintaining your cloud deployment

![VPC Chart 1](https://github.com/user-attachments/assets/d4712496-d7ac-4145-9752-3eac9a310fb6)
![VPC Chart 2](https://github.com/user-attachments/assets/ced12315-281d-4570-b6e4-c65f699b6e87)

![Screen 5 - Example](https://github.com/user-attachments/assets/09bf0384-db6e-438d-a9ed-5a72d4e05835)
![Screen 5 - Example](https://github.com/user-attachments/assets/0026a4c2-8d04-4520-b1a6-f82ad1c4aabf)
































---------------


6

![image](https://github.com/user-attachments/assets/4be04aa0-21cc-4e15-a878-3f7f963824fe)

![image](https://github.com/user-attachments/assets/9c6d49cf-04e0-4202-a681-25c0c498e4f7)

screenshot for 2:

![image](https://github.com/user-attachments/assets/b983ffda-4e3a-4034-a955-b5ca61b76dd5)

![image](https://github.com/user-attachments/assets/864c1210-e058-4b95-9746-c17e70cde57f)

screenshot for 3:

![image](https://github.com/user-attachments/assets/6a711e02-5807-450f-b9c7-86b71fa8698e)

![image](https://github.com/user-attachments/assets/6d59f3ab-090a-493a-b1e1-37a5d1901724)

4 Vpc chart ( subnet, route table &  

![image](https://github.com/user-attachments/assets/d4712496-d7ac-4145-9752-3eac9a310fb6)

![image](https://github.com/user-attachments/assets/ced12315-281d-4570-b6e4-c65f699b6e87)

 Screen for 5: 

![image](https://github.com/user-attachments/assets/09bf0384-db6e-438d-a9ed-5a72d4e05835)

![image](https://github.com/user-attachments/assets/0026a4c2-8d04-4520-b1a6-f82ad1c4aabf)


