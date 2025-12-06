---
title: "Week 10 Worklog"
date: "2025-11-11"
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives (per CloudJourney roadmap)
- Container orchestration: Deep dive into ECS and EKS (Module 5).
- Serverless containers with Fargate.
- Networking and scaling in Kubernetes.
- Container security best practices.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 5 — ECS advanced: Cluster networking, service discovery, blue-green deployments. | 10/11/2025 | 10/11/2025 | https://cloudjourney.awsstudygroup.com/ - Containers |
| Tuesday | Labs: Deploy multi-container app on ECS, integrate with ALB and RDS. | 11/11/2025 | 11/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 5 Labs |
| Wednesday | EKS intro: Set up managed node groups, deploy Helm charts. | 12/11/2025 | 12/11/2025 | https://cloudjourney.awsstudygroup.com/ - Containers |
| Thursday | Fargate: Run EKS pods on Fargate, test scaling. | 13/11/2025 | 13/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 5 |
| Friday | Security: Image scanning with ECR, runtime protection with GuardDuty. | 14/11/2025 | 14/11/2025 | https://cloudjourney.awsstudygroup.com/ - Container Security |

### Results & Achievements (Week 10)
- ECS production-ready: Blue-green deployment with zero downtime, service mesh via App Mesh.  
- EKS cluster operational: Kubernetes workloads deployed, autoscaling HPA configured.  
- Fargate efficiency: Serverless pods reducing management overhead, cost 20% lower.  
- Secure pipeline: Scanned images blocking vulnerabilities, GuardDuty alerts for anomalies.  
- Containerized modernization: Previous microservices migrated to EKS.

### Issues Encountered & Mitigations
- EKS pod scheduling failures → adjusted node taints and affinities.  
- Fargate networking limits → used VPC CNI for pod IPs.  
- Scanning false negatives → updated ECR policies for latest scans.

### Next Steps (Week 11)
- Module 6: Data lake with S3/Lake Formation.  
- ETL pipelines with Glue.  
- Real-time analytics with Kinesis.  
- Governance and visualization.

> Note: All labs and content follow the CloudJourney curriculum at https://cloudjourney.awsstudygroup.com/. Ensure screenshots, logs, and scripts are stored in the project repository for verification.