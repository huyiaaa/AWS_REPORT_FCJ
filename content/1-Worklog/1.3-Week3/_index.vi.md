---
title: "Tuần 3 - Worklog"
date: "2025-09-23"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu Tuần 3 (theo roadmap CloudJourney)
- Khám phá compute nâng cao: Container bằng ECS/EKS và serverless với Lambda (Module 4).  
- Giới thiệu cơ sở dữ liệu quan hệ: triển khai RDS, cấu hình Multi‑AZ và sao lưu.  
- Tích hợp dịch vụ với mạng và lưu trữ đã thiết lập.  
- Nâng cấp giám sát cơ bản với CloudWatch.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 4 — Container: Học task definition ECS, Fargate; deploy ứng dụng container đơn giản. | 22/09/2025 | 22/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thứ Ba | Module 4 — Lab: Tạo cluster ECS, chạy task từ ECR, tích hợp với ALB. | 23/09/2025 | 23/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Thứ Tư | Module 4 — Serverless: Viết Lambda, cấu hình trigger từ S3, tích hợp API Gateway. | 24/09/2025 | 24/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thứ Năm | Cơ sở dữ liệu — RDS: Provision RDS (MySQL/Postgres), kết nối từ EC2, bật Multi‑AZ và snapshots tự động. | 25/09/2025 | 25/09/2025 | https://cloudjourney.awsstudygroup.com/ - Explore AWS Services |
| Thứ Sáu | Giám sát cơ bản: Thiết lập CloudWatch alarms cho EC2 CPU, RDS storage; ghi log Lambda. | 26/09/2025 | 26/09/2025 | https://cloudjourney.awsstudygroup.com/ - Monitoring |

### Kết quả & Thành tựu (Tuần 3)
- Ứng dụng container chạy: Cluster ECS Fargate phục vụ web app, tích hợp ALB, image đẩy lên ECR.  
- Luồng serverless hoạt động: Lambda kích hoạt khi upload S3, API Gateway cung cấp endpoint REST.  
- RDS hoạt động: Tạo instance MySQL Multi‑AZ, app trên EC2 kết nối thành công, snapshot tự động cấu hình.  
- Giám sát cơ bản: Dashboard CloudWatch cho các chỉ số chính; cảnh báo gửi qua SNS.  
- Chuẩn bị demo tích hợp: Stack mẫu EC2–Lambda–RDS–CloudWatch.

### Vấn đề gặp phải & Biện pháp khắc phục
- ECS không kéo image → kiểm tra và sửa quyền ECR và VPC endpoint.  
- Lambda cold start ảnh hưởng hiệu năng → tối ưu code và tăng memory.  
- Kết nối RDS timeout → cập nhật Security Group cho phép traffic từ subnet EC2.

### Bước tiếp theo (Tuần 4)
- Sâu hơn về cơ sở dữ liệu NoSQL: DynamoDB và caching với ElastiCache.  
- Mở rộng giám sát: bật CloudTrail để audit, tích hợp X‑Ray cho tracing.  
- Bắt đầu lên kế hoạch migration theo Module 2.  
- Tài liệu hóa các pattern tích hợp trên Hugo.