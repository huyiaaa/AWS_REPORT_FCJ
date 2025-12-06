---
title: "Week 6 Worklog"
date: "2025-10-14"
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives (per CloudJourney roadmap)
- Database migration: Schema conversion and data transfer with DMS (Module 2).
- Hybrid networking: VPN/Direct Connect setup.
- Post-migration tasks: Testing, optimization, cleanup.
- Risk mitigation strategies.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 2 — DB migration: Study DMS endpoints, replication instances, ongoing replication. | 13/10/2025 | 13/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Tuesday | Labs: Migrate MySQL to RDS PostgreSQL using DMS, validate data integrity. | 14/10/2025 | 14/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Wednesday | Hybrid networking: Create Client VPN endpoint, connect EC2 to "on-prem" VPC. | 15/10/2025 | 15/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thursday | Post-migration: Performance tuning, security scans, application testing. | 16/10/2025 | 16/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Friday | Risk management: Document rollback plans, simulate failures, review compliance. | 17/10/2025 | 17/10/2025 | https://cloudjourney.awsstudygroup.com/ - Risk Mitigation |

### Results & Achievements (Week 6)
- DB migrated seamlessly: DMS full load + CDC from on-prem MySQL to RDS, zero data loss verified.  
- Hybrid connectivity established: VPN allowing secure access between VPCs, latency under 50ms.  
- Post-migration optimized: Tuned RDS parameters, scanned for vulnerabilities with Inspector.  
- Risk framework built: Rollback playbook created, failure scenarios tested with Chaos Engineering basics.  
- Module 2 foundational migration complete, ready for optimization.

### Issues Encountered & Mitigations
- DMS schema conversion errors → used SCT tool for pre-conversion fixes.  
- VPN auth failures → enabled SAML integration for user access.  
- Post-migration query slowdown → indexed tables and enabled query caching.

### Next Steps (Week 7)
- Enter Module 3: Focus on cost optimization and performance efficiency.  
- Implement auto-scaling and right-sizing.  
- Begin security pillar with GuardDuty.  
- Analyze overall journey costs so far.