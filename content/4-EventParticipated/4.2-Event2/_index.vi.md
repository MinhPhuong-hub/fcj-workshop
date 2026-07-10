---
title: "Event 2"
date: 2026-05-23
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch sự kiện Technology Knowledge Sharing

## Mục Đích Của Sự Kiện

Sự kiện được tổ chức nhằm tạo cơ hội kết nối, học hỏi và trao đổi kiến thức giữa các nhà phát triển, kỹ sư hệ thống và chuyên gia công nghệ.

Các nội dung chính của chương trình tập trung vào:

- Tối ưu chi phí và tăng cường bảo mật cho hệ thống ứng dụng.
- Ứng dụng AI để tự động hóa các quy trình vận hành doanh nghiệp.
- Xây dựng hệ thống AI đa tác nhân phục vụ môi trường doanh nghiệp.
- Quản trị dữ liệu, bảo mật và kiểm soát rủi ro khi triển khai AI.
- Phân tích những đặc điểm thực tế của mô hình ngôn ngữ lớn trong môi trường production.
- Chia sẻ phương pháp xây dựng ngữ cảnh hiệu quả khi làm việc với AI.

---

## Danh Sách Diễn Giả

- **Phạm Nguyễn Hải Anh** – G-AsiaPacific Vietnam, AWS Community Builder
- **Nguyễn Tuấn Thịnh** – DevOps Engineer, First Cloud AI Journey
- **Tình Trương** – Platform Engineer, GoTymeX
- **Lâm Vy** – Senior Business Systems Analyst, VPBank
- **Đào Đức** – Solution Architect, Cloud Kinetics

---

## Nội Dung Nổi Bật

### 1. Giải Pháp Nền Tảng Và Tối Ưu Chi Phí Với Amazon CloudFront

Phần trình bày giới thiệu các giải pháp sử dụng Amazon CloudFront nhằm tăng hiệu năng, nâng cao bảo mật và kiểm soát chi phí vận hành hệ thống.

#### Flat-rate Pricing

AWS cung cấp các gói giá cố định dành cho CloudFront, bao gồm:

- Free
- Pro
- Business
- Premium

Mô hình này giúp doanh nghiệp dự đoán chi phí CDN hàng tháng dễ dàng hơn so với hình thức hoàn toàn dựa trên mức sử dụng.

Đặc biệt, việc sử dụng gói chi phí cố định có thể hạn chế nguy cơ phát sinh hóa đơn bất thường khi:

- Ứng dụng tăng trưởng lưu lượng đột biến.
- Nội dung trở nên phổ biến trong thời gian ngắn.
- Hệ thống bị tấn công DDoS với lưu lượng lớn.

#### Tối ưu hóa hạ tầng

Một số lợi ích kỹ thuật đáng chú ý gồm:

- Dữ liệu truyền từ AWS Origins đến CloudFront không phát sinh phí truyền dữ liệu.
- Các tác vụ như thiết lập kết nối TCP và nén HTTP được xử lý tại hệ thống Edge.
- Giảm tải CPU cho máy chủ gốc.
- Giảm lượng dữ liệu đi qua Load Balancer.
- Cải thiện tốc độ phản hồi cho người dùng ở nhiều khu vực khác nhau.

HTTP Compression có thể giúp giảm đáng kể kích thước của các tệp được truyền tải, từ đó cải thiện thời gian tải trang và tiết kiệm băng thông.

#### Phòng chống DDoS phân tán

CloudFront có thể ngăn chặn các cuộc tấn công lưu lượng lớn ngay tại các Edge Location gần nguồn phát sinh.

Cơ chế này giúp:

- Hạn chế lưu lượng độc hại đi vào hệ thống backend.
- Giảm áp lực lên máy chủ gốc.
- Rút ngắn thời gian phản ứng trước tấn công.
- Tăng tính sẵn sàng của ứng dụng.

Ngoài ra, việc hỗ trợ xác thực hai chiều bằng mTLS giúp tăng mức độ bảo mật đối với các hệ thống tài chính hoặc các dịch vụ yêu cầu xác thực nghiêm ngặt.

---

### 2. GenAIOps Và Kỹ Nghệ Ngữ Cảnh

Phần chia sẻ nhấn mạnh rằng chất lượng phản hồi của AI không chỉ phụ thuộc vào mô hình mà còn phụ thuộc rất lớn vào thông tin ngữ cảnh được cung cấp.

#### Tầm quan trọng của Context

Một phản hồi kém chất lượng không phải lúc nào cũng xuất phát từ lỗi của mô hình.

Các nguyên nhân phổ biến có thể gồm:

- Mục tiêu chưa được mô tả rõ ràng.
- Thông tin cung cấp không liên quan đến yêu cầu.
- Thiếu các ràng buộc kỹ thuật.
- Không có tiêu chí đánh giá kết quả.
- Đưa quá nhiều tài liệu không cần thiết vào prompt.

Việc cung cấp quá nhiều dữ liệu có thể làm tăng chi phí token nhưng không đảm bảo kết quả chính xác hơn.

#### Context Quality lớn hơn Context Quantity

Một ngữ cảnh tốt nên bao gồm bốn thành phần:

1. **Goal** – Mục tiêu cần đạt được.
2. **Relevant Information** – Thông tin liên quan và cô đọng.
3. **Constraints** – Các ràng buộc về kỹ thuật, định dạng hoặc phạm vi.
4. **Success Criteria** – Tiêu chí xác định kết quả đạt yêu cầu.

Cách tiếp cận này giúp AI hiểu rõ nhiệm vụ và giảm khả năng tạo ra phản hồi không phù hợp.

#### Xu hướng phát triển của AI

Quá trình ứng dụng AI đang chuyển dịch theo các giai đoạn:

- Từ các prompt đơn lẻ.
- Sang hệ thống quản lý context có cấu trúc.
- Tiến tới khả năng lưu trữ memory dài hạn.
- Xây dựng hệ thống Agent có khả năng phối hợp và quản lý quy trình.

Xu hướng này mở ra khả năng hình thành một “bộ não AI thứ hai”, hỗ trợ người dùng ghi nhớ, phân tích và thực hiện các tác vụ phức tạp.

---

### 3. Tự Động Hóa Quy Trình Doanh Nghiệp Với Amazon Quick Suite

Amazon Quick Suite được giới thiệu như một giải pháp AI hợp nhất, giúp doanh nghiệp tự động hóa các công việc thủ công và lặp lại.

#### Bài toán thực tế

Trong nhiều tổ chức, nhân viên phải dành nhiều thời gian để:

- Thu thập dữ liệu từ nhiều nguồn.
- Tổng hợp báo cáo.
- Phân tích thông tin.
- Ghi biên bản cuộc họp.
- Gửi email thông báo đến các bên liên quan.
- Theo dõi nhiều quy trình vận hành khác nhau.

Những công việc này có thể tiêu tốn thời gian nhưng không tạo ra nhiều giá trị chuyên môn.

#### Hệ sinh thái Agentic AI

Amazon Quick Suite có khả năng:

- Kết nối với hơn 40 nguồn dữ liệu.
- Tích hợp với các mô hình trên Amazon Bedrock.
- Kết nối với nhiều ứng dụng của bên thứ ba.
- Thực hiện hàng nghìn loại tác vụ tự động.
- Hỗ trợ các quy trình trong nhân sự, marketing và chăm sóc khách hàng.

Một ví dụ điển hình là tự động:

1. Ghi nhận nội dung cuộc họp.
2. Tạo biên bản cuộc họp.
3. Xác định các công việc cần thực hiện.
4. Gửi email đến các bên liên quan.

Giải pháp này giúp giảm thời gian thực hiện các tác vụ lặp lại và nâng cao hiệu quả vận hành.

---

### 4. Hệ Thống Đa Tác Nhân Cấp Doanh Nghiệp

Phần trình bày giới thiệu cách sử dụng hệ thống Multi-Agent để giải quyết các bài toán doanh nghiệp phức tạp.

#### Bài toán chấm điểm tín dụng Startup

Các mô hình tín dụng truyền thống thường gặp khó khăn khi đánh giá startup do:

- Thiếu lịch sử tài chính dài hạn.
- Không phù hợp với mô hình dữ liệu tiêu chuẩn.
- Dòng tiền chưa ổn định.
- Giá trị doanh nghiệp phụ thuộc nhiều vào đội ngũ, thị trường và tiềm năng tăng trưởng.

Hệ thống Multi-Agent có thể chia nhỏ quá trình đánh giá thành các Agent chuyên biệt, bao gồm:

- Financial Agent
- Market Agent
- Team Agent
- Risk Agent
- Compliance Agent

Các Agent phối hợp với nhau như một hội đồng tín dụng ảo để đưa ra đánh giá toàn diện hơn.

#### Lợi ích so với Single-Agent

Hệ thống đa tác nhân mang lại:

- Khả năng kiểm tra chéo giữa các Agent.
- Tăng tính minh bạch của quá trình ra quyết định.
- Hỗ trợ kiểm toán và truy vết kết quả.
- Giảm thời gian xử lý hồ sơ.
- Giảm chi phí vận hành cho mỗi quyết định.

Theo nội dung trình bày, thời gian xử lý có thể được rút ngắn từ nhiều tuần xuống còn vài giờ trong một số trường hợp phù hợp.

#### Enterprise-Grade AI

Khi triển khai AI trong môi trường doanh nghiệp, hệ thống cần được thiết kế với các lớp bảo vệ ngay từ đầu.

Một số yêu cầu quan trọng gồm:

- Lọc nội dung đầu vào và đầu ra.
- Phát hiện dữ liệu định danh cá nhân.
- Ngăn chặn Prompt Injection.
- Kiểm soát quyền truy cập.
- Cô lập hệ thống trong VPC Private Subnets.
- Lưu nhật ký và hỗ trợ kiểm toán.
- Quản trị dữ liệu và tuân thủ chính sách doanh nghiệp.

---

### 5. Tính Phi Định Hình Của Mô Hình Ngôn Ngữ Lớn

Một nội dung đáng chú ý khác là tính phi định hình của LLM, kể cả khi mô hình được thiết lập với `temperature = 0`.

#### Bản chất của hiện tượng

Trong thực tế, cùng một đầu vào có thể tạo ra các kết quả không hoàn toàn giống nhau giữa nhiều lần chạy.

Ngay cả khi giảm temperature về mức thấp nhất, hệ thống vẫn có thể xuất hiện sai khác ở:

- Cách lựa chọn từ ngữ.
- Thứ tự nội dung.
- Cấu trúc câu trả lời.
- Kết quả ở các tác vụ phức tạp.

Điều này cho thấy việc đặt `temperature = 0` không đồng nghĩa với khả năng tái tạo kết quả chính xác tuyệt đối.

#### Nguyên nhân

Một số nguyên nhân kỹ thuật có thể gồm:

- Phép tính số dấu phẩy động trên GPU không có tính kết hợp hoàn toàn.
- Thứ tự thực hiện phép tính song song có thể thay đổi.
- Nhà cung cấp dịch vụ thực hiện inference batching.
- Hệ thống phần cứng và phần mềm có thể tối ưu hóa yêu cầu theo các cách khác nhau.

#### Chiến lược giảm thiểu

Một số phương pháp được đề xuất gồm:

- Sử dụng `temperature = 0.1` trong những trường hợp phù hợp.
- Áp dụng majority voting.
- Chạy nhiều lần và lựa chọn kết quả phổ biến nhất.
- Ép đầu ra theo định dạng JSON.
- Sử dụng Regex Grammar hoặc Structured Output.
- Xây dựng hệ thống downstream có khả năng chấp nhận sai khác nhỏ.
- Không phụ thuộc hoàn toàn vào một phản hồi duy nhất của mô hình.

---

## Những Gì Học Được

### Kiểm Soát Chi Phí Và Bảo Mật Hệ Thống

Tôi hiểu rõ hơn cách CloudFront có thể đồng thời cải thiện hiệu năng, giảm tải cho hệ thống backend và hỗ trợ kiểm soát chi phí.

Việc ngăn chặn lưu lượng độc hại tại Edge cũng giúp tăng khả năng bảo vệ hệ thống trước các cuộc tấn công DDoS.

---

### Cải Thiện Chất Lượng Ngữ Cảnh Cho AI

Một trong những bài học quan trọng nhất là:

> Chất lượng ngữ cảnh quan trọng hơn số lượng ngữ cảnh.

Thay vì cung cấp thật nhiều tài liệu cho AI, cần tập trung vào:

- Mục tiêu.
- Thông tin liên quan.
- Ràng buộc.
- Tiêu chí thành công.

Điều này giúp tạo ra phản hồi chính xác hơn và giảm chi phí xử lý.

---

### Tự Động Hóa Quy Trình Bằng Agentic AI

Tôi hiểu thêm cách các AI Agent có thể tự động hóa những công việc lặp lại trong doanh nghiệp.

AI không chỉ được sử dụng để trả lời câu hỏi mà còn có thể:

- Thu thập dữ liệu.
- Phân tích thông tin.
- Tạo báo cáo.
- Gửi email.
- Phối hợp nhiều công cụ.
- Thực hiện quy trình theo nhiều bước.

---

### Thiết Kế Multi-Agent System

Tôi nhận ra rằng các bài toán phức tạp không nên luôn được giao cho một Agent duy nhất.

Việc chia thành nhiều Agent chuyên trách giúp:

- Tăng độ chính xác.
- Giảm phạm vi trách nhiệm của từng Agent.
- Tăng khả năng kiểm tra chéo.
- Dễ kiểm toán và quản trị hơn.

---

### Chấp Nhận Tính Biến Thiên Của AI

LLM không phải là hệ thống hoàn toàn xác định.

Do đó, khi xây dựng ứng dụng AI, cần:

- Kiểm tra đầu ra.
- Áp dụng xác thực dữ liệu.
- Sử dụng định dạng có cấu trúc.
- Chuẩn bị cơ chế xử lý khi kết quả thay đổi.
- Không xem AI là nguồn quyết định duy nhất trong các tác vụ quan trọng.

---

## Ứng Dụng Vào Công Việc

Sau sự kiện, tôi nhận thấy có thể áp dụng các kiến thức đã học theo những hướng sau:

- Sử dụng CloudFront để cải thiện hiệu năng và bảo vệ các ứng dụng web.
- Thiết kế chiến lược cache và phân phối nội dung phù hợp.
- Xây dựng prompt theo cấu trúc Goal, Relevant Information, Constraints và Success Criteria.
- Hạn chế đưa các dữ liệu không liên quan vào context.
- Sử dụng Structured Output khi tích hợp LLM vào ứng dụng.
- Xây dựng các bước kiểm tra kết quả AI trước khi đưa vào hệ thống downstream.
- Nghiên cứu mô hình Multi-Agent cho các bài toán có nhiều vai trò chuyên môn.
- Đưa Guardrails và cơ chế bảo mật vào hệ thống AI ngay từ giai đoạn thiết kế.
- Tự động hóa các tác vụ lặp lại bằng AI Agent và các công cụ tích hợp.

---

## Trải Nghiệm Trong Sự Kiện

Tham gia sự kiện là cơ hội giúp tôi tiếp cận nhiều góc nhìn thực tế về Cloud, AI và hệ thống doanh nghiệp.

### Kiến Thức Thực Tiễn

Các nội dung không chỉ tập trung vào lý thuyết mà còn đưa ra nhiều bài toán cụ thể, chẳng hạn như:

- Kiểm soát chi phí CDN.
- Phòng chống DDoS.
- Tự động hóa biên bản cuộc họp.
- Xây dựng hệ thống chấm điểm tín dụng startup.
- Quản lý tính phi định hình của LLM.

Những ví dụ này giúp tôi dễ hình dung cách áp dụng công nghệ vào môi trường thực tế.

### Góc Nhìn Về Enterprise AI

Tôi hiểu rằng việc xây dựng một demo AI tương đối đơn giản, nhưng đưa hệ thống vào production lại yêu cầu nhiều yếu tố hơn:

- Bảo mật.
- Tuân thủ.
- Khả năng kiểm toán.
- Quản trị dữ liệu.
- Kiểm soát truy cập.
- Giám sát và xử lý lỗi.

### Thay Đổi Tư Duy Khi Làm Việc Với AI

Trước đây, tôi thường tập trung nhiều vào cách viết prompt.

Sau sự kiện, tôi nhận ra rằng một hệ thống AI hiệu quả còn phụ thuộc vào:

- Chất lượng context.
- Bộ nhớ.
- Công cụ tích hợp.
- Quy trình Agent.
- Guardrails.
- Cơ chế xác thực kết quả.

### Kết Nối Và Trao Đổi

Sự kiện cũng tạo cơ hội để giao lưu với các kỹ sư, chuyên gia và thành viên trong cộng đồng công nghệ.

Thông qua các phần trình bày, tôi có thêm nhiều góc nhìn về cách các doanh nghiệp triển khai Cloud và AI trong thực tế.

---

## Bài Học Rút Ra

- CloudFront không chỉ là CDN mà còn là một thành phần quan trọng trong bảo mật và tối ưu chi phí.
- Context Engineering có vai trò rất lớn đối với chất lượng phản hồi của AI.
- Multi-Agent phù hợp với các bài toán có nhiều vai trò và yêu cầu kiểm tra chéo.
- Guardrails cần được thiết kế ngay từ đầu, không nên bổ sung sau khi hệ thống đã hoàn thành.
- LLM luôn có mức độ biến thiên nhất định, ngay cả khi temperature được đặt ở mức thấp.
- Hệ thống AI trong production cần có cơ chế kiểm tra, giám sát và xử lý sai lệch.
- AI Agent có tiềm năng tự động hóa nhiều quy trình vận hành trong doanh nghiệp.

---

## Một Số Hình Ảnh Khi Tham Gia Sự Kiện

<!-- Đổi tên và đường dẫn ảnh theo file thực tế của bạn -->

![image](/fcj-workshop/images/4-Event/event2-1.jpg)

![H](/fcj-workshop/images/4-Event/event2-2.jpg)

![H](/fcj-workshop/images/4-Event/event2-3.jpg)

> Sự kiện giúp tôi hiểu rõ hơn rằng việc triển khai Cloud và AI trong doanh nghiệp không chỉ phụ thuộc vào công nghệ, mà còn đòi hỏi tư duy hệ thống, khả năng quản trị rủi ro, kiểm soát dữ liệu và thiết kế quy trình phù hợp.