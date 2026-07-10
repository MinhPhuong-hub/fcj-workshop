---
title: "Worklog tuần 9"
weight: 9
chapter: false
pre: " <b>1.9 </b> "
---

# Worklog tuần 9: Infrastructure as Code, CloudFormation/Terraform và kiểm tra policy

**Thời gian:** 08/06/2026 - 14/06/2026

## Mục tiêu tuần 9

- Hiểu nguyên tắc Infrastructure as Code và quản lý hạ tầng bằng template/module.
- Tìm hiểu cách mô hình hóa resource AWS trước khi triển khai project.
- Chuẩn bị cách kiểm tra cấu hình để tránh triển khai sai bảo mật.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học khái niệm Infrastructure as Code qua CloudFormation: template, stack, resource, parameter, output<br>- So sánh với cách project dùng Terraform module | 08/06/2026 | 08/06/2026 | [CloudFormation Docs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)<br>[AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) |
| 3 | - Đọc ví dụ khai báo EC2/VPC/RDS bằng template để hiểu mapping resource<br>- Ghi chú các thuộc tính quan trọng: subnet_id, security_group, tags, IAM role | 09/06/2026 | 09/06/2026 | [CloudFormation Resource Reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-template-resource-type-ref.html)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |
| 4 | - Thiết kế module logic cho project: network, security, database, worker, observability, evidence<br>- Viết checklist biến đầu vào và output cần hiển thị | 10/06/2026 | 10/06/2026 | [VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)<br>[RDS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)<br>[CloudWatch Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) |
| 5 | - Tìm hiểu policy-as-code/OPA ở mức kiểm tra ý tưởng: không cho public database, không mở SSH/RDP 0.0.0.0/0, bắt buộc tag<br>- Ghi ra rule kiểm tra cho proposal | 11/06/2026 | 11/06/2026 | [Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)<br>[IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html) |
| 6-CN | - Tổng hợp khung triển khai hạ tầng tuần cuối<br>- Kiểm tra cách tổ chức file trong workshop Hugo để gắn phần kỹ thuật vào đúng trang | 12/06/2026 | 14/06/2026 | [AWS Documentation](https://docs.aws.amazon.com/)<br>[AWS Study Group](https://cloudjourney.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 9

- Hiểu cách IaC giúp triển khai lặp lại và chứng minh cấu hình hạ tầng rõ ràng hơn thao tác tay.
- Xác định được module/boundary chính cho project private-by-default.
- Có checklist rule bảo mật cần kiểm tra trước khi deploy: private subnet, không public DB, security group chặt, tag và output rõ ràng.


---
