---
title: "Week 2 Worklog"
date: "2025-09-16"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives (per CloudJourney roadmap)
- Deepen storage knowledge with EFS, FSx, and migration tools (Module 3).
- Introduce compute services: EC2 advanced features, Auto Scaling Groups, and initial container concepts (Module 4).
- Integrate compute with existing VPC and storage setups.
- Update Hugo site with Week 2 logs and organize lab artifacts.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 3 — Storage advanced: Study EFS shared file systems, FSx for Windows/Linux, configure EFS for EC2 access. | 15/09/2025 | 15/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Tuesday | Module 3 — Labs: Set up EFS mount targets, FSx file shares, perform data migration using AWS MGN for storage workloads. | 16/09/2025 | 16/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Wednesday | Module 4 — Compute intro: Review EC2 instance types, launch templates, create Auto Scaling Groups integrated with VPC. | 17/09/2025 | 17/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thursday | Module 4 — Labs: Deploy EC2 ASG with load balancer, simulate scaling events, attach EBS volumes dynamically. | 18/09/2025 | 18/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Friday | Backup and restore practice: Test EFS backups with AWS Backup, review cost implications of storage/compute setups. | 19/09/2025 | 19/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3/4 |

### Results & Achievements (Week 2)
- Advanced storage configured: EFS mounted on multiple EC2 instances for shared access, FSx set up for managed file systems, MGN used for initial storage migration simulation.  
- Compute foundation built: ASG deployed with ELB for high availability, scaling policies tested under load, integrated with existing VPC and EBS/EFS.  
- Backup strategies implemented: Automated backups for EFS and EC2 volumes via AWS Backup, restore procedures verified.  
- Resource organization improved: Created a team guide on cleanup and cost optimization, shared via Hugo site.  
- Week 2 logs documented, screenshots of ASG scaling and EFS mounts added to repository.

### Issues Encountered & Mitigations
- EFS lab encountered mount permission errors → adjusted security groups and IAM roles for NFS access.  
- ASG scaling failed initially due to IAM policy gaps → added necessary EC2 and AutoScaling permissions.  
- Minor cost spikes from untagged resources → implemented tagging policies and reviewed with Cost Explorer.

### Next Steps (Week 3)
- Advance Module 4: Dive into ECS, EKS, and Lambda for containerized and serverless compute.  
- Begin databases: RDS setup and integration with compute services.  
- Experiment with basic monitoring using CloudWatch.  
- Prepare integration demo of storage-compute-database stack.