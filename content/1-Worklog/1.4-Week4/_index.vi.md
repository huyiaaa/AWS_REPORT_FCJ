---
title: "Tuần 4 - Worklog"
date: "2025-09-30"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu Tuần 4 (theo roadmap CloudJourney)
- Mở rộng về cơ sở dữ liệu: NoSQL với DynamoDB và tầng cache (Databases).  
- Nâng cao khả năng quan sát: audit bằng CloudTrail, tracing bằng X‑Ray.  
- Đánh giá di trú ban đầu và công cụ hỗ trợ (bắt đầu Module 2).  
- Củng cố các dịch vụ nền tảng đã triển khai.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Databases — NoSQL: Thiết kế bảng DynamoDB, cân nhắc provisioned vs on‑demand, global tables. | 29/09/2025 | 29/09/2025 | https://cloudjourney.awsstudygroup.com/ - Explore AWS Services |
| Thứ Ba | Lab: Tạo bảng DynamoDB, nạp dữ liệu qua Lambda, truy vấn bằng PartiQL. | 30/09/2025 | 30/09/2025 | https://cloudjourney.awsstudygroup.com/ - Databases Labs |
| Thứ Tư | Caching: Thiết lập ElastiCache (Redis), tích hợp với RDS/DynamoDB cho ứng dụng đọc nhiều. | 01/10/2025 | 01/10/2025 | https://cloudjourney.awsstudygroup.com/ - Databases |
| Thứ Năm | Giám sát nâng cao: Bật CloudTrail trails, tích hợp X‑Ray với Lambda/ECS. | 02/10/2025 | 02/10/2025 | https://cloudjourney.awsstudygroup.com/ - Monitoring |
| Thứ Sáu | Module 2 intro: Đánh giá workload bằng Migration Evaluator, lập kế hoạch lift‑and‑shift đơn giản. | 03/10/2025 | 03/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |

### Kết quả & Thành tựu (Tuần 4)
- Làm chủ DynamoDB: Tạo bảng với secondary indexes, nạp dữ liệu và tối ưu truy vấn.  
- Thêm tầng cache: Redis giảm tải RDS ~70% trong kịch bản test.  
- Hoàn thiện observability: CloudTrail ghi nhận API call; X‑Ray hiển thị latency end‑to‑end.  
- Bắt đầu lập kế hoạch di trú: Đánh giá workload on‑prem mẫu, xác định loại EC2 tương đương.  
- Củng cố dịch vụ nền tảng: Tài liệu hóa full‑stack (network‑storage‑compute‑db‑monitoring).

### Vấn đề gặp phải & Biện pháp khắc phục
- Provisioned capacity cho DynamoDB bị provision quá mức → chuyển sang on‑demand và giám sát bằng CloudWatch.  
- Tỷ lệ sampling X‑Ray quá cao → điều chỉnh về 10% để tiết kiệm chi phí.  
- Tải lên dữ liệu cho Migration Evaluator chậm → sử dụng connector trực tiếp để tăng tốc.

### Bước tiếp theo (Tuần 5)
- Đi sâu Module 2: Chiến lược migration cho server và ứng dụng.  
- Thực hành di chuyển database với DMS.  
- Thiết lập kết nối mạng cho kịch bản hybrid.  
- Ôn lại kiến thức nền bằng một mini‑project.