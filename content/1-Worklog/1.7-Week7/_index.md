---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---


## Week 7 Objectives

* Complete Lab14 and Lab15.
* Learn Amazon Elastic Container Service (Amazon ECS).
* Understand container deployment using AWS Fargate.
* Deploy containerized applications from Amazon ECR to Amazon ECS.
* Learn how Application Load Balancer (ALB) distributes traffic.
* Explore AWS Cloud Map and Service Discovery.
* Understand the Blue/Green Deployment strategy.

---

## Tasks Completed This Week

| Day | Task | Start Date | Completion Date | Reference Material |
|------|------|------------|-----------------|--------------------|
| Monday | - Start Lab14.<br>- Learn Amazon ECS.<br>- Explore Clusters, Task Definitions, Tasks, and Services. | 01/06/2026 | 01/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Tuesday | - Learn AWS Fargate.<br>- Deploy containerized applications without managing EC2 instances.<br>- Compare ECS EC2 Launch Type and Fargate Launch Type. | 02/06/2026 | 02/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Wednesday | - Integrate Amazon ECS with Amazon ECR.<br>- Pull Docker Images from Amazon ECR.<br>- Deploy containerized applications to an ECS Cluster. | 03/06/2026 | 03/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thursday | - Start Lab15.<br>- Configure an Application Load Balancer.<br>- Create Target Groups and Listener Rules.<br>- Test application accessibility. | 04/06/2026 | 05/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Friday | - Learn AWS Cloud Map.<br>- Practice Service Discovery.<br>- Study Blue/Green Deployment.<br>- Observe application updates with minimal downtime. | 06/06/2026 | 06/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Sunday | - Complete Lab14 and Lab15.<br>- Review the week's knowledge.<br>- Prepare the study plan for Week 8. | 07/06/2026 | 07/06/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Achievements

* Successfully completed Lab14 and Lab15.
* Understood the architecture of containerized applications on AWS.
* Learned the core components of Amazon ECS:
  * Cluster.
  * Task Definition.
  * Task.
  * Service.

* Understood the differences between:
  * ECS using EC2 launch type.
  * ECS using AWS Fargate launch type.

* Successfully deployed containerized applications from Amazon ECR to Amazon ECS.
* Learned how Amazon ECS manages the lifecycle of containers automatically.
* Successfully configured:
  * Application Load Balancer.
  * Target Groups.
  * Listener Rules.

* Understood how ALB distributes traffic across multiple containers.
* Became familiar with AWS Cloud Map for service discovery.
* Learned how Blue/Green Deployment minimizes downtime during application updates.
* Understood the advantages of running containers on the serverless AWS Fargate platform.

---

## Challenges Encountered

* Initially found it difficult to distinguish between Task Definitions, Tasks, and Services in Amazon ECS.
* Configuring ECS Services together with ALB required multiple steps and careful configuration.
* AWS Cloud Map was a new concept that required additional study.
* Blue/Green Deployment involves several AWS services, making the deployment workflow more complex.

---

## Lessons Learned

* Containerization makes application deployment faster, more consistent, and easier to scale.
* AWS Fargate allows developers to run containers without managing EC2 instances, reducing operational overhead.
* Amazon ECS, Amazon ECR, and Application Load Balancer together provide a complete container deployment solution on AWS.
* Blue/Green Deployment is a modern deployment strategy that minimizes downtime and reduces deployment risks.
* AWS Cloud Map simplifies service discovery within distributed applications by allowing services to locate each other automatically.
