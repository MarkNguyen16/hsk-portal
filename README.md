# CỔNG LUYỆN THI HSK TRỰC TUYẾN - TIẾNG TRUNG HSK NHA TRANG

Dự án web sẵn sàng triển khai 1-click lên Vercel để phục vụ nhiều đề thi trên cùng một tên miền web.

## CẤU TRÚC THƯ MỤC:
- `index.html`: Cổng trang chủ hiển thị danh sách các đề thi, thông tin học sinh, bộ lọc cấp độ HSK.
- `de-2.html`: Giao diện làm bài thi HSK 3 Đề số 2 (Mã H31002) tương tác 80 câu hoàn chỉnh.
- `teacher.html`: Bảng điều khiển Giáo viên giám sát điểm số toàn bộ học sinh theo thời gian thực.
- `vercel.json`: Tệp cấu hình đường dẫn tối ưu cho nền tảng Vercel.

## HƯỚNG DẪN ĐẨY LÊN VERCEL (CỰC KỲ ĐƠN GIẢN):

### Cách 1: Đẩy qua GitHub (Khuyên dùng - Cập nhật tự động)
1. Tạo 1 repository mới trên GitHub (đặt tên ví dụ: `hsk-nhatrang-portal`).
2. Tải toàn bộ các file trong thư mục này lên repository đó.
3. Truy cập https://vercel.com, đăng nhập bằng GitHub.
4. Bấm **Add New...** > **Project** > Chọn repository `hsk-nhatrang-portal`.
5. Bấm **Deploy**. Sau 30 giây bạn sẽ có ngay địa chỉ web miễn phí dạng: `https://hsk-nhatrang-portal.vercel.app`.

### Cách 2: Kéo thả trực tiếp lên Vercel CLI / Dashboard
1. Nếu bạn cài Vercel CLI trên máy tính: Mở terminal tại thư mục này và gõ lệnh `vercel`.
2. Hoặc nén thư mục và kéo thả theo hướng dẫn của Vercel.

## CÁCH THÊM ĐỀ THI MỚI (ĐỀ 1, ĐỀ 3, ĐỀ 4,...):
1. Nhân bản file `de-2.html` thành `de-1.html` hoặc `de-3.html`.
2. Thay thế dữ liệu câu hỏi trong tệp mới.
3. Mở `index.html`, nhân bản thẻ card đề thi và đổi link sang `de-1.html` / `de-3.html`.
