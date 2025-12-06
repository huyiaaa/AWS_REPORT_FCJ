---
title: "Week 1 Worklog"
date: "2025-09-09"
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Week 1 Objectives (per CloudJourney roadmap)
- Complete account setup and security configuration (Module 1).
- Master basic networking concepts: VPC, Subnet, Route Table, Security Group (Module 2).
- Set up the working environment (Hugo) and record logs in Markdown.
- Complete the hands-on labs on https://cloudjourney.awsstudygroup.com/ to verify work.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 1 — Account setup & security: Create AWS account, enable root MFA, create user groups & basic policies, configure billing alerts and budget. | 08/09/2025 | 08/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 1 |
| Tuesday | Module 2 — Networking theory: Study VPC, Subnet, Route Table, Security Group, ENI/EIP, ELB concepts. Prepare Hugo environment. | 09/09/2025 | 09/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Wednesday | Module 2 — Labs: Create a VPC, public/private subnets, launch EC2 in a public subnet, configure Security Groups, create a NAT Gateway, SSH into EC2. | 10/09/2025 | 10/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Thursday | Module 2 — Labs continued: Set up VPC Peering, configure NACLs, cross-VPC route tables; adjust templates (optimize instance types). | 11/09/2025 | 11/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Friday | Module 3 — Storage overview & labs: EBS vs Instance Store, S3 static site hosting, S3 versioning & replication, Backup Plan & Restore; Storage Gateway lab. | 12/09/2025 | 12/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |

### Results & Achievements (Week 1)
- AWS account created and secured: root MFA enabled, admin user & group created, budget and billing alerts configured.  
- Completed Module 2 theory and gained clear understanding of VPC, Subnet, Route Table, Security Group, and common connection patterns (NAT, Peering, Transit Gateway concepts).  
- Hands-on labs performed: EC2 launched and accessed via SSH, Security Groups configured, NAT Gateway and VPC Peering created, NACLs applied, and template issues resolved (adjusted instance types).  
- Storage labs completed: S3 static hosting with versioning and replication; Backup Plan/Vault configured; Storage Gateway set up.  
- Hugo site initialized for reporting and the weekly worklog recorded in Markdown; project files organized.

### Issues Encountered & Mitigations
- Module 1 budget lab (Lab 7-3) showed an empty usage-type dropdown → logged the issue, retried later, will escalate to lab support if it persists.  
- Some lab templates lacked Security Group rules → added minimal required rules (SSH/HTTP) to proceed.  
- Uncleaned resources caused minor unexpected charges → performed resource cleanup and enabled stricter billing alerts.

### Next Steps (Week 2)
- Continue Module 3: EFS/FSx and MGN labs; deepen storage and backup practice.  
- Start Module 4: Compute (ECS/EKS/Lambda) and integrate with the established networking setup.  
- Prepare a short guide for the team on resource cleanup and cost optimization.  
- Collect screenshots, logs, and scripts in the project folder for submission.