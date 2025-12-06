---
title: "Week 3 Worklog"
date: "2025-09-23"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives (per CloudJourney roadmap)
- Explore advanced compute: Containers with ECS/EKS and serverless with Lambda (Module 4).
- Introduce relational databases: RDS setup, multi-AZ, backups (Databases in Module 1 Explore).
- Integrate services with prior networking and storage.
- Enhance monitoring with CloudWatch basics.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 4 — Containers intro: Study ECS task definitions, Fargate launch types; deploy simple container app. | 22/09/2025 | 22/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Tuesday | Module 4 — Labs: Create ECS cluster, run tasks with ECR images, integrate with ALB. | 23/09/2025 | 23/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Wednesday | Module 4 — Serverless: Lambda functions, triggers from S3/EC2, API Gateway integration. | 24/09/2025 | 24/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thursday | Databases — RDS: Provision RDS instance (MySQL/PostgreSQL), connect from EC2, enable multi-AZ. | 25/09/2025 | 25/09/2025 | https://cloudjourney.awsstudygroup.com/ - Explore AWS Services |
| Friday | Monitoring basics: Set up CloudWatch alarms for EC2 CPU, RDS storage; log Lambda invocations. | 26/09/2025 | 26/09/2025 | https://cloudjourney.awsstudygroup.com/ - Monitoring |

### Results & Achievements (Week 3)
- Containerized app deployed: ECS Fargate cluster running web app, scaled with ALB, images pushed to ECR.  
- Serverless workflow established: Lambda triggered by S3 uploads, integrated with API Gateway for REST endpoints.  
- RDS operational: Multi-AZ MySQL instance created, connected via EC2 app, automated snapshots configured.  
- Monitoring implemented: CloudWatch dashboards for key metrics, alarms notified via SNS.  
- Integration demo prepared: Simple app stack with EC2-Lambda-RDS-CloudWatch.

### Issues Encountered & Mitigations
- ECS task failed to pull image → verified ECR permissions and VPC endpoint setup.  
- Lambda cold starts impacted performance → optimized code and increased memory allocation.  
- RDS connection timeout → updated security groups to allow EC2 subnet traffic.

### Next Steps (Week 4)
- Deepen databases: NoSQL with DynamoDB, caching with ElastiCache.  
- Advance monitoring: CloudTrail for auditing, X-Ray for tracing.  
- Start migration planning from Module 2.  
- Document integration patterns in Hugo.