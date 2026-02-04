# Portfolio Website - Minh Chi

Portfolio cá nhân được tạo theo template Jon Barron.

## 📁 Cấu trúc Files

```
portfolio/
├── index.html          # Trang chính
├── stylesheet.css      # CSS styling
├── images/            # Thư mục chứa ảnh
│   ├── profile.jpg    # Ảnh đại diện
│   ├── project1.jpg   # Ảnh dự án 1
│   ├── project2.jpg   # Ảnh dự án 2
│   └── project3.jpg   # Ảnh dự án 3
└── README.md          # File này
```

## 🚀 Hướng dẫn Deploy lên GitHub Pages

### Bước 1: Tạo tài khoản GitHub
1. Truy cập https://github.com
2. Click "Sign up" ở góc phải trên
3. Điền thông tin:
   - Username (ví dụ: minhchi-ktdn)
   - Email
   - Password
4. Xác nhận email

### Bước 2: Tạo Repository
1. Sau khi đăng nhập, click nút **"+"** ở góc phải trên → chọn **"New repository"**
2. Đặt tên repository: **`username.github.io`** (thay username bằng tên GitHub của bạn)
   - Ví dụ: `minhchi-ktdn.github.io`
3. Chọn **Public**
4. Tick vào **"Add a README file"**
5. Click **"Create repository"**

### Bước 3: Upload files
1. Trong repository vừa tạo, click nút **"Add file"** → **"Upload files"**
2. Kéo thả hoặc chọn các files:
   - `index.html`
   - `stylesheet.css`
   - Thư mục `images/` (cùng với các ảnh bên trong)
3. Kéo xuống dưới, gõ commit message: "Initial commit"
4. Click **"Commit changes"**

### Bước 4: Thêm ảnh
1. Trong repository, click vào thư mục **"images"**
2. Click **"Add file"** → **"Upload files"**
3. Upload các ảnh:
   - `profile.jpg` - ảnh đại diện của bạn (nên là ảnh vuông)
   - `project1.jpg`, `project2.jpg`, `project3.jpg` - ảnh cho các dự án
4. Commit changes

### Bước 5: Kích hoạt GitHub Pages
1. Trong repository, click tab **"Settings"**
2. Ở menu bên trái, click **"Pages"**
3. Phần **"Source"**, chọn **"Deploy from a branch"**
4. Phần **"Branch"**, chọn **"main"** và folder **"/ (root)"**
5. Click **"Save"**

### Bước 6: Xem website
- Sau 1-2 phút, website sẽ live tại: `https://username.github.io`
- Ví dụ: `https://minhchi-ktdn.github.io`

## ✏️ Tùy chỉnh nội dung

### Cập nhật thông tin cá nhân
Mở file `index.html` và sửa:
- **Tên**: Tìm `<n>Minh Chi</n>` và thay đổi
- **Giới thiệu**: Sửa đoạn văn trong phần giới thiệu
- **Email/Links**: Thay `your.email@example.com` và các link mạng xã hội

### Thêm dự án
1. Copy đoạn code của một dự án mẫu (từ `<tr>` đến `</tr>`)
2. Paste vào cuối phần dự án
3. Sửa:
   - Tên dự án trong `<papertitle>`
   - Mô tả
   - Link GitHub/Demo
   - Tên file ảnh

### Cập nhật kỹ năng
Tìm phần **"Kỹ Năng"** và thêm/sửa các kỹ năng của bạn.

## 💡 Tips
- Ảnh profile nên là ảnh vuông (vd: 400x400px) để hiển thị đẹp
- Ảnh project nên tỉ lệ 16:9 hoặc 4:3
- Sau khi sửa file trên GitHub, click **"Edit"** → sửa → **"Commit changes"**
- Website sẽ tự động cập nhật sau vài phút

## 📚 Tài liệu tham khảo
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jon Barron's Website](https://jonbarron.info/)
- [Markdown Guide](https://www.markdownguide.org/)

---

**Chúc bạn làm portfolio thành công! 🎉**
