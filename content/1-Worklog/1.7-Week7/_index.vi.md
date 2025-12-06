---
title: "Tuần 7 - Worklog"
date: "2025-10-21"
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu Tuần 7 (theo roadmap CloudJourney)
- Tối ưu chi phí: Right‑sizing, Compute Optimizer (Module 3).  
- Hiệu năng: Auto‑scaling và tinh chỉnh caching.  
- Bảo mật sơ bộ: Kích hoạt GuardDuty để phát hiện mối đe dọa.  
- Vận hành xuất sắc: Tự động hoá bằng SSM.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 3 — Tối ưu chi phí: Phân tích sử dụng với Cost Explorer, xem khuyến nghị từ Compute Optimizer. | 20/10/2025 | 20/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thứ Ba | Lab: Right‑size EC2, mua Savings Plans, thiết lập ngân sách (budgets). | 21/10/2025 | 21/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Thứ Tư | Hiệu năng: Tinh chỉnh chính sách ASG, triển khai ElastiCache cho caching ứng dụng. | 22/10/2025 | 22/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thứ Năm | Bảo mật sơ bộ: Bật GuardDuty, rà soát kết quả, tích hợp với EventBridge. | 23/10/2025 | 23/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Thứ Sáu | Tự động hoá: Dùng SSM để patch EC2 fleet, ghi lại runbook. | 24/10/2025 | 24/10/2025 | https://cloudjourney.awsstudygroup.com/ - Operational Excellence |

### Kết quả & Thành tựu (Tuần 7)
- Giảm chi phí 25%: Right‑size EC2, áp dụng Savings Plans, bật cảnh báo bất thường.  
- Hiệu năng cải thiện: ASG phản hồi trong <1 phút, cache đạt tỉ lệ hit ~80%.  
- Phát hiện mối đe dọa hoạt động: GuardDuty quét log, các thử nghiệm mối đe dọa được phân loại.  
- Tự động hoá: SSM thực hiện patch hàng tuần, runbook lưu trong repo Git.  
- Báo cáo chi phí giữa chặng: Tổng chi tiêu theo dõi và các tối ưu hoá có hiệu quả.

### Vấn đề gặp phải & Biện pháp khắc phục
- Compute Optimizer dữ liệu chậm → đợi 48 giờ để nhận đủ khuyến nghị.  
- GuardDuty báo false positive → điều chỉnh rule ức chế theo môi trường.  
- SSM thực thi lỗi → cấp thêm IAM role cho các instance.

### Bước tiếp theo (Tuần 8)
- Tiếp Module 3: Tăng tính sẵn sàng (multi‑AZ/DR) và bảo mật sâu hơn.  
- Mô hình chịu lỗi (fault tolerance) và DR drills.  
- Chuẩn bị cho giai đoạn hiện đại hoá (modernization) ở Tuần 9.  
- Chia sẻ kiến thức nội bộ về các tối ưu hoá đã thực hiện.