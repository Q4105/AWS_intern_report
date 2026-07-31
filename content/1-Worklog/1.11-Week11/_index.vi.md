---
title: "Worklog Tuần 11"
date: 2026-07-30
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Tuần 11: Tìm dataset, làm sạch dữ liệu, training model và xây dựng giao diện demo

**Thời gian:** 20/07/2026 – 26/07/2026

#### Mục tiêu

* Tìm và chọn bộ dữ liệu phù hợp cho project
* Làm sạch và chuẩn bị dữ liệu để training model
* Bắt đầu xây dựng prototype giao diện demo

#### Công việc đã thực hiện

* Nghiên cứu và đánh giá các bộ dữ liệu tiếng Việt cho bài toán kiểm duyệt văn bản, chọn bộ dữ liệu phù hợp và kiểm tra cấu trúc, nhãn, định dạng
* Viết script làm sạch dữ liệu: chuẩn hoá tiếng Việt, loại bỏ bản ghi trùng, lọc nhiễu, và sửa nhãn không nhất quán
* Chuẩn bị các tập train/val/test với quy tắc tiền xử lý và tokenization đồng nhất
* Thiết lập môi trường training trên Google Colab, chạy lần đầu mô hình trên bộ dữ liệu sạch và theo dõi kết quả đánh giá ban đầu
* Thiết kế luồng giao diện demo bằng React, xây dựng form nhập liệu và khu vực hiển thị kết quả, xác định API contract cho backend

#### Kết quả đạt được

* bộ dữ liệu đã được làm sạch và sẵn sàng cho training, kèm code tiền xử lý được ghi lại trong repo
* Hoàn thành chạy training lần đầu và có mô hình ban đầu để tinh chỉnh
* Prototype UI đã sẵn sàng để kết nối backend và hiển thị kết quả phân loại
