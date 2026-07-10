---
title: "Worklog tuần 8"
weight: 8
chapter: false
pre: " <b>1.8 </b> "
---

# Worklog tuần 8: CloudWatch, logs, metrics, alarms và evidence

**Thời gian:** 01/06/2026 - 07/06/2026

## Mục tiêu tuần 8

- Hiểu CloudWatch như lớp observability cho AWS workload.
- Thực hành log group, metric, alarm và dashboard.
- Chuẩn bị evidence plane cho project cuối kỳ.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|---|---|---|---|---|
| 2 | - Học tổng quan CloudWatch, Metrics, Logs, Alarms và Dashboard<br>- Ghi chú sự khác nhau giữa log, metric và alarm | 01/06/2026 | 01/06/2026 | [CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)<br>[CloudWatch Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) |
| 3 | - Tạo log group và đọc log từ ứng dụng/lab<br>- Xác định log nào dùng làm bằng chứng khi demo project | 02/06/2026 | 02/06/2026 | [CloudWatch Logs Lab](https://000008.awsstudygroup.com/vi/)<br>[CloudWatch Logs Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html) |
| 4 | - Thực hành metrics và math expression trong CloudWatch<br>- Ghi lại cách nhìn CPU, network, error count và trạng thái tài nguyên | 03/06/2026 | 03/06/2026 | [CloudWatch Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)<br>[CloudWatch Workshop](https://000008.awsstudygroup.com/vi/) |
| 5 | - Tạo alarm đơn giản và đưa vào dashboard<br>- Liên hệ alarm với SNS notification trong project cuối kỳ | 04/06/2026 | 04/06/2026 | [CloudWatch Alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Alarms.html)<br>[CloudWatch Dashboard Lab](https://000008.awsstudygroup.com/vi/) |
| 6-CN | - Thiết kế danh sách evidence cần có: log worker, metric, alarm state, RDS record, queue message, Terraform output<br>- Dọn dẹp log group/dashboard thử nghiệm nếu không cần giữ | 05/06/2026 | 07/06/2026 | [CloudWatch Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)<br>[AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) |

---

## Kết quả đạt được tuần 8

- Hiểu CloudWatch là phần bắt buộc để chứng minh workload thật sự vận hành, không chỉ vẽ diagram.
- Biết phân biệt log để debug, metric để đo trạng thái và alarm để cảnh báo.
- Chuẩn bị được danh sách evidence cho tuần triển khai project.


---
