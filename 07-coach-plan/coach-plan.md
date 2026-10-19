# Mình sẽ coach một nhóm làm bài này như thế nào

## Mục tiêu và nguyên tắc

Trong năm buổi ngắn, nhóm đi từ quan sát đến prototype đặt lịch có bằng chứng. Tôi giữ phạm vi hẹp: **người đã biết chuyên khoa cần khám**, không giải bài toán chẩn đoán/chọn chuyên khoa dựa trên triệu chứng. Mọi kết luận phải truy được về ghi chép; mọi đề xuất phải có rào chắn an toàn.

## Nhịp làm việc

| Buổi | Mục tiêu | Đầu ra/quality gate | Vai trò coach |
|---|---|---|---|
| 1 — Khởi động | Chọn khoảnh khắc đặt lịch và rà ràng buộc | Scope 1 câu, checklist đồng ý, interview guide | Hỏi “ai đã biết chuyên khoa, họ muốn hoàn thành gì?”; loại phần tư vấn y khoa |
| 2 — Nghiên cứu | Tổng hợp ≥3 phỏng vấn và dùng thử app | Notes ẩn danh, audit luồng, bảng mã hóa | Review dữ liệu thô; chỉ rõ phản ví dụ thay vì ép dữ liệu khớp ý tưởng |
| 3 — Hội tụ | Vẽ journey map, viết/chọn need statement | Need statement không có giải pháp; pain point có nguồn | Hỏi “điều gì xảy ra trước khi người dùng phải mở nhiều lịch?”; cắt giả định chưa có bằng chứng |
| 4 — Tạo/test | Làm luồng chọn chuyên khoa → lịch sớm và test 2–3 người | Prototype, prompt/guardrail, test plan và log | Timebox build; kiểm tra người dùng hiểu lý do xếp hạng và giới hạn giờ hẹn |
| 5 — Đóng gói | Tổng hợp thay đổi, rủi ro, deck | Repo đủ bằng chứng, slide ≤10, diễn tập | Dùng rubric cuối; phản biện theo vai người dùng và reviewer an toàn |

## Khi nhóm bị kẹt

- **Không đủ insight:** quay lại quote/ghi chép và phỏng vấn thêm; không bịa số liệu hay “nhu cầu phổ quát”.
- **Giải pháp thành chatbot tư vấn bệnh:** thu hẹp về dữ liệu hành chính người dùng đã chọn (chuyên khoa, ngày, cơ sở), thêm thông báo chuyển tuyến.
- **Prototype quá lớn:** chỉ dựng hai nhánh: (a) lịch sớm cùng chuyên khoa; (b) bác sĩ yêu thích hết lịch → phương án thay thế.
- **Lịch thật không truy cập được:** dùng dữ liệu giả lập có gắn nhãn; không gọi đó là tính năng đã triển khai.

## Cách kiểm tra chất lượng

Tại mỗi checkpoint, tôi yêu cầu nhóm chứng minh chuỗi: **quote/quan sát → insight → pain point trên journey map → need statement → giả thuyết prototype → kết quả test → thay đổi**. Tôi không duyệt nếu thiếu liên kết, need statement có sẵn giải pháp, log có dữ liệu nhận diện, hoặc UI không nói rõ vì sao một lịch được gợi ý và cách chuyển sang hỗ trợ chính thức.
