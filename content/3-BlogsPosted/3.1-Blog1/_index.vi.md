---
title: "Blog 1"
date: 2026-07-05
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

# WEB SEARCH TRONG AMAZON BEDROCK AGENTCORE

Các mô hình AI hiện nay có khả năng xử lý ngôn ngữ rất tốt, tuy nhiên vẫn tồn tại một hạn chế lớn: chúng chỉ có thể trả lời dựa trên dữ liệu đã được huấn luyện. Khi người dùng đặt câu hỏi về những sự kiện vừa mới xảy ra như tin tức, giá cổ phiếu, tỷ giá tiền tệ hay các sản phẩm vừa được phát hành, AI Agent thường không thể đưa ra câu trả lời chính xác nếu không được kết nối với nguồn dữ liệu bên ngoài.

Để giải quyết vấn đề này, AWS đã giới thiệu **Web Search trên Amazon Bedrock AgentCore**. Đây là một dịch vụ tìm kiếm web được AWS quản lý hoàn toàn, cho phép AI Agent truy cập thông tin mới nhất trên Internet mà không cần tích hợp các Search API của bên thứ ba.

## Những điểm nổi bật

* Cho phép AI Agent truy cập dữ liệu thời gian thực từ Internet.
* Không cần tích hợp Google Search API, Bing Search API hoặc SerpAPI.
* AWS quản lý toàn bộ quá trình tìm kiếm và xử lý dữ liệu.
* Hỗ trợ chuẩn **Model Context Protocol (MCP)** giúp dễ dàng tích hợp với nhiều AI Framework.
* Hoạt động thông qua **Amazon Bedrock AgentCore Gateway**.
* Dữ liệu truy vấn được xử lý hoàn toàn trong hạ tầng AWS, tăng tính bảo mật.
* Kết quả tìm kiếm được tối ưu dưới dạng **Semantic Snippet**, giúp AI chỉ nhận những đoạn nội dung liên quan nhất.
* Hỗ trợ **Knowledge Graph** nhằm nâng cao độ chính xác đối với các câu hỏi về thực thể (Entity).

Tính năng này đặc biệt phù hợp với các hệ thống AI Chatbot, AI Assistant, Research Agent, News Agent hoặc các ứng dụng cần truy cập thông tin luôn được cập nhật theo thời gian thực.

---

## Kiến trúc hoạt động

Quá trình xử lý của Web Search diễn ra theo các bước sau:

1. Người dùng gửi câu hỏi đến AI Agent.
2. AI Agent xác định cần dữ liệu mới ngoài mô hình huấn luyện.
3. Agent gửi yêu cầu đến **Amazon Bedrock AgentCore Gateway**.
4. Gateway sử dụng **Web Search Tool** để truy vấn Web Index của AWS.
5. AWS tìm kiếm và trích xuất những đoạn thông tin phù hợp nhất.
6. Kết quả được gửi lại cho AI Agent.
7. AI Agent tổng hợp câu trả lời và hiển thị cho người dùng kèm nguồn tham khảo.

![Kiến trúc Web Search](/images/3-Blogposted/architecture.png)

---

## Web Search Tool

Việc cấu hình Web Search khá đơn giản. Nhà phát triển chỉ cần thêm một Web Search Tool vào Gateway bằng `connectorId = "web-search"`.

Sau khi được cấu hình, AI Agent sẽ tự động quyết định khi nào cần sử dụng Web Search để lấy dữ liệu mới nhất thay vì chỉ dựa vào kiến thức của mô hình.


---

## Amazon Web Index

Khác với nhiều giải pháp sử dụng công cụ tìm kiếm của bên thứ ba, AWS xây dựng và vận hành **Web Index** của riêng mình.

Theo AWS, Web Index có các đặc điểm:

* Chứa hàng chục tỷ tài liệu trên Internet.
* Nội dung được cập nhật liên tục chỉ sau vài phút.
* Tối ưu cho các mô hình AI.
* Bao phủ nhiều lĩnh vực và nguồn dữ liệu khác nhau.

Nhờ đó AI Agent có thể truy xuất những thông tin mới nhất với độ chính xác cao hơn.

---

## Semantic Snippet Extraction

Thay vì trả về toàn bộ nội dung của một trang web, Web Search sẽ chỉ trích xuất những đoạn văn bản có liên quan trực tiếp đến câu hỏi của người dùng.

Cách tiếp cận này giúp:

* Giảm số lượng token mà mô hình phải xử lý.
* Tăng tốc độ phản hồi.
* Nâng cao độ chính xác.
* Giảm lượng dữ liệu không cần thiết.

---

## Knowledge Graph

Bên cạnh việc tìm kiếm trên Web Index, Web Search còn hỗ trợ **Knowledge Graph**.

Đối với các câu hỏi về:

* Con người
* Tổ chức
* Địa điểm
* Doanh nghiệp

Knowledge Graph sẽ cung cấp dữ liệu có cấu trúc, giúp giảm hiện tượng **hallucination** và cải thiện độ tin cậy của câu trả lời.

---

## Bảo mật

Một ưu điểm đáng chú ý của Web Search trên Amazon Bedrock AgentCore là toàn bộ truy vấn đều được xử lý bên trong hạ tầng AWS.

Điều này giúp:

* Không gửi truy vấn đến Search Engine của bên thứ ba.
* Đơn giản hóa việc quản lý API Key.
* Tăng khả năng bảo mật dữ liệu.
* Phù hợp với các doanh nghiệp có yêu cầu cao về quyền riêng tư.

Quá trình xác thực được thực hiện thông qua IAM Role của AgentCore Gateway.

---

## Khả năng tích hợp

Web Search được xây dựng theo chuẩn **Model Context Protocol (MCP)** nên có thể tích hợp với nhiều framework AI phổ biến như:

* Strands
* LangChain
* LangGraph
* CrewAI

AI Agent có thể tự động khám phá (Discover) Web Search Tool thông qua Gateway và sử dụng khi cần thiết mà không phải lập trình thêm nhiều logic xử lý.

---

## Chi phí

Theo AWS, Web Search được tính phí theo mô hình Pay-as-you-go.

Giá hiện tại:

* **7 USD cho mỗi 1.000 lượt tìm kiếm.**

Điều này giúp doanh nghiệp chỉ phải trả chi phí dựa trên số lượng truy vấn thực tế.

---

## Kết luận

Amazon Bedrock AgentCore Web Search là một tính năng giúp AI Agent vượt qua giới hạn của dữ liệu huấn luyện bằng cách truy cập thông tin mới nhất từ Internet.

Thay vì phải tự xây dựng hệ thống tích hợp Search API, xử lý dữ liệu và quản lý nhiều dịch vụ khác nhau, nhà phát triển chỉ cần cấu hình một Web Search Tool để AWS đảm nhận toàn bộ quá trình tìm kiếm, xác thực và tối ưu dữ liệu.

Đây là một giải pháp phù hợp cho các ứng dụng AI cần dữ liệu thời gian thực như chatbot thông minh, trợ lý nghiên cứu, tổng hợp tin tức, phân tích thị trường và các hệ thống hỗ trợ khách hàng.

---

## Tài liệu tham khảo

**AWS Machine Learning Blog**

Introducing Web Search on Amazon Bedrock AgentCore

https://aws.amazon.com/blogs/machine-learning/introducing-web-search-on-amazon-bedrock-agentcore/