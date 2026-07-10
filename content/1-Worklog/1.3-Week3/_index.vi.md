---
title: "Worklog tuần 3"
weight: 3
chapter: false
pre: " <b>1.3 </b> "
---

# Worklog tuần 3: VPC, subnet, route table và truy cập private

**Thời gian:** 27/04/2026 - 03/05/2026

## Mục tiêu tuần 3

- Thiết kế được VPC cơ bản với public/private subnet.
- Hiểu Internet Gateway, NAT Gateway, route table, security group và network boundary.
- Chuẩn bị nền tảng network cho project private-by-default.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học khái niệm VPC, CIDR, subnet, route table, Internet Gateway và NAT Gateway<br>- Vẽ sơ đồ mạng mức cơ bản bằng ký hiệu AWS | 27/04/2026 | 27/04/2026 | [VPC Workshop](https://000003.awsstudygroup.com/vi/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) |
| 3 | - Tạo VPC lab gồm public subnet và private subnet<br>- Kiểm tra route table và gateway attachment | 28/04/2026 | 28/04/2026 | [Create VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/create-vpc.html)<br>[VPC Workshop](https://000003.awsstudygroup.com/vi/) |
| 4 | - Cấu hình security group cho EC2 và kiểm tra inbound/outbound rule<br>- Ghi chú khác biệt security group và subnet boundary | 29/04/2026 | 29/04/2026 | [Security Group Docs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html)<br>[Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) |
| 5 | - Tìm hiểu hướng truy cập private bằng SSM Session Manager hoặc EC2 Instance Connect Endpoint<br>- Phân tích vì sao project cuối kỳ không cần mở SSH/RDP ra Internet | 30/04/2026 | 30/04/2026 | [Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |
| 6-CN | - Review diagram network, sửa nhãn public/private subnet<br>- Ghi lại tiêu chí network đúng: database không public, worker private, endpoint/service access rõ ràng | 01/05/2026 | 03/05/2026 | [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)<br>[VPC Workshop](https://000003.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 3

- Tạo được tư duy thiết kế VPC theo boundary: public layer, private workload layer và managed service layer.
- Hiểu vai trò security group trong kiểm soát traffic tới EC2/RDS.
- Chuẩn bị được tiêu chí kiểm tra diagram cuối kỳ: service nào nằm trong private subnet, service nào là regional managed service, service nào dùng để audit/evidence.


---
