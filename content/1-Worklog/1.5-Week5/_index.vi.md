---
title: "Tuần 5 - Worklog"
date: "2025-10-07"
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu Tuần 5 (theo roadmap CloudJourney)
- Di chuyển máy chủ: Sử dụng AWS MGN và Server Migration Service (Module 2).  
- Mẫu di chuyển ứng dụng: Lift-and-shift lên EC2.  
- Thực hành replication và cutover.  
- Cập nhật quản lý chi phí cho tài nguyên đã di chuyển.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 2 — Di chuyển server: Nghiên cứu cấu hình AWS MGN, replication servers, thử nghiệm migration. | 06/10/2025 | 06/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thứ Ba | Lab: Cài agent MGN, migrate VM mẫu sang EC2, validate sau khi khởi chạy. | 07/10/2025 | 07/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 Labs |
| Thứ Tư | Lift-and-shift ứng dụng: Đóng gói app bằng SMS, deploy lên EC2, cấu hình các dependency. | 08/10/2025 | 08/10/2025 | https://cloudjourney.awsstudygroup.com/ - Migrate to AWS |
| Thứ Năm | Thực hành cutover: Thực hiện cutover thử nghiệm, cập nhật DNS, mô phỏng rollback. | 09/10/2025 | 09/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 2 |
| Thứ Sáu | Rà soát chi phí: Phân tích tài nguyên đã di chuyển bằng Cost Explorer, áp dụng savings plans. | 10/10/2025 | 10/10/2025 | https://cloudjourney.awsstudygroup.com/ - Cost Management |

### Kết quả & Thành tựu (Tuần 5)
- Migration VM thành công: MGN replicate server Windows/Linux sang EC2, ứng dụng kiểm tra sau cutover hoạt động.  
- Lift-and-shift hoàn tất: Ứng dụng legacy chạy trên EC2 với thay đổi tối thiểu, dependency đã được xử lý.  
- Quy trình rollback được ghi tài liệu: Thực hiện dry‑run cutover và chuyển lại traffic trong dưới 5 phút.  
- Tối ưu chi phí: Mua Reserved Instances cho fleet EC2 ổn định.  
- Mini‑project đánh giá: Hoàn thành migration end‑to‑end cho workload mẫu từ "on‑prem" lên AWS.

### Vấn đề gặp phải & Biện pháp khắc phục
- Agent MGN gặp sự cố kết nối → cấu hình rule outbound trên firewall mô phỏng on‑prem.  
- Dependency ứng dụng lỗi sau migrate → dùng SSM để patch và cấu hình tự động.  
- DNS propagation chậm trong cutover → dùng Route 53 health checks để failover nhanh hơn.

### Bước tiếp theo (Tuần 6)
- Di chuyển cơ sở dữ liệu với AWS DMS.  
- Kết nối mạng hybrid: Direct Connect / VPN.  
- Kiểm tra hậu migrate và tối ưu hóa.  
- Chuẩn bị cho module tối ưu hóa.