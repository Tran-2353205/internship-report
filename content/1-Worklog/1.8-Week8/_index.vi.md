---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Bắt đầu triển khai phần backend cho dự án Website Quản lý thư viện bằng Django.
* Khởi tạo cấu trúc dự án Django và kết nối tới cơ sở dữ liệu.
* Xây dựng các app Django cốt lõi và expose thành RESTful API bằng Django REST Framework.
* Áp dụng kiến thức AWS đã học vào quá trình phát triển.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| T2 | - Khởi tạo cấu trúc dự án Django trên GitHub <br>&emsp;+ Tạo project Django và các app ban đầu (books, readers, accounts) <br>&emsp;+ Thiết lập các nhánh phát triển <br>&emsp;+ Thống nhất coding convention cho Django cùng nhóm | 27/07/2026 | 27/07/2026 | Team Discussion |
| T3 | - Thiết lập môi trường phát triển Django <br>&emsp;+ Cấu hình Docker và Docker Compose <br>&emsp;+ Định nghĩa Django model và chạy makemigrations/migrate <br>&emsp;+ Kết nối Django với database qua Django ORM | 28/07/2026 | 28/07/2026 | Team Discussion |
| T4 | - Xây dựng module Quản lý sách <br>&emsp;+ Model, serializer và DRF viewset cho sách (CRUD) <br>&emsp;+ Model, serializer và DRF viewset cho thể loại (CRUD) <br>&emsp;+ Kiểm thử các API cốt lõi bằng Postman | 29/07/2026 | 29/07/2026 | Team Discussion |
| T5 | - Xây dựng module Quản lý độc giả <br>&emsp;+ Model, serializer và DRF viewset cho độc giả (CRUD) <br>&emsp;+ API quản lý tài khoản người dùng (dùng hệ thống authentication của Django) <br>&emsp;+ Kiểm thử tích hợp giữa Django và database | 30/07/2026 | 30/07/2026 | Team Discussion |
| T6 | - Tham gia buổi review Sprint 1 <br> - Đánh giá tiến độ triển khai Django <br> - Khắc phục các vấn đề phát sinh và cập nhật kế hoạch phát triển backend cho tuần tiếp theo | 31/07/2026 | 31/07/2026 | Team Discussion |

### Kết quả đạt được tuần 8:

* Hoàn thành khởi tạo dự án Django và cấu hình môi trường phát triển cục bộ.

* Thiết lập cấu trúc dự án Django (các app books, readers, accounts) trên GitHub và thống nhất quy trình làm việc chung với nhóm.

* Cấu hình thành công Docker và Docker Compose, thiết lập kết nối ổn định giữa Django và database qua Django ORM.

* Xây dựng thành công các chức năng backend cốt lõi của hệ thống bằng Django REST Framework:
  * API Quản lý sách
  * API Quản lý thể loại
  * API Quản lý độc giả

* Kiểm thử thành công các API cốt lõi bằng Postman, xác nhận dữ liệu được lưu trữ và truy xuất chính xác qua Django ORM.

* Hoàn thành sprint phát triển backend đầu tiên và xác định các công việc cần thực hiện trong giai đoạn hoàn thiện tiếp theo.
