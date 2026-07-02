# FireSkull 🔥

Dashboard theo dõi thị trường tiền điện tử & giá vàng real-time, giao diện tiếng Việt.

## Tính năng

- 📊 **Giá coin real-time** — Top 50 coin theo vốn hóa, cập nhật mỗi 20 giây (CoinGecko)
- 📈 **Biểu đồ giá** — BTC/ETH/BNB/SOL/XRP theo khung 24h / 7d / 30d
- 💰 **Giá vàng** — vàng thế giới (XAU), quy đổi VND theo lượng/chỉ
- 😱 **Chỉ số Fear & Greed** — tâm lý thị trường
- 📰 **Tin tức** — tự động dịch tiếng Việt từ CoinTelegraph, CoinDesk, Decrypt, CryptoSlate
- 🎯 Ticker chạy, sắp xếp bảng, lọc coin tăng/giảm mạnh

## Công nghệ

Trang web tĩnh thuần (HTML + CSS + JavaScript), không cần backend hay API key.
Dùng Chart.js cho biểu đồ, gọi trực tiếp các API công khai.

## Chạy local

Mở `index.html` bằng trình duyệt, hoặc serve bằng bất kỳ web server nào:

```bash
npx serve .
```

## Deploy

Tự động deploy lên GitHub Pages từ nhánh `main`.
