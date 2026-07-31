---
title: "Chia sẻ, đóng góp ý kiến"
date: 2026-07-30
weight: 7
chapter: false
pre: " <b> 7. </b> "
--------------------

Dưới đây là những chia sẻ và góp ý của tôi sau quá trình tham gia chương trình First Cloud AI Journey, hy vọng giúp team FCAJ hoàn thiện chương trình hơn cho các khóa sau.

**1. Môi trường học tập và trải nghiệm thực tế**

Chương trình tạo ra một môi trường học tập chủ động, trong đó người tham gia không chỉ tiếp nhận kiến thức mà còn phải tự tìm hiểu, thử nghiệm và giải quyết các vấn đề phát sinh. Việc được thực hành trực tiếp với AWS, Docker, Machine Learning và các công cụ triển khai giúp tôi hiểu rõ hơn cách các thành phần kết nối với nhau trong một hệ thống thực tế. Đặc biệt, quá trình xây dựng dự án theo nhóm giúp việc học không chỉ dừng ở từng dịch vụ riêng lẻ mà được liên kết thành một quy trình phát triển hoàn chỉnh.

**2. Sự hỗ trợ của mentor / team admin**

Trong quá trình tham gia, mentor và team admin đã hỗ trợ khá kịp thời khi nhóm gặp khó khăn về kỹ thuật hoặc cần định hướng cho các bước tiếp theo. Tôi đánh giá cao cách hỗ trợ tập trung vào việc gợi ý hướng tiếp cận, cung cấp tài liệu hoặc đặt câu hỏi để nhóm tự phân tích, thay vì đưa ra lời giải có sẵn. Cách làm này giúp tôi chủ động hơn trong việc tìm hiểu nguyên nhân, thử nghiệm các phương án và nâng cao khả năng tự giải quyết vấn đề.

**3. Sự phù hợp giữa nội dung và định hướng nghề nghiệp**

Nội dung của chương trình phù hợp với định hướng phát triển của tôi trong lĩnh vực Cloud và AI. Lộ trình từ kiến thức AWS cơ bản, kiến trúc serverless, Docker đến việc tích hợp mô hình Machine Learning đã giúp tôi có cái nhìn rõ hơn về cách xây dựng và triển khai một ứng dụng trên nền tảng cloud. Bên cạnh kiến thức kỹ thuật, các buổi chia sẻ cộng đồng cũng giúp tôi hiểu thêm về công việc thực tế, yêu cầu của doanh nghiệp và những kỹ năng cần tiếp tục phát triển trong tương lai.

**4. Cơ hội học hỏi và phát triển kỹ năng**

Thông qua quá trình học tập và thực hiện dự án, tôi cải thiện được khả năng tự học, tìm kiếm tài liệu và chuyển kiến thức thành các phần chức năng cụ thể. Việc phối hợp với các thành viên trong nhóm cũng giúp tôi rèn luyện kỹ năng phân chia công việc, trao đổi tiến độ, thống nhất giải pháp và xử lý các vấn đề trong quá trình tích hợp. Ngoài ra, việc viết tài liệu, tổng hợp kết quả và xây dựng báo cáo bằng tiếng Anh giúp tôi nâng cao khả năng trình bày nội dung kỹ thuật một cách rõ ràng và có hệ thống.

**5. Góp ý cải thiện**

Tôi mong chương trình có thể bổ sung một số nội dung hỗ trợ cho các khóa sau: (1) cung cấp roadmap hoặc checklist rõ hơn cho từng giai đoạn để người học dễ theo dõi tiến độ và xác định các kiến thức cần hoàn thành; (2) tổ chức thêm các buổi review kiến trúc hoặc demo giữa kỳ để các nhóm có cơ hội nhận phản hồi sớm trước khi hoàn thiện dự án; (3) bổ sung thêm tài liệu hướng dẫn về quy trình triển khai và xử lý các lỗi thường gặp khi tích hợp nhiều dịch vụ AWS; và (4) dành thêm thời gian cho phần tối ưu, kiểm thử và đánh giá hệ thống sau khi hoàn thành phiên bản đầu tiên.

**7. Sau khi nộp — giai đoạn tiếp nhận phản hồi và phát triển thêm (01/08 – 14/08/2026)**

Báo cáo được nộp ngày 31/07/2026, nhưng kỳ Thực tập ngoài trường của Trường kéo dài tới 14/08/2026. Nhóm dùng hai tuần còn lại để khép vòng lặp thay vì dừng lại:

* **Thu thập phản hồi.** Nhóm tổng hợp bình luận về ba bài blog từ cộng đồng AWS Study Group và các câu hỏi nhận được trong buổi cộng đồng ngày 25/07, rồi biến chúng thành một danh sách vấn đề đã sắp thứ tự ưu tiên.
* **Xử lý kết quả model.** Phản hồi rõ nhất nằm ở phần đánh giá của mục 5.3 — model fine-tune thấp hơn baseline TF-IDF về macro-F1 vì Colab bản miễn phí chặn việc train ở 3 epoch. Trong giai đoạn này nhóm train lại trên runtime GPU trả phí kèm early stopping theo macro-F1, và bắt đầu đối chứng với một encoder pretrain riêng cho tiếng Việt. Các kết quả đó không được đưa vào báo cáo chấm điểm, vì báo cáo chỉ trình bày những gì đã đo được tính tới ngày nộp.
* **Làm chắc hệ thống.** Giảm cold start bằng cách tinh gọn container image, thêm kiểm tra độ dài đầu vào ở phía server thay vì chỉ dựa vào `maxLength` của trình duyệt, và thêm giới hạn tần suất theo IP ở API Gateway.
* **Tài liệu.** Viết runbook triển khai để một thành viên mới có thể dựng lại toàn bộ hệ thống từ một tài khoản AWS trống.

Giai đoạn này chính là mục đích của hai tuần sau ngày nộp, và cũng là nơi phần lớn các mục "nếu làm lại nhóm sẽ làm gì" ở mục 5.3 thực sự được thử nghiệm.

**6. Giới thiệu chương trình**

Tôi chắc chắn sẽ giới thiệu First Cloud AI Journey cho bạn bè cùng ngành — đây là một trong số ít chương trình cho sinh viên trải nghiệm trọn vẹn chu trình xây dựng sản phẩm cloud thực tế với chi phí gần như bằng 0.
