---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


## Mục tiêu tuần 10

* Hoàn thiện các chức năng chính của dự án.
* Kiểm thử và sửa các lỗi phát sinh trong quá trình phát triển.
* Tối ưu hiệu năng và cấu hình hệ thống trên AWS.
* Kiểm tra tính ổn định của ứng dụng.
* Cập nhật tài liệu kỹ thuật và tài liệu triển khai.
* Chuẩn bị cho giai đoạn nghiệm thu và trình bày dự án.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Rà soát toàn bộ chức năng của hệ thống.<br>- Kiểm tra các chức năng quản lý sự kiện và đăng ký tham gia.<br>- Ghi nhận các lỗi cần sửa. | 22/06/2026 | 22/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 3 | - Sửa lỗi Backend.<br>- Tối ưu API và xử lý dữ liệu.<br>- Kiểm tra kết nối với Amazon RDS. | 23/06/2026 | 23/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 4 | - Hoàn thiện giao diện Frontend.<br>- Kiểm tra trải nghiệm người dùng.<br>- Sửa các lỗi giao diện và kết nối API. | 24/06/2026 | 24/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 5 | - Kiểm thử toàn bộ hệ thống.<br>- Thực hiện các bài kiểm thử chức năng.<br>- Kiểm tra tính ổn định khi nhiều người dùng truy cập. | 25/06/2026 | 26/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 6 | - Theo dõi hệ thống bằng Amazon CloudWatch.<br>- Kiểm tra Log và tối ưu cấu hình EC2.<br>- Rà soát Security Group và các thiết lập bảo mật. | 27/06/2026 | 27/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Chủ nhật | - Hoàn thiện tài liệu triển khai.<br>- Tổng hợp kết quả thực hiện.<br>- Chuẩn bị nội dung báo cáo và kế hoạch tuần tiếp theo. | 28/06/2026 | 28/06/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Kết quả đạt được

* Hoàn thiện các chức năng chính của hệ thống.
* Kiểm thử thành công các chức năng:
  * Đăng nhập.
  * Quản lý sự kiện.
  * Đăng ký tham gia sự kiện.
  * Hiển thị danh sách sự kiện.
  * Kết nối cơ sở dữ liệu.

* Khắc phục các lỗi phát sinh trong quá trình triển khai.
* Tối ưu hiệu năng của Backend và các API.
* Hoàn thiện giao diện người dùng và cải thiện trải nghiệm sử dụng.
* Kiểm tra tính ổn định của hệ thống trên môi trường AWS.
* Theo dõi Log và Metrics bằng Amazon CloudWatch để đánh giá hiệu năng hệ thống.
* Hoàn thiện tài liệu kỹ thuật và cập nhật tiến độ dự án.

---

## Khó khăn gặp phải

* Một số lỗi chỉ xuất hiện sau khi triển khai lên môi trường AWS, không xuất hiện khi chạy trên máy cục bộ.
* Quá trình tối ưu API cần cân nhắc giữa hiệu năng và tính dễ bảo trì.
* Một số lỗi giao diện phát sinh do dữ liệu trả về từ Backend thay đổi.
* Việc kiểm thử nhiều chức năng liên tiếp đòi hỏi phải chuẩn bị đầy đủ dữ liệu kiểm thử.

---

## Kinh nghiệm rút ra

* Kiểm thử thường xuyên giúp phát hiện lỗi sớm và giảm thời gian sửa lỗi ở giai đoạn cuối.
* Cần phân biệt rõ lỗi đến từ Frontend, Backend hay hạ tầng AWS để xử lý hiệu quả.
* Amazon CloudWatch là công cụ hữu ích để theo dõi Log và đánh giá tình trạng hoạt động của hệ thống.
* Tài liệu triển khai nên được cập nhật song song với quá trình phát triển để tránh thiếu sót.
* Một hệ thống hoàn chỉnh không chỉ cần đầy đủ chức năng mà còn phải đảm bảo tính ổn định, hiệu năng và khả năng bảo trì.
