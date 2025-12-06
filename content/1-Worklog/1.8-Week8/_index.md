---
title: "Week 8 Worklog"
date: "2025-10-28"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives (per CloudJourney roadmap)
- Reliability pillar: High availability, disaster recovery (Module 3).
- Advanced security: Zero-trust, compliance with Config.
- Incident response basics.
- Cross-pillar integration.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 3 — Reliability: Design multi-AZ architectures, RTO/RPO planning. | 27/10/2025 | 27/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Tuesday | Labs: Set up DR with Pilot Light strategy, test failover to secondary region. | 28/10/2025 | 28/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Wednesday | Security advanced: Implement zero-trust with IAM policies, enable AWS Config rules. | 29/10/2025 | 29/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thursday | Compliance: Audit resources with Config, remediate non-compliant items. | 30/10/2025 | 30/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Friday | Incident response: Simulate outage, use Incident Manager, document lessons. | 31/10/2025 | 31/10/2025 | https://cloudjourney.awsstudygroup.com/ - Operational Excellence |

### Results & Achievements (Week 8)
- HA/DR resilient: Multi-AZ RDS/ECS clusters, Pilot Light DR tested with <15min RTO.  
- Zero-trust enforced: Least-privilege IAM, Config conformance packs applied.  
- Compliance score 95%: Automated remediation for common rules like encryption.  
- IR playbook refined: Outage simulation resolved in 10min, integrated with PagerDuty.  
- Optimizations integrated: Security/reliability enhancing prior workloads.

### Issues Encountered & Mitigations
- DR cross-region latency → optimized with global Accelerator.  
- Config rule evaluation delays → increased evaluation frequency.  
- IR simulation alert fatigue → refined notification thresholds.

### Next Steps (Week 9)
- Transition to Module 4: Microservices decomposition.  
- Serverless patterns with Lambda/EventBridge.  
- API design with API Gateway/AppSync.  
- Modernization team demo.

> Note: All labs and content follow the CloudJourney curriculum at https://cloudjourney.awsstudygroup.com/. Ensure screenshots, logs, and scripts are stored in the project repository for verification.