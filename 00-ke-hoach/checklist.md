# Checklist bài làm

## Nghiên cứu và định nghĩa bài toán — đã hoàn thiện

- [x] Chọn khoảnh khắc hẹp: đặt lịch khám ngoại trú.
- [x] Ghi chép trải nghiệm MyVinmec và hai trạng thái app minh họa: danh sách bác sĩ, không có lịch 3 ngày.
- [x] Chuẩn hóa ba phỏng vấn theo mã P1–P3; người thực hiện xác nhận đã xin đồng ý.
- [x] Tổng hợp insight và phản ví dụ; không suy rộng từ mẫu định tính nhỏ.
- [x] Tạo journey map, need statement và tìm ba best practice có nguồn.

## Prototype — đã có bản click demo

- [x] Xác định giả thuyết, tác vụ, thước đo và giới hạn AI.
- [x] Tạo prototype tương tác với lịch mô phỏng; có luồng đổi sang bác sĩ cùng chuyên khoa.
- [x] Lưu prompt, mô tả phạm vi và guardrail.
- [x] Cho 3 người thử prototype; ghi kết quả tổng quát vào test log. Một số chi tiết như trích dẫn và thời gian thao tác không được thu thập.

## Đóng gói

- [x] Hoàn thiện risk register và kế hoạch coach nhóm K4.
- [x] Tạo deck HTML 8 slide và xuất `slides.pdf`.
- [x] Đối chiếu nội dung với nghiên cứu, công bố phần AI hỗ trợ và không tạo kết quả test giả.
- [ ] Nếu ảnh gốc có dưới dạng tệp riêng, thay phần giao diện dựng lại trong deck bằng ảnh gốc đã kiểm tra.

## Tiêu chí tự rà soát

| Câu hỏi | Kết quả hiện tại |
|---|---|
| Đây có phải vấn đề thật? | Có một audit app và một người phỏng vấn nêu khó khăn; hai người khác thấy đặt lịch suôn sẻ. Cần test thêm để biết độ phổ biến. |
| AI có cần thiết không? | AI có thể chuyển câu tự nhiên thành bộ lọc tiện dụng; tìm kiếm và xếp hạng lịch vẫn làm theo quy tắc xác định. |
| Prototype đã được kiểm chứng với người dùng chưa? | Có 3 người thử; log ghi thời lượng, số lần quay lại và nhận xét tổng quát. Chưa có trích dẫn hoặc thời gian từng thao tác. |
| Có an toàn không? | Không tư vấn y khoa, dùng lịch mock, giữ lựa chọn người dùng và nêu lối chuyển sang hỗ trợ chính thức. |
| Coach plan có checkpoint không? | Có lịch D1–D7 và quality gate truy vết bằng chứng. |
