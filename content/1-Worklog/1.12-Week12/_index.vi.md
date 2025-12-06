---
title: "Tuần 12 - Worklog"
date: "2025-11-25"
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu Tuần 12 (theo roadmap CloudJourney)
- Nền tảng AI/ML: Bedrock cho foundation model, SageMaker cho ML tùy chỉnh (Module 7).
- Xây dựng ứng dụng RAG đơn giản.
- Thực hành AI có trách nhiệm.
- Tích hợp và đánh giá dự án tổng kết.

### Công việc trong tuần (theo ngày)
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tham khảo |
| --- | ---- | ---------- | --------------- | --------- |
| Thứ Hai | Module 7 — Giới thiệu AI: Khám phá model Bedrock, gọi LLM để sinh text. | 24/11/2025 | 24/11/2025 | https://cloudjourney.awsstudygroup.com/ - AI/ML |
| Thứ Ba | Lab: Xây dựng pipeline RAG với Bedrock và Kendra cho hỏi đáp tài liệu. | 25/11/2025 | 25/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 7 Labs |
| Thứ Tư | ML tùy chỉnh: Thiết lập SageMaker Studio, huấn luyện model đơn giản với dữ liệu S3. | 26/11/2025 | 26/11/2025 | https://cloudjourney.awsstudygroup.com/ - AI/ML |
| Thứ Năm | AI có trách nhiệm: Phát hiện thiên lệch với Clarify, công cụ giải thích. | 27/11/2025 | 27/11/2025 | https://cloudjourney.awsstudygroup.com/ - Module 7 |
| Thứ Sáu | Tổng kết: Tích hợp AI vào pipeline dữ liệu, review toàn bộ hành trình, chuẩn bị nộp bài. | 28/11/2025 | 28/11/2025 | https://cloudjourney.awsstudygroup.com/ - Review |

### Kết quả & Thành tựu (Tuần 12)
- Ứng dụng Generative AI: Chatbot chạy Bedrock truy vấn tài liệu S3 qua RAG, độ chính xác >85%.
- Triển khai model ML: Endpoint SageMaker phục vụ dự đoán, tích hợp với Lambda.
- Áp dụng thực hành đạo đức: Kiểm tra thiên lệch model, thêm giải thích cho output.
- Hoàn thành dự án tổng kết: Ứng dụng end-to-end kết hợp migration, optimization, container, data, AI.
- Kết thúc hành trình 12 tuần: Hoàn thành mọi module, xây dựng portfolio, sẵn sàng cho FCJ Workforce.

### Vấn đề gặp phải & Biện pháp khắc phục
- Giới hạn token Bedrock → chia nhỏ input cho câu hỏi dài.
- Chi phí huấn luyện SageMaker → dùng spot instance cho job không gấp.
- Dataset thiên lệch → bổ sung dữ liệu huấn luyện để cân bằng.

### Bước tiếp theo (Sau chương trình)
- Đăng ký chương trình FCJ Workforce.
- Đóng góp cho dự án cộng đồng.
- Theo đuổi chứng chỉ AWS (Solutions Architect Associate).
- Mentoring cho khóa tiếp theo từ kinh nghiệm học được.

> Lưu ý: Mọi lab và nội dung tuân theo chương trình CloudJourney tại https://cloudjourney.awsstudygroup.com/. Đảm bảo ảnh chụp màn hình, logs và scripts được lưu trong repository dự án để kiểm chứng.