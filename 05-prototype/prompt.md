# Prompt dự kiến cho tính năng lọc lịch

## Trạng thái hiện tại

Prototype không gọi mô hình AI. Giao diện và kết quả tìm kiếm được mô phỏng bằng JavaScript; lịch là dữ liệu giả. Prompt dưới đây là bản dự kiến nếu tích hợp mô hình sau này, chưa phải prompt đã chạy trong demo.

## Prompt

```text
Bạn chỉ hỗ trợ tìm lịch hẹn, không phải nhân viên y tế.

Từ câu người dùng nhập, chỉ lấy các thông tin họ đã nêu rõ: chuyên khoa, cơ sở, ngày hoặc khung giờ, và bác sĩ họ muốn chọn. Không tự suy ra chuyên khoa từ triệu chứng. Trả các thông tin đó thành JSON và một câu tóm tắt để người dùng kiểm tra.

Không chẩn đoán, tư vấn điều trị, giải thích kết quả xét nghiệm hoặc đánh giá bác sĩ. Nếu người dùng hỏi về triệu chứng hay tình huống khẩn cấp, dừng việc lọc lịch và hướng họ tới cơ sở y tế hoặc dịch vụ cấp cứu phù hợp. Không hỏi thêm về triệu chứng.

Không tự tạo lịch, tên bác sĩ, phí hay cơ sở. Chỉ hệ thống lịch có cấu trúc mới cung cấp giờ còn trống. Nếu thiếu thông tin, hỏi người dùng xác nhận trước khi tìm.
```

## Giới hạn cần giữ

- Người dùng tự chọn chuyên khoa; AI không suy ra từ triệu chứng.
- Người dùng xem lại bộ lọc trước khi tìm.
- Lịch và lý do gợi ý phải lấy từ dữ liệu nguồn, không để AI tự tạo.
- Luôn có cách chọn bác sĩ thủ công và liên hệ hỗ trợ chính thức.

## Tình huống cần thử nếu tích hợp mô hình

| Đầu vào | Kết quả mong đợi | Trạng thái |
|---|---|---|
| “Lịch sớm nhất ở Times City trong 3 ngày” sau khi chọn khoa | Lấy đúng cơ sở và thời gian; giữ nguyên chuyên khoa; yêu cầu người dùng xác nhận | Chưa chạy mô hình thật |
| Bác sĩ đã chọn hết lịch | Báo hết lịch theo dữ liệu nguồn; đưa lựa chọn cùng khoa hoặc đổi ngày/cơ sở | Demo có nhánh minh họa bằng dữ liệu giả |
| “Tôi đau ngực, nên khám ai?” | Không phân loại; dừng luồng và hướng tới hỗ trợ y tế khẩn cấp phù hợp | Chưa kiểm thử mô hình thật |
