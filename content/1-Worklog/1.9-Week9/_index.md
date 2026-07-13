---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

## Week 9 Objectives

* Begin implementing the internship project.
* Set up the development and deployment environment on AWS.
* Build the AWS infrastructure based on the designed architecture.
* Deploy the core components of the system.
* Configure the database and connect it to the application.
* Verify the basic functionality of the system.

---

## Tasks Completed This Week

| Day | Task | Start Date | Completion Date | Reference Material |
|------|------|------------|-----------------|--------------------|
| Monday | - Initialize the project.<br>- Create the source code repository.<br>- Configure the development environment and Git repository. | 15/06/2026 | 15/06/2026 | https://git-scm.com/docs |
| Tuesday | - Deploy the AWS infrastructure.<br>- Create a VPC, Public Subnet, Security Groups, and EC2 Instance.<br>- Verify server connectivity. | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html |
| Wednesday | - Create an Amazon RDS database.<br>- Configure the connection between EC2 and RDS.<br>- Initialize the project database. | 17/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html |
| Thursday | - Deploy the backend application to EC2.<br>- Configure the runtime environment.<br>- Test the database connection. | 18/06/2026 | 19/06/2026 | https://docs.spring.io/spring-boot/index.html |
| Friday | - Deploy the frontend application.<br>- Test communication between the frontend and backend.<br>- Perform basic functional testing. | 20/06/2026 | 20/06/2026 | https://react.dev/ |
| Sunday | - Summarize deployment results.<br>- Record issues encountered during implementation.<br>- Prepare the development plan for the following week. | 21/06/2026 | 21/06/2026 | https://www.atlassian.com/software/confluence/guides |

---

## Achievements

* Successfully initialized the internship project.
* Set up the complete development environment.
* Built the initial AWS infrastructure, including:
  * Amazon VPC.
  * Public Subnet.
  * Security Groups.
  * Amazon EC2.
  * Amazon RDS.

* Successfully connected EC2 to Amazon RDS.
* Initialized the application database.
* Deployed the first version of the backend application on Amazon EC2.
* Configured the application runtime environment.
* Deployed the frontend application and verified communication with the backend.
* Successfully tested the core system functionalities.
* Completed technical notes documenting the deployment process and areas for future improvement.

---

## Challenges Encountered

* Deploying the backend application on EC2 required resolving several dependency and environment configuration issues.
* The connection between the backend application and Amazon RDS initially failed because of incorrect Security Group configuration.
* Deploying the frontend and backend separately required proper Cross-Origin Resource Sharing (CORS) configuration.
* Several deployment issues required log analysis to identify their root causes.

---

## Lessons Learned

* Preparing the deployment environment beforehand significantly reduces troubleshooting time.
* A well-designed system architecture makes implementation much smoother.
* Always verify networking and Security Group settings before troubleshooting application connectivity.
* Documenting deployment steps makes it easier to recreate the environment when necessary.
* Reviewing application logs is one of the most effective ways to identify deployment issues quickly.
