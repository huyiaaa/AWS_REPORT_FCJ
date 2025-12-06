---
title: "Week 7 Worklog"
date: "2025-10-21"
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives (per CloudJourney roadmap)
- Cost optimization: Right-sizing, Compute Optimizer (Module 3).
- Performance efficiency: Auto-scaling, caching refinements.
- Initial security: GuardDuty threat detection.
- Operational excellence basics: Automation with SSM.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 3 — Cost opt: Analyze usage with Cost Explorer, recommendations from Compute Optimizer. | 20/10/2025 | 20/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Tuesday | Labs: Right-size EC2 instances, purchase Savings Plans, set up budgets. | 21/10/2025 | 21/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Wednesday | Performance: Refine ASG policies, implement ElastiCache for app caching. | 22/10/2025 | 22/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thursday | Security intro: Enable GuardDuty, review findings, integrate with EventBridge. | 23/10/2025 | 23/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Friday | Automation: Use SSM for patching EC2 fleet, document runbooks. | 24/10/2025 | 24/10/2025 | https://cloudjourney.awsstudygroup.com/ - Operational Excellence |

### Results & Achievements (Week 7)
- Costs reduced by 25%: EC2 right-sized, Savings Plans applied, anomaly detection alerts set.  
- Performance improved: ASG responding in <1min, caching hitting 80% success rate.  
- Threat detection active: GuardDuty scanning logs, simulated threats triaged.  
- Automation streamlined: SSM automating weekly patches, runbooks in Git repo.  
- Mid-journey cost analysis: Total spend tracked, optimizations yielding savings.

### Issues Encountered & Mitigations
- Compute Optimizer data lag → waited 48h for full recommendations.  
- GuardDuty false positives → tuned suppression rules based on environment.  
- SSM execution failures → granted additional IAM roles to instances.

### Next Steps (Week 8)
- Continue Module 3: Reliability with multi-AZ/DR, deeper security.  
- Fault tolerance patterns.  
- Prepare for modernization in Week 9.  
- Team sharing session on optimizations.