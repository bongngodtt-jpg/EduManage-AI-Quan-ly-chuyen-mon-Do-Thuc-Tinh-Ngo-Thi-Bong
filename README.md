# EduManage AI

Ứng dụng quản lý hồ sơ chuyên môn nhà trường (bản V5 Premium - Mẫu mới), chạy trực tiếp trên trình duyệt, chỉ gồm một tệp `index.html`.

## Cách xem trang

1. Vào **Settings → Pages**.
2. Mục **Source** chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, rồi bấm **Save**.
3. Sau vài phút, GitHub cung cấp đường link để mở trang.

Có thể mở trực tiếp `index.html` bằng trình duyệt trên máy.

## Cấu trúc

- `index.html`: toàn bộ ứng dụng
- `.nojekyll`: báo GitHub Pages không xử lý bằng Jekyll
- `README.md`: tệp hướng dẫn này

## Trợ lý ảo EduBot AI

Góc dưới bên phải trang có nút **EduBot AI**: hướng dẫn nghiệp vụ, tra cứu nhanh trạng thái hồ sơ theo vai trò và ghi nhận báo lỗi. EduBot chạy hoàn toàn trên trình duyệt (trả lời theo từ khoá, chưa gọi AI trực tuyến); báo lỗi được lưu cùng dữ liệu ứng dụng và có trong bản sao lưu JSON.
