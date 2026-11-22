# ROKID ARCHERY — bản thử nghiệm 0.1

Đây là **mã nguồn Android**, chưa phải file APK đã biên dịch.

## Tính năng hiện có
- Giao diện ngang, nền tối và HUD xanh.
- Vòng bia ngắm.
- 10 lượt bắn, điểm số.
- Chạm để ngắm và chạm để bắn (điều khiển thử nghiệm).

## Chưa có trong bản 0.1
- Chưa tích hợp camera hoặc nhận diện bàn tay.
- Chưa có neo AR vào không gian thực.
- Chưa xác nhận tương thích đầy đủ với Rokid RV101; cần biên dịch và thử trực tiếp trên kính.

## Tạo APK bằng GitHub Actions
1. Tải và giải nén ZIP.
2. Tải toàn bộ nội dung bên trong thư mục dự án lên repository `phidoi113-netizen/rokid-archery`, giữ nguyên cấu trúc thư mục.
3. Sau khi các tệp được commit lên nhánh `main`, mở tab **Actions** của repository.
4. Chọn workflow **Build ROKID ARCHERY APK** và mở lần chạy mới nhất.
5. Khi workflow chạy thành công, tải artifact `rokid-archery-v0.1-apk`; giải nén artifact để lấy `app-debug.apk`.

Nếu build thất bại, mở workflow và gửi ảnh phần lỗi màu đỏ để kiểm tra.
