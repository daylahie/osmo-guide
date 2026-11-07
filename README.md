# Osmo Guide

Bảng tra nhanh DJI Osmo Pocket 4 & DJI Mic Mini 2 — web app 1 trang, mobile-first, chạy trên GitHub Pages.

- Không cần build: chỉ `index.html` (Tailwind CSS + Alpine.js qua CDN).
- PWA: mở bằng Safari → Chia sẻ → **Thêm vào MH chính** để chạy toàn màn hình.
- 4 tab: Điều khiển, Công thức (có minh họa khung hình), Giờ vàng · Giờ xanh, Sửa lỗi.
- Giờ vàng / giờ xanh tính ngay trên máy theo vị trí mặt trời, không cần mạng.
- "Công thức của tôi" và các lựa chọn được lưu trong `localStorage` của trình duyệt (chỉ trên máy đó).

Chạy thử trên máy: `python3 -m http.server 8000` rồi mở http://localhost:8000
