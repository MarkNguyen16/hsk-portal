# CỔNG KHẢO THÍ HSK ĐA ĐỀ THI - TIẾNG TRUNG HSK NHA TRANG

Cổng luyện thi trực tuyến được thiết kế theo cơ chế **Tự động nhận diện đề thi mới (Auto-Discovery)**:
Bạn **KHÔNG CẦN** sửa `index.html`, **KHÔNG CẦN** cấu hình lại `teacher.html`. Chỉ cần thả 1 file HTML vào GitHub là hệ thống tự động nhận diện và hiển thị đề thi mới ngay lập tức!

---

## 1. QUY TẮC ĐẶT TÊN FILE ĐỂ TỰ ĐỘNG NHẬN DIỆN:
Khi bạn thêm bài thi mới, hãy đặt tên file theo đúng quy tắc sau:

- **HSK 3**:
  - Đề 1: `de-1.html` (Đang mở)
  - Đề 2: `de-2.html` (Đang mở)
  - Đề 3: `de-3.html`
  - Đề 4: `de-4.html`
  - ... đến Đề 10: `de-10.html`
  - File nghe tương ứng: đặt vào `audio/H31001.mp3`, `audio/H31002.mp3`, `audio/H31003.mp3`,...

- **HSK 4**: `hsk4-de-1.html`, `hsk4-de-2.html`, ..., `hsk4-de-10.html`
- **HSK 5**: `hsk5-de-1.html`, ..., `hsk5-de-10.html`
- **HSK 6**: `hsk6-de-1.html`, ..., `hsk6-de-10.html`
- **HSK 3.0**: `hsk30-l1.html`, `hsk30-l2.html`, ..., `hsk30-l79.html`
- **Bài tập Chuẩn**: `sc3-bai-1.html`, `sc3-bai-2.html`, ..., `sc3-bai-20.html`

---

## 2. QUY TRÌNH THÊM 1 ĐỀ THI MỚI (CHỈ 1 BƯỚC DUY NHẤT):
1. Bạn gửi tài liệu đề thi mới (PDF + Audio) vào đây để tôi tạo file HTML (ví dụ: `de-3.html`).
2. Mở GitHub > Bấm **Add file** > **Upload files** > Kéo thả file `de-3.html` vào (và file `audio/H31003.mp3` nếu có).
3. Bấm **Commit changes**.
4. **Xong!** Trang chủ `index.html` sẽ tự động phát hiện file `de-3.html` đã tồn tại trên Vercel, tự động bật nút xanh **"● Đang mở thi"** và cho học viên vào thi ngay lập tức mà bạn không cần chỉnh sửa bất kỳ dòng code nào!
5. Khi học viên nộp bài, Bảng điều khiển `teacher.html` cũng tự động bổ sung mã đề `H31003` vào danh sách lọc kết quả!
