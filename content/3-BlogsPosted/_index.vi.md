---
title: "Các bài blogs đã đăng"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 3. </b> "
---


### [Blog 1 - SERVERLESS BOOKSTORE: LÀM QUEN VỚI AWS LAMBDA FUNCTIONS](3.2-Blog2/)
Blog này chia sẻ trải nghiệm tìm hiểu **AWS Lambda** – dịch vụ Serverless Computing giúp chạy code mà không cần tự quản lý máy chủ. Nội dung giải thích cách Lambda hoạt động theo cơ chế **Event-driven** với các nguồn sự kiện phổ biến như **S3, DynamoDB, API Gateway, EventBridge, SNS, SQS**, vai trò của **IAM Execution Role** trong việc cấp quyền, cách **CloudWatch** hỗ trợ giám sát và debug, cùng lưu ý quan trọng về vòng lặp vô hạn khi cấu hình **S3 Trigger** không đúng cách.


### [Blog 2 - TỰ ĐỘNG HÓA QUẢN LÝ DỮ LIỆU: TRIỂN KHAI HỆ THỐNG BACKUP & RESTORE TOÀN DIỆN TRÊN AWS](3.1-Blog1/)
Blog này giới thiệu cách xây dựng hệ thống **Backup & Restore** tự động trên AWS bằng cách kết hợp **AWS Backup, Amazon SNS, AWS Lambda và Amazon EC2**. Nội dung tập trung vào việc triển khai hạ tầng bằng **CloudFormation**, thiết lập kế hoạch sao lưu theo tag, tự động kiểm tra khả năng khôi phục sau mỗi lần backup và tối ưu chi phí bằng cách dọn dẹp tài nguyên phục hồi, giúp nâng cao tính sẵn sàng và an toàn cho hệ thống.

### [Blog 3 - AWS KMS – SAU KHI TÌM HIỂU, MÌNH HIỂU GÌ VỀ DỊCH VỤ QUẢN LÝ KHÓA MÃ HÓA CỦA AWS?](3.3-Blog3/)
Blog này chia sẻ những kiến thức và trải nghiệm của mình sau khi tìm hiểu **AWS Key Management Service (AWS KMS)** và thực hành mã hóa dữ liệu trên **Amazon S3**. Nội dung tập trung giới thiệu cơ chế quản lý khóa mã hóa, sự khác biệt giữa **Encryption in Transit** và **Encryption at Rest**, cách hoạt động của **CMK** và **Data Key**, đồng thời minh họa việc kết hợp **AWS KMS**, **IAM**, **Amazon S3** và **AWS CloudTrail** để xây dựng hệ thống lưu trữ dữ liệu an toàn và kiểm soát quyền truy cập hiệu quả.