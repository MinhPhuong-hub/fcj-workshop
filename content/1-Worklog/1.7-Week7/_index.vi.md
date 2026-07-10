---
title: "Worklog tuần 7"
weight: 7
chapter: false
pre: " <b>1.7 </b> "
---

# Worklog tuần 7: Cost Management, AWS Budgets và cleanup discipline

**Thời gian:** 25/05/2026 - 31/05/2026

## Mục tiêu tuần 7

- Thiết lập cảnh báo chi phí và thói quen dọn dẹp tài nguyên sau lab.
- Hiểu Cost Budget, Usage Budget và giới hạn sử dụng tài nguyên trong môi trường thực tập.
- Liên hệ chi phí với lựa chọn kiến trúc project.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học AWS Billing and Cost Management và AWS Budgets<br>- Tạo Cost Budget với ngưỡng cảnh báo phù hợp cho tài khoản lab | 25/05/2026 | 25/05/2026 | [AWS Budgets Workshop](https://000007.awsstudygroup.com/vi/)<br>[AWS Free Tier Workshop](https://000001.awsstudygroup.com/vi/) |
| 3 | - Tạo Usage Budget để theo dõi mức dùng dịch vụ<br>- Ghi chú các resource dễ phát sinh chi phí: NAT Gateway, RDS, snapshot, EIP, Load Balancer | 26/05/2026 | 26/05/2026 | [Usage Budget Lab](https://000007.awsstudygroup.com/vi/)<br>[AWS Free Tier Workshop](https://000001.awsstudygroup.com/vi/) |
| 4 | - Rà soát tài khoản lab, kiểm tra resource còn chạy<br>- Tạo checklist cleanup theo service: EC2, RDS, ASG, EIP, snapshot, log group | 27/05/2026 | 27/05/2026 | [AWS Budget Workshop](https://000007.awsstudygroup.com/vi/)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)<br>[RDS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) |
| 5 | - Viết ghi chú kiểm soát chi phí cho proposal: tagging, budget alert, cleanup, giới hạn instance type<br>- Liên hệ budget với IAM condition và security governance | 28/05/2026 | 28/05/2026 | [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)<br>[AWS Budgets Workshop](https://000007.awsstudygroup.com/vi/) |
| 6-CN | - Dọn dẹp tài nguyên thử nghiệm trong các lab trước<br>- Kiểm tra lại bill, forecast và log resource còn tồn tại | 29/05/2026 | 31/05/2026 | [Budget Cleanup Lab](https://000007.awsstudygroup.com/vi/)<br>[AWS Free Tier Workshop](https://000001.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 7

- Tạo được Cost Budget/Usage Budget và biết đọc tín hiệu cảnh báo chi phí.
- Hình thành checklist cleanup trước khi chuyển sang lab mới.
- Bổ sung vào tư duy kiến trúc: giải pháp phải chạy được, nhưng cũng phải kiểm soát được chi phí và tài nguyên tồn dư.


---
