# Ba ví dụ về đặt lịch khám

Các sản phẩm dưới đây gợi ý cách thiết kế. Chúng không chứng minh rằng cách làm đó sẽ hiệu quả với MyVinmec.

## 1. Zocdoc: kiểm tra giờ còn trống

Zocdoc cho phép tìm giờ theo bác sĩ và cơ sở. Tài liệu API mô tả cách lấy giờ còn trống và chỉ đặt vào một giờ vẫn khả dụng.

**Bài học cho Vinmec:** Chỉ báo “còn lịch” khi dữ liệu được cập nhật và kiểm tra lại trước khi xác nhận.

**Giới hạn:** Cách này phụ thuộc vào dữ liệu lịch chính xác, cập nhật.

Nguồn: [Zocdoc API — Find Provider Availability and Book Appointments](https://api-docs.zocdoc.com/guides/patient/book-appointments), truy cập 19/10/2026.

## 2. Zocdoc: sắp xếp theo nhu cầu đặt lịch

Zocdoc cho biết kết quả có thể tính đến các yếu tố như nhu cầu, địa điểm và giờ hẹn sắp tới.

**Bài học cho Vinmec:** Nếu xếp lịch sớm lên trước, hãy ghi rõ lý do và vẫn cho người dùng tự chọn bác sĩ. Thứ tự này không nên bị hiểu là đánh giá chuyên môn.

**Giới hạn:** Đây là mô tả của sản phẩm Zocdoc, chưa phải bằng chứng hiệu quả với người dùng Vinmec.

Nguồn: [Zocdoc — How real-time availability and instant booking work](https://www.zocdoc.com/blog/facts/real-time-availability-instant-booking/), truy cập 19/10/2026.

## 3. Kaiser Permanente: đưa ra lựa chọn khác

Trang trợ giúp của Kaiser hướng dẫn người dùng thử ngày, cơ sở hoặc bác sĩ khác, hoặc gọi hỗ trợ khi chưa tìm được lịch.

**Bài học cho Vinmec:** Khi một bác sĩ hết lịch, có thể đưa ra bác sĩ cùng chuyên khoa hoặc đổi ngày/cơ sở. Không tự chuyển sang chuyên khoa khác.

**Giới hạn:** Lựa chọn thay thế phải phù hợp với nhu cầu người dùng; tình huống khẩn cấp cần ra khỏi luồng đặt lịch thường.

Nguồn: [Kaiser Permanente — Appointments help](https://healthy.kaiserpermanente.org/southern-california/support/help/appointments), truy cập 19/10/2026.
