# Phần 1: Phân tích lỗi (3 Quy tắc vàng bị vi phạm)
Dùng Merge Cell ở tiêu đề: Làm đứt gãy cấu trúc vùng dữ liệu, khiến AutoFilter không nhận diện được toàn bộ bảng.

Để hàng trống giữa bảng: Làm gián đoạn bộ lọc, khiến nút Filter bị mất hoặc chỉ lọc được một phần phía trên.

Dữ liệu không đồng nhất (Khoảng trắng ẩn): Chứa khoảng trắng vô hình (ví dụ: "hỏng " và "hỏng"), khiến Excel hiểu là hai giá trị khác nhau khi lọc.

# Phần 2: Hướng dẫn sửa lỗi & Hoàn thiện
Gỡ Merge Cell: Bôi đen tiêu đề, bỏ gộp (Merge & Center) và đặt tên riêng cho từng cột.

Xóa hàng trống: Click chuột phải vào số hàng trống giữa bảng và chọn Delete để nối liền dữ liệu.

Làm sạch khoảng trắng: Dùng hàm =TRIM(cell) ở cột phụ để loại bỏ khoảng trắng thừa, sau đó Paste Values đè lại cột cũ.

Bật Filter: Bôi đen toàn bộ bảng và nhấn Ctrl + Shift + L để bộ lọc hoạt động chính xác.
