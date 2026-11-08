# Bánh Mỳ Cổng Địa Ngục

Game 3D hoạt hình chạy ngay trên trình duyệt: bạn khởi nghiệp với một xe bánh mỳ đặt trước cổng địa ngục và bán cho ma quỷ đang chờ qua cổng.

## Chơi thế nào

1. Xem order trên đầu khách.
2. Bấm **🥖 Lấy vỏ bánh** (hoặc phím B / Space) để lấy ổ bánh từ tủ kính ra thớt, rồi chạm nguyên liệu (Nhân, Rau, Sốt) để kẹp.
3. Chạm vào khách hoặc bong bóng order để giao bánh. Làm hỏng thì bấm 🗑️ Bỏ bánh và lấy vỏ mới.

Khi cả 3 chỗ trước quầy đã kín, khách mới sẽ xếp hàng phía sau và lên thay ngay khi có chỗ trống. Càng về sau khách đến càng dày.

Mỗi đêm dài 2 phút. Giao nhanh được nhiều tip, giao đúng liên tiếp có combo. Sai món hoặc để khách chờ lâu thì danh tiếng giảm. Hết mỗi đêm phải trả tiền thuê chỗ cho Quỷ Sai (tăng dần: 25, 50, 85, 130, 185...), rồi vào cửa hàng dùng vàng mã mua nguyên liệu mới và nâng cấp xe. Danh tiếng về 0 hoặc nợ 3 đêm liền là thua.

Khách đặc biệt: Ngạ quỷ gọi 2 ổ, Hắc Bạch Vô Thường đi cùng nhau (giao đủ cả hai mới được thưởng), Mạnh Bà tặng Cháo Lãng Quên để tha một lần sai món.

Khách bí ẩn: một vị khách trùm áo choàng có thể ghé bất kỳ đêm nào. Giao đúng và nhanh thì lộ diện thành quý nhân (Diêm Vương thưởng vàng và danh tiếng, Thần Tài lì xì, Thanh tra Vệ sinh tặng giấy khen); phục vụ kém thì bị phạt.

Ngưu Đầu Mã Diện: từ đêm 2, hai vị sai nha có thể tới kiểm tra giấy phép bán hàng rong. Bạn đẩy xe chạy trốn trong 25 giây: vuốt trái/phải (hoặc phím mũi tên) để đổi làn, vuốt lên (hoặc Space) để nhảy qua vạc dầu, nhặt thỏi vàng dọc đường. Bị bắt thì nộp phạt. Nâng cấp *Xe máy độ* giúp chạy trước xa hơn.

Mở đầu: khi khởi nghiệp lần đầu, câu chuyện được kể bằng hoạt cảnh 3D (con hẻm Sài Gòn đêm Rằm tháng Bảy, Quỷ Môn Quan, điện Diêm La) kèm lời thoại; chạm hoặc bấm *Tiếp* để đi tiếp, hoặc *Bỏ qua*.

Sổ tay khách hàng: ghi lại mọi nhân vật bạn đã gặp (khách quen, khách bí ẩn, sai nha âm phủ) kèm chân dung, sở thích và mẹo phục vụ. Mở từ màn hình chính, cửa hàng hoặc nút ⚙️ khi đang chơi.

Hoạt cảnh: cuối mỗi đêm có cảnh đóng cửa xe; khi phá sản hoặc mất hết danh tiếng có cảnh bị thu hồi xe rồi đi tìm việc khác (chèo đò, phụ bán cháo cho Mạnh Bà…). Có nút Bỏ qua.

Âm thanh: nhạc nền ma quái (đàn bầu, mõ, chuông chùa) được tổng hợp ngay trong trình duyệt. Nút ⚙️ trên màn hình mở Cài đặt để bật/tắt nhạc nền, tiếng động và chỉnh âm lượng (đồng thời tạm dừng game).

## Chạy thử

Không cần cài đặt. Mở `index.html` bằng trình duyệt (Chrome, Edge, Safari, Firefox) là chơi được, trên cả máy tính và điện thoại. Cần có mạng để tải thư viện Three.js và font chữ.

## Chia sẻ cho bạn bè (GitHub Pages)

Vào **Settings → Pages** của repo, chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`, rồi bấm Save. Sau khoảng 1 phút, game có ở địa chỉ:

https://idarkiit.github.io/Banh-mi-dia-nguc/

## Cấu trúc

Toàn bộ game nằm trong một file `index.html`: dữ liệu (thực đơn, khách), cảnh 3D dựng bằng Three.js với vật liệu toon và viền đen, logic game và giao diện. Tiến trình được lưu trong trình duyệt (localStorage).
