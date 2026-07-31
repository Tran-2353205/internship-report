---
title: "Blog 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 3.2. </b> "
---
# SERVERLESS BOOKSTORE: LÀM QUEN VỚI AWS LAMBDA FUNCTIONS

AWS Lambda là dịch vụ Serverless Computing trên nền tảng AWS, cho phép chạy code mà không cần tự quản lý máy chủ. Thay vì phải chuẩn bị hạ tầng, cài đặt môi trường, theo dõi tài nguyên như khi dùng EC2, Lambda chỉ chạy khi có sự kiện xảy ra và tự động thu hồi tài nguyên sau khi hoàn thành, giúp tiết kiệm chi phí và phù hợp với các tác vụ xử lý theo sự kiện như upload file, gửi email hay xử lý ảnh.

Các điểm chính cần nắm:

* AWS Lambda là dịch vụ **Serverless Computing**, cho phép chạy code mà không cần tự quản lý, cấu hình hay bảo trì máy chủ.
* Hoạt động theo cơ chế **Event-driven**: Lambda chỉ khởi động khi nhận được sự kiện (Event) từ các dịch vụ AWS khác.
* Có thể nhận sự kiện kích hoạt từ nhiều nguồn như **Amazon S3, DynamoDB, API Gateway, EventBridge, SNS, SQS**.
* Lambda mặc định không có quyền truy cập bất kỳ dịch vụ AWS nào; cần cấp quyền thông qua **IAM Execution Role**.
* **Amazon CloudWatch** tự động ghi lại thời gian thực thi, số lần gọi, trạng thái thành công/lỗi và log do lập trình viên in ra.
* Cần lưu ý về rủi ro **vòng lặp vô hạn** khi cấu hình S3 Trigger: nếu Lambda ghi kết quả trở lại cùng Bucket đã kích hoạt nó, file mới sẽ tiếp tục kích hoạt Lambda và gây ra hàng nghìn lượt thực thi ngoài ý muốn.
* Nên lưu kết quả sang một Bucket khác hoặc cấu hình Trigger để chỉ xử lý một số loại file nhất định nhằm tránh lỗi trên.

AWS Lambda đặc biệt phù hợp với các tác vụ xử lý theo sự kiện, quy mô nhỏ và không cần chạy liên tục, giúp lập trình viên tập trung vào việc viết code thay vì quản lý hạ tầng, đồng thời tối ưu chi phí và khả năng mở rộng cho các kiến trúc Cloud hiện đại.


## Hướng dẫn thực hiện

### Bước 1: Tìm hiểu về AWS Lambda

- Truy cập dịch vụ **AWS Lambda** trên AWS Console.
- Tìm hiểu khái niệm Serverless Computing và sự khác biệt giữa Lambda và EC2.
- Xác định các tác vụ phù hợp để triển khai bằng Lambda, ví dụ: tạo thumbnail ảnh, kiểm tra định dạng file, gửi email xác nhận đơn hàng.

### Bước 2: Tạo Lambda Function

- Chọn **Create Function**.
- Chọn runtime phù hợp (ví dụ: Python, Node.js).
- Viết đoạn code xử lý tác vụ mong muốn.

### Bước 3: Cấu hình Execution Role

- Tạo hoặc chọn một **IAM Role** cho Lambda Function.
- Cấp quyền cần thiết để Lambda có thể truy cập các dịch vụ AWS liên quan, ví dụ như Amazon S3.

### Bước 4: Thiết lập Trigger

- Cấu hình sự kiện kích hoạt (Trigger) cho Lambda, ví dụ như sự kiện upload file lên **Amazon S3**.
- Kiểm tra kỹ cấu hình để tránh vòng lặp vô hạn nếu output cũng được ghi vào cùng Bucket kích hoạt Trigger.

### Bước 5: Kiểm tra và giám sát

- Thực hiện thao tác kích hoạt sự kiện (ví dụ: upload file lên S3).
- Truy cập **Amazon CloudWatch** để xem log, thời gian thực thi và trạng thái chạy của Lambda Function.
- Kiểm tra và xử lý lỗi nếu có dựa trên thông tin log.

### Kết quả đạt được

- Hiểu được khái niệm và vai trò của **AWS Lambda** trong kiến trúc Serverless.
- Phân biệt được sự khác nhau giữa **Lambda** và **EC2** trong cách vận hành.
- Nắm được cơ chế **Event-driven** và các nguồn sự kiện phổ biến kích hoạt Lambda.
- Hiểu vai trò của **IAM Execution Role** trong việc cấp quyền cho Lambda.
- Biết cách sử dụng **CloudWatch** để giám sát và debug Lambda Function.
- Nhận biết và biết cách phòng tránh lỗi **vòng lặp vô hạn** khi cấu hình S3 Trigger.

![](/images/3-Blog/Blog-1/blog-1.png)

## Nguồn tham khảo

- Workshop: https://000078.awsstudygroup.com/
- Video hướng dẫn: https://youtu.be/eOBq__h4OJ4?si=ulpAoOrEMKxXV9iq

