---
title: "Worklog tuần 6"
weight: 6
chapter: false
pre: " <b>1.6 </b> "
---

# Worklog tuần 6: Auto Scaling, Load Balancing và tính sẵn sàng

**Thời gian:** 18/05/2026 - 24/05/2026

## Mục tiêu tuần 6

- Hiểu Auto Scaling Group, Launch Template và Elastic Load Balancer ở mức ứng dụng web.
- Phân biệt workload public web app với internal worker không cần public ALB.
- Rút ra tiêu chí scaling phù hợp cho project cuối kỳ.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học Launch Template, AMI, user data và Auto Scaling Group<br>- Ghi chú quan hệ giữa template và instance được tạo tự động | 18/05/2026 | 18/05/2026 | [ASG Workshop](https://000006.awsstudygroup.com/vi/)<br>[EC2 Docs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html) |
| 3 | - Thực hành tạo ASG cho ứng dụng mẫu<br>- Kiểm tra desired/min/max capacity và health check | 19/05/2026 | 19/05/2026 | [ASG Workshop](https://000006.awsstudygroup.com/vi/) |
| 4 | - Tìm hiểu ELB và cách phân phối traffic đến nhiều instance<br>- Vẽ lại luồng web app: user → load balancer → EC2 → RDS | 20/05/2026 | 20/05/2026 | [ASG Workshop](https://000006.awsstudygroup.com/vi/)<br>[Well-Architected Reliability](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) |
| 5 | - So sánh ASG web app với internal worker queue-based<br>- Ghi chú vì sao project cuối kỳ ưu tiên queue/SQS thay vì public load balancer | 21/05/2026 | 21/05/2026 | [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)<br>[CloudWatch Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) |
| 6-CN | - Tổng hợp bài học về availability, health check, scaling signal và cost<br>- Dọn dẹp ASG, launch template và instance test | 22/05/2026 | 24/05/2026 | [ASG Cleanup Lab](https://000006.awsstudygroup.com/vi/)<br>[AWS Budget Workshop](https://000007.awsstudygroup.com/vi/) |

---

## Kết quả đạt được tuần 6

- Biết triển khai ASG/Launch Template trong lab và hiểu cách nó hỗ trợ availability.
- Phân biệt được kiến trúc public web app và kiến trúc internal worker.
- Có căn cứ để giải thích trong proposal vì sao project cuối kỳ không dùng public ALB mà dùng event/queue để kích hoạt xử lý nội bộ.


---
