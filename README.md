# 💬 Bubble Maker — Công cụ tạo bóng thoại

Công cụ vẽ **bóng thoại (speech bubble)** chạy hoàn toàn trên trình duyệt, không cần cài đặt, không cần backend. Chỉ cần mở file HTML là dùng được ngay — phù hợp cho làm truyện tranh, meme, minh hoạ, edit ảnh, v.v.

![HTML](https://img.shields.io/badge/HTML-5-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow) ![No Backend](https://img.shields.io/badge/Backend-Không%20cần-blue) ![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Tính năng

- **5 kiểu bóng thoại**: Bầu dục, Chữ nhật (bo góc), Đám mây (thought bubble), Gai (shout/nổ), và **Tự vẽ** hình tuỳ ý.
- **3 cách tự vẽ hình**: click từng điểm, vẽ tự do (freehand), hoặc dùng bút với các cạnh bo cong.
- **Đuôi bóng thoại linh hoạt**: kéo thả điểm gốc, điểm mút, bật/tắt, đổi giữa đuôi nhọn hoặc đuôi kiểu chuỗi bong bóng tròn, bo cong đuôi tuỳ ý.
- **Tuỳ chỉnh gai** (cho bóng "hét"): số lượng gai, độ dài, độ dày, độ so le, độ cong đáy.
- **Tuỳ chỉnh viền**: độ dày, màu nền/viền, nét đứt (dash) với độ dài/khoảng cách tuỳ chỉnh.
- **Nhiều bóng thoại cùng lúc** trên một canvas, quản lý qua danh sách bên trái.
- **Ảnh nền tham chiếu**: tải ảnh lên để vẽ bóng thoại theo, chỉnh độ mờ, ẩn/hiện, xoá — ảnh nền không xuất hiện khi export.
- **Xuất ảnh PNG**:
  - Xuất riêng bóng thoại đang chọn (tự động crop sát viền, nền trong suốt).
  - Xuất toàn bộ canvas.
  - Chọn tỉ lệ xuất ảnh 1x / 2x / 3x / 4x.
- Tuỳ chỉnh kích thước canvas theo ý muốn.

## 🚀 Cách sử dụng

Không cần cài đặt gì cả:

1. Tải file `index.html` (hoặc file `.html` chính của repo) về máy.
2. Mở file đó bằng bất kỳ trình duyệt hiện đại nào (Chrome, Edge, Firefox...).
3. Bắt đầu tạo bóng thoại!

> Hoặc dùng **GitHub Pages** để chạy trực tiếp trên web — xem phần bên dưới.

### Chạy bằng GitHub Pages

1. Push file HTML này lên repository GitHub.
2. Vào **Settings → Pages**, chọn nhánh (branch) chứa file, thư mục gốc (`/root`).
3. Truy cập link được GitHub cung cấp, ví dụ: `https://<username>.github.io/<repo-name>/`.

## 🖱️ Hướng dẫn nhanh

| Thao tác | Cách làm |
|---|---|
| Thêm bóng thoại mới | Nhấn **"Thêm bóng thoại"** ở thanh công cụ |
| Đổi hình dạng | Chọn một trong 5 icon hình (Bầu dục, Chữ nhật, Đám mây, Gai, Tự vẽ) |
| Di chuyển bóng | Kéo thả tại tâm bóng thoại |
| Đổi kích thước | Kéo tay cầm ở góc dưới-phải |
| Chỉnh đuôi | Kéo chấm màu đỏ (đầu đuôi) và chấm màu tím (gốc đuôi) |
| Đổi màu | Dùng ô chọn màu **Nền** / **Viền** trên thanh công cụ |
| Vẽ hình tự do | Chọn **"Tự vẽ"** → chọn chế độ (điểm / tự do / bút) → vẽ trên canvas → nhấn **Hoàn tất** (hoặc `Enter`), `Esc` để huỷ |
| Xuất ảnh | Nhấn **"Export bóng đang chọn"** hoặc **"Export toàn canvas"** |

## 🛠️ Công nghệ

- HTML5 Canvas (vẽ và xuất ảnh)
- Vanilla JavaScript (không dùng framework, không cần build)
- CSS thuần

Toàn bộ logic nằm gọn trong **1 file HTML duy nhất**, dễ tuỳ biến và triển khai.

## 📁 Cấu trúc

```
├── index.html   # Toàn bộ ứng dụng (HTML + CSS + JS)
└── README.md
```

## 🤝 Đóng góp

Mọi ý kiến đóng góp, báo lỗi (issue), hoặc pull request đều được hoan nghênh!

## 📄 Giấy phép

Phát hành theo giấy phép [MIT](LICENSE) — tự do sử dụng, chỉnh sửa và phân phối.
