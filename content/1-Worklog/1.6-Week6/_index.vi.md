---
title: "Worklog Tuần 6"
date: 2026-07-30
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
----------------------

### Tuần 6: Giám sát dịch vụ và bảo mật cơ bản trên AWS

**Thời gian:** 15/06/2026 – 21/06/2026

#### Mục tiêu

* Tìm hiểu các công cụ logging và monitoring trên AWS
* Thực hành thu thập log, theo dõi metrics và thiết lập cảnh báo cho dịch vụ
* Tìm hiểu cách sử dụng IAM Role và áp dụng nguyên tắc đặc quyền tối thiểu

#### Công việc đã thực hiện

* Học về Amazon CloudWatch, CloudWatch Logs, Metrics và Alarms; tìm hiểu cách các công cụ này hỗ trợ theo dõi trạng thái và hiệu suất của dịch vụ trên AWS
* Kích hoạt logging cho AWS Lambda và kiểm tra log được ghi lại trên CloudWatch Logs để theo dõi quá trình thực thi và hỗ trợ xử lý lỗi
* Thực hành theo dõi các metrics cơ bản của Lambda, đồng thời tạo một CloudWatch Alarm để phát hiện và cảnh báo khi một chỉ số vượt quá ngưỡng đã thiết lập
* Tìm hiểu cách sử dụng IAM Role để cấp quyền cho các dịch vụ AWS truy cập tài nguyên cần thiết mà không phải lưu thông tin xác thực trực tiếp trong mã nguồn
* Nghiên cứu nguyên tắc đặc quyền tối thiểu (least privilege) và cách chỉ cấp các quyền cần thiết cho người dùng hoặc dịch vụ

#### Kết quả đạt được

* Hiểu được vai trò của CloudWatch Logs, Metrics và Alarms trong việc giám sát các dịch vụ trên AWS
* Có thể bật logging cho Lambda, kiểm tra log và tạo cảnh báo cơ bản dựa trên các metrics
* Biết cách sử dụng CloudWatch để theo dõi hoạt động và hỗ trợ phát hiện sự cố của dịch vụ
* Hiểu được vai trò của IAM Role và nguyên tắc least privilege trong việc tăng cường bảo mật cho hệ thống
