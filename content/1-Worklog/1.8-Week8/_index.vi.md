---
title: "Worklog Tuần 8"
date: 2026-07-30
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
----------------------

### Tuần 8: Tích hợp mô hình Machine Learning với AWS Lambda

**Thời gian:** 29/06/2026 – 05/07/2026

#### Mục tiêu

* Tìm hiểu cách tích hợp mô hình Machine Learning với kiến trúc serverless trên AWS
* Thực hành triển khai AWS Lambda bằng container image được lưu trữ trên Amazon ECR
* Kiểm tra khả năng hoạt động của API backend với mô hình Machine Learning
* Tìm hiểu các phương pháp tối ưu thời gian phản hồi và chi phí vận hành

#### Công việc đã thực hiện

* Học cách sử dụng Lambda container image để đóng gói mã nguồn, mô hình Machine Learning và các thư viện cần thiết trong một môi trường triển khai thống nhất
* Tìm hiểu quy trình build Docker image, lưu trữ image trên Amazon ECR và sử dụng image này để tạo hoặc cập nhật Lambda function
* Thực hành triển khai Lambda function chạy bằng container image và kiểm tra quá trình khởi tạo, thực thi của mô hình
* Kết nối Lambda với API endpoint và gửi các request thử nghiệm để kiểm tra khả năng xử lý dữ liệu và trả kết quả của backend
* Tìm hiểu các phương pháp tối ưu response time và chi phí, bao gồm giảm kích thước container image, tối ưu thời gian khởi tạo và lựa chọn cấu hình tài nguyên phù hợp

#### Kết quả đạt được

* Hiểu được quy trình tích hợp mô hình Machine Learning với AWS Lambda thông qua container image
* Triển khai thành công Lambda function sử dụng container image được lưu trữ trên Amazon ECR
* Hoàn thành API backend có khả năng nhận request, chạy mô hình và trả về kết quả
* Có kiến thức cơ bản về các yếu tố ảnh hưởng đến response time và chi phí vận hành của hệ thống serverless
