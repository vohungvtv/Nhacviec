# NhắcNhở+ (iOS App & PWA)

Bộ mã nguồn hoàn chỉnh cho ứng dụng nhắc việc cá nhân tối ưu hóa trên iOS, tích hợp:
- Lưu trữ dữ liệu bền vững bằng **IndexedDB** (không mất dữ liệu khi đóng app).
- 4 âm thanh báo thức tổng hợp bằng **Web Audio API** + nút nghe thử.
- Hỗ trợ thông báo đẩy hệ thống qua **Capacitor Local Notifications** (báo thức chính xác ngay cả khi đã vuốt tắt hoàn toàn ứng dụng trên iPhone).

## Cấu trúc thư mục
- `www/index.html`: Giao diện & toàn bộ logic ứng dụng.
- `www/manifest.json`: Cấu hình PWA.
- `www/icon.png` & `assets/icon-1024.png`: Icon ứng dụng chuẩn iOS (1024x1024).
- `package.json`: Khai báo thư viện Capacitor iOS.
- `capacitor.config.json`: Cấu hình định danh app (`com.vovanhung.nhacnho`).
- `codemagic.yaml`: Kịch bản tự động build file `.ipa` trên đám mây (không cần máy Mac).

## Hướng dẫn đưa lên GitHub và Build file cài iPhone (.ipa)
1. Giải nén file `NhacNhoPlus-iOS.zip`.
2. Tạo một kho lưu trữ mới (**New Repository**) trên GitHub (ví dụ: `nhac-nho-plus-ios`).
3. Tải toàn bộ các file/thư mục bên trong lên kho GitHub đó (có thể dùng nút **Add file > Upload files** trực tiếp trên web GitHub).
4. Truy cập [codemagic.io](https://codemagic.io), đăng nhập bằng tài khoản GitHub và chọn kho `nhac-nho-plus-ios`.
5. Chọn workflow **Build iOS Capacitor App** (`codemagic.yaml`) và nhấn **Start new build**.
6. Sau khoảng 5-7 phút, tải file `NhacNhoPlus-unsigned.ipa` về máy tính Windows và dùng **Sideloadly** để cài trực tiếp vào iPhone qua cáp USB.
