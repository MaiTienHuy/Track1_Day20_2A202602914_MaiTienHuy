# Day 20 — Metrics Pack

- **Họ tên:** Mai Tiến Huy
- **MHV:** 2A202602914
- **Dự án:** CareLoop AI — AI Agent hỗ trợ chăm sóc sau xuất viện và phòng tái nhập viện
- **Metrics Pack:** [Mở tệp trình bày trực quan](metrics-pack.html)

## Điều tôi mang về áp dụng cho dự án thật

- Đo hành vi đem lại thông tin theo dõi hữu ích theo các mốc của kế hoạch chăm sóc đã duyệt, thay vì đếm lượt mở ứng dụng hay số tin nhắn AI.
- Viết rõ mẫu số, cửa sổ và điều kiện chất lượng cho metric; đặt chỉ số an toàn cạnh chỉ số tăng trưởng để không tối ưu sai.
- Dùng event gắn với trạng thái đã hoàn tất và khóa định danh cho từng lần chuyển trạng thái; không tính lại do reload hoặc retry.

## Đối chiếu năm gate

| Gate | Bằng chứng trong Metrics Pack |
|---|---|
| 1 · Core Action | Mục 01: actor, object, completion rule và tự kiểm 5/5. |
| 2 · Cadence | Mục 02: Action Nature Card và kết luận D1/D3/D7/D14 có lý do. |
| 3 · Metric & Retention | Mục 03–04: activation, engagement, NSM có ngưỡng chất lượng, counter-metric và retention đủ 6 thành phần. |
| 4 · Loop | Mục 05: hai chu kỳ, lý do quay lại từ care plan và metric hypothesis có thời hạn. |
| 5 · Tracking | Mục 06: 7 event nối metric, 4 acceptance criteria và identity để tính. |

> Tệp HTML trong repo là bản xem trực quan. Trước khi gửi link nộp bài, bảo đảm người chấm có quyền xem repo/tệp. Khung đánh giá 6 tuần là giả định của bản lab; điều chỉnh khi pilot có dữ liệu thực.

## AI Support Log

Xem [ai-support-log.md](ai-support-log.md).
