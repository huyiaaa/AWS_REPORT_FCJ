---
title: "Week 11 Worklog"
date: "2025-11-18"
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives (per CloudJourney roadmap)
- Data lake architecture: S3 partitioning, Lake Formation governance (Module 6).
- ETL/ELT: Glue jobs for data processing.
- Streaming: Kinesis for real-time ingestion.
- BI basics with QuickSight.

### Tasks This Week (by day)
| Day | Task | Start Date | Completion Date | Reference |
| --- | ---- | ---------- | --------------- | --------- |
| Monday | Module 6 — Data lake: Design S3-based lake, enable versioning, set up Lake Formation catalogs. | 17/11/2025 | 17/11/2025 | https://cloudjourney.awsstudygroup.com/ - Data & Analytics |
| Tuesday | Labs: Partition data in S3, grant permissions via Lake Formation. | 18/11/2025 | 18/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 6 Labs |
| Wednesday | ETL: Create Glue crawlers and jobs, transform CSV to Parquet. | 19/11/2025 | 19/11/2025 | https://cloudjourney.awsstudygroup.com/ - Data & Analytics |
| Thursday | Streaming: Set up Kinesis Data Streams, produce/consume events. | 20/11/2025 | 20/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 6 |
| Friday | Visualization: Connect QuickSight to S3/Glue, build dashboards. | 21/11/2025 | 21/11/2025 | https://cloudjourney.awsstudygroup.com/ - BI |

### Results & Achievements (Week 11)
- Data lake built: S3 organized with Athena queries, Lake Formation securing access.  
- ETL automated: Glue jobs processing 1M rows, output to S3 optimized formats.  
- Real-time pipeline: Kinesis streaming app logs, analytics with Kinesis Analytics.  
- Dashboards interactive: QuickSight visualizing ETL outputs, shared with team.  
- Data journey complete: From ingestion to insights, integrated with prior services.

### Issues Encountered & Mitigations
- Lake Formation permission propagation delays → used blueprints for faster setup.  
- Glue job memory errors → scaled DPU allocation.  
- Kinesis shard limits → monitored throughput and resharded.

### Next Steps (Week 12)
- Module 7: Intro to AI/ML with Bedrock, SageMaker basics.  
- Generative AI applications.  
- Capstone project review.  
- Final reflections and workforce program prep.

> Note: All labs and content follow the CloudJourney curriculum at https://cloudjourney.awsstudygroup.com/. Ensure screenshots, logs, and scripts are stored in the project repository for verification.