# subvi — bản phát hành

Tạo phụ đề tiếng Việt chuẩn rạp từ video tiếng Anh.

Repo này **chỉ chứa các bản phát hành**. Mã nguồn được lưu riêng.

## Cài lần đầu

1. Vào mục [**Releases**](https://github.com/morganluu/tool-auto-subtitle-releases/releases/latest), tải file `tool-auto-subtitle-X.Y.Z.zip`.
2. Giải nén ra một thư mục cố định, ví dụ `D:\subvi`.
3. Double-click `setup.bat`, rồi dán khóa API vào file `.env` như nó hướng dẫn.
4. Kéo file video thả lên `dich-phu-de.bat`.

Mở `HUONG-DAN.html` trong thư mục vừa giải nén để xem hướng dẫn đầy đủ.

## Cập nhật

Không cần tải lại. Mỗi lần mở `dich-phu-de.bat`, công cụ tự hỏi khi có bản mới — bấm Enter là xong.
Khóa API, `glossary.txt`, thư mục `output` và model đã tải đều được giữ nguyên.

Mỗi file ZIP đi kèm một file `.sha256` để công cụ kiểm tra file tải về không bị hỏng.
