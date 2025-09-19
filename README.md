Dự Án Tốt Nghiệp - Chợ Đầu Mối

1️⃣ Công nghệ

Backend: Laravel 10 (PHP 8, chạy XAMPP)

Frontend: Tailwind CSS / Bootstrap 5 + Alpine.js/Vue.js

Database: MySQL

Realtime: Pusher + Laravel Echo (đơn hàng, chat)

Thư viện hỗ trợ: DataTables.js, Chart.js, SweetAlert2

2️⃣ Chức năng chính
A. Người dùng (Customer)

Đăng ký / đăng nhập / quên mật khẩu.

Quản lý hồ sơ cá nhân.

Quản lý nhiều địa chỉ giao hàng (chọn khi đặt hàng).

Xem sản phẩm theo danh mục, filter, search.

Trang chi tiết sản phẩm (ảnh, giá, mô tả, review).

Giỏ hàng realtime (thêm, sửa, xóa).

Đặt hàng (COD + demo VNPay/Momo).

Theo dõi đơn hàng realtime (Pending → Confirmed → Shipping → Completed).

Đánh giá sản phẩm (rating + bình luận).

Wishlist (yêu thích sản phẩm).

Chat trực tiếp với seller (realtime).

Xem sản phẩm trong Flash Sale (giá khuyến mãi + đồng hồ đếm ngược).

B. Seller (Nhà bán hàng)

Đăng ký shop mới (chờ admin duyệt).

Quản lý sản phẩm của shop (CRUD).

Quản lý đơn hàng của shop.

Trả lời tin nhắn khách hàng.

Xem dashboard doanh thu riêng cho shop.

C. Admin

Quản lý toàn hệ thống.

Duyệt shop mới.

Quản lý sản phẩm, đơn hàng, khách hàng, seller.

Quản lý mã giảm giá (coupon).

Quản lý bình luận/đánh giá.

Dashboard tổng quan (thống kê doanh thu toàn hệ thống, số đơn, số khách).

D. Vận chuyển (Shipping)

Bảng shipping_methods: demo 1–2 đơn vị (GHN, Viettel Post).

Khi đặt hàng → chọn đơn vị vận chuyển.

Admin cập nhật trạng thái giao hàng.

Realtime update: khách thấy trạng thái đơn đổi ngay trên UI (Pusher).

3️⃣ Tính năng nâng cao

Responsive mobile-first.

Search nâng cao + filter theo giá, thương hiệu, rating.

Export báo cáo (Excel/PDF).

Dark mode / Light mode.

API JSON cho sản phẩm/đơn hàng.

4️⃣ Database (bổ sung)

users (quản lý role: admin, seller, customer).

shops (nhiều nhà bán).

products (bổ sung sale_price, sale_start, sale_end).

categories

orders (shipping_id, shipping_status).

order_details

reviews

coupons

wishlists

addresses (nhiều địa chỉ giao hàng).

messages (chat buyer–seller).

shipping_methods (đơn vị vận chuyển).


6️⃣ Demo khi bảo vệ

Đăng nhập bằng user → chọn sản phẩm → thêm giỏ hàng → đặt hàng.

Chọn đơn vị vận chuyển + địa chỉ giao hàng.

Admin cập nhật trạng thái đơn → UI khách tự đổi realtime.

User mở chat với seller → nhắn tin realtime.

Flash Sale hiển thị countdown + giá khuyến mãi.

Admin/Seller trình bày dashboard doanh thu + export báo cáo.
