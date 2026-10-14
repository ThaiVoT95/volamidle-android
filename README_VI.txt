VÕ LÂM IDLE - ANDROID WEBVIEW APP

Dự án Android Studio mở website https://volamidle.pages.dev/ trong một ứng dụng riêng.

CÁCH TẠO APK
1. Cài Android Studio trên máy tính.
2. Giải nén file ZIP.
3. Trong Android Studio chọn Open và chọn thư mục VoLamIdle.
4. Chờ Gradle Sync hoàn tất. Nếu được hỏi, cài Android SDK Platform 35 và Build Tools theo đề xuất.
5. Chọn Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK debug thường nằm tại: app/build/outputs/apk/debug/app-debug.apk

LƯU Ý
- Đây là ứng dụng WebView, không phải game offline; cần mạng và website còn hoạt động.
- Dữ liệu đăng nhập/lưu game phía website có thể được lưu trong dữ liệu ứng dụng theo cơ chế của website.
- Nếu game cần API hoặc tính năng trình duyệt đặc biệt mà Android WebView không hỗ trợ, cần điều chỉnh thêm.
- Mã nguồn hiện chưa được biên dịch thành APK trong môi trường tạo file này vì không có Android SDK/Gradle cài sẵn.
