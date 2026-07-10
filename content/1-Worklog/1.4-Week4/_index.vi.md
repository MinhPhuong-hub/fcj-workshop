---
title: "Worklog tuần 4"
weight: 4
chapter: false
pre: " <b>1.4 </b> "
---

# Worklog tuần 4: EC2, AMI, user data và triển khai ứng dụng mẫu

**Thời gian:** 04/05/2026 - 10/05/2026

## Mục tiêu tuần 4

- Thực hành tạo EC2 Linux/Windows và kết nối phù hợp.
- Triển khai ứng dụng mẫu để hiểu compute workload trên AWS.
- Tìm hiểu AMI, snapshot, instance type và user data.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học EC2 instance, AMI, key pair, security group và instance type<br>- Launch thử Linux instance trong môi trường lab | 04/05/2026 | 04/05/2026 | [EC2 Workshop](https://000004.awsstudygroup.com/vi/)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |
| 3 | - Cài web server cơ bản bằng user data<br>- Kiểm tra log khởi tạo và trạng thái instance | 05/05/2026 | 05/05/2026 | [Get Started EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)<br>[EC2 User Data Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-metadata.html) |
| 4 | - Triển khai ứng dụng AWS User Management theo hướng dẫn workshop EC2<br>- Ghi lại dependency cài đặt và lỗi thường gặp khi cấu hình môi trường | 06/05/2026 | 06/05/2026 | [EC2 Workshop](https://000004.awsstudygroup.com/vi/) |
| 5 | - Tạo snapshot/custom AMI sau khi cấu hình xong ứng dụng<br>- Kiểm tra launch instance mới từ AMI | 07/05/2026 | 07/05/2026 | [EC2 AMI Lab](https://000004.awsstudygroup.com/vi/)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |
| 6-CN | - Ghi bài học về compute layer cho project: worker chỉ xử lý nội bộ, không cần public web endpoint<br>- Dọn dẹp instance/AMI/snapshot không dùng | 08/05/2026 | 10/05/2026 | [AWS Budget Workshop](https://000007.awsstudygroup.com/vi/)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |

---

## Kết quả đạt được tuần 4

- Triển khai được EC2 và ứng dụng mẫu, hiểu chu kỳ launch-connect-configure-test-cleanup.
- Biết dùng AMI/snapshot để tái tạo môi trường EC2.
- Rút ra thiết kế cho project cuối kỳ: EC2 worker chạy trong private subnet và chỉ cần quyền/service access đúng chức năng.


---
