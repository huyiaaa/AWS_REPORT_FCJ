---
title: "Tuần 11 - Worklog"
date: "2025-11-18"
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu Tuần 11 (theo roadmap CloudJourney)
- Kiến trúc data lake: Phân vùng S3, quản trị Lake Formation (Module 6).
- ETL/ELT: Job Glue xử lý dữ liệu.
- Streaming: Kinesis cho thu thập real-time.
- Cơ bản về BI với QuickSight.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 6 — Data lake: Thiết kế lake trên S3, bật versioning, cấu hình catalog Lake Formation. | 17/11/2025 | 17/11/2025 | https://cloudjourney.awsstudygroup.com/ - Data & Analytics |
| Thứ Ba | Lab: Phân vùng dữ liệu trong S3, cấp quyền qua Lake Formation. | 18/11/2025 | 18/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 6 Labs |
| Thứ Tư | ETL: Tạo crawler và job Glue, chuyển đổi CSV sang Parquet. | 19/11/2025 | 19/11/2025 | https://cloudjourney.awsstudygroup.com/ - Data & Analytics |
| Thứ Năm | Streaming: Thiết lập Kinesis Data Streams, tạo/tiêu thụ event. | 20/11/2025 | 20/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 6 |
| Thứ Sáu | Trực quan hóa: Kết nối QuickSight với S3/Glue, xây dựng dashboard. | 21/11/2025 | 21/11/2025 | https://cloudjourney.awsstudygroup.com/ - BI |

### Kết quả & Thành tựu (Tuần 11)
- Xây dựng data lake: S3 tổ chức với truy vấn Athena, bảo mật bằng Lake Formation.
- ETL tự động: Job Glue xử lý 1M dòng, output tối ưu định dạng trên S3.
- Pipeline real-time: Kinesis streaming log ứng dụng, phân tích bằng Kinesis Analytics.
- Dashboard tương tác: QuickSight trực quan hóa output ETL, chia sẻ với team.
- Hoàn thiện hành trình dữ liệu: Từ thu thập đến insight, tích hợp với dịch vụ trước.

### Vấn đề gặp phải & Biện pháp khắc phục
- Lake Formation chậm lan truyền quyền → dùng blueprint để thiết lập nhanh hơn.
- Job Glue lỗi memory → tăng cấp phát DPU.
- Giới hạn shard Kinesis → theo dõi throughput và resharding.

### Bước tiếp theo (Tuần 12)
- Module 7: Giới thiệu AI/ML với Bedrock, cơ bản về SageMaker.
- Ứng dụng Generative AI.
- Đánh giá dự án tổng kết.
- Tổng kết và chuẩn bị chương trình workforce.

> Lưu ý: Mọi lab và nội dung tuân theo chương trình CloudJourney tại https://cloudjourney.awsstudygroup.com/. Đảm bảo ảnh chụp màn hình, logs và scripts được lưu trong repository dự án để kiểm chứng.