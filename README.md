# Coffee E-commerce Demo — website mẫu bán cà phê đặc sản

Website mẫu (thương hiệu giả định **MỘC**) minh hoạ đầy đủ luồng thương mại điện tử cho ngành cà phê / trà / wellness.

**Live:** https://luongkhanhtoann.github.io/coffee-ecommerce-demo/

## Luồng có trong demo

1. Trang chủ — câu chuyện thương hiệu, giao diện "premium heritage" (bảng màu lấy từ sơn mài Việt: giấy dó, vàng quỳ, son đỏ)
2. Bộ sưu tập 8 sản phẩm, lọc theo nhóm
3. Chi tiết sản phẩm — chọn trọng lượng (250g / 500g / 1kg), kiểu xay, số lượng
4. Giỏ hàng (drawer) — sửa/xoá, ngưỡng miễn phí vận chuyển 500.000₫
5. Thanh toán — form người nhận có validate, COD / chuyển khoản / ví điện tử, mã giảm giá `MOC10`
6. Xác nhận đơn — sinh mã đơn + mã vận đơn, mô phỏng gửi email & SMS
7. Theo dõi giao hàng — timeline 5 trạng thái tự cập nhật, tra cứu lại bằng mã đơn

Giao diện sáng/tối, responsive. Một file `index.html` tĩnh, không phụ thuộc thư viện ngoài.

> Dữ liệu chạy trong trình duyệt (prototype). Bản production cần backend đơn hàng, cổng thanh toán (VNPay / MoMo) và webhook đơn vị vận chuyển (GHTK / GHN) để tracking là dữ liệu thật.
