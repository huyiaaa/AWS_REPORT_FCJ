---
title: "Tuần 2 - Worklog"
date: "2025-09-16"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu Tuần 2 (theo roadmap CloudJourney)
- Nâng cao kiến thức lưu trữ: EFS, FSx và công cụ migration (Module 3).  
- Giới thiệu dịch vụ compute: EC2 nâng cao, Auto Scaling Groups, khái niệm container ban đầu (Module 4).  
- Tích hợp compute với VPC và cấu hình lưu trữ đã tạo.  
- Cập nhật Hugo với worklog Tuần 2 và tổ chức các artefact lab.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 3 — Lưu trữ nâng cao: Học EFS (shared file systems), FSx cho Windows/Linux, cấu hình EFS cho EC2. | 15/09/2025 | 15/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Thứ Ba | Module 3 — Lab: Tạo EFS mount targets, cấu hình FSx file shares, mô phỏng di chuyển dữ liệu bằng AWS MGN. | 16/09/2025 | 16/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Thứ Tư | Module 4 — Giới thiệu compute: Xem lại loại EC2, launch templates, tạo Auto Scaling Groups tích hợp VPC. | 17/09/2025 | 17/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 |
| Thứ Năm | Module 4 — Lab: Triển khai ASG với Load Balancer, mô phỏng sự kiện scale, gắn EBS động cho instance. | 18/09/2025 | 18/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 4 Labs |
| Thứ Sáu | Thực hành backup & restore: Kiểm tra backup EFS bằng AWS Backup, đánh giá chi phí lưu trữ và compute. | 19/09/2025 | 19/09/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3/4 |

### Kết quả & Thành tựu (Tuần 2)
- Lưu trữ nâng cao: EFS mount trên nhiều EC2 để chia sẻ dữ liệu, FSx cấu hình cho file system quản lý, đã thử mô phỏng migration bằng MGN.  
- Kiến trúc compute: ASG triển khai cùng ELB, chính sách scale kiểm tra thành công, tích hợp với VPC và EBS/EFS.  
- Chiến lược backup: Thiết lập backup tự động cho EFS và volume EC2 bằng AWS Backup, đã thử restore.  
- Tổ chức tài nguyên tốt hơn: Hướng dẫn dọn dẹp/tối ưu chi phí được tạo và chia sẻ trên Hugo.  
- Worklog Tuần 2 đã ghi; ảnh chụp màn hình ASG scale và EFS mounts lưu vào repository.

### Vấn đề gặp phải & Biện pháp khắc phục
- Lỗi mount EFS do permission → điều chỉnh Security Group và IAM role cho truy cập NFS.  
- ASG không scale do thiếu IAM policy → bổ sung quyền cho EC2 và AutoScaling.  
- Chi phí tăng nhẹ do resources chưa tag → áp dụng chính sách tag và rà soát bằng Cost Explorer.

### Bước tiếp theo (Tuần 3)
- Tiếp sâu Module 4: ECS, EKS và Lambda cho compute container/serverless.  
- Bắt đầu phần cơ sở dữ liệu: triển khai RDS và tích hợp với compute.  
- Thử nghiệm giám sát cơ bản bằng CloudWatch.  
- Chuẩn bị demo tích hợp storage-compute-database.