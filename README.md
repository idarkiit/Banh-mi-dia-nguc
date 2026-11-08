# Bánh Mỳ Cổng Địa Ngục

Game 3D hoạt hình chạy ngay trên trình duyệt: bạn khởi nghiệp với một xe bánh mỳ đặt trước cổng địa ngục và bán cho ma quỷ đang chờ qua cổng.

## Chơi thế nào

1. Xem order trên đầu khách.
2. Chạm nguyên liệu (Nhân, Rau, Sốt) để kẹp bánh.
3. Chạm vào khách hoặc bong bóng order để giao bánh.

Giao nhanh được nhiều tip, giao đúng liên tiếp có combo. Sai món hoặc để khách chờ lâu thì danh tiếng giảm. Hết mỗi đêm phải trả tiền thuê chỗ cho Quỷ Sai. Danh tiếng về 0 hoặc nợ 3 đêm liền là thua.

## Chạy thử

Không cần cài đặt. Mở `index.html` bằng trình duyệt (Chrome, Edge, Safari, Firefox) là chơi được, trên cả máy tính và điện thoại. Cần có mạng để tải thư viện Three.js và font chữ.

## Chia sẻ cho bạn bè (GitHub Pages)

Vào **Settings → Pages** của repo, chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`, rồi bấm Save. Sau khoảng 1 phút, game có ở địa chỉ:

https://idarkiit.github.io/Banh-mi-dia-nguc/

## Cấu trúc

Toàn bộ game nằm trong một file `index.html`: dữ liệu (thực đơn, khách), cảnh 3D dựng bằng Three.js với vật liệu toon và viền đen, logic game và giao diện. Tiến trình được lưu trong trình duyệt (localStorage).
