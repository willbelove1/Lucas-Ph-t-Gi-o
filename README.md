# 🪷 Lucas Phật Giáo

Ứng dụng Phật Giáo Việt Nam cho Android — kinh sách, lịch âm dương, giờ hành lễ,
Thất Tuần/Giỗ, giáo lý... dành cho cả Tăng Ni/trụ trì lẫn Phật tử tại gia.

**Offline-first · Không quảng cáo · Không tài khoản · Không thu thập dữ liệu**

---

## Tính năng

**📅 Lịch Âm Dương & Hoàng Đạo** — xem Can Chi, giờ Hoàng Đạo, Lễ Vía theo từng
ngày; chấm báo ngày có lễ ngay trên lịch tháng.

**📖 Kinh Sách offline** — đọc kinh không cần mạng, tìm kiếm có dấu hoặc không
dấu đều được, hỗ trợ giọng nói, đánh dấu/highlight, đọc bằng giọng đọc (TTS).

**⚰️ Thất Tuần & Giỗ** — nhập ngày mất (Dương lịch hoặc Âm lịch tuỳ trường hợp),
app tự tính 7 Thất, Bách Nhật, Tiểu/Đại Tường. Hỗ trợ cả trường hợp giỗ lâu năm
chỉ nhớ ngày/tháng âm, không nhớ năm mất.

**🔔 Giờ Hành Lễ** — 2 chế độ: **Tự Viện** (cố định theo "hai thời công phu")
hoặc **Tại Gia** (tự chọn giờ rảnh để tụng kinh/niệm Phật).

**🪷 Giáo Lý** — tổng hợp kiến thức nền: Tứ Diệu Đế, Bát Chánh Đạo, Ngũ Giới,
Nhân Quả - Luân Hồi, và giới thiệu cả 3 truyền thống Bắc Tông/Nam Tông/Khất Sĩ.

**📥 Cập Nhật & Chia Sẻ Kinh** — thêm kinh mới bằng file `.lucasphatgiao`, không
cần server. Người dùng có thể tự soạn, chia sẻ file cho nhau.

**💾 Sao Lưu & Khôi Phục** — toàn bộ dữ liệu cá nhân (hồ sơ hương linh, ghi chú,
đánh dấu) xuất/nhập qua 1 file, không phụ thuộc đám mây.

**🏠 Widget & khoá màn hình** — xem nhanh ngày âm, giờ hành lễ, lễ vía sắp tới
ngay trên màn hình chính.

---

## Điểm khác biệt

- **Phân loại rõ ràng Phật Giáo chính thống ↔ tín ngưỡng dân gian** (thờ cúng tổ
  tiên, Đạo Mẫu/Tứ Phủ...) — nhiều app gộp chung khiến người dùng lầm tưởng tục
  lệ dân gian là giáo lý nhà Phật. App này tách bạch rõ bằng nhãn phân loại trên
  từng kinh/ngày lễ.
- **Hỗ trợ cả 3 truyền thống** — Bắc Tông, Nam Tông, Khất Sĩ — trong cùng một
  ứng dụng, thay vì chỉ phục vụ một hệ phái.
- **Tính giỗ theo ÂM LỊCH THẬT** — Tiểu Tường/Đại Tường tính đúng theo ngày âm
  lịch năm sau, không cộng cứng 365 ngày dương lịch (cách làm phổ biến nhưng sai
  lệch dần qua từng năm).
- **Cập nhật kinh không lệ thuộc server** — cộng đồng có thể tự bổ sung, chỉnh
  sửa và chia sẻ nội dung kinh cho nhau qua file, không cần chờ nhà phát triển
  cập nhật app.
- **Tôn trọng bản quyền kinh văn** — nội dung kinh được research nguồn cụ thể,
  minh bạch; những phần chưa xác minh được để trống kèm nguồn gợi ý thay vì tự
  chế nội dung.
- **100% offline sau khi cài** — không quảng cáo, không tài khoản, không theo
  dõi người dùng.
- **Mã nguồn mở, kiến trúc rõ ràng** — dễ đọc, dễ tuỳ biến hoặc phát triển thêm
  tính năng.

---

## Công nghệ

Kotlin · Jetpack Compose (Material 3) · Room Database · Hilt (DI) · Moshi (JSON)
· thuật toán lịch âm dương Hồ Ngọc Đức.

---

## Đóng góp nội dung kinh

Không cần sửa code. Cài Đặt → **Cập Nhật & Chia Sẻ Kinh** → **Xuất file** để lấy
mẫu đúng chuẩn, chỉnh sửa/bổ sung nội dung, rồi **Nhập file** lại vào máy — hoặc
chia sẻ file đó cho người khác dùng.

---

## Giấy phép & nguồn nội dung

Mã nguồn phát hành mở để tham khảo và sử dụng. Nội dung kinh/giáo lý được tổng
hợp có ghi nguồn; phần nào chưa xác minh được nguồn rõ ràng sẽ để trống thay vì
tự soạn — xem chi tiết trong `README.md` (kỹ thuật) đi kèm mã nguồn.
