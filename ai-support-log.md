# AI Support Log — Day 20

- **Học viên:** Mai Tiến Huy · **MHV:** 2A202602914
- **Dự án:** CareLoop AI
- **Công cụ AI:** Codex (OpenAI)

## Phần tôi đã làm

1. Tôi cung cấp bản mô tả CareLoop AI do nhóm chuẩn bị, gồm bài toán sau xuất viện, các vai trò bệnh nhân/người chăm sóc/điều dưỡng và quy trình theo dõi hiện tại.
2. Tôi nêu các điểm nghẽn của dự án: bệnh nhân phải ghi nhớ nhiều hướng dẫn, đội chăm sóc thiếu dữ liệu giữa hai lần liên hệ, khó thấy xu hướng xấu dần và follow-up thủ công khó mở rộng.
3. Tôi xác định phạm vi MVP trong bản mô tả: chuyển hướng dẫn xuất viện thành care plan, thu thập check-in, sàng lọc tín hiệu nguy cơ và chuyển trường hợp cần thiết cho nhân viên y tế. Mục tiêu prototype chưa phải chứng minh giảm tái nhập viện.
4. Tôi cung cấp ranh giới vận hành của sản phẩm: kế hoạch ban đầu cần người duyệt; AI không tự chẩn đoán, đổi thuốc hay tự đóng critical alert; trường hợp mơ hồ hoặc lỗi công cụ được chuyển người.
5. Tôi cung cấp luồng theo dõi mẫu D1/D3/D7/D14, quy tắc nhắc sau 24 giờ và chuyển điều dưỡng nếu tiếp tục mất phản hồi. Đây là đầu vào để thiết kế cadence và window đo.
6. Tôi chọn **bệnh nhân hoàn tất check-in theo care plan** làm core action cho bài cá nhân.
7. Tôi chọn nhịp **theo mốc D1/D3/D7/D14** vì nhu cầu theo dõi gắn với giai đoạn hồi phục và mốc do nhân viên y tế duyệt.
8. Tôi chọn hướng giả thuyết **tỷ lệ hoàn tất check-in đúng cửa sổ tăng qua các mốc**. Lý do tôi đưa ra: dữ liệu lần trước được lưu giúp lần sau dễ báo tình trạng và thấy tiến trình.

## AI đã hỗ trợ

Tôi dùng Codex để brainstorm ứng viên core action, đặt câu hỏi phản biện và biên tập các lựa chọn của tôi thành Metrics Pack. AI dự thảo công thức metric/retention, gợi ý event và tiêu chí tracking, tạo HTML/README/log, rồi kiểm tra cấu trúc tệp. AI đề xuất khung đánh giá giả thuyết **6 tuần**; cửa sổ check-in **24 giờ** và mốc xác nhận alert **15 phút** được suy ra từ quy tắc vận hành tôi đã cung cấp. Các ngưỡng này là giả định đo lường cho prototype.

## Nguồn và giới hạn

- Nguồn sử dụng: brief Day 20 và mô tả CareLoop AI tôi cung cấp. Deck bài giảng chưa được cung cấp cho AI; AI không dùng nguồn y khoa bên ngoài.
- Các target kỹ thuật của CareLoop AI là mục tiêu prototype, chưa phải kết quả đo. Metrics Pack không khẳng định sản phẩm đã giảm tái nhập viện.
