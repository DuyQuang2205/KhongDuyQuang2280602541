---
title: "Week 2 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

## Week 2 Objectives

* Complete Lab04, Lab05, and Lab06.
* Understand how to deploy a web application on AWS.
* Learn the basic concept of multi-tier architecture.
* Understand Elastic Load Balancer and traffic distribution.
* Learn how Auto Scaling Group works.
* Practice deploying Amazon RDS.
* Understand how to connect EC2 instances with Amazon RDS.
* Get familiar with Amazon CloudWatch for basic resource monitoring.

---

## Tasks Completed This Week

| Day | Task | Start Date | Completion Date | Reference Material |
|------|------|------------|-----------------|--------------------|
| Monday | - Review the knowledge learned in Week 1.<br>- Start Lab04.<br>- Learn the basic architecture of deploying a web application on AWS.<br>- Review VPC, Public Subnet, and Security Group concepts. | 27/04/2026 | 27/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Tuesday | - Continue Lab04.<br>- Launch an EC2 instance.<br>- Configure Security Group rules.<br>- Practice connecting to EC2 through SSH. | 28/04/2026 | 28/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Wednesday | - Complete Lab05.<br>- Learn about Amazon RDS.<br>- Create a MySQL database on Amazon RDS.<br>- Connect the EC2 instance to the RDS database and test the connection. | 29/04/2026 | 30/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Friday | - Start Lab06.<br>- Learn about Application Load Balancer.<br>- Configure Auto Scaling Group.<br>- Create a Launch Template for EC2 instances. | 01/05/2026 | 02/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Sunday | - Test Auto Scaling behavior.<br>- Monitor EC2 resources with Amazon CloudWatch.<br>- Review all implementation steps and complete Lab04, Lab05, and Lab06. | 03/05/2026 | 03/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Achievements

* Successfully completed Lab04, Lab05, and Lab06 according to the Bootcamp schedule.
* Understood the basic architecture of deploying a web application on AWS.
* Practiced important EC2 operations, including:
  * Launching an EC2 instance.
  * Configuring Security Groups.
  * Connecting to EC2 using SSH.
  * Managing Key Pairs.

* Learned how to deploy and use Amazon RDS, including:
  * Creating a MySQL database.
  * Configuring the database Security Group.
  * Connecting EC2 to RDS.
  * Testing database connectivity.

* Understood the basic operation of Elastic Load Balancer, including:
  * Traffic distribution.
  * Health Checks.
  * Target Groups.
  * High Availability.

* Learned the key components of Auto Scaling Group:
  * Launch Template.
  * Desired Capacity.
  * Minimum Capacity.
  * Maximum Capacity.
  * Scaling policies.

* Practiced monitoring AWS resources using Amazon CloudWatch:
  * CPU Utilization.
  * Network traffic.
  * EC2 instance status.
  * Basic monitoring metrics.

* Gained a better understanding of how multiple AWS services work together to build a scalable and highly available web system.

---

## Challenges Encountered

* At first, it was difficult to understand the relationship between VPC, Subnet, Route Table, and Security Group.
* The connection between EC2 and Amazon RDS failed at first because the MySQL port 3306 was not properly configured in the Security Group.
* Auto Scaling Group concepts such as Desired Capacity, Minimum Size, and Maximum Size required additional time to understand clearly.
* Reading and interpreting CloudWatch metrics was still challenging in the beginning.

---

## Lessons Learned

* Before deploying a system, it is important to draw or review the architecture diagram to understand how AWS services connect with each other.
* Security Groups play a critical role in AWS networking and should always be checked carefully when troubleshooting connection issues.
* Amazon RDS should be placed in a Private Subnet in real-world production environments for better security.
* Elastic Load Balancer and Auto Scaling Group are important components for building scalable and highly available systems.
* Amazon CloudWatch is useful for monitoring system performance and detecting issues early.
* Writing notes after each lab helps improve understanding and makes it easier to apply the knowledge to real projects.
