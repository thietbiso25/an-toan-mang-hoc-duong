# AN TOÀN MẠNG HỌC ĐƯỜNG

Website tĩnh (một file `index.html`) về an toàn mạng cho học sinh: quy tắc 4C, học liệu số, thử thách 7 ngày, hỗ trợ...

## Cấu trúc

```
.
├── index.html    # toàn bộ trang web (HTML + CSS + JS)
├── supabase.sql  # tạo bảng + phân quyền trên Supabase
├── HUONG_DAN.md  # các bước kết nối khu quản trị
├── README.md    # tài liệu này
└── .gitignore
```

## Xem trang trên máy

Mở file `index.html` bằng trình duyệt (nhấp đúp). Không cần cài đặt gì thêm.

## Khu quản trị

Nội dung (video, trò chơi, cẩm nang, bộ thẻ, bài viết) được lưu trên Supabase. Xem `HUONG_DAN.md` để cài đặt. Tab **Thử thách 7 ngày** nhập nhiệm vụ từ file Word/txt; tab **Bộ đếm** cập nhật số Sứ giả. Khi chưa điền `SB_URL`/`SB_KEY`, trang chạy chế độ demo (không lưu).

## Cập nhật giao diện/mã

1. Sửa file `index.html`.
2. Commit và push lên GitHub.
3. Vercel (hoặc GitHub Pages) tự động cập nhật trang sau ít phút.

## Triển khai

- **Vercel:** Import repo, Framework Preset = *Other*, để trống Build Command và Output Directory, bấm Deploy.
- **GitHub Pages:** Settings → Pages → Branch `main`, thư mục `/ (root)`.

## Ghi chú

- Phông chữ Be Vietnam Pro tải từ Google Fonts (cần Internet).
- Liên hệ/hỗ trợ: xem phần liên kết Zalo và Facebook trong trang.
