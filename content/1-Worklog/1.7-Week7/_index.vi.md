---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

## Mục tiêu tuần 7

* Hoàn thành Lab14 và Lab15.
* Tìm hiểu dịch vụ Amazon Elastic Container Service (Amazon ECS).
* Hiểu cách triển khai container bằng AWS Fargate.
* Thực hành triển khai ứng dụng từ Amazon ECR lên ECS.
* Tìm hiểu cơ chế cân bằng tải với Application Load Balancer (ALB).
* Làm quen với AWS Cloud Map và Service Discovery.
* Hiểu quy trình triển khai Blue/Green Deployment.

---

## Công việc thực hiện trong tuần

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| Thứ 2 | - Bắt đầu Lab14.<br>- Tìm hiểu Amazon ECS.<br>- Làm quen với Cluster, Task Definition, Task và Service. | 01/06/2026 | 01/06/2026 | Amazon ECS Documentation |
| Thứ 3 | - Tìm hiểu AWS Fargate.<br>- Triển khai ứng dụng Container mà không cần quản lý EC2.<br>- So sánh ECS EC2 Launch Type và Fargate Launch Type. | 02/06/2026 | 02/06/2026 | AWS Fargate Documentation |
| Thứ 4 | - Kết nối Amazon ECS với Amazon ECR.<br>- Pull Docker Image từ Amazon ECR.<br>- Triển khai ứng dụng Container lên ECS Cluster. | 03/06/2026 | 03/06/2026 | Amazon ECR Documentation |
| Thứ 5 | - Bắt đầu Lab15.<br>- Cấu hình Application Load Balancer (ALB).<br>- Thiết lập Target Group và Listener.<br>- Kiểm tra khả năng truy cập ứng dụng. | 04/06/2026 | 05/06/2026 | Elastic Load Balancing Documentation |
| Thứ 6 | - Tìm hiểu AWS Cloud Map.<br>- Thực hành Service Discovery.<br>- Tìm hiểu Blue/Green Deployment.<br>- Quan sát quy trình cập nhật ứng dụng mà không gây gián đoạn dịch vụ. | 06/06/2026 | 06/06/2026 | AWS Cloud Map Documentation |
| Chủ nhật | - Hoàn thành Lab14 và Lab15.<br>- Tổng hợp kiến thức tuần.<br>- Chuẩn bị nội dung cho tuần tiếp theo. | 07/06/2026 | 07/06/2026 | AWS Study Group |

---

## Kết quả đạt được

* Hoàn thành Lab14 và Lab15 theo đúng tiến độ.
* Hiểu kiến trúc triển khai ứng dụng Container trên AWS.
* Nắm được các thành phần chính của Amazon ECS:
  * Cluster.
  * Task Definition.
  * Task.
  * Service.

* Hiểu sự khác biệt giữa:
  * ECS sử dụng EC2.
  * ECS sử dụng AWS Fargate.

* Triển khai thành công ứng dụng Container từ Amazon ECR lên Amazon ECS.
* Hiểu cách ECS tự động quản lý vòng đời của Container.
* Cấu hình thành công:
  * Application Load Balancer.
  * Target Group.
  * Listener Rule.

* Hiểu cách ALB phân phối lưu lượng truy cập tới nhiều Container.
* Làm quen với AWS Cloud Map để hỗ trợ Service Discovery giữa các dịch vụ.
* Hiểu quy trình Blue/Green Deployment nhằm giảm downtime khi cập nhật ứng dụng.
* Nhận thức được lợi ích của việc triển khai Container trên nền tảng Serverless với AWS Fargate.

---

## Khó khăn gặp phải

* Ban đầu còn nhầm lẫn giữa Task Definition, Task và Service trong Amazon ECS.
* Quá trình cấu hình ECS Service với ALB yêu cầu nhiều bước nên dễ xảy ra sai sót.
* AWS Cloud Map là dịch vụ khá mới nên cần thời gian để hiểu cách hoạt động.
* Blue/Green Deployment liên quan đến nhiều thành phần như Load Balancer, Target Group và Deployment Controller nên cần thực hành nhiều lần để nắm rõ quy trình.

---

## Kinh nghiệm rút ra

* Container hóa giúp việc triển khai và cập nhật ứng dụng trở nên nhanh chóng, đồng nhất và dễ mở rộng.
* AWS Fargate giúp triển khai Container mà không cần quản lý máy chủ EC2, từ đó giảm đáng kể công việc vận hành.
* Amazon ECS kết hợp với Amazon ECR và Application Load Balancer tạo thành một giải pháp triển khai ứng dụng hoàn chỉnh trên AWS.
* Blue/Green Deployment là phương pháp triển khai hiện đại giúp giảm thời gian gián đoạn và hạn chế rủi ro khi phát hành phiên bản mới.
* AWS Cloud Map giúp các dịch vụ trong hệ thống dễ dàng tìm thấy nhau mà không cần cấu hình thủ công.
