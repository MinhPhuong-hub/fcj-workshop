---
title: "Chia sẻ, đóng góp ý kiến"
weight: 7
chapter: false
pre: "<b>7. </b>"
slug: "7-feedback"
---

# Chia sẻ, đóng góp ý kiến

## Đánh giá chung

### 1. Môi trường làm việc

Môi trường thực tập giúp em có điều kiện tiếp cận Cloud Computing theo hướng thực tế hơn so với việc chỉ đọc lý thuyết. Trong quá trình thực tập, em được học theo các workshop AWS, đối chiếu với tài liệu chính thống của AWS và tự ghi lại tiến độ bằng worklog hằng tuần. Điều này giúp em hình thành thói quen học có hệ thống hơn: đọc tài liệu, thực hành lab, ghi chú lỗi gặp phải, sau đó tổng hợp lại thành nội dung có thể trình bày được.

Điểm em đánh giá cao là chương trình không chỉ yêu cầu làm lab rời rạc, mà còn yêu cầu xây dựng proposal, AWS diagram và project cuối kỳ. Nhờ vậy, em có cơ hội hiểu rõ hơn mối liên hệ giữa từng dịch vụ AWS với một bài toán kiến trúc hoàn chỉnh.

### 2. Sự hỗ trợ của mentor / team admin

Mentor và team admin đã hỗ trợ tốt trong việc định hướng tài liệu, yêu cầu nộp bài và cách trình bày kết quả. Các hướng dẫn từ workshop giúp em có điểm bắt đầu rõ ràng, đặc biệt trong giai đoạn đầu khi em còn chưa quen với AWS Console, IAM, VPC, EC2 và các khái niệm về private/public subnet.

Trong quá trình làm project cuối kỳ, những góp ý về proposal và diagram giúp em nhận ra rằng một sơ đồ AWS không chỉ cần có đủ service, mà còn phải thể hiện đúng luồng nghiệp vụ, boundary bảo mật, quyền truy cập và bằng chứng vận hành. Đây là phần em thấy có giá trị nhất vì nó buộc em phải hiểu lý do thiết kế, không chỉ vẽ diagram cho đẹp.

### 3. Sự phù hợp giữa công việc và chuyên ngành học

Nội dung thực tập phù hợp với chuyên ngành Công nghệ thông tin và giúp em mở rộng từ kiến thức lập trình/hệ thống sang hướng Cloud Architecture và Cloud Security. Những phần em học được có liên hệ trực tiếp với các mảng sau:

* **Cloud Computing:** làm quen với AWS Console, EC2, VPC, RDS, CloudWatch, IAM và các dịch vụ nền tảng.
* **Network & Security:** hiểu public/private subnet, route table, security group, IAM role, least privilege và private-by-default design.
* **System Design:** biết cách biến yêu cầu thành kiến trúc có thành phần, luồng dữ liệu, boundary và cơ chế giám sát.
* **Documentation:** viết worklog, proposal, mô tả diagram và chuẩn hóa nội dung trong Hugo workshop.

Trước khi thực tập, em thường nhìn từng dịch vụ AWS như các phần riêng lẻ. Sau 12 tuần, em hiểu hơn cách kết nối chúng thành một workload có mục tiêu rõ ràng, ví dụ một private worker có thể đọc cấu hình, xử lý task, ghi log/evidence và hạn chế truy cập public.

### 4. Cơ hội học hỏi & phát triển kỹ năng

Trong 12 tuần thực tập, em phát triển được cả kỹ năng kỹ thuật và tư duy kiến trúc.

Kỹ năng kỹ thuật:

* Cấu hình IAM theo nguyên tắc least privilege.
* Thiết kế VPC có public/private subnet, route table và security group.
* Triển khai EC2, hiểu AMI, user data và kết nối quản trị an toàn hơn.
* Làm quen Amazon RDS theo hướng private database, subnet group, backup và kết nối từ application/worker.
* Sử dụng CloudWatch Logs, Metrics, Alarms để tạo bằng chứng vận hành.
* Tìm hiểu AWS Budgets, cost awareness và cleanup tài nguyên sau lab.
* Tiếp cận Infrastructure as Code bằng CloudFormation/Terraform ở mức nền tảng.

Kỹ năng mềm:

* Ghi chép tiến độ theo tuần, tránh học xong nhưng không tổng hợp được.
* Đọc tài liệu tiếng Anh và lọc ý chính để áp dụng vào project.
* Trao đổi với bạn cùng nhóm trong 2 tuần cuối để thống nhất proposal, diagram và hướng triển khai.
* Nhận feedback, sửa lại diagram sai và điều chỉnh cách trình bày cho rõ hơn.

Điểm tiến bộ rõ nhất của em là khả năng giải thích kiến trúc. Ban đầu em chỉ biết “service này dùng để làm gì”, nhưng về cuối em có thể nói rõ hơn “vì sao service này xuất hiện trong diagram, nó giao tiếp với thành phần nào, rủi ro là gì và bằng chứng kiểm tra nằm ở đâu”.

### 5. Văn hóa & tinh thần đồng đội

Trong quá trình thực tập, em thấy tinh thần làm việc nhóm và hỗ trợ lẫn nhau là yếu tố quan trọng. Khi làm riêng các tuần đầu, mỗi người có thể tập trung vào hướng học riêng. Nhưng đến 2 tuần cuối, khi phải hoàn thiện proposal, sửa AWS diagram và triển khai project, việc thống nhất cách hiểu giữa hai người trở nên rất cần thiết.

Em và bạn cùng nhóm đã phân chia vai trò theo hướng hợp lý hơn: em tập trung nhiều vào kiến trúc, security boundary, IAM, VPC private design, monitoring và evidence; bạn em tập trung nhiều hơn vào triển khai, vận hành, kiểm thử, tài liệu hóa và cleanup. Cách chia này giúp project có sự phối hợp tốt hơn thay vì cả hai làm trùng hoàn toàn một phần.

### 6. Chính sách / phúc lợi cho thực tập sinh

Chương trình thực tập có tài liệu và lộ trình khá rõ, phù hợp với sinh viên mới tiếp cận AWS. Việc sử dụng workshop, tài liệu AWS chính thống, worklog, proposal và project cuối kỳ giúp thực tập sinh vừa học, vừa có sản phẩm cụ thể để chứng minh quá trình học.

Em đặc biệt đánh giá cao việc chương trình yêu cầu làm diagram và proposal. Đây là hai phần khó hơn việc chạy lab, nhưng lại giúp em hiểu bài sâu hơn. Nếu chỉ chạy lab, em có thể hoàn thành thao tác nhưng chưa chắc giải thích được thiết kế. Khi phải viết proposal và bảo vệ diagram, em buộc phải kiểm tra lại từng thành phần và từng đường kết nối.

Nếu có thể bổ sung thêm, em mong chương trình có thêm một số buổi review diagram hoặc review proposal sớm hơn trước tuần cuối. Điều này sẽ giúp thực tập sinh phát hiện lỗi kiến trúc sớm, tránh dồn quá nhiều chỉnh sửa vào giai đoạn cuối.

---

## Một số câu hỏi khác

### Điều bạn hài lòng nhất trong thời gian thực tập?

Điều em hài lòng nhất là em đã có một cách nhìn rõ hơn về AWS Architecture. Trước đây em học cloud theo kiểu dịch vụ nào cũng biết một ít, nhưng chưa có điểm neo để hiểu vì sao các dịch vụ đó cần đứng chung trong một hệ thống. Sau quá trình thực tập, đặc biệt là khi làm proposal và diagram, em hiểu hơn cách đặt câu hỏi: workload này phục vụ mục tiêu gì, dữ liệu đi qua đâu, phần nào cần private, ai có quyền truy cập, log/evidence nằm ở đâu và chi phí có được kiểm soát không.

Em cũng hài lòng vì bản thân đã cải thiện khả năng tự học. Thay vì chỉ làm theo từng bước, em biết đối chiếu workshop với AWS Docs, ghi lại lỗi, sửa nội dung trong Hugo và tổng hợp kết quả thành worklog.

### Điều bạn nghĩ công ty cần cải thiện cho các thực tập sinh sau?

Theo em, chương trình đã có nền tảng tốt. Tuy nhiên, để các bạn thực tập sinh sau học hiệu quả hơn, em có một số góp ý:

* Nên có checklist rõ hơn cho từng mốc nộp: worklog, proposal, diagram, project và self-assessment.
* Nên có một buổi review AWS diagram ở giữa kỳ hoặc trước tuần cuối để tránh sửa lỗi kiến trúc quá muộn.
* Nên có ví dụ ngắn về một project đạt yêu cầu: có problem statement, business/action flow, diagram, evidence và cleanup.
* Nên ghim các thông báo quan trọng về deadline, format nộp bài và yêu cầu song ngữ để tránh thực tập sinh bỏ sót.

Những điểm này không làm thay đổi cấu trúc chương trình, nhưng sẽ giúp thực tập sinh mới giảm nhầm lẫn và tập trung nhiều hơn vào chất lượng kỹ thuật.

### Nếu giới thiệu cho bạn bè, bạn có khuyên họ thực tập ở đây không? Vì sao?

Có. Em sẽ khuyên bạn bè tham gia nếu các bạn thật sự muốn học AWS theo hướng thực hành. Chương trình phù hợp với người muốn có lộ trình từ cơ bản đến project, đặc biệt là những bạn muốn hiểu Cloud không chỉ ở mức “biết tên service”, mà còn biết cách giải thích luồng triển khai, bảo mật, vận hành và chi phí.

Tuy nhiên, em cũng sẽ nói rõ rằng chương trình cần sự chủ động. Nếu chỉ làm theo lab mà không đọc thêm AWS Docs, không ghi chú lỗi và không tự hỏi vì sao kiến trúc được thiết kế như vậy, kết quả học được sẽ không sâu. Người học cần chủ động đặt câu hỏi, đọc lại tài liệu và kiểm tra lại project của mình.

---

## Đề xuất & mong muốn

### Bạn có đề xuất gì để cải thiện trải nghiệm trong kỳ thực tập?

Em đề xuất bổ sung thêm một buổi hướng dẫn ngắn về cách đánh giá AWS diagram. Nội dung có thể tập trung vào các câu hỏi cơ bản như:

* Diagram đã thể hiện đúng public/private boundary chưa?
* Service nào xử lý nghiệp vụ chính?
* Dữ liệu đi từ đâu đến đâu?
* Có IAM role, security group và monitoring/evidence chưa?
* Có thể chứng minh project đã chạy bằng log, metric hoặc screenshot nào?

Nếu có checklist kiểu này, thực tập sinh sẽ dễ tự kiểm tra project hơn trước khi nộp.

### Bạn có muốn tiếp tục chương trình này trong tương lai?

Có. Nếu có cơ hội, em muốn tiếp tục học sâu hơn về Cloud Security, Infrastructure as Code và kiến trúc workload private trên AWS. Em cũng muốn thực hành thêm các dịch vụ như VPC Endpoint, SQS, EventBridge, SNS, CloudWatch Alarm, KMS và Systems Manager để hiểu rõ hơn cách triển khai một workload nội bộ an toàn, có log/evidence và có kiểm soát chi phí.

Ngoài ra, em muốn tiếp tục cải thiện khả năng viết tài liệu kỹ thuật song ngữ, vì trong quá trình làm workshop bằng Hugo, em nhận ra rằng tài liệu tốt không chỉ cần đúng kỹ thuật mà còn phải rõ cấu trúc, dễ đọc và dễ kiểm tra.

### Góp ý khác:

Em cảm ơn công ty, mentor và team admin đã tạo điều kiện để em được tiếp cận AWS theo hướng thực tế. Kỳ thực tập giúp em nhận ra rằng học Cloud không chỉ là tạo tài nguyên trên AWS, mà còn là hiểu kiến trúc, bảo mật, vận hành, chi phí và cách chứng minh hệ thống hoạt động đúng.

Sau 12 tuần, em thấy mình có nền tảng tốt hơn để tiếp tục học Cloud Architecture và Cloud Security. Em vẫn cần cải thiện tốc độ triển khai, khả năng diễn đạt ngắn gọn và kỹ năng kiểm tra diagram, nhưng quá trình thực tập đã giúp em có hướng học rõ ràng hơn.

---

Đây là chia sẻ chân thực dựa trên trải nghiệm cá nhân của em trong quá trình thực tập.
