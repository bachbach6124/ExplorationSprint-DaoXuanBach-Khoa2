# Rủi ro và cách hạn chế

Prototype chỉ minh họa việc tìm lịch. Không có lịch thật, không đặt hẹn và không đưa lời khuyên y tế.

| Rủi ro | Có thể xảy ra | Cách hạn chế | Khi nào phải dừng |
|---|---|---|---|
| Lịch đã thay đổi nhưng vẫn hiện còn trống | Người dùng không đặt được hoặc mất niềm tin | Chỉ dùng lịch được cập nhật; kiểm tra lại trước khi xác nhận; báo rõ giờ cập nhật. Demo luôn ghi là lịch giả. | Không xác minh được lịch từ nguồn. |
| Gợi ý bị hiểu là đánh giá bác sĩ | Người dùng nghĩ bác sĩ đứng đầu giỏi hơn | Nêu lý do như “còn lịch sớm”; không chấm điểm chuyên môn; luôn cho tự chọn bác sĩ. | Người dùng hiểu thứ tự là xếp hạng chất lượng. |
| Người dùng hỏi về triệu chứng hoặc cấp cứu | Họ có thể chậm tìm trợ giúp phù hợp | Dừng luồng đặt lịch và hướng tới cơ sở y tế/kênh cấp cứu phù hợp. Không hỏi thêm triệu chứng. | Có nội dung về triệu chứng, thuốc, xét nghiệm hoặc cấp cứu. |
| Lộ thông tin cá nhân | Ảnh hoặc ghi chép có thể nhận diện người tham gia | Dùng mã P1–P3; không lưu tên, số điện thoại, hồ sơ hay ghi âm; rà soát ảnh trước khi chia sẻ. | Phát hiện thông tin nhận diện hoặc sức khỏe. |
| AI tạo giờ hoặc thông tin sai | Người dùng tin vào lịch không có thật | Chỉ lấy giờ từ hệ thống lịch; nếu không có dữ liệu thì báo không biết. Demo dùng dữ liệu giả có nhãn. | Xuất hiện giờ, cơ sở hoặc bác sĩ không có trong nguồn. |
| Một số người khó dùng giao diện | Họ không tìm được giờ hoặc bộ lọc cần thiết | Dùng câu chữ đơn giản, chữ dễ đọc; không bắt buộc dùng AI; giữ kênh hỗ trợ. | Người dùng liên tục không hiểu hoặc không thao tác được. |
| Giờ hẹn bị hiểu là không phải chờ | Người dùng kỳ vọng sai khi đến viện | Ghi rõ giờ hẹn không đảm bảo không phải chờ. | Giao diện hứa hoặc ám chỉ chắc chắn không phải chờ. |

## Khi có câu hỏi y tế khẩn cấp

1. Dừng hỗ trợ tìm lịch; không trả lời y khoa và không hỏi thêm về tình trạng.
2. Hướng người dùng liên hệ cơ sở y tế hoặc dịch vụ cấp cứu phù hợp tại địa phương.
3. Không lưu nội dung sức khỏe vào log. Nếu luồng không dừng đúng, ghi nhận lỗi đã ẩn danh và tắt phần AI cho tới khi sửa.
