# Tóm tắt ý tưởng prototype

**Nhu cầu:** Giúp người đã biết chuyên khoa tìm giờ khám phù hợp mà không phải mở lần lượt nhiều hồ sơ. Xem [need statement](../03-need-statement/need-statement.md).

## Người dùng và vấn đề

Người đặt khám ngoại trú đã chọn hoặc biết chuyên khoa. Họ muốn tìm giờ sớm, hoặc muốn chọn bác sĩ cụ thể. Prototype không hỗ trợ cấp cứu hay tư vấn triệu chứng.

## Giả thuyết

Nếu danh sách cho thấy bác sĩ cùng chuyên khoa còn giờ sớm, người dùng có thể tìm lịch với ít thao tác hơn mà vẫn giữ quyền tự chọn.

## Luồng demo

1. Chọn chuyên khoa.
2. Nhập mong muốn về ngày hoặc cơ sở bằng câu tự nhiên.
3. Xem và xác nhận các bộ lọc.
4. Xem lịch minh họa, chọn giờ hoặc bác sĩ khác cùng khoa.

## AI và phần không dùng AI

AI được đề xuất để chuyển câu tự nhiên thành bộ lọc lịch hành chính. Trong file demo hiện tại, bước này được mô phỏng bằng JavaScript; không có mô hình AI thật. Lọc và sắp xếp dùng quy tắc cố định trên dữ liệu giả lập.

## Phạm vi

| Có trong demo | Không có trong demo |
|---|---|
| Chọn chuyên khoa, ngày/cơ sở; xem bộ lọc; xem giờ mô phỏng; xem bác sĩ cùng khoa khác | Đặt hẹn thật, dùng lịch Vinmec thật, tư vấn y tế, chọn chuyên khoa từ triệu chứng, đánh giá năng lực bác sĩ |

## Cách đánh giá

Ghi xem người tham gia hoàn thành tác vụ không, mất bao lâu, có quay lại mở lịch không và bộ lọc hiển thị có đúng yêu cầu mô phỏng không. Cũng cần xem họ có hiểu đây chỉ là bản demo và giờ hẹn không đảm bảo không phải chờ.
