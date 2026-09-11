# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : Swetha A  Reg no :212224040343    Date :11/09/2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 

<img width="943" height="922" alt="638325117-bb11370e-29ba-4c0d-8029-8e7ed0e0044f" src="https://github.com/user-attachments/assets/22834790-a075-4771-b76a-5598ebbc6577" />

<img width="964" height="904" alt="638325242-5db0b907-ea07-4062-ba1d-8e68e4f0ba46" src="https://github.com/user-attachments/assets/deb1eeb8-07d8-4ed9-a931-38a4b16a3b8f" />

<img width="948" height="664" alt="638325374-1f0c34da-2b0b-4df3-a6c4-832dadd91a4e" src="https://github.com/user-attachments/assets/4df7173b-d162-44de-bb0f-397234249b1e" />

<img width="947" height="915" alt="638325471-11ecd7ae-0fba-4754-9373-004af47e3206" src="https://github.com/user-attachments/assets/2955c22d-1ba4-4384-b8af-c7d9840fc016" />



---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
