---
title: "Tự đánh giá"
weight: 6
chapter: false
pre: "<b>6. </b>"
slug: "6-self-rating"
---

# Tự đánh giá

Trong suốt thời gian thực tập từ **17/04/2026 đến 10/07/2026**, tôi đã tập trung xây dựng nền tảng Cloud theo hướng **Cloud Security / Infrastructure Architect**. Nội dung học và thực hành được triển khai theo worklog 12 tuần, bắt đầu từ việc làm quen AWS Free Tier, IAM, VPC, EC2, RDS, Auto Scaling, CloudWatch, Cost Management, Infrastructure as Code, sau đó chuyển sang hoàn thiện proposal, AWS diagram và triển khai project cuối kỳ.

Ban đầu, tôi còn gặp khó khăn trong việc liên kết các dịch vụ AWS thành một kiến trúc hoàn chỉnh. Tôi có thể hiểu từng dịch vụ riêng lẻ, nhưng chưa tự tin khi giải thích vì sao một workload cần private subnet, IAM role, security group, VPC endpoint, monitoring và evidence. Sau quá trình thực tập, tôi đã cải thiện khả năng đọc tài liệu chính thống, đối chiếu với lab AWS Study Group, ghi chép worklog theo tuần và chuyển kiến thức rời rạc thành thiết kế kiến trúc có mục tiêu rõ ràng.

Thông qua quá trình thực tập, tôi đã cải thiện các nhóm kỹ năng chính:

- **Kỹ thuật:** IAM, least privilege, VPC private design, EC2, RDS private database, CloudWatch Logs/Metrics/Alarms, AWS Budgets, CloudFormation/Terraform và kiểm tra kiến trúc theo hướng private-by-default.
- **Tư duy kiến trúc:** Biết phân tách public/private boundary, xác định luồng truy cập giữa EC2 worker, RDS, SQS/EventBridge, CloudWatch, SNS và các thành phần bảo mật.
- **Tài liệu và báo cáo:** Ghi worklog 12 tuần, tổng hợp nguồn học, viết proposal, chỉnh AWS diagram và giải thích được lý do thiết kế.
- **Làm việc nhóm:** Phối hợp với bạn cùng nhóm trong 2 tuần cuối để hoàn thiện proposal, sửa diagram bị sai và triển khai project thống nhất.

Tôi nhận thấy bản thân vẫn cần cải thiện tốc độ triển khai thực tế và kỹ năng diễn đạt ngắn gọn khi giải thích kiến trúc. Tuy nhiên, quá trình thực tập đã giúp tôi có nền tảng rõ hơn về cách học AWS: không chỉ chạy lab cho xong, mà phải hiểu mục tiêu vận hành, rủi ro bảo mật, chi phí và bằng chứng kiểm tra sau triển khai.

---

## Bảng đánh giá theo tiêu chí

| STT | Tiêu chí | Mô tả | Tốt | Khá | Trung bình |
|---|---|---|---|---|---|
| 1 | Kiến thức và kỹ năng chuyên môn | Hiểu IAM, VPC, EC2, RDS, CloudWatch, IaC và áp dụng vào project AWS | ✅ | ☐ | ☐ |
| 2 | Khả năng học hỏi | Tự học từ AWS Study Group, AWS Docs và ghi chú lại theo worklog hằng tuần | ✅ | ☐ | ☐ |
| 3 | Chủ động | Chủ động tìm hiểu lỗi diagram, đọc thêm tài liệu và đề xuất hướng chỉnh sửa | ✅ | ☐ | ☐ |
| 4 | Tinh thần trách nhiệm | Hoàn thành worklog, proposal, diagram và phần triển khai project đúng tiến độ | ✅ | ☐ | ☐ |
| 5 | Kỷ luật | Có theo dõi tiến độ, nhưng đôi lúc còn cần rà soát lại format trước khi nộp | ☐ | ✅ | ☐ |
| 6 | Tính cầu tiến | Sẵn sàng nhận feedback, sửa diagram sai và điều chỉnh proposal theo yêu cầu | ✅ | ☐ | ☐ |
| 7 | Giao tiếp | Giải thích được ý chính, nhưng cần luyện cách trình bày ngắn gọn hơn khi bảo vệ | ☐ | ✅ | ☐ |
| 8 | Hợp tác nhóm | Phối hợp với bạn cùng nhóm trong 2 tuần cuối để thống nhất proposal và project | ✅ | ☐ | ☐ |
| 9 | Ứng xử chuyên nghiệp | Tôn trọng quy trình học, nguồn tài liệu chính thống và yêu cầu của công ty | ✅ | ☐ | ☐ |
| 10 | Tư duy giải quyết vấn đề | Biết truy nguyên lỗi từ diagram, requirement, network boundary và luồng triển khai | ✅ | ☐ | ☐ |
| 11 | Đóng góp vào dự án/tổ chức | Đóng góp chính vào kiến trúc, diagram, security boundary và evidence | ✅ | ☐ | ☐ |
| 12 | Tổng thể | Hoàn thành tốt quá trình thực tập theo hướng Cloud Security / Infrastructure Architect | ✅ | ☐ | ☐ |

---

## Cần cải thiện

- Cần luyện thêm tốc độ triển khai thực tế bằng Terraform/CloudFormation để giảm phụ thuộc vào thao tác thủ công.
- Cần trình bày AWS architecture ngắn gọn hơn, tập trung vào problem, solution, flow và security control.
- Cần rèn kỹ năng kiểm tra diagram sớm hơn để tránh sửa nhiều ở giai đoạn cuối.
- Cần tiếp tục học sâu về VPC Endpoint, SQS/EventBridge, CloudWatch Alarm và cost optimization trong workload private.
- Cần luyện cách biến log, metric và screenshot thành evidence rõ ràng cho người chấm hoặc người vận hành.
