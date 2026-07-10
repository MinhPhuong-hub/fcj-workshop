---
title: "Worklog tuần 2"
weight: 2
chapter: false
pre: " <b>1.2 </b> "
---

# Worklog tuần 2: IAM, phân quyền và nguyên tắc least privilege

**Thời gian:** 20/04/2026 - 26/04/2026

## Mục tiêu tuần 2

- Hiểu IAM user, group, policy, role và temporary credentials.
- Thực hành phân quyền theo nhóm, switch role và policy giới hạn thao tác.
- Ghi lại các lỗi phân quyền thường gặp khi làm lab.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học mô hình IAM: principal, action, resource, condition<br>- Ghi chú khác biệt giữa IAM user, IAM group, IAM role và policy | 20/04/2026 | 20/04/2026 | [IAM Workshop](https://000002.awsstudygroup.com/vi/)<br>[IAM Docs](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) |
| 3 | - Tạo mô hình phân quyền mẫu: Admin, Operator, ReadOnly<br>- Thực hành switch role và kiểm tra phiên quyền tạm thời | 21/04/2026 | 21/04/2026 | [Switch Role Lab](https://000002.awsstudygroup.com/vi/)<br>[IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html) |
| 4 | - Viết policy kiểm soát region và instance type dùng trong lab<br>- Kiểm tra tác động của allow/deny và condition trong IAM policy | 22/04/2026 | 22/04/2026 | [IAM Docs](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)<br>[EC2 Cost Governance Lab](https://000004.awsstudygroup.com/vi/) |
| 5 | - Liên hệ IAM với project cuối kỳ: EC2 worker cần instance profile, không hard-code access key<br>- Ghi checklist quyền tối thiểu cho worker | 23/04/2026 | 23/04/2026 | [IAM Role Lab](https://000002.awsstudygroup.com/vi/)<br>[Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) |
| 6-CN | - Tổng hợp lỗi gặp khi cấp quyền sai resource hoặc thiếu trust relationship<br>- Dọn dẹp user/role/policy thử nghiệm không cần thiết | 24/04/2026 | 26/04/2026 | [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)<br>[AWS Free Tier Workshop](https://000001.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 2

- Nắm được cách IAM kiểm soát xác thực và ủy quyền trong AWS.
- Biết sử dụng role thay cho access key cố định khi service cần gọi AWS API.
- Có checklist least privilege áp dụng cho EC2 worker, RDS, SQS, CloudWatch và S3 evidence trong project cuối kỳ.


---
