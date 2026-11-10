# Hướng Dẫn Đưa Trang Web Áo Dài Lên GitHub Pages (Miễn Phí)

Trang web này được đóng gói trọn vẹn trong tệp `index.html`. Bạn có thể đưa trang web lên mạng Internet hoàn toàn miễn phí qua **GitHub Pages** chỉ với vài thao tác kéo thả đơn giản.

---

## Cách 1: Đưa lên trực tiếp bằng trình duyệt Web (Không cần cài phần mềm)

1. **Đăng nhập GitHub**:
   - Truy cập [github.com](https://github.com) và đăng nhập tài khoản của bạn (nếu chưa có thì đăng ký tài khoản miễn phí).

2. **Tạo kho lưu trữ mới (Repository)**:
   - Bấm vào nút dấu cộng **`+`** ở góc trên cùng bên phải màn hình -> Chọn **New repository**.
   - Tại ô **Repository name**, đặt tên bất kỳ (Ví dụ: `ao-dai-viet-nam`).
   - Đánh dấu chọn **Public**.
   - Bấm nút **Create repository**.

3. **Tải tệp `index.html` lên**:
   - Tại trang vừa tạo, bấm vào dòng chữ xanh **`uploading an existing file`**.
   - Kéo tệp `index.html` từ thư mục này thả vào ô tải lên.
   - Bấm nút xanh **Commit changes** ở cuối trang.

4. **Bật GitHub Pages**:
   - Bấm vào mục **Settings** (ở thanh menu trên cùng của repository).
   - Ở cột menu bên trái, tìm và bấm chọn mục **Pages**.
   - Tại mục **Build and deployment** -> **Branch**:
     - Chọn nhánh là `main` (hoặc `master`).
     - Chọn thư mục là `/ (root)`.
     - Bấm nút **Save**.

5. **Xem trang web của bạn**:
   - Chờ khoảng 1 đến 2 phút, làm mới (F5) trang Pages. Bạn sẽ thấy dòng thông báo kèm đường link trang web của bạn, có dạng:  
     `https://<tên-tài-khoản-github>.github.io/ao-dai-viet-nam/`

---

## Cách 2: Sử dụng dòng lệnh Git (Dành cho ai đã quen dùng Git)

```bash
git init
git add index.html README.md
git commit -m "Khoi tao landing page Ao Dai Viet Nam"
git branch -M main
git remote add origin https://github.com/<tai-khoan>/<ten-repo>.git
git push -u origin main
```
Sau đó vào **Settings** -> **Pages** trên GitHub và kích hoạt nhánh `main`.

---

## Các điểm nổi bật của trang web:
- **Chủ đề**: Tôn vinh nét đẹp văn hóa và nghệ thuật may đo tà Áo Dài Việt Nam.
- **Phong cách thiết kế**: Sang trọng, đậm chất di sản với tông màu đỏ son, vàng hoàng kim và trắng ngà lụa tơ tằm.
- **Tính năng có sẵn**:
  - Tương thích tốt trên cả điện thoại di động, máy tính bảng và máy tính.
  - Lịch sử dòng thời gian áo dài qua các thời kỳ.
  - Bộ sưu tập có bộ lọc theo từng loại (Cưới hỏi, Cách tân, Truyền thống, Công sở/Nữ sinh).
  - Cửa sổ xem nhanh thông tin chi tiết sản phẩm (Modal Popup).
  - Bảng giá minh bạch và form đặt lịch hẹn may đo tận nơi.
