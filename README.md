# NhắcNhở+ v1.3 (Mặc định Bật Báo thức & Công tắc Tắt/Bật linh hoạt)

## Tính năng mới ở phiên bản v1.3
- **Mặc định luôn BẬT báo thức (`Báo thức: BẬT`)**: Mở app lên là sẵn sàng đổ chuông ngay lập tức, không cần thao tác cấp quyền thủ công.
- **Công tắc Tắt/Bật báo thức nhanh ở góc trên bên phải**: Khi bạn nghỉ ngơi hoặc đang họp, chỉ cần chạm 1 lần để chuyển sang **`Báo thức: TẮT`** — hệ thống sẽ hủy toàn bộ chuông báo ngầm trên iOS để không làm phiền; khi họp/nghỉ xong, chạm lại để chuyển sang **`Báo thức: BẬT`**, app sẽ tự động khôi phục lại toàn bộ lịch báo thức sắp tới.
- **4 nhạc chuông WAV 18 giây** (`urgent.wav`, `classic.wav`, `chime.wav`, `nature.wav`) được tự động đóng gói vào tài nguyên gốc Xcode qua `codemagic.yaml`.

## Quy trình cập nhật lên iPhone
1. Giải nén `NhacNhoPlus-iOS-v1.3.zip` và tải đè lên kho GitHub của bạn.
2. Vào **Codemagic** chạy build mới để tải tệp `NhacNhoPlus-v1.3-unsigned.ipa`.
3. Nạp tệp `.ipa` qua **Sideloadly** để cài đè vào iPhone.
