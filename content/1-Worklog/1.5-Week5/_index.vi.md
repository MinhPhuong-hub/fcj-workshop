---
title: "Worklog tuần 5"
weight: 5
chapter: false
pre: " <b>1.5 </b> "
---

# Worklog tuần 5: Amazon RDS, subnet group, backup và kết nối ứng dụng

**Thời gian:** 11/05/2026 - 17/05/2026

## Mục tiêu tuần 5

- Hiểu RDS là managed relational database và khác với tự cài database trên EC2.
- Thực hành DB subnet group, security group, backup/snapshot và kết nối từ EC2.
- Áp dụng nguyên tắc database private cho project cuối kỳ.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học tổng quan RDS, DB instance, engine, parameter group và subnet group<br>- Ghi chú vì sao RDS không nên public trong workload nội bộ | 11/05/2026 | 11/05/2026 | [RDS Workshop](https://000005.awsstudygroup.com/vi/)<br>[RDS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) |
| 3 | - Tạo DB subnet group trong private subnet<br>- Cấu hình security group chỉ cho phép EC2 app/worker truy cập DB | 12/05/2026 | 12/05/2026 | [RDS Workshop](https://000005.awsstudygroup.com/vi/)<br>[Security Group Docs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html) |
| 4 | - Tạo RDS MySQL/PostgreSQL lab và kết nối từ EC2<br>- Kiểm tra endpoint, port, credential và network path | 13/05/2026 | 13/05/2026 | [RDS Getting Started](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)<br>[RDS Workshop](https://000005.awsstudygroup.com/vi/) |
| 5 | - Thực hành backup/snapshot và theo dõi trạng thái backup<br>- Ghi chú cách RDS hỗ trợ vận hành so với database tự quản lý | 14/05/2026 | 14/05/2026 | [RDS Backup Lab](https://000005.awsstudygroup.com/vi/)<br>[RDS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) |
| 6-CN | - Viết phần ghi chú cho project: worker ghi trạng thái job vào RDS, RDS không nhận traffic Internet<br>- Dọn dẹp DB instance sau lab để tránh chi phí | 15/05/2026 | 17/05/2026 | [RDS Cleanup Lab](https://000005.awsstudygroup.com/vi/)<br>[AWS Budgets Workshop](https://000007.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 5

- Hiểu luồng EC2 kết nối RDS qua private networking và security group.
- Nắm được các thao tác backup/snapshot cơ bản và ý nghĩa của managed database.
- Chốt nguyên tắc project: RDS private, không SSH vào database host, credential không hard-code trong source.


---
