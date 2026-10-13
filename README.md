# Giá Xăng Hôm Nay — Widget & Tính Chi Phí

Ứng dụng Android xem giá xăng dầu bán lẻ tại Việt Nam, tính chi phí đổ xăng và theo dõi chi tiêu nhiên liệu.

**Tính năng:**
- **Giá hôm nay:** giá vùng 1 và vùng 2, mức tăng/giảm so với kỳ trước, đếm ngược tới kỳ điều hành tiếp theo.
- **Thông báo khi giá đổi:** mỗi kỳ điều hành giá, báo mức tăng/giảm cho đúng loại xăng dầu xe bạn dùng.
- **Tính chi phí:** đổi tiền ⇄ lít, tiền đổ đầy bình, chi phí cho một chuyến đi.
- **Nhật ký đổ xăng:** chi tiêu theo tháng và mức tiêu hao thực tế.
- **Sao lưu & khôi phục:** lưu xe, nhật ký và cài đặt ra một file để chuyển sang máy mới hoặc cài lại app.
- **Quản lý xe:** gần 190 dòng xe có sẵn dung tích bình và mức tiêu hao: xe máy Honda, Yamaha, SYM, Suzuki, Vespa, Piaggio, KTM, Husqvarna, Kawasaki, Triumph, Ducati và ô tô Toyota, Hyundai, Kia, Mazda, Honda, Mitsubishi, Ford, Nissan, Suzuki. Tự tìm theo tên và đời xe.
- **Widget màn hình chính:** tuỳ biến bằng **Widget Studio**, với 4 phong cách Trống Đồng, Phố Cổ Hội An, Kính mờ và AMOLED.
- **Giao diện:** nền Sáng / Tối / Theo hệ thống; theme "Modern Heritage" với hoạ tiết trống đồng, nón lá, đèn lồng, nền đổi theo giờ trong ngày.

## 📲 Tải bản dùng thử

### [⬇️ Tải APK mới nhất](https://github.com/NamOK21/vietnam-fuel-price/releases/download/preview/gia-xang-hom-nay.apk)

Khoảng 3 MB · Android 8.0 trở lên · [Trang phát hành](https://github.com/NamOK21/vietnam-fuel-price/releases/tag/preview)

**Cách cài:**
1. Mở link trên bằng **trình duyệt trên điện thoại Android** để tải file `gia-xang-hom-nay.apk`.
2. Mở file vừa tải. Nếu máy hỏi, cho phép trình duyệt **"Cài ứng dụng không rõ nguồn gốc"**.
3. Bấm **Cài đặt**, rồi mở app. Giá xăng được tải tự động trong lần mở đầu tiên.
4. Thêm widget: mở app, chạm biểu tượng ô vuông ở góc trên màn **Giá hôm nay** để vào **Widget Studio**, rồi bấm **Thêm widget ra màn hình chính**.

**Lưu ý:**
- Đây là **bản dùng thử**, chưa phát hành trên Google Play, nên Play Protect có thể cảnh báo "ứng dụng chưa xác minh".
- Link trên luôn trỏ tới bản mới nhất. Tải bản mới rồi cài đè lên là được; xe và nhật ký đã lưu vẫn giữ nguyên.
- Từ ngày 12/10/2026, APK được ký bằng một khoá cố định. Nếu bạn đã cài bản trước ngày này và máy báo **"Ứng dụng chưa được cài đặt"**, hãy gỡ bản cũ một lần rồi cài lại. Xe và nhật ký đã lưu sẽ mất.

## Dữ liệu

App tải dữ liệu từ thư mục [`data/`](data) của repo này. Dữ liệu được cập nhật tự động:

| File | Nội dung | Cập nhật |
|---|---|---|
| [`data/prices.json`](data/prices.json) | Giá bán lẻ hiện hành và các kỳ điều hành gần đây | Mỗi giờ; 10 phút/lần vào chiều thứ Năm |
| [`data/vehicle_specs.json`](data/vehicle_specs.json) | Dung tích bình và mức tiêu hao nhiên liệu của các dòng xe | Hằng tuần |

Nguồn: Petrolimex, VnExpress, website chính hãng Honda Việt Nam và Yamaha Motor Việt Nam. Giá chỉ mang tính tham khảo; giá thực tế tại cửa hàng có thể khác.
