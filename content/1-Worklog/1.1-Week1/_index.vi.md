---
title: "Tuần 1 - Worklog"
date: "2025-09-09"
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu Tuần 1 (theo roadmap CloudJourney)
- Hoàn thành thiết lập tài khoản và cấu hình bảo mật (Module 1).  
- Nắm vững kiến thức mạng cơ bản: VPC, Subnet, Route Table, Security Group (Module 2).  
- Thiết lập môi trường làm việc (Hugo) và ghi chép worklog bằng Markdown.  
- Hoàn thành các lab thực hành trên https://cloudjourney.awsstudygroup.com/ để kiểm chứng kết quả.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 1 — Thiết lập tài khoản & bảo mật: Tạo tài khoản AWS, bật MFA cho root, tạo user/group & policy cơ bản, cấu hình cảnh báo và ngân sách. | 08/09/2025 | 08/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 1 |
| Thứ Ba | Module 2 — Lý thuyết mạng: Học VPC, Subnet, Route Table, Security Group, ENI/EIP, ELB. Chuẩn bị môi trường Hugo. | 09/09/2025 | 09/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Thứ Tư | Module 2 — Lab: Tạo VPC, subnet public/private, khởi tạo EC2 trong subnet public, cấu hình Security Group, tạo NAT Gateway, SSH vào EC2. | 10/09/2025 | 10/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Thứ Năm | Module 2 — Tiếp lab: Thiết lập VPC Peering, cấu hình NACL, route table cross-VPC; điều chỉnh template (tối ưu loại instance). | 11/09/2025 | 11/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Thứ Sáu | Module 3 — Lưu trữ & lab: Phân biệt EBS vs Instance Store, hosting S3 tĩnh, versioning & replication, kế hoạch Backup & Restore; lab Storage Gateway. | 12/09/2025 | 12/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |

### Kết quả & Thành tựu (Tuần 1)
- Tài khoản AWS được tạo và bảo mật: bật MFA cho root, tạo user và group admin, cấu hình ngân sách và cảnh báo thanh toán.  
- Hoàn thành phần lý thuyết Module 2, nắm rõ VPC, Subnet, Route Table, Security Group và các mô hình kết nối phổ biến (NAT, Peering, Transit Gateway concept).  
- Thực hành lab: Khởi tạo EC2 và truy cập SSH, cấu hình Security Groups, tạo NAT Gateway và VPC Peering, áp dụng NACL, điều chỉnh template (thay đổi loại instance) để chạy được lab.  
- Hoàn tất lab lưu trữ: Hosting S3 tĩnh với versioning và replication; cấu hình Backup Plan/Vault; thiết lập Storage Gateway.  
- Khởi tạo site Hugo để báo cáo và ghi worklog bằng Markdown; sắp xếp file dự án.

### Vấn đề gặp phải & Cách giải quyết
- Lab ngân sách (Module 1, Lab 7-3) hiển thị dropdown loại sử dụng trống → đã ghi nhận, thử lại sau, sẽ báo support nếu vẫn lỗi.  
- Một số template lab thiếu rule cho Security Group → thêm rule tối thiểu (SSH/HTTP) để tiếp tục.  
- Tài nguyên chưa dọn dẹp gây phát sinh chi phí nhỏ → đã dọn sạch tài nguyên và bật cảnh báo thanh toán chặt chẽ hơn.

### Bước tiếp theo (Tuần 2)
- Tiếp tục Module 3: lab EFS/FSx và MGN; làm sâu phần lưu trữ và backup.  
- Bắt đầu Module 4: Compute (ECS/EKS/Lambda) và tích hợp vào hạ tầng mạng đã thiết lập.  
- Soạn hướng dẫn ngắn cho team về dọn dẹp tài nguyên và tối ưu chi phí.  
- Thu thập ảnh chụp màn hình, log và script vào thư mục dự án để nộp.
