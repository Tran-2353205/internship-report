---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Bắt đầu triển khai phần backend cho dự án Website Quản lý thư viện bằng Django.
* Khởi tạo cấu trúc dự án Django, kết nối cơ sở dữ liệu và đóng gói bằng Docker.
* Xây dựng các module cốt lõi và expose thành RESTful API bằng Django REST Framework.
* Tìm hiểu thêm về Amazon CloudWatch để chuẩn bị cho giai đoạn giám sát hệ thống sau khi deploy.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| T2 | - Khởi tạo cấu trúc dự án Django trên GitHub <br>&emsp;+ Tạo project Django và các app ban đầu (books, readers, accounts) <br>&emsp;+ Thiết lập các nhánh phát triển <br>&emsp;+ Thống nhất coding convention cùng nhóm | 27/07/2026 | 27/07/2026 | Team Discussion |
| T3 | - Cấu hình Docker và Docker Compose cho môi trường phát triển <br>&emsp;+ Định nghĩa Django model theo Database Schema đã thiết kế <br>&emsp;+ Kết nối Django với cơ sở dữ liệu PostgreSQL (dùng để test cục bộ) qua Django ORM | 28/07/2026 | 28/07/2026 | Team Discussion |
| T4 | - Xây dựng module Quản lý sách <br>&emsp;+ Model, Serializer và DRF ViewSet cho sách (CRUD) <br>&emsp;+ Model, Serializer và DRF ViewSet cho thể loại (CRUD) <br>&emsp;+ Kiểm thử các API bằng Postman | 29/07/2026 | 29/07/2026 | Team Discussion |
| T5 | - Xây dựng module Quản lý độc giả <br>&emsp;+ Model, Serializer và DRF ViewSet cho độc giả (CRUD) <br>&emsp;+ API quản lý tài khoản người dùng (dùng hệ thống authentication của Django) <br>&emsp;+ Kiểm thử tích hợp giữa Django và database | 30/07/2026 | 30/07/2026 | Team Discussion |
| T6 | - Học: Monitoring with Amazon CloudWatch (metrics, log, alarm) <br> - Tham gia buổi review Sprint 1, khắc phục các vấn đề phát sinh và cập nhật kế hoạch cho tuần deploy | 31/07/2026 | 31/07/2026 | https://000008.awsstudygroup.com |

### Kết quả đạt được tuần 7:

* Hoàn thành khởi tạo dự án Django và thiết lập cấu trúc dự án (app books, readers, accounts) trên GitHub.

* Cấu hình thành công Docker và Docker Compose, thiết lập kết nối ổn định giữa Django và database qua Django ORM.

* Xây dựng thành công các API cốt lõi bằng Django REST Framework: Quản lý sách, Quản lý thể loại, Quản lý độc giả, Quản lý tài khoản người dùng.

* Kiểm thử thành công các API bằng Postman, xác nhận dữ liệu được lưu trữ và truy xuất chính xác.

* Nắm được cách sử dụng Amazon CloudWatch để giám sát tài nguyên, chuẩn bị cho việc theo dõi hệ thống sau khi deploy.

* Hoàn thành sprint phát triển backend đầu tiên, sẵn sàng cho giai đoạn deploy lên AWS trong tuần cuối.
