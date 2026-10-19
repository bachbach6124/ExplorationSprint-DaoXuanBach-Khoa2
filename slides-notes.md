# Ghi chú thuyết trình — 8 slide, khoảng 7–9 phút

## Mạch kể

Từ một lần dùng thử MyVinmec, đối chiếu với ba cuộc phỏng vấn, xác định cơ hội để AI hỗ trợ tìm lịch, rồi trình bày prototype và phản hồi ban đầu. Phân biệt rõ bằng chứng đã có với hướng AI đang đề xuất: prototype chưa kết nối mô hình AI hay lịch thật.

## 1. Mở đầu — Dùng AI tìm lịch khám phù hợp

**Thời lượng:** 45 giây

“Tôi tập trung vào một đoạn hẹp trong hành trình đặt lịch ngoại trú: người dùng đã biết chuyên khoa nhưng chưa biết bác sĩ nào còn giờ phù hợp. Tôi bắt đầu bằng một lần tự thử MyVinmec, phỏng vấn ba người, rồi dựng prototype cho hướng AI hiểu yêu cầu đặt lịch và giúp so lịch. AI hỗ trợ tìm kiếm; người bệnh vẫn xác nhận nhu cầu và tự chọn bác sĩ. Đây là khám phá ban đầu, chưa phải kết luận cho mọi người dùng.”

**Chuyển:** “Tôi bắt đầu từ tình huống đã trực tiếp gặp trên ứng dụng.”

## 2. Dùng thử MyVinmec — Bác sĩ đầu danh sách đã hết lịch

**Thời lượng:** 1 phút

“Danh sách hiển thị bác sĩ từ nhiều chuyên khoa. Tôi chọn bác sĩ Nguyễn Thanh Liêm vì bác sĩ đứng đầu danh sách. Khi mở lịch, ứng dụng báo không có giờ trống trong ba ngày từ 21 đến 23 tháng 10 năm 2026. Tôi kiểm tra tiếp các ngày gần nhất nhưng vẫn không thấy giờ. Trong tình huống này, bước tiếp theo là tự đổi ngày hoặc quay lại tìm bác sĩ khác. Đây là một lần dùng thử, nên tôi xem đó là điểm cần tìm hiểu thêm.”

**Chuyển:** “Tôi đem câu hỏi này đối chiếu với trải nghiệm của ba người.”

## 3. Phỏng vấn — Có người gặp khó, cũng có người đặt lịch suôn sẻ

**Thời lượng:** 1 phút

“P1 nói khó chọn giờ phù hợp và thường gọi điện để hỏi thêm. P2 kể trải nghiệm đặt lịch suôn sẻ. P3 thấy thao tác MyVinmec nhìn chung ổn, nhưng nhắc rằng bệnh viện đông thì vẫn có thể phải chờ dù đã đặt lịch. Ba cuộc phỏng vấn không đại diện cho số đông; chúng giúp tôi lưu ý rằng gợi ý AI cần tùy chọn, và không được hứa có giờ hẹn là sẽ không phải chờ.”

**Chuyển:** “Điểm giao giữa lần audit và lời kể của P1 nằm ở lúc người dùng cần biết còn giờ hay không.”

## 4. Hành trình — Điểm vướng xuất hiện sau khi chọn bác sĩ

**Thời lượng:** 1 phút

“Tôi gom hành trình thành năm bước: mở đặt lịch, xem danh sách, chọn bác sĩ, kiểm tra ngày, rồi tìm lựa chọn khác nếu hết lịch. Trong lần audit, khả năng đặt được giờ chỉ hiện sau khi tôi đã chọn một bác sĩ. Đây là cơ hội để AI giúp tìm và so lịch sớm hơn; việc người dùng có muốn dùng cách này hay không vẫn cần kiểm chứng.”

**Chuyển:** “Từ điểm vướng đó, tôi xác định vai trò AI nhưng vẫn giữ quyền quyết định cho người đặt lịch.”

## 5. Câu hỏi thiết kế — AI hỗ trợ tìm, người bệnh tự chọn

**Thời lượng:** 50 giây

“Câu hỏi thiết kế là: làm sao để AI hiểu yêu cầu đặt lịch bằng lời thường, đưa ra bộ lọc dễ kiểm tra để người đã biết chuyên khoa tìm giờ phù hợp mà vẫn tự chọn bác sĩ? AI nên chuyển mong muốn thành tiêu chí tìm kiếm, giúp so giờ và giải thích kết quả. Người dùng kiểm tra bộ lọc, chọn bác sĩ và quyết định có đặt hay không.”

**Chuyển:** “Prototype minh họa luồng đó, nhưng chưa dùng AI hay lịch thật.”

## 6. Prototype — AI chuyển lời nhắn thành bộ lọc để người dùng duyệt

**Thời lượng:** 1 phút 15 giây

“Người dùng chọn hoặc nhập mong muốn về chuyên khoa, cơ sở và thời gian. Hướng AI sẽ chuyển lời nhắn thành bộ lọc; người dùng xác nhận trước khi xem bác sĩ cùng khoa còn giờ. Nếu bác sĩ ban đầu hết lịch, có thể xem lựa chọn khác. Trong bản demo hiện tại, phần này chỉ mô phỏng bằng JavaScript: không có mô hình AI, không kết nối lịch hay đặt hẹn Vinmec; bác sĩ và giờ đều là dữ liệu giả.”

**Khi demo:** Nhấn vào việc nhập mong muốn, xác nhận bộ lọc, rồi so giờ và tự chọn.

**Chuyển:** “Tôi cho ba người thử giao diện mô phỏng để xem họ có hiểu và hoàn thành được luồng không.”

## 7. Thử prototype — Phản hồi tích cực, chưa đánh giá AI thật

**Thời lượng:** 1 phút

“Cả ba hoàn thành tác vụ; thời gian lần lượt là hai, bốn và hai phút. Có một lượt mở lại lịch hoặc quay lại. Người thử thấy gợi ý thông minh và trải nghiệm tìm lịch dễ hơn. Tuy nhiên, đây là phản hồi về prototype mô phỏng, không phải đánh giá chất lượng AI. Log cũng không có ghi chép từng thao tác hay câu nói nguyên văn, và chưa có so sánh với luồng hiện tại.”

**Chuyển:** “Muốn thử tiếp hướng AI này, trước hết cần dữ liệu lịch đáng tin và cách đánh giá rõ ràng.”

## 8. Giới hạn và bước tiếp theo — Kiểm chứng AI cùng dữ liệu lịch được phép

**Thời lượng:** 1 phút

“Hướng AI này chỉ hỗ trợ tìm lịch sau khi người dùng đã biết chuyên khoa; không chẩn đoán hay tự chọn khoa từ triệu chứng. Prototype chưa báo lịch thật. Nếu tiếp tục sprint, tôi sẽ thử lại có ghi chép theo từng tác vụ, so sánh với luồng hiện tại, rồi mới kiểm tra khả năng AI hiểu đúng bộ lọc và kết nối nguồn lịch được cấp phép. Kết luận hiện tại: đáng thử tiếp, nhưng chưa đủ bằng chứng để đưa vào dùng thật.”

## Câu hỏi có thể gặp

### “Đây có thực sự là AI không?”

“Chưa. Prototype hiện tại mô phỏng bằng JavaScript. AI là hướng đề xuất để chuyển yêu cầu tự nhiên thành bộ lọc; cần đánh giá riêng độ chính xác, cho người dùng xác nhận và kết nối dữ liệu lịch được phép trước khi dùng thật.”

### “Ba người thử có chứng minh giải pháp tốt hơn không?”

“Không. Ba lượt cho biết người thử hoàn thành demo và phản hồi tích cực. Chưa có đối chứng với luồng hiện tại, ghi chép chi tiết hay mẫu đủ lớn để kết luận hiệu quả.”

### “Nếu người dùng chưa biết cần khám chuyên khoa nào thì sao?”

“Luồng này không dùng AI để chọn khoa từ triệu chứng. Cần hướng người dùng đến nhân viên y tế hoặc kênh hỗ trợ phù hợp.”
