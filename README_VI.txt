DATBUSSTIM.IOS — BẢN PWA DEMO
===========================

Tính năng:
- Giao diện đen/hồng neon phù hợp điện thoại.
- Hai lựa chọn: 1.000 Follow và 10.000 Tim.
- Nhập ID/tên người dùng TikTok.
- Lưu lịch sử tối đa 50 yêu cầu trong bộ nhớ cục bộ của trình duyệt.
- Có manifest và service worker cho khả năng cài lên màn hình chính/offline cơ bản.

GIỚI HẠN QUAN TRỌNG
- Đây là bản demo giao diện; KHÔNG tăng follow/tim thật.
- Không kết nối API TikTok, không có backend và không gửi dữ liệu đi đâu.
- Không yêu cầu mật khẩu hoặc mã OTP.
- Đừng mô tả đây là dịch vụ tăng tương tác thật.

CÁCH CHẠY THỬ
Mở index.html trong trình duyệt để thử giao diện. Một số tính năng PWA/cài đặt
chỉ hoạt động khi website được phục vụ qua HTTPS hoặc localhost.

CÁCH ĐƯA LÊN MẠNG
1. Tạo repository GitHub mới.
2. Tải lên index.html, manifest.json, service-worker.js, icon.svg.
3. Trong Settings → Pages, bật xuất bản từ nhánh main/root.
4. Đợi GitHub Pages tạo đường dẫn HTTPS.
5. Mở đường dẫn trên điện thoại.

CÀI TRÊN IPHONE
1. Mở đường dẫn bằng Safari.
2. Nhấn nút Chia sẻ.
3. Chọn “Thêm vào Màn hình chính”.
4. Nhấn Thêm.

CÀI TRÊN ANDROID
1. Mở đường dẫn HTTPS bằng Chrome.
2. Chọn menu ⋮.
3. Chọn “Cài đặt ứng dụng” hoặc “Thêm vào màn hình chính”.

MUỐN ĐƯA LÊN APP STORE / GOOGLE PLAY
PWA này chưa phải gói native .ipa/.apk. Để xuất bản lên cửa hàng cần quy trình
đóng gói native hoặc dùng wrapper phù hợp, kiểm tra chính sách hiện hành và
hoàn tất tài khoản nhà phát triển. iOS không cho cài file .ipa tùy ý như Android.
