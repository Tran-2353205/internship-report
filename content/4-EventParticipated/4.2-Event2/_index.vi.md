---
title: "Event 2"
date: 2026-06-20
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---
# Bài thu hoạch "Cloud Architect"

### Mục Tiêu Sự Kiện

- Tạo sân chơi công nghệ tương tác cao dưới hình thức đấu trí trắc nghiệm, vừa thắt chặt tình đoàn kết vừa kích thích tinh thần chủ động học hỏi của các thành viên.
- Hệ thống hóa toàn bộ kiến thức cốt lõi về thiết kế kiến trúc hệ thống trên AWS thông qua các bài toán tình huống thực tế.
- Rèn luyện tư duy quản trị rủi ro, phản xạ đưa ra quyết định dưới áp lực thời gian và nâng cao kỹ năng làm việc nhóm.
- Mở rộng mạng lưới kết nối giữa các nhóm thực tập sinh và cộng đồng sinh viên đam mê Điện toán đám mây.

### Danh Sách 8 Đội Tranh Tài

- **NGŨ ĐẠI HIỆP**
- **KTLT**
- **PrimeOps**
- **YoungFlame IT**
- **LOSERR**
- **GẶP PHẢI THẰNG LIỀU**
- **LIFE LONG LEARNER**
- **KLKAT**

---

### Nội Dung Nổi Bật

#### 1. An ninh, Tuân thủ & Quản trị vận hành (Security, Compliance & Operations)

- **AWS Artifact:** Công cụ tra cứu các báo cáo và chứng chỉ tuân thủ quốc tế (ISO, PCI, SOC) phục vụ nhu cầu kiểm toán.
- **AWS WAF:** Cấu hình Rate-based Rule giúp ngăn chặn hiệu quả các cuộc tấn công Layer 7 và kiểm soát lưu lượng truy cập bất thường mà vẫn tối ưu trải nghiệm người dùng.
- **Amazon S3 Bucket Policy:** Cơ chế kiểm soát và phân quyền truy cập chi tiết đối với tài nguyên lưu trữ tĩnh.
- **AWS Systems Manager Patch Manager:** Tự động hóa quy trình quản lý bản vá (Patch Groups, Patch Baselines) dựa trên EC2 Tags, giúp tối ưu chi phí và thời gian vận hành.

#### 2. AWS Well-Architected Framework

- Đánh giá và áp dụng các trụ cột cốt lõi trong **AWS Well-Architected Framework**.
- Đi sâu vào trụ cột **Performance Efficiency** (Hiệu năng vận hành), chú trọng việc lựa chọn đúng chủng loại và quy mô tài nguyên phù hợp với nhu cầu hệ thống.

#### 3. Cơ sở dữ liệu & Xử lý sự kiện (Database & Event Handling)

- **Amazon DynamoDB:** Giải pháp tối ưu cho các ứng dụng di động có lưu lượng truy cập lớn nhờ độ trễ cực thấp và khả năng tự động mở rộng (Auto Scaling).
- **DynamoDB Streams + AWS Lambda:** Mô hình kiến trúc kích hoạt xử lý dữ liệu tự động ngay khi có thay đổi.
- Phân biệt rõ ngữ cảnh áp dụng thực tế giữa **DynamoDB Streams** và **DAX Cluster**.

#### 4. Hạ tầng Cloud, Hybrid Architecture & Auto Scaling

- **AWS Storage Gateway (File Gateway):** Giải pháp Hybrid Cloud kết nối mượt mà hạ tầng On-Premises sẵn có với AWS qua giao thức SMB.
- **Amazon S3 Lifecycle Rules:** Thiết lập quy tắc tự động chuyển dữ liệu sao lưu sang Amazon S3 Glacier để lưu trữ dài hạn và tối ưu ngân sách.
- **AWS Pricing Calculator:** Công cụ dự toán chi phí hạ tầng chính xác trước khi tiến hành triển khai.
- **Amazon EC2 Auto Scaling:** Tự động điều chỉnh quy mô tài nguyên linh hoạt theo biến động lưu lượng thực tế.
- **Application Load Balancer (ALB):** Định tuyến lưu lượng thông minh thông qua Path-based Routing và Host-based Routing.

#### 5. Yếu tố chiến thuật trong cuộc thi

- **Chiến thuật "Rủi ro tối thiểu":** Ưu tiên giải pháp an toàn để bảo toàn điểm số khi đối mặt với các câu hỏi chưa chắc chắn.
- **Thẻ "Ngôi sao hy vọng":** Lựa chọn thời điểm vàng để nhân đôi điểm số, tạo bước ngoặt chiến lược trong các câu hỏi mang tính quyết định.

---

### Giá Trị Thu Hoạch

#### Tư Duy Thiết Kế Hệ Thống

- **Quản trị rủi ro & Đánh đổi (Trade-offs):** Học cách đánh giá rủi ro và cân bằng giữa Chi phí - Hiệu năng - Bảo mật khi thiết kế giải pháp.
- **Hiện đại hóa & Tự động hóa:** Hiểu cách phối hợp giữa Serverless, Hybrid Storage và các công cụ quản trị tự động nhằm tối ưu hóa quy trình vận hành.

#### Kỹ Năng Kiến Trúc Chuyên Sâu

- Phân biệt rõ ranh giới và phạm vi ứng dụng của các cặp dịch vụ AWS: **WAF vs NACL**, **DynamoDB Streams vs DAX**, **ALB vs NLB**, **Systems Manager vs Custom Scripts**.
- Thấu hiểu và biết cách vận dụng linh hoạt các nguyên tắc chuẩn từ **AWS Well-Architected Framework** vào bài toán thực tế.

---

### Trải Nghiệm & Cảm Nhận Cá Nhân

Đóng vai trò là khán giả theo dõi gameshow **“Cloud Architect”**, đây là một trải nghiệm học tập đầy mới mẻ, giúp các khái niệm kỹ thuật của AWS trở nên trực quan và dễ tiếp thu hơn rất nhiều.

#### Tiếp thu qua các tình huống thực tiễn

- Bộ câu hỏi được thiết kế bám sát thực tế doanh nghiệp, giúp tôi tự kiểm tra và đánh giá lại năng lực của bản thân.
- Phần giải thích đáp án chi tiết từ Ban Tổ chức giúp tôi hiểu rõ bản chất vì sao một dịch vụ cụ thể lại là lựa chọn tối ưu nhất cho từng bài toán.

#### Bầu không khí thi đấu sôi nổi

- Việc quan sát các đội thi phân tích bài toán và ra quyết định giúp tôi học hỏi được tư duy xử lý vấn đề nhanh chóng dưới áp lực thời gian.
- Màn rượt đuổi tỷ số gay kịch giữa 8 đội thi mang lại nguồn năng lượng tích cực và cảm hứng học tập mạnh mẽ.
- Việc ứng dụng các chiến thuật như **"Ngôi sao hy vọng"** hay **"Rủi ro tối thiểu"** minh họa rõ nét tầm quan trọng của việc quản trị rủi ro và ra quyết định đúng thời điểm.

#### Giao lưu và kết nối

- Sự kiện là cầu nối giúp tôi gặp gỡ, trao đổi kinh nghiệm với các bạn học viên có chung niềm đam mê Điện toán đám mây.
- Qua các cuộc thảo luận bên lề, tôi đúc kết thêm nhiều góc nhìn mới về cách tiếp cận các bài toán kiến trúc Cloud thực tế.

#### Bài học cốt lõi

- Phương pháp học qua tình huống giúp ghi nhớ kiến thức AWS sâu sắc và trực quan hơn hẳn lý thuyết thuần túy.
- Thiết kế hệ thống đòi hỏi góc nhìn toàn diện về Chi phí, Hiệu năng, Bảo mật và Khả năng mở rộng trước khi quyết định chọn dịch vụ.
- Đọc kỹ yêu cầu bài toán và thấu hiểu đặc tính từng dịch vụ AWS là chìa khóa để đưa ra quyết định kiến trúc chính xác.

#### Hình ảnh ghi nhận tại sự kiện

![](/images/4-Event/event2.jpg)

> Tóm lại, cuộc thi **Cloud Architect** không chỉ là một buổi củng cố kiến thức AWS hiệu quả mà còn rèn luyện cho tôi tư duy phân tích, khả năng so sánh các phương án kiến trúc và cách ra quyết định trong tình huống thực tế. Đây là một trải nghiệm học tập đắt giá, tạo thêm động lực để tôi tiếp tục theo đuổi và phát triển sự nghiệp trong lĩnh vực Cloud Computing.