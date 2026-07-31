---
title: "Event 3"
date: 2026-07-25
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Bài thu hoạch "Agentic AI Build Week (AABW) – Demo Day"

### Mục Tiêu Sự Kiện

- Trình bày thành quả thực tiễn từ chuỗi ngày xây dựng sản phẩm Agentic AI trên nền tảng AWS.
- Tạo sân chơi thực chiến giúp các đội thi ứng dụng hệ sinh thái AWS AI/ML vào giải quyết các bài toán thực tế của doanh nghiệp.
- Kết nối các tài năng trẻ với đội ngũ chuyên gia, mentor giàu kinh nghiệm trong cộng đồng AWS.
- Lan tỏa tinh thần "Build Week" – chuyển hóa ý tưởng thành sản phẩm hoàn chỉnh có khả năng vận hành trong thời gian giới hạn.

### Danh Sách Các Đội Trực Tiếp Tranh Tài

- **3KA:** Huỳnh An Khương, Nguyễn Quốc Huy, Ngô Quang Khôi, Hoàng Lê Thành Đức, Đặng Nguyễn Phước Lộc, Đặng Trường Hưng.
- **OneTeam:** Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy.
- **Plan V:** Pham Tien Thuan Phat, Huynh Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An.
- **Signal Scout:** Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan.

---

### Nội Dung Nổi Bật Từ Các Dự Án

#### 1. Nhóm 3KA – S.H.E.P.H.E.R.D (Giám sát & Quản lý đám đông)
- **Bài toán:** Giám sát mật độ, hàng chờ và cảnh báo ùn tắc thời gian thực tại các địa điểm sự kiện đông người.
- **Giải pháp & Kiến trúc:** Kết hợp **YOLO + ByteTrack** (nhận diện/tracking) + **Amazon SageMaker** (inference) + **Amazon Bedrock AgentCore & Strands Agent** (tầng AI Agent) + Dashboard theo dõi thời gian thực.
- **Điểm sáng:** Vận hành 2 lớp AI linh hoạt: **Autonomous Monitor** (tự động phát hiện, cảnh báo rủi ro chủ động) và **Operator Copilot** (hỗ trợ nhân viên truy vấn số liệu bằng ngôn ngữ tự nhiên).
- **Thách thức:** Duy trì luồng video ổn định, giảm độ trễ inference, tối ưu chi phí và đảm bảo tính giải thích được (explainability) của Agent.

#### 2. Nhóm OneTeam – KFC Bot Agent (Hệ thống đặt hàng qua hội thoại)
- **Bài toán:** Giải quyết đứt gãy trải nghiệm khi mua hàng qua chat (chuyển đổi ứng dụng khiến người dùng bỏ ngang đơn hàng).
- **Giải pháp:** Agent đặt hàng đa kênh (Zalo OA, Messenger) vận hành theo nguyên lý 5 bước: **Goal → Plan → Tools → Act → Verify**.
- **Kết quả:** Độ trễ phản hồi chỉ **3–5 giây**, chi phí tối ưu (**~$0.006/đơn hàng**, **~$88/tháng** hạ tầng) và giảm tới **60% lượng code hạ tầng** nhờ ứng dụng AgentCore.

#### 3. Nhóm Plan V – Solution Architect Professional Native App (Trợ lý AI cho Solution Architect)
- **Bài toán:** Tự động hóa quy trình phân tích tài liệu BRD/SOP, thiết kế kiến trúc và ước tính chi phí vốn tốn nhiều thời gian xử lý thủ công.
- **Giải pháp:** Xây dựng ứng dụng AI-native kết nối **Amazon Bedrock**, **Draw.io MCP** và **AWS Pricing MCP**.
- **Tác động:** Chuyển đổi từ quy trình thủ công sang mô hình "Upload + Chat" – tự động xuất Requirements Catalogue, sơ đồ kiến trúc chuẩn AWS và bảng dự toán chi phí chi tiết chỉ trong vài phút.

#### 4. Nhóm Signal Scout – Tình báo chiến lược doanh nghiệp
- **Bài toán:** Thu thập, kiểm chứng bằng chứng công khai và phát hiện sớm các tín hiệu tái cấu trúc, chuyển hướng chiến lược của đối thủ/doanh nghiệp.
- **Kiến trúc Multi-Agent:** Mô hình **A2A (Agent-to-Agent)** gồm **Crawler Subagent** (thu thập dữ liệu qua TinyFish, Apify) và **Analysis Subagent** (phân tích, kiểm soát qua Bedrock Guardrails, ghi log Langfuse), tích hợp toàn diện hệ thống bảo mật AWS (WAF, Cognito, CloudWatch).
- **Giá trị:** Cung cấp thông tin xác thực hỗ trợ ra quyết định kinh doanh (Maintain – Adapt – Accelerate) với chi phí vận hành tối ưu (**$81–$359/tháng**).

---

### Giá Trị Thu Hoạch

#### Kỹ Thuật Chuyên Sâu
- **Kiến trúc Agentic AI trên AWS:** Làm chủ cách phối hợp Amazon Bedrock, AgentCore Runtime, Strands Agent để tạo ra Agent có khả năng lập kế hoạch, sử dụng công cụ và tự xác minh kết quả.
- **Mô hình Multi-Agent (A2A):** Hiểu rõ tư duy phân tách trách nhiệm giữa các subagent chuyên biệt để tối ưu hiệu năng hệ thống.
- **Tự động hóa & Thị giác máy tính:** Áp dụng xử lý luồng video thời gian thực (YOLO, ByteTrack) và tự động hóa quy trình thiết kế kiến trúc qua các MCP Server.

#### Tư Duy Sản Phẩm
- Luôn xuất phát từ **pain point thực tế** của người dùng trước khi quyết định lựa chọn công nghệ.
- Tối ưu hóa chi phí vận hành (Cost Design) ngay từ bước thiết kế kiến trúc ban đầu.
- Cân bằng giữa tốc độ phát triển trong thời gian ngắn và tính giải thích được (explainability) của mô hình AI.

#### Tư Duy Làm Việc Nhóm
- Thấm nhuần tinh thần *"Execution matters more than perfection"* – một sản phẩm nhỏ chạy hoàn chỉnh có giá trị hơn một ý tưởng lớn dở dang.
- Phân định rõ vai trò và mục tiêu giúp tối ưu hóa hiệu suất làm việc dưới áp lực thời gian.

---

### Ứng Dụng Vào Công Việc Thực Tế

- Áp dụng chu trình tư duy Agentic (**Goal → Plan → Tools → Act → Verify**) khi thiết kế các tính năng tự động hóa hệ thống.
- Thử nghiệm **AgentCore / Strands Agent** cho các bài toán phức tạp cần sự phối hợp của nhiều subagent.
- Sử dụng mô hình trợ lý AI để chuẩn hóa quy trình phân tích tài liệu và lập dự toán chi phí cho các đề xuất giải pháp AWS.

---

### Trải Nghiệm & Cảm Nhận Cá Nhân

Đóng vai trò quan sát viên tại **Agentic AI Build Week – Demo Day** là một trải nghiệm đầy cảm hứng, giúp tôi nhận ra Agentic AI không còn là lý thuyết suông mà đã thực sự sẵn sàng cho các bài toán vận hành thực tế.

#### Sự đa dạng trong góc nhìn ứng dụng
Cả 4 đội thi mang đến 4 bài toán hoàn toàn khác biệt: từ an ninh đám đông, thương mại hội thoại, tư vấn kiến trúc đến tình báo doanh nghiệp. Điều này minh chứng cho tính linh hoạt và sức mạnh vượt trội của hệ sinh thái AWS AI/ML.

#### Tiếp cận kiến trúc thực chiến
Tôi đã tích lũy thêm nhiều kinh nghiệm quý báu về cách triển khai các dịch vụ AWS tân tiến (**Bedrock AgentCore, Strands Agent, AgentCore Gateway/Memory**) cũng như cách các đội giải quyết những bài toán vận hành hóc chuẩn thực tế: quản lý độ trễ, bảo mật Guardrails và tối ưu hóa chi phí.

#### Bài học cốt lõi
- AI đang có sự dịch chuyển mạnh mẽ từ "Chatbot phản hồi" sang "Agent hành động" – có khả năng suy luận, dùng công cụ và thực thi công việc độc lập.
- Việc kết hợp mạch lạc các dịch vụ AWS là chìa khóa then chốt để đưa một ý tưởng từ phòng thí nghiệm ra vận hành ổn định trong môi trường thực tế.

#### Hình ảnh ghi nhận tại sự kiện

![](/images/4-Event/event3.jpg)
![](/images/4-Event/event3-2.jpg)

> Tóm lại, **Agentic AI Build Week Demo Day** không chỉ củng cố kiến thức chuyên môn về AI/ML trên AWS mà còn truyền cảm hứng mạnh mẽ về tinh thần thực chiến: từ bài toán thực tế, chọn kiến trúc tối ưu, cho đến một sản phẩm hoàn chỉnh có thể vận hành thực sự.