---
title: "Tuần 10 - Worklog"
date: "2025-11-11" 
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu Tuần 10 (theo roadmap CloudJourney)
- Container orchestration: Đi sâu vào ECS và EKS (Module 5).
- Container serverless với Fargate.
- Networking và scaling trong Kubernetes.
- Best practice bảo mật container.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 5 — ECS nâng cao: Mạng cluster, service discovery, triển khai blue‑green. | 10/11/2025 | 10/11/2025 | https://cloudjourney.awsstudygroup.com/ - Containers |
| Thứ Ba | Lab: Triển khai ứng dụng multi‑container trên ECS, tích hợp ALB và RDS. | 11/11/2025 | 11/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 5 Labs |
| Thứ Tư | EKS giới thiệu: Thiết lập managed node groups, triển khai Helm charts. | 12/11/2025 | 12/11/2025 | https://cloudjourney.awsstudygroup.com/ - Containers |
| Thứ Năm | Fargate: Chạy EKS pod trên Fargate, test scaling. | 13/11/2025 | 13/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 5 |
| Thứ Sáu | Bảo mật: Quét image với ECR, bảo vệ runtime với GuardDuty. | 14/11/2025 | 14/11/2025 | https://cloudjourney.awsstudygroup.com/ - Container Security |

### Kết quả & Thành tựu (Tuần 10)
- ECS sẵn sàng production: Triển khai blue‑green không downtime, service mesh qua App Mesh.
- Cluster EKS hoạt động: Workload Kubernetes triển khai, cấu hình autoscaling HPA.
- Hiệu quả Fargate: Pod serverless giảm gánh nặng quản lý, chi phí giảm 20%.
- Pipeline bảo mật: Quét image chặn lỗ hổng, GuardDuty cảnh báo bất thường.
- Containerized hiện đại: Microservices trước đã chuyển sang EKS.

### Vấn đề gặp phải & Biện pháp khắc phục
- EKS pod lập lịch thất bại → điều chỉnh node taints và affinities.
- Giới hạn mạng Fargate → dùng VPC CNI cho pod IP.
- False negative khi quét → cập nhật policy ECR cho bản quét mới nhất.

### Bước tiếp theo (Tuần 11)
- Module 6: Data lake với S3/Lake Formation.
- Pipeline ETL với Glue.
- Phân tích real‑time với Kinesis.
- Quản trị và trực quan hóa.

> Lưu ý: Mọi lab và nội dung tuân theo chương trình CloudJourney tại https://cloudjourney.awsstudygroup.com/. Đảm bảo ảnh chụp màn hình, logs và scripts được lưu trong repository dự án để kiểm chứng.