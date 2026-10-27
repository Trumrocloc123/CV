# Portfolio Cá Nhân – Đoàn Huy Tùng

## 1. Tên dự án
Portfolio cá nhân website giới thiệu bản thân, kỹ năng, dự án tiêu biểu và thông tin liên hệ.

## 2. Mô tả
Dự án là một trang web portfolio cá nhân được xây dựng bằng HTML5 và CSS3, nhằm giới thiệu thông tin cơ bản về người dùng như tên, nghề nghiệp, kỹ năng, dự án đã thực hiện và phương thức liên lạc. Trang web mang phong cách hiện đại, tối giản nhưng vẫn dễ nhìn, dễ sử dụng và phù hợp với nhiều thiết bị.

Dự án này phù hợp để giới thiệu bản thân cho:
- sinh viên
- người tìm việc
- freelancer
- nhà phát triển frontend
- cá nhân muốn xây dựng hồ sơ trực tuyến

## 3. Chức năng
- Hiển thị banner giới thiệu cá nhân
- Hiển thị tên, vai trò nghề nghiệp và mô tả ngắn
- Trình bày các kỹ năng theo kiểu danh sách hoặc chip
- Hiển thị các dự án tiêu biểu với hình ảnh và mô tả
- Cung cấp phần liên hệ để người xem có thể kết nối
- Hỗ trợ giao diện responsive cho desktop, tablet và mobile
- Có điều hướng nhanh giữa các phần chính của trang

## 4. Công nghệ sử dụng
- HTML5
- CSS3
- Flexbox
- CSS Grid
- Responsive Design
- Git & GitHub
- Trình duyệt web hiện đại như Chrome, Edge, Firefox

## 5. Yêu cầu môi trường
Để chạy được dự án, máy tính cần có:
- Trình duyệt web: Chrome, Edge, Firefox, Safari
- VS Code (khuyến nghị)
- Git
- Python 3 (để chạy local server)
- Docker (nếu muốn chạy bằng container)

## 6. Cài đặt
### Cách 1: Mở trực tiếp bằng trình duyệt
1. Clone hoặc tải toàn bộ project về máy.
2. Mở thư mục dự án.
3. Nhấp đúp vào file `index.html`.
4. Trang web sẽ mở trong trình duyệt mặc định.

### Cách 2: Chạy bằng local server (khuyến nghị)
1. Mở Terminal hoặc Command Prompt trong thư mục dự án.
2. Chạy lệnh:

```bash
python -m http.server 8000
```

3. Mở trình duyệt và truy cập:

```text
http://localhost:8000
```

## 7. Cấu hình
Dự án là project tĩnh nên không cần cấu hình phức tạp. Các tệp chính bao gồm:

```text
KT A2.1/
├── index.html
├── README.MD
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       └── các file hình ảnh
└── BAOCAO-A2.1.docx
```

Nếu muốn tùy chỉnh nội dung, bạn có thể chỉnh sửa trực tiếp trong file `index.html` như:
- tiêu đề chính
- mô tả giới thiệu
- kỹ năng
- dự án
- thông tin liên hệ

Ví dụ:

```html
<h1 class="hero-title">Đoàn Huy Tùng</h1>
<p class="hero-desc">Tôi xây dựng giao diện web đẹp cho bạn</p>
```

## 8. Chạy thử
### Windows
1. Mở Command Prompt hoặc PowerShell trong thư mục project.
2. Chạy lệnh:

```bash
python -m http.server 8000
```

3. Mở trình duyệt và truy cập:

```text
http://localhost:8000
```

### macOS
1. Mở Terminal trong thư mục project.
2. Chạy lệnh:

```bash
python3 -m http.server 8000
```

3. Mở trình duyệt và truy cập:

```text
http://localhost:8000
```

### Linux
1. Mở Terminal trong thư mục project.
2. Chạy lệnh:

```bash
python3 -m http.server 8000
```

3. Mở trình duyệt và truy cập:

```text
http://localhost:8000
```

### Docker
Nếu dùng Docker, bạn có thể chạy website tĩnh bằng nginx như sau:

```bash
docker run -d --name portfolio-site -p 8080:80 -v "$PWD":/usr/share/nginx/html nginx:alpine
```

Sau đó truy cập:

```text
http://localhost:8080
```

Dừng container:

```bash
docker stop portfolio-site
```

Xóa container:

```bash
docker rm portfolio-site
```

## 9. Hướng dẫn sử dụng nhanh
- Thay ảnh đại diện trong thư mục `assets/img/`
- Sửa thông tin cá nhân trong file `index.html`
- Thêm hoặc bớt kỹ năng và dự án bằng cách chỉnh các phần HTML tương ứng
- Nếu gặp lỗi đường dẫn hình ảnh, hãy kiểm tra lại đường dẫn trong file HTML

## 10. Thông tin liên hệ
- Họ tên: Đoàn Huy Tùng
- Email: huytung2112008@example.com
- GitHub: github.com/Trumrocloc123!
- LinkedIn: linkedin.com/in/doanhuytungchimto

## 11. Lưu ý
Dự án này là một website tĩnh nên rất dễ triển khai và tùy chỉnh. Nếu muốn nâng cấp hơn nữa, bạn có thể thêm:
- JavaScript tương tác
- Dark mode
- Form liên hệ
- Animation
- Chuyển đổi sang React hoặc Next.js

## 12. Kết luận
Dự án portfolio cá nhân này giúp bạn trình bày thông tin bản thân một cách rõ ràng, chuyên nghiệp và thân thiện với người dùng. Đây là một mẫu web tĩnh dễ học, dễ sửa và dễ mở rộng cho cả người mới bắt đầu lẫn người muốn xây dựng hồ sơ cá nhân chuyên nghiệp.

---

Nếu bạn muốn, tôi có thể tiếp tục giúp bạn:
1. Chỉnh sửa giao diện đẹp hơn nữa
2. Viết thêm file `Dockerfile`
3. Tạo phiên bản React cho dự án này
4. Sửa lại nội dung theo đúng thông tin cá nhân của bạn
