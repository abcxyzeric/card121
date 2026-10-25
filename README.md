# card121 - Nhà Sombreuil (Louisiana Control Center)

Bản dịch tiếng Việt hoàn chỉnh cho giao diện Trung tâm Điều khiển (Control Center v3) của thẻ SillyTavern **Nhà Sombreuil** (DeSombreuil / 桑布勒伊之家).

## 1. Thông tin tài nguyên
- **ControlCenter-v3.js**: Tệp nhúng giao diện điều khiển hoàn chỉnh cho Tavern Helper.
- **ControlCenter-v3.html**: Mã nguồn HTML, CSS và JavaScript của giao diện.

## 2. Liên kết CDN jsDelivr
Để tích hợp vào Tavern Helper của thẻ SillyTavern, sử dụng liên kết:
```javascript
import 'https://cdn.jsdelivr.net/gh/abcxyzeric/card121@main/ControlCenter-v3.js';
```

## 3. Các điểm nổi bật
- Dịch chuẩn xác toàn bộ giao diện người dùng, thông báo và trạng thái sang tiếng Việt tự nhiên.
- Đồng nhất 100% cấu trúc biến với bộ schema Zod tiếng Việt và script kiểm soát biến (`varctl_vi.js`).
- Hỗ trợ cơ chế tra cứu hai chiều (`KEY_MAP`) đảm bảo tương thích ngược và không bao giờ gặp lỗi thiếu dữ liệu (undefined variable).
- Đấu nối chính thức qua kênh `$Xử lý` cho các thao tác Mua sắm, Thanh toán hóa đơn, Nghiên cứu cố định và Nghiên cứu tự do.
