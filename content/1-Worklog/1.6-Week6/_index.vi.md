---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---


## Mục tiêu tuần 6

* Hoàn thành Lab12 và Lab13.
* Hiểu khái niệm Container và Docker.
* Thực hành tạo Docker Image và Docker Container.
* Làm quen với Docker Hub và Amazon Elastic Container Registry (Amazon ECR).
* Tìm hiểu quy trình lưu trữ và quản lý Docker Image trên AWS.
* Học cách Import và Export Virtual Machine bằng AWS VM Import/Export.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Bắt đầu Lab12.<br>- Tìm hiểu Docker Fundamentals.<br>- Cài đặt Docker Desktop.<br>- Làm quen với kiến trúc Docker Engine. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 3 | - Thực hành Docker Image và Docker Container.<br>- Tìm hiểu Dockerfile.<br>- Build Image và chạy Container đầu tiên. | 26/05/2026 | 26/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 4 | - Làm quen với Docker Hub.<br>- Pull và Push Docker Image.<br>- Quản lý Docker Image thông qua Registry. | 27/05/2026 | 27/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 5 | - Bắt đầu Lab13.<br>- Tìm hiểu Amazon Elastic Container Registry (Amazon ECR).<br>- Tạo Repository trên ECR.<br>- Push Docker Image lên Amazon ECR. | 28/05/2026 | 29/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Thứ 6 | - Tìm hiểu AWS VM Import/Export.<br>- Học quy trình Import và Export Virtual Machine.<br>- So sánh VM truyền thống và Container. | 30/05/2026 | 30/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| Chủ nhật | - Hoàn thành Lab12 và Lab13.<br>- Ôn tập kiến thức Docker và Amazon ECR.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 31/05/2026 | 31/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

## Kết quả đạt được

* Hoàn thành Lab12 và Lab13 theo đúng tiến độ.
* Hiểu được sự khác biệt giữa Virtual Machine và Container.
* Nắm được kiến thức cơ bản về Docker:
  * Docker Engine.
  * Docker Image.
  * Docker Container.
  * Dockerfile.
  * Docker Registry.

* Thực hành thành công:
  * Build Docker Image.
  * Chạy Docker Container.
  * Quản lý Container thông qua Docker CLI.
  * Xóa và cập nhật Docker Image.

* Làm quen với Docker Hub:
  * Pull Image.
  * Push Image.
  * Quản lý Image Repository.

* Hiểu cách hoạt động của Amazon ECR:
  * Tạo Repository.
  * Push Image.
  * Pull Image.
  * Quản lý Container Image trên AWS.

* Tìm hiểu quy trình VM Import/Export:
  * Import máy ảo từ môi trường On-premises lên AWS.
  * Export Virtual Machine từ AWS về môi trường bên ngoài.
  * Hiểu các trường hợp sử dụng trong quá trình di chuyển hệ thống lên Cloud.

---

## Khó khăn gặp phải

* Ban đầu còn nhầm lẫn giữa Docker Image và Docker Container.
* Việc viết Dockerfile cần chú ý đến cú pháp và thứ tự các lệnh để tối ưu Image.
* Quá trình Push Image lên Amazon ECR yêu cầu cấu hình AWS CLI và xác thực Docker chính xác.
* Khái niệm VM Import/Export khá mới nên cần thêm thời gian để hiểu quy trình triển khai trong thực tế.

---

## Kinh nghiệm rút ra

* Docker giúp đóng gói ứng dụng cùng toàn bộ môi trường chạy, giúp việc triển khai trở nên nhanh chóng và nhất quán.
* Docker Image nên được tối ưu kích thước để giảm thời gian build và triển khai.
* Amazon ECR là dịch vụ phù hợp để lưu trữ Container Image trong hệ sinh thái AWS và tích hợp tốt với ECS, EKS.
* Việc thành thạo Docker là nền tảng quan trọng trước khi học các dịch vụ Container như Amazon ECS hoặc Kubernetes.
* VM Import/Export hỗ trợ doanh nghiệp chuyển đổi hạ tầng từ môi trường truyền thống lên AWS dễ dàng hơn.
