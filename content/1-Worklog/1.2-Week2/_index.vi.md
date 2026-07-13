---
title: "Week 2 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---


## Mục tiêu tuần 2

* Hoàn thành các nội dung của Lab04, Lab05 và Lab06.
* Hiểu cách triển khai một hệ thống Web Application trên AWS.
* Làm quen với kiến trúc nhiều tầng (Multi-tier Architecture).
* Tìm hiểu cơ chế cân bằng tải (Elastic Load Balancer).
* Tìm hiểu Auto Scaling Group và cơ chế tự động mở rộng tài nguyên.
* Thực hành triển khai cơ sở dữ liệu Amazon RDS.
* Hiểu cách kết nối giữa EC2 và RDS.
* Làm quen với CloudWatch để theo dõi tài nguyên hệ thống.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Ôn tập kiến thức tuần trước.<br>- Bắt đầu Lab04.<br>- Tìm hiểu kiến trúc triển khai Web Application trên AWS.<br>- Làm quen với VPC, Public Subnet và Security Group. | 27/04/2026 | 27/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 3 | - Tiếp tục Lab04.<br>- Khởi tạo EC2 Instance.<br>- Cấu hình Security Group.<br>- Thực hành truy cập EC2 qua SSH. | 28/04/2026 | 28/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 4 | - Hoàn thành Lab05.<br>- Tìm hiểu Amazon RDS.<br>- Khởi tạo cơ sở dữ liệu MySQL trên RDS.<br>- Kết nối EC2 với RDS và kiểm tra kết nối. | 29/04/2026 | 30/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 5 | - Thực hiện Lab06.<br>- Tìm hiểu Elastic Load Balancer (ALB).<br>- Cấu hình Auto Scaling Group.<br>- Thiết lập Launch Template cho EC2. | 01/05/2026 | 02/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 6 | - Thực hành kiểm thử Auto Scaling.<br>- Theo dõi hoạt động của EC2 thông qua CloudWatch.<br>- Tổng hợp kiến thức và hoàn thành Lab04, Lab05, Lab06. | 03/05/2026 | 03/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Kết quả đạt được

* Hoàn thành đầy đủ Lab04, Lab05 và Lab06 theo đúng tiến độ Bootcamp.
* Hiểu được mô hình triển khai một Web Application trên AWS theo kiến trúc nhiều tầng.
* Thực hành thành công việc:

  * Khởi tạo EC2 Instance.
  * Cấu hình Security Group.
  * Kết nối EC2 thông qua SSH.
  * Quản lý Key Pair.

* Hiểu được cách triển khai và sử dụng Amazon RDS:

  * Tạo Database MySQL.
  * Cấu hình Security Group cho Database.
  * Kết nối EC2 với RDS.
  * Kiểm tra khả năng truy cập cơ sở dữ liệu.

* Tìm hiểu cơ chế hoạt động của Elastic Load Balancer:

  * Phân phối lưu lượng truy cập.
  * Health Check.
  * Target Group.
  * High Availability.

* Hiểu được nguyên lý hoạt động của Auto Scaling Group:

  * Launch Template.
  * Desired Capacity.
  * Minimum Capacity.
  * Maximum Capacity.
  * Chính sách tự động mở rộng và thu hẹp tài nguyên.

* Thực hành giám sát tài nguyên thông qua Amazon CloudWatch:

  * Theo dõi CPU Utilization.
  * Network Traffic.
  * EC2 Status.
  * Basic Monitoring.

* Hiểu được cách các dịch vụ AWS phối hợp với nhau để xây dựng một hệ thống Web có khả năng mở rộng và độ sẵn sàng cao.

---

## Khó khăn gặp phải

* Ban đầu còn gặp khó khăn trong việc hiểu mối quan hệ giữa VPC, Subnet, Route Table và Security Group.
* Quá trình kết nối EC2 với Amazon RDS gặp lỗi do Security Group chưa mở đúng cổng MySQL (3306).
* Chưa quen với cơ chế hoạt động của Auto Scaling Group nên mất thời gian để hiểu các thông số như Desired Capacity, Minimum Size và Maximum Size.
* Khi thực hành CloudWatch, còn gặp khó khăn trong việc đọc và phân tích các chỉ số giám sát.

---

## Kinh nghiệm rút ra

* Trước khi triển khai hệ thống, cần thiết kế sơ đồ kiến trúc để hiểu rõ mối quan hệ giữa các dịch vụ AWS.
* Security Group là thành phần rất quan trọng, cần kiểm tra kỹ các Inbound Rule và Outbound Rule trước khi xử lý lỗi kết nối.
* Amazon RDS nên được đặt trong Private Subnet để tăng tính bảo mật cho hệ thống.
* Elastic Load Balancer và Auto Scaling Group là hai thành phần quan trọng giúp xây dựng hệ thống có khả năng mở rộng và đảm bảo tính sẵn sàng cao.
* CloudWatch là công cụ hữu ích để theo dõi hiệu năng hệ thống và hỗ trợ phát hiện sự cố sớm.
* Sau khi hoàn thành mỗi Lab, việc tổng hợp kiến thức và ghi chú lại các bước triển khai giúp dễ dàng ôn tập và áp dụng vào dự án thực tế.
