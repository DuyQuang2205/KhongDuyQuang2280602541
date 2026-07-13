---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---


## Mục tiêu tuần 4

* Hoàn thành Lab08 và Lab09.
* Tìm hiểu dịch vụ Amazon Route 53 và Hybrid DNS.
* Làm quen với Infrastructure as Code (IaC) thông qua AWS CloudFormation.
* Học cách giám sát hệ thống bằng Amazon CloudWatch.
* Thực hành sử dụng CloudWatch Logs, Dashboard và Alarm.
* Hiểu quy trình quản lý hạ tầng và giám sát hệ thống trên AWS.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Bắt đầu Lab08.<br>- Tìm hiểu Amazon Route 53.<br>- Học về DNS, Hosted Zone và Record Set. | 11/05/2026 | 11/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 3 | - Tiếp tục Lab08.<br>- Tìm hiểu Hybrid DNS.<br>- Thực hành cấu hình Route 53 và kiểm tra phân giải tên miền. | 12/05/2026 | 12/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 4 | - Bắt đầu Lab09.<br>- Học AWS CloudFormation.<br>- Tìm hiểu khái niệm Infrastructure as Code (IaC). | 13/05/2026 | 13/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 5 | - Tiếp tục Lab09.<br>- Thực hành triển khai tài nguyên AWS bằng CloudFormation Template.<br>- Tìm hiểu Stack và Stack Update. | 14/05/2026 | 15/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 6 | - Học Amazon CloudWatch.<br>- Thực hành CloudWatch Logs, Dashboard và Alarm.<br>- Theo dõi tài nguyên EC2 và RDS. | 16/05/2026 | 16/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Chủ nhật | - Hoàn thành Lab08 và Lab09.<br>- Tổng hợp kiến thức đã học.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 17/05/2026 | 17/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Kết quả đạt được

* Hoàn thành Lab08 và Lab09 theo đúng tiến độ.
* Hiểu cách hoạt động của hệ thống DNS trên AWS thông qua Amazon Route 53.
* Nắm được kiến thức cơ bản về:
  * Hosted Zone.
  * Public DNS.
  * Private DNS.
  * Record Set.
  * Hybrid DNS.

* Hiểu khái niệm **Infrastructure as Code (IaC)** và lợi ích của việc tự động hóa triển khai hạ tầng.
* Thực hành triển khai tài nguyên AWS bằng CloudFormation Template.
* Hiểu được quy trình:
  * Tạo Stack.
  * Cập nhật Stack.
  * Xóa Stack.
  * Quản lý tài nguyên tự động.

* Làm quen với Amazon CloudWatch:
  * Metrics.
  * Logs.
  * Dashboard.
  * Alarm.

* Biết cách theo dõi trạng thái hoạt động của EC2 và RDS thông qua CloudWatch.
* Hiểu được vai trò của Dashboard trong việc trực quan hóa dữ liệu giám sát.
* Thực hành tạo Alarm để cảnh báo khi tài nguyên vượt quá ngưỡng cho phép.

---

## Khó khăn gặp phải

* Khái niệm Hybrid DNS khá mới nên cần thời gian để hiểu cách Route 53 hoạt động với hệ thống On-premises.
* Việc viết CloudFormation Template yêu cầu chú ý đến cú pháp YAML và cấu trúc tài nguyên.
* Ban đầu còn nhầm lẫn giữa CloudWatch Metrics và CloudWatch Logs.
* Việc thiết lập Alarm cần lựa chọn ngưỡng phù hợp để tránh cảnh báo không cần thiết.

---

## Kinh nghiệm rút ra

* Infrastructure as Code giúp việc triển khai hạ tầng nhanh hơn, đồng nhất hơn và giảm sai sót so với cấu hình thủ công.
* CloudFormation là công cụ rất hữu ích để quản lý hạ tầng AWS trong các dự án thực tế.
* CloudWatch là thành phần quan trọng giúp giám sát và phát hiện sự cố sớm.
* Dashboard giúp việc theo dõi hệ thống trực quan và thuận tiện hơn.
* Alarm là công cụ cần thiết để tự động cảnh báo khi hệ thống gặp vấn đề.
* Sau mỗi Lab cần lưu lại Template và tài liệu triển khai để tái sử dụng trong các dự án sau.
