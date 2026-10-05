# Bố cục responsive với CSS Flexbox

Bài thực hành có Header, Navigation, Main Content, Sidebar và Footer; sử dụng HTML và CSS riêng biệt.

## Chạy bài

Mở `index.html` bằng trình duyệt. CSS nằm trong `style.css`.

## Bố cục

- Container sử dụng display flex và flex-direction column.
- Main Container sử dụng display flex, content có flex 3, sidebar có flex 1; padding hai cột bằng nhau.
- Navigation và nhóm bài viết sử dụng flex-wrap.
- Ở màn hình từ 768px trở xuống, Main Container chuyển sang column, sidebar nằm dưới content.
- Sử dụng min-height 100vh để trang vẫn mở rộng khi nội dung dài.

## Ảnh kết quả

- `desktop.png`: giao diện desktop.
- `mobile.png`: giao diện mobile.
