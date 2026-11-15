# NhắcNhở+ v1.4 (Lặp lại theo ngày & tuần + Chỉnh sửa lịch linh hoạt)

## Cải tiến mới ở phiên bản v1.4
1. **Chu kỳ lặp lại theo ngày và theo tuần**:
   - **Hàng ngày**: Tự động báo thức vào đúng khung giờ đó mỗi ngày.
   - **Thứ 2 – Thứ 6 (Ngày làm việc)**: Tự động bỏ qua Thứ 7 & Chủ nhật.
   - **Hàng tuần (Tùy chọn các thứ T2 → CN)**: Chạm chọn chính xác những thứ cần nhắc trong tuần (ví dụ: T2, T4, T6).
2. **Tự động cuốn chiếu lịch ngầm trên iOS**: Hệ thống tự động nạp sẵn chuỗi 7 kỳ báo thức kế tiếp vào nhân iOS nên kể cả khi bạn không mở ứng dụng trong nhiều ngày, iPhone vẫn đổ chuông đúng từng ngày/thứ đã cài. Khi bấm **"✓ Tắt chuông (Hẹn kỳ sau)"**, lịch tự động nhảy sang kỳ tiếp theo.
3. **Chỉnh sửa trực tiếp lịch đã tạo (`✏️`) & Bộ lọc nhanh**: Chạm vào bất kỳ công việc nào để đổi giờ, đổi thứ lặp lại hoặc đổi nhạc chuông; lọc nhanh theo *Tất cả*, *🔁 Lặp lại*, *1️⃣ Một lần*, *✓ Đã xong*.
4. **Giữ nguyên toàn bộ tính năng v1.3**: Mặc định luôn bật báo thức (`Báo thức: BẬT`), công tắc tạm tắt khi nghỉ ngơi/họp (`Báo thức: TẮT`), và 4 chuông báo thức WAV 18 giây âm lượng lớn.

## Quy trình cập nhật lên iPhone
1. Giải nén `NhacNhoPlus-iOS-v1.4.zip` và tải đè lên kho GitHub của bạn.
2. Vào **Codemagic**, nhấn **Start new build** để nhận tệp `NhacNhoPlus-v1.4-unsigned.ipa`.
3. Nạp tệp `.ipa` qua **Sideloadly** để cài đè lên iPhone (dữ liệu cũ trong IndexedDB vẫn giữ nguyên).
