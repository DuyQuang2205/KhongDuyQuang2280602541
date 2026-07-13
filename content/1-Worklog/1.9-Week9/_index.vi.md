---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


## Mục tiêu tuần 9

* Bắt đầu triển khai dự án thực tập.
* Thiết lập môi trường phát triển và triển khai trên AWS.
* Xây dựng kiến trúc hạ tầng theo thiết kế đã đề ra.
* Triển khai các thành phần cơ bản của hệ thống.
* Thiết lập cơ sở dữ liệu và kết nối với ứng dụng.
* Kiểm tra khả năng hoạt động của hệ thống.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Khởi tạo Project.<br>- Tạo Source Code Repository.<br>- Cấu hình môi trường phát triển và quản lý mã nguồn bằng Git. | 15/06/2026 | 15/06/2026 | https://git-scm.com/docs |
| Thứ 3 | - Triển khai hạ tầng AWS.<br>- Tạo VPC, Public Subnet, Security Group và EC2 Instance.<br>- Kiểm tra khả năng truy cập máy chủ. | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html |
| Thứ 4 | - Tạo Amazon RDS.<br>- Thiết lập kết nối giữa EC2 và RDS.<br>- Khởi tạo cơ sở dữ liệu cho hệ thống. | 17/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html |
| Thứ 5 | - Triển khai Backend lên EC2.<br>- Cấu hình môi trường chạy ứng dụng.<br>- Kiểm tra kết nối Database. | 18/06/2026 | 19/06/2026 | https://docs.spring.io/spring-boot/index.html |
| Thứ 6 | - Triển khai Frontend.<br>- Kiểm tra giao tiếp giữa Frontend và Backend.<br>- Thực hiện các bài kiểm thử chức năng cơ bản. | 20/06/2026 | 20/06/2026 | https://react.dev/ |
| Chủ nhật | - Tổng hợp kết quả triển khai.<br>- Ghi nhận các lỗi phát sinh.<br>- Chuẩn bị kế hoạch phát triển cho tuần tiếp theo. | 21/06/2026 | 21/06/2026 | https://www.atlassian.com/software/confluence/guides |

---

## Kết quả đạt được

* Hoàn thành giai đoạn khởi tạo dự án.
* Thiết lập thành công môi trường phát triển.
* Xây dựng hạ tầng AWS ban đầu gồm:
  * Amazon VPC.
  * Public Subnet.
  * Security Group.
  * Amazon EC2.
  * Amazon RDS.

* Hoàn thành kết nối giữa EC2 và Amazon RDS.
* Khởi tạo cơ sở dữ liệu của hệ thống.
* Triển khai thành công phiên bản đầu tiên của Backend lên EC2.
* Hoàn thành cấu hình môi trường chạy ứng dụng.
* Triển khai Frontend và kiểm tra khả năng giao tiếp với Backend.
* Kiểm thử thành công các chức năng cơ bản của hệ thống.
* Hoàn thiện tài liệu ghi chú quá trình triển khai và các vấn đề cần cải thiện.

---

## Khó khăn gặp phải

* Quá trình triển khai ứng dụng lên EC2 phát sinh một số lỗi liên quan đến cấu hình môi trường và Dependency.
* Kết nối giữa Backend và Amazon RDS ban đầu chưa ổn định do cấu hình Security Group.
* Việc triển khai Frontend và Backend trên hai môi trường khác nhau yêu cầu cấu hình CORS phù hợp.
* Một số lỗi phát sinh trong quá trình Deploy cần kiểm tra Log để xác định nguyên nhân.

---

## Kinh nghiệm rút ra

* Chuẩn bị đầy đủ môi trường trước khi triển khai giúp giảm đáng kể thời gian xử lý lỗi.
* Việc thiết kế kiến trúc ngay từ đầu giúp quá trình triển khai diễn ra thuận lợi hơn.
* Luôn kiểm tra Security Group và Network trước khi xử lý lỗi kết nối.
* Ghi lại từng bước triển khai giúp dễ dàng tái tạo môi trường khi cần.
* Kiểm tra Log thường xuyên là cách hiệu quả để phát hiện và xử lý lỗi trong quá trình Deploy.
