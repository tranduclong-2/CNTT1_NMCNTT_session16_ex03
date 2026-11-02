# Bài 3 Xử lý Sự cố Giao diện Website Doanh nghiệp

### Phần 1. Báo cáo phân tích (I/O)

Khung "Nội dung bài học" bị chồng lên khung "Danh sách video".

Nguyên nhân có thể do Margin âm, Padding quá lớn hoặc Width chưa hợp lý.

Khi kiểm tra bằng F12 → Computed:
- Content: Nội dung bên trong.
- Padding: Khoảng cách bên trong.
- Border: Đường viền.
- Margin: Khoảng cách bên ngoài.

### Phần 2. Thiết kế giải pháp

Đề xuất chỉnh sửa:
- Đưa Margin âm về 0.
- Giảm Padding nếu quá lớn.
- Điều chỉnh Width của hai khung.
- Thêm box-sizing: border-box.
Nếu chỉ chỉnh Margin mà không kiểm tra Padding, hai khung vẫn có thể bị chồng lấn do kích thước thực tế chưa được tính đúng.

Kết luận: Cần kiểm tra cả 4 thành phần Box Model để sửa lỗi giao diện.
