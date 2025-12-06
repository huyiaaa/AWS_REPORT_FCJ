// ...existing code...
---
title: "Tuần 6 - Worklog"
date: "2025-10-14"
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu Tuần 6 (theo roadmap CloudJourney)
- Di chuyển cơ sở dữ liệu: Chuyển đổi schema và dữ liệu bằng DMS (Module 2).  
- Mạng hybrid: Thiết lập VPN / Direct Connect.  
- Công việc hậu di chuyển: Kiểm thử, tối ưu, dọn dẹp.  
- Chiến lược giảm thiểu rủi ro.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 2 — Di chuyển DB: Nghiên cứu endpoint DMS, replication instance, và ongoing replication. | 13/10/2025 | 13/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thứ Ba | Lab: Di chuyển MySQL sang RDS PostgreSQL bằng DMS, xác thực toàn vẹn dữ liệu. | 14/10/2025 | 14/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Thứ Tư | Mạng hybrid: Tạo Client VPN endpoint, kết nối EC2 với VPC "on‑prem". | 15/10/2025 | 15/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thứ Năm | Hậu di chuyển: Tối ưu hiệu năng, quét bảo mật, kiểm thử ứng dụng. | 16/10/2025 | 16/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Thứ Sáu | Quản lý rủi ro: Ghi chép kế hoạch rollback, mô phỏng sự cố, rà soát compliance. | 17/10/2025 | 17/10/2025 | https://cloudjourney.awsstudygroup.com/ - Risk Mitigation |

### Kết quả & Thành tựu (Tuần 6)
- DB di chuyển thành công: DMS thực hiện full load + CDC từ MySQL on‑prem sang RDS, xác minh không mất dữ liệu.  
- Kết nối hybrid thiết lập: VPN cho phép truy cập an toàn giữa các VPC, độ trễ < 50ms.  
- Hậu di chuyển tối ưu: Điều chỉnh tham số RDS, quét lỗ hổng bằng Inspector.  
- Khung quản lý rủi ro: Tạo playbook rollback, thử nghiệm các kịch bản lỗi cơ bản (Chaos Engineering).  
- Hoàn thành nền tảng Module 2, sẵn sàng cho giai đoạn tối ưu hóa.

### Vấn đề gặp phải & Biện pháp khắc phục
- Lỗi chuyển đổi schema DMS → Sử dụng SCT để sửa trước khi chuyển.  
- Lỗi xác thực VPN → Kích hoạt tích hợp SAML cho xác thực người dùng.  
- Truy vấn chậm sau di chuyển → Thêm index và bật caching truy vấn.

### Bước tiếp theo (Tuần 7)
- Vào Module 3: Tập trung tối ưu chi phí và hiệu năng.  
- Triển khai auto‑scaling và right‑sizing.  
- Bắt đầu trạm bảo mật: bật GuardDuty.  
- Phân tích chi phí toàn hành trình đến hiện tại.
<!-- ...existing code... -->