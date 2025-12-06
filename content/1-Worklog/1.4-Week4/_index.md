---
title: "Week 4 Worklog"
date: "2025-09-30"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives (per CloudJourney roadmap)
- Expand databases: NoSQL DynamoDB, caching layers (Databases in Module 1).
- Enhance observability: Auditing with CloudTrail, tracing with X-Ray (Monitoring).
- Initial migration assessment tools (Transition to Module 2).
- Consolidate foundational services.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Databases — NoSQL: Design DynamoDB tables, provisioned vs on-demand capacity, global tables. | 29/09/2025 | 29/09/2025 | https://cloudjourney.awsstudygroup.com/ - Explore AWS Services |
| Tuesday | Labs: Create DynamoDB table, load data via Lambda, query with PartiQL. | 30/09/2025 | 30/09/2025 | https://cloudjourney.awsstudygroup.com/ - Databases Labs |
| Wednesday | Caching: Set up ElastiCache Redis, integrate with RDS/DynamoDB for read-heavy apps. | 01/10/2025 | 01/10/2025 | https://cloudjourney.awsstudygroup.com/ - Databases |
| Thursday | Monitoring advanced: Enable CloudTrail trails, integrate X-Ray with Lambda/ECS. | 02/10/2025 | 02/10/2025 | https://cloudjourney.awsstudygroup.com/ - Monitoring |
| Friday | Module 2 intro: Workload assessment using Migration Evaluator, plan simple lift-and-shift. | 03/10/2025 | 03/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |

### Results & Achievements (Week 4)
- DynamoDB mastered: Tables created with secondary indexes, data ingested, queries optimized for performance.  
- Caching layer added: Redis cluster reducing RDS load by 70% in test scenarios.  
- Observability stack complete: CloudTrail logging API calls, X-Ray traces showing end-to-end latencies.  
- Migration planning initiated: Assessed sample on-prem workload, identified EC2 equivalents.  
- Foundational services consolidated: Full stack (network-storage-compute-db-monitoring) documented.

### Issues Encountered & Mitigations
- DynamoDB provisioned capacity over-provisioned → switched to on-demand and monitored with CloudWatch.  
- X-Ray sampling rate too high → adjusted to 10% for cost control.  
- Migration Evaluator data upload slow → used direct connector for faster assessment.

### Next Steps (Week 5)
- Dive into Module 2: Server and application migration strategies.  
- Database migration with DMS.  
- Network connectivity for hybrid setups.  
- Review foundational knowledge with a mini-project.