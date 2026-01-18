# Phiên bản V2.0 dưới đây đã được viết lại hoàn toàn (Refactor code) với tư duy lập trình hướng đối tượng (OOP) để tối ưu hiệu năng.

Các nâng cấp lớn trong bản V2.0 này:
Sửa lỗi Nhấp nháy: Hoạt động chuẩn xác theo nhịp điệu.

Thêm 3 Hiệu ứng mới:

Typewriter: Gõ từng chữ (như máy đánh chữ).

Shake: Hiệu ứng rung lắc (như bảng điện bị lỏng dây).

Pulse: Nhịp tim (Sáng lên rồi tối dần đều).

Tùy chỉnh Hình dáng LED: Chọn được LED Tròn hoặc Vuông (Pixel).

Chỉnh độ chói (Glow): Tăng giảm độ tỏa sáng của đèn.

Presets (Mẫu có sẵn): Các nút bấm nhanh để chọn phong cách (Cyberpunk, Retro, Shop, v.v.).


 




# Các tính năng mới chi tiết:
Sửa lỗi Nhấp nháy (Blink):

Trước đây nhấp nháy dựa trên timer không đồng bộ, giờ đây dựa trên số khung hình (frame rate). Bạn chỉnh thanh Tốc độ (Speed) càng thấp thì nháy càng chậm (nhịp thở), kéo cao lên thì nháy loạn xạ như đèn vũ trường.

3 Hiệu ứng mới:

Gõ chữ (Typewriter): Chữ sẽ xuất hiện từng ký tự một kèm dấu nháy _ ở cuối, rất hợp làm intro.

Rung lắc (Shake): Chữ rung bần bật, tạo cảm giác biển hiệu cũ kỹ hoặc cảnh báo nguy hiểm.

Nhịp tim (Pulse): Chữ đứng yên nhưng độ sáng sẽ mờ dần rồi sáng lại nhịp nhàng.

Tùy biến sâu hơn (Pro Features):

Hình dạng LED: Có nút chọn Tròn hoặc Vuông. Vuông nhìn sẽ giống phong cách Retro Pixel 8-bit, Tròn nhìn giống biển LED module P10 ngoài đời.

Độ chói (Glow): Bạn có thể tắt hẳn glow để tăng tốc độ máy (nếu máy yếu) hoặc kéo max cây để chữ rực rỡ như đèn Neon.

Độ sáng LED tắt: Chỉnh được độ sáng của những bóng đèn đang tắt. Nếu kéo về 0 thì nền đen tuyền. Kéo lên một chút sẽ thấy lờ mờ các bóng đèn nền (nhìn thật hơn).

Hệ thống Presets (Mẫu):

Tôi đã tạo sẵn 5 nút bấm (Cyberpunk, Retro, Store...) ở dưới cùng. Bạn bấm vào đó nó sẽ tự động chỉnh màu, font, tốc độ, kiểu dáng cho phù hợp chủ đề đó ngay lập tức.

Tối ưu hóa Code:

Sử dụng biến config tập trung để quản lý trạng thái, giúp code mượt hơn, ít bị lag khi đổi hiệu ứng liên tục.
