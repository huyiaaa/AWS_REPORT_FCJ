---
title: "Week 9 Worklog"
date: "2025-11-04"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives (per CloudJourney roadmap)
- Microservices: Bounded contexts, decomposition of monolith (Module 4).
- Serverless: Event-driven with Lambda, Step Functions.
- API-first: REST/GraphQL design.
- DevOps integration.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 4 — Microservices: Study domain-driven design, decompose sample app into services. | 03/11/2025 | 03/11/2025 | https://cloudjourney.awsstudygroup.com/ - Modernize |
| Tuesday | Labs: Refactor monolith to ECS microservices, use API Gateway for routing. | 04/11/2025 | 04/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Wednesday | Serverless: Build workflow with Lambda and EventBridge rules. | 05/11/2025 | 05/11/2025 | https://cloudjourney.awsstudygroup.com/ - Modernize |
| Thursday | APIs: Create REST API with Gateway, GraphQL with AppSync. | 06/11/2025 | 06/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Friday | DevOps: Set up CI/CD with CodePipeline for microservices deployment. | 07/11/2025 | 07/11/2025 | https://cloudjourney.awsstudygroup.com/ - DevOps |

### Results & Achievements (Week 9)
- Monolith decomposed: 3 bounded services running independently on ECS, inter-service comms via SQS.  
- Event-driven app: Lambda orchestrating order processing, triggered by EventBridge.  
- APIs live: REST endpoints secured with Cognito, GraphQL schema with resolvers.  
- CI/CD automated: CodePipeline deploying updates, integrated with GitHub.  
- Modernization demo: End-to-end refactored app showcased to team.

### Issues Encountered & Mitigations
- Service discovery challenges → integrated Service Discovery with ECS.  
- EventBridge rule matching issues → debugged with CloudWatch Logs Insights.  
- Pipeline approval gates slow → automated for non-prod environments.

### Next Steps (Week 10)
- Module 5: Container orchestration with ECS/EKS.  
- Fargate for serverless containers.  
- Service mesh with App Mesh.  
- Security in containers.

> Note: All labs and content follow the CloudJourney curriculum at https://cloudjourney.awsstudygroup.com/. Ensure screenshots, logs, and scripts are stored in the project repository for verification.