# 1.Fix tính năng toàn màn hình: 
**Đã điều chỉnh logic tính toán trong hàm resize(). Trước đây, khi tính toán số lượng đèn LED lấp đầy màn hình, nó thường lấy sát mép window.innerWidth, dẫn đến việc hàng đèn LED ngoài cùng (Viền) bị khuất hoặc mất nét do hiển thị tràn viền. Tôi đã thêm một khoảng đệm an toàn nhỏ (window.innerWidth - 4) để đảm bảo viền LED luôn hiển thị trọn vẹn bên trong màn hình**

# 2.Thêm tính năng Chặn chụp màn hình (Anti-Screenshot): Đã thêm nút bật tắt trong mục "Hệ thống".

**Cơ chế: Khi bật, web sẽ chặn chuột phải (Save image), và nếu phát hiện người dùng nhấn phím PrintScreen hoặc chuyển tab (dấu hiệu dùng Snipping Tool), màn hình sẽ tự động đen đi hoặc ẩn nội dung để bảo vệ.**
