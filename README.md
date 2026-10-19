# Một lần đi khám — thiết kế lại trải nghiệm người bệnh với AI trên MyVinmec

> Trạng thái: bài làm đã đóng gói, prototype tương tác và deck PDF sẵn sàng. Nghiên cứu người dùng được ẩn danh; chỉ chia sẻ khi người tham gia đã đồng ý.

## Mục tiêu

Khám phá **một khoảnh khắc hẹp** trong hành trình đi khám, kiểm chứng điểm đau bằng nghiên cứu người dùng, rồi tạo prototype AI có thể bấm thử và thử nghiệm với người dùng.

**Khoảnh khắc đã chọn:** Đặt lịch khám ngoại trú trên MyVinmec.  
**Đối tượng trọng tâm:** Người đã biết chuyên khoa cần khám, muốn chủ động chọn bác sĩ hoặc đặt lịch sớm.  
**Phiên bản prototype hiện tại:** Clickable HTML dùng lịch mô phỏng; giao diện được dựng lại dựa trên hai ảnh MyVinmec do ứng viên cung cấp.

## Mục lục bằng chứng

| Phần | Nội dung | Trạng thái |
|---|---|---|
| [00-ke-hoach](00-ke-hoach/checklist.md) | Checklist, tiến độ và lịch làm | ✅ |
| [01-phong-van](01-phong-van/README.md) | Dùng thử MyVinmec, phỏng vấn và tổng hợp | ✅ |
| [02-journey-map](02-journey-map/README.md) | Các bước đặt lịch và điểm vướng | ✅ |
| [03-need-statement](03-need-statement/need-statement.md) | Need statement và bằng chứng | ✅ |
| [04-best-practice](04-best-practice/README.md) | Ba ví dụ tham khảo có nguồn | ✅ |
| [05-prototype](05-prototype/README.md) | Click demo, prompt dự kiến và log thử với 3 người | ✅ prototype / test |
| [06-rui-ro-dao-duc](06-rui-ro-dao-duc/risk-register.md) | Rủi ro, giảm thiểu và chuyển tuyến khẩn cấp | ✅ |
| [07-coach-plan](07-coach-plan/coach-plan.md) | Kế hoạch coach nhóm K4 | ✅ |
| [slides.html](slides.html) / [slides.pdf](slides.pdf) | Bộ slide 8 trang cho phần trình bày khoảng 7–9 phút | ✅ |
| [slides-design.md](slides-design.md) | Brief nội dung và bố cục để tạo bộ slide mới | ✅ |

## Công bố sử dụng AI

| Hạng mục | AI đã hỗ trợ gì | Người thực hiện đã kiểm tra/chỉnh sửa gì |
|---|---|---|
| Tổng hợp và trình bày | AI hỗ trợ sắp xếp ghi chép, viết nội dung, đề xuất luồng demo, viết mã prototype và slides | Ứng viên cung cấp trải nghiệm ứng dụng, nội dung phỏng vấn và ảnh tham chiếu. Lịch trong demo là dữ liệu giả. Kết quả test dựa trên thông tin ứng viên cung cấp. |

AI không thay thế phỏng vấn, quan sát, quyết định thiết kế hay đánh giá an toàn. Các trích dẫn trong repo dẫn về ghi chép phỏng vấn đã ẩn danh.

## Rà soát trước khi nộp

- [x] Có ghi chép dùng thử MyVinmec và ba phỏng vấn ẩn danh; ứng viên xác nhận script đã được dùng với người tham gia đồng ý.
- [x] Có hành trình đặt lịch, need statement không chứa giải pháp và ba ví dụ tham khảo có nguồn.
- [x] Có prototype bấm được, prompt dự kiến và log thử với 3 người; một số chi tiết không được thu thập.
- [x] Có đánh giá rủi ro/an toàn, kế hoạch coach và `slides.pdf` 8 trang.
- [x] Không chép thông tin sức khỏe cá nhân hoặc dữ liệu định danh người phỏng vấn vào repo.

Hai ảnh evidence ở trang 02 của deck là ảnh chụp MyVinmec gốc do ứng viên cung cấp. Các màn hình prototype được dựng lại để minh họa; tên bác sĩ và lịch trong prototype là dữ liệu mô phỏng, không kết nối lịch Vinmec.
