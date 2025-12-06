---
title: "Tuần 9 - Worklog" 
date: "2025-11-04"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu Tuần 9 (theo roadmap CloudJourney)
- Microservices: Bounded contexts, phân tách monolith (Module 4).
- Serverless: Kiến trúc event‑driven với Lambda, Step Functions.
- API‑first: Thiết kế REST/GraphQL.
- Tích hợp DevOps.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 4 — Microservices: Học domain‑driven design, phân tách ứng dụng mẫu thành services. | 03/11/2025 | 03/11/2025 | https://cloudjourney.awsstudygroup.com/ - Modernize |
| Thứ Ba | Lab: Refactor monolith sang microservices trên ECS, dùng API Gateway cho routing. | 04/11/2025 | 04/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Thứ Tư | Serverless: Xây dựng workflow với Lambda và EventBridge rules. | 05/11/2025 | 05/11/2025 | https://cloudjourney.awsstudygroup.com/ - Modernize |
| Thứ Năm | APIs: Tạo REST API với Gateway, GraphQL với AppSync. | 06/11/2025 | 06/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thứ Sáu | DevOps: Thiết lập CI/CD với CodePipeline để triển khai microservices. | 07/11/2025 | 07/11/2025 | https://cloudjourney.awsstudygroup.com/ - DevOps |

### Kết quả & Thành tựu (Tuần 9)
- Phân tách monolith: 3 bounded service chạy độc lập trên ECS, giao tiếp qua SQS.
- Ứng dụng event‑driven: Lambda điều phối xử lý đơn hàng, kích hoạt bởi EventBridge.
- APIs hoạt động: Endpoint REST bảo mật bằng Cognito, schema GraphQL với resolvers.
- CI/CD tự động: CodePipeline triển khai cập nhật, tích hợp với GitHub.
- Demo hiện đại hóa: Trình diễn ứng dụng đã refactor end‑to‑end cho team.

### Vấn đề gặp phải & Biện pháp khắc phục
- Thách thức service discovery → tích hợp Service Discovery với ECS.
- Vấn đề khớp rule EventBridge → debug bằng CloudWatch Logs Insights.
- Cổng phê duyệt pipeline chậm → tự động hóa cho môi trường non‑prod.

### Bước tiếp theo (Tuần 10)
- Module 5: Container orchestration với ECS/EKS.
- Fargate cho serverless containers.
- Service mesh với App Mesh.
- Bảo mật trong containers.

> Lưu ý: Mọi lab và nội dung tuân theo chương trình CloudJourney tại https://cloudjourney.awsstudygroup.com/. Đảm bảo ảnh chụp màn hình, logs và scripts được lưu trong repository dự án để kiểm chứng.