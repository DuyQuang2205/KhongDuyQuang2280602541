---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


## Mục tiêu tuần 5

* Hoàn thành Lab10 và Lab11.
* Tìm hiểu cách triển khai và quản trị Windows Server trên Amazon EC2.
* Nâng cao kỹ năng sử dụng AWS CLI trong quản lý tài nguyên.
* Làm quen với dịch vụ Amazon Simple Notification Service (SNS).
* Học các phương pháp Troubleshooting trên AWS.
* Rèn luyện kỹ năng phân tích và xử lý sự cố trong môi trường Cloud.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Bắt đầu Lab10.<br>- Tìm hiểu Amazon EC2 Windows.<br>- Khởi tạo Windows EC2 Instance.<br>- Thực hành kết nối bằng Remote Desktop (RDP). | 18/05/2026 | 18/05/2026 | AWS EC2 Documentation |
| Thứ 3 | - Tiếp tục Lab10.<br>- Làm quen với môi trường Windows Server trên AWS.<br>- Thực hành quản lý Windows Instance. | 19/05/2026 | 19/05/2026 | Microsoft Windows Server Documentation |
| Thứ 4 | - Bắt đầu Lab11.<br>- Ôn tập AWS CLI.<br>- Thực hành quản lý EC2, S3 và IAM thông qua dòng lệnh. | 20/05/2026 | 20/05/2026 | AWS CLI Documentation |
| Thứ 5 | - Tìm hiểu Amazon SNS.<br>- Tạo Topic.<br>- Đăng ký Email Subscription.<br>- Thực hành gửi Notification. | 21/05/2026 | 21/05/2026 | Amazon SNS Documentation |
| Thứ 6 | - Học Troubleshooting trên AWS.<br>- Phân tích lỗi kết nối EC2.<br>- Kiểm tra Security Group, Route Table và IAM Permissions. | 22/05/2026 | 23/05/2026 | AWS Well-Architected Framework |
| Chủ nhật | - Hoàn thành Lab10 và Lab11.<br>- Tổng hợp kiến thức.<br>- Chuẩn bị kế hoạch cho tuần tiếp theo. | 24/05/2026 | 24/05/2026 | AWS Study Group |

---

## Kết quả đạt được

* Hoàn thành Lab10 và Lab11 đúng tiến độ.
* Hiểu cách triển khai và quản trị Windows Server trên Amazon EC2.
* Thực hành thành công:
  * Tạo Windows EC2 Instance.
  * Kết nối Remote Desktop (RDP).
  * Quản lý hệ điều hành Windows trên Cloud.

* Nâng cao kỹ năng sử dụng AWS CLI:
  * Quản lý EC2.
  * Quản lý S3.
  * Quản lý IAM.
  * Thực hiện các thao tác thông qua Command Line.

* Hiểu cơ chế hoạt động của Amazon SNS:
  * Topic.
  * Subscription.
  * Notification.
  * Publish Message.

* Thực hành gửi thông báo qua Email bằng Amazon SNS.
* Hiểu quy trình xử lý sự cố trên AWS, bao gồm:
  * Kiểm tra Security Group.
  * Kiểm tra IAM Permissions.
  * Kiểm tra Route Table.
  * Kiểm tra Network Connectivity.
  * Phân tích log để xác định nguyên nhân lỗi.

---

## Khó khăn gặp phải

* Việc kết nối Remote Desktop tới Windows EC2 yêu cầu cấu hình đúng Security Group và mật khẩu Administrator.
* AWS CLI có nhiều lệnh và tham số nên mất thời gian để ghi nhớ.
* Ban đầu chưa hiểu rõ cơ chế Publish/Subscribe của Amazon SNS.
* Quá trình Troubleshooting cần kiểm tra nhiều thành phần khác nhau nên đôi khi khó xác định nguyên nhân lỗi.

---

## Kinh nghiệm rút ra

* AWS CLI giúp tự động hóa việc quản lý tài nguyên nhanh hơn so với thao tác trên giao diện Console.
* Amazon SNS là dịch vụ hữu ích để gửi thông báo trong các hệ thống Cloud và có thể tích hợp với nhiều dịch vụ AWS khác.
* Khi xử lý sự cố trên AWS nên kiểm tra theo từng lớp:
  * IAM Permission.
  * Security Group.
  * Network.
  * EC2 Instance.
  * Application.

* Ghi lại từng bước Troubleshooting giúp tiết kiệm thời gian khi gặp lại lỗi tương tự.
* Việc thành thạo cả AWS Console và AWS CLI sẽ giúp quản trị hệ thống linh hoạt và hiệu quả hơn.
