<p align="center">
  <img src="logo_ngang.png" alt="Đăng Bài Pro" width="640">
</p>

# Đăng Bài Pro

Phần mềm Windows **đăng video hàng loạt lên Fanpage Facebook**, tự lấy **ID bài viết** để lên quảng cáo và **hẹn giờ** đăng bài.

## ⬇ Tải về

👉 **[Tải bản mới nhất](https://github.com/nvhienn01-spec/dang-bai-pro/releases/latest)** – tải file `DangBaiPro_vX.Y.zip` ở mục *Assets*.

1. Giải nén vào một thư mục riêng (ví dụ `D:\DangBaiPro\`).
2. Bấm đúp `DangBaiPro.exe`. Nếu Windows hiện *"Windows protected your PC"*: bấm **More info → Run anyway**.
3. Vào tab **📄 Fanpage** thêm Page (Page ID + Page Access Token), rồi đăng bài ở các tab đăng.

Hướng dẫn chi tiết nằm trong file `HUONG_DAN_SU_DUNG.txt` đi kèm.

## Tính năng

- **Nhiều tab trong 1 cửa sổ** – mỗi tab chọn 1 Page, chạy song song, quy trình riêng.
- **Đăng ngay** (giãn cách ngẫu nhiên, tạm dừng / dừng, đăng lại hàng lỗi) hoặc **hẹn giờ**.
- Nạp bài từ **Excel**, dán thẳng từ Excel, hoặc chọn **thư mục video**; hỗ trợ **link TikTok** (tự tải, lỗi thì thử lại 3 lần).
- **Cột ID bài viết** – lấy đúng ID bài (kể cả bài video Facebook còn đang xử lý), bấm đúp để copy, copy cả cột.
- **Tự xoá video sau khi đăng** cho nhẹ máy (video của bạn vào Thùng rác, video tạm TikTok xoá hẳn).
- Tự **kiểm tra token** các Page, nhật ký lọc theo tab / lỗi, thanh trạng thái, nhớ các tab khi mở lại.
- **Tự cập nhật**: có bản mới, tool hỏi rồi tự tải, tự đóng và mở lại – dữ liệu giữ nguyên.

## Lưu ý

- Dữ liệu (danh sách Page có token, lịch sử) nằm trong `facebook.db` cạnh exe – **không gửi file này cho người khác**.
- Dùng API chính thức của Facebook (Graph API) với token Page của bạn. Đăng quá dày vào 1 Page dễ bị Facebook giới hạn.
- Chỉ đăng nội dung bạn có quyền sử dụng. Phần mềm không liên kết hay được bảo trợ bởi Meta / Facebook / TikTok.
