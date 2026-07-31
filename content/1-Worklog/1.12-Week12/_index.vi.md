---
title: "Worklog Tuần 12"
date: 2026-07-13
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Tuần 12: Hoàn thiện training, tích hợp UI, demo và bàn giao báo cáo

**Thời gian:** 27/07/2026 – 31/07/2026

#### Mục tiêu

* Hoàn thiện quá trình training và kết quả đánh giá model
* Tích hợp giao diện demo với backend và hoàn tất kiểm thử end-to-end
* Chuẩn bị báo cáo cuối cùng và bàn giao demo cho nhóm

#### Công việc đã thực hiện

* Hoàn thành vòng training cuối cùng trên bộ dữ liệu đã làm sạch, chọn checkpoint tốt nhất và ghi lại các chỉ số chính như accuracy, precision, recall và F1 score
* Export model đã train để sẵn sàng triển khai và ghi lại pipeline training cùng các tham số đã điều chỉnh
* Triển khai giao diện demo bằng React, kết nối form nhập liệu với endpoint phân loại, và hiển thị kết quả rõ ràng cho cả tiếng Việt và tiếng Anh
* Tiến hành kiểm thử end-to-end trên demo UI với các ví dụ comment độc hại và bình thường, xác nhận kết quả model và sửa các lỗi tích hợp frontend/backend
* Ghi lại ảnh chụp màn hình demo, tài liệu hóa các trường hợp sử dụng và chuẩn bị phần đóng góp cuối cho báo cáo nhóm

#### Kết quả đạt được

* demo UI hoạt động kết nối với model đã train, kèm chỉ số đánh giá và ảnh minh hoạ sẵn sàng cho báo cáo cuối cùng
* Bàn giao bộ dữ liệu đã làm sạch, code training và prototype frontend cho nhóm để triển khai và đánh giá
