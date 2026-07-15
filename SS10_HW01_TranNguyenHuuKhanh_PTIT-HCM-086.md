# HW01 - Phân tích & Lựa chọn chiến lược tài liệu hóa

## Phương án được chọn: **Phương án B – Antigravity**

### Lý do lựa chọn
- Index toàn bộ dự án nên AI hiểu được luồng xử lý xuyên suốt Controller → Security Filter → Service → Repository.
- Giảm thất thoát ngữ cảnh (context loss).
- Có thể truy vết lời gọi hàm, dependency và business flow.
- Phù hợp để sinh tài liệu SRS/Use Case từ hệ thống lớn.
- Có thể cập nhật tài liệu khi mã nguồn thay đổi.

### Loại trừ phương án A
- Chỉ đọc từng file riêng lẻ.
- AI không thấy toàn bộ luồng nghiệp vụ.
- Dễ bỏ sót logic nằm ở các lớp khác.
- Tốn thời gian tổng hợp.

### Loại trừ phương án C
- Phải copy thủ công.
- Token/context giới hạn.
- Dễ bỏ sót file.
- Nguy cơ lộ mã nguồn khi đưa lên dịch vụ web.
