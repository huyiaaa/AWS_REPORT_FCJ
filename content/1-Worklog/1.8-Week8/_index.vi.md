---
title: "Tuần 8 - Worklog"
date: "2025-10-28"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu Tuần 8 (theo roadmap CloudJourney)
- Trụ cột độ tin cậy: Tính sẵn sàng cao, khôi phục thảm họa (Module 3).
- Bảo mật nâng cao: Zero-trust, tuân thủ với Config.
- Cơ bản về phản ứng sự cố.
- Tích hợp xuyên trụ cột.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 3 — Độ tin cậy: Thiết kế kiến trúc multi-AZ, lập kế hoạch RTO/RPO. | 27/10/2025 | 27/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thứ Ba | Lab: Thiết lập DR với chiến lược Pilot Light, thử nghiệm failover sang region phụ. | 28/10/2025 | 28/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 Labs |
| Thứ Tư | Bảo mật nâng cao: Triển khai zero-trust với IAM policies, bật AWS Config rules. | 29/10/2025 | 29/10/2025 | https://cloudjourney.awsstudygroup.com/ - Optimize |
| Thứ Năm | Tuân thủ: Audit tài nguyên với Config, sửa các mục không tuân thủ. | 30/10/2025 | 30/10/2025 | https://cloudjourney.awsstudygroup.com/ - Module 3 |
| Thứ Sáu | Phản ứng sự cố: Mô phỏng sự cố, sử dụng Incident Manager, ghi chép bài học. | 31/10/2025 | 31/10/2025 | https://cloudjourney.awsstudygroup.com/ - Operational Excellence |

### Kết quả & Thành tựu (Tuần 8)
- HA/DR bền vững: Cluster RDS/ECS multi-AZ, DR Pilot Light thử nghiệm RTO <15 phút.
- Zero-trust triển khai: IAM least-privilege, áp dụng Config conformance packs.
- Điểm tuân thủ 95%: Tự động sửa lỗi cho các rule phổ biến như mã hóa.
- IR playbook cải tiến: Xử lý mô phỏng sự cố trong 10 phút, tích hợp PagerDuty.
- Tích hợp tối ưu: Bảo mật/độ tin cậy nâng cao cho workload trước.

### Vấn đề gặp phải & Biện pháp khắc phục
- Độ trễ DR cross-region → tối ưu bằng Global Accelerator.
- Config rule đánh giá chậm → tăng tần suất đánh giá.
- Cảnh báo IR quá nhiều → điều chỉnh ngưỡng thông báo.

### Bước tiếp theo (Tuần 9)
- Chuyển sang Module 4: Phân rã microservices.
- Mẫu serverless với Lambda/EventBridge.
- Thiết kế API với API Gateway/AppSync.
- Demo modernization cho team.

> Lưu ý: Mọi lab và nội dung tuân theo chương trình CloudJourney tại https://cloudjourney.awsstudygroup.com/. Đảm bảo ảnh chụp màn hình, logs và scripts được lưu trong repository dự án để kiểm chứng.