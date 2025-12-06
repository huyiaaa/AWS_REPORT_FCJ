---
title: "Week 5 Worklog"
date: "2025-10-07"
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives (per CloudJourney roadmap)
- Server migration: Using AWS MGN and Server Migration Service (Module 2).
- Application migration patterns: Lift-and-shift to EC2.
- Hands-on replication and cutover.
- Update cost management with migrated resources.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 2 — Server migration: Study AWS MGN setup, replication servers, test migrations. | 06/10/2025 | 06/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Tuesday | Labs: Launch MGN replication agent, migrate sample VM to EC2, validate post-launch. | 07/10/2025 | 07/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Wednesday | Application lift-and-shift: Package app with SMS, deploy to EC2, configure dependencies. | 08/10/2025 | 08/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thursday | Cutover practice: Perform test cutover, DNS updates, rollback simulation. | 09/10/2025 | 09/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Friday | Cost review: Analyze migrated resources with Cost Explorer, apply savings plans. | 10/10/2025 | 10/10/2025 | https://cloudjourney.awsstudygroup.com/ - Cost Management |

### Results & Achievements (Week 5)
- Successful VM migration: MGN replicated Windows/Linux servers to EC2, tested applications post-cutover.  
- Lift-and-shift completed: Legacy app running on EC2 with minimal changes, dependencies resolved.  
- Rollback procedures documented: Dry-run cutover with traffic switchback in under 5 minutes.  
- Cost optimizations applied: Reserved Instances purchased for steady-state EC2 fleet.  
- Mini-project reviewed: End-to-end migration of a sample workload from "on-prem" to AWS.

### Issues Encountered & Mitigations
- MGN agent connectivity issues → configured outbound rules in on-prem firewall simulation.  
- App dependencies failed post-migration → used SSM for automated patching.  
- Cutover DNS propagation delay → implemented Route 53 health checks for faster failover.

### Next Steps (Week 6)
- Database migration with AWS DMS.  
- Hybrid network connectivity: Direct Connect/VPN.  
- Post-migration validation and optimization.  
- Prepare for optimization module.