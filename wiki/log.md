# Log

Nhật ký thao tác — append-only.

---

## 2026-06-27 — Ingest lần đầu (chunk_001 đến chunk_006)

**Nguồn**: raw/chunk_001.txt đến raw/chunk_006.txt (Prologue, Chunk 1–6 of 378)

**Trang tạo mới**:
- `prologue.md` — tóm tắt và phân tích phần Prologue
- `la-maison.md` — căn nhà gia đình, chambre du cerisier, commode
- `jules-chichery.md` — arrière-grand-père, anh hùng WWI
- `marguerite.md` — grand-mère bị xóa khỏi ký ức gia đình
- `nguoi-ke-chuyen.md` — người kể ngôi thứ nhất ẩn danh
- `cha-nguoi-ke-chuyen.md` — cha người kể, cựu chiến binh Algeria, tự tử
- `su-xoa-bo.md` — motif cắt/tô mặt Marguerite trong ảnh
- `ky-uc-va-do-vat.md` — đồ vật như phương tiện ký ức
- `bi-mat-gia-dinh.md` — các lớp im lặng và bí mật gia đình
- `index.md` — tạo mới
- `log.md` — tạo mới

**Câu hỏi mở sau lần ingest này**:
- Ai đã xóa mặt Marguerite trong ảnh, và vì lý do gì?
- Bí mật gì về Marguerite khiến gia đình phải im lặng suốt nhiều thế hệ?
- "René BOYLESVE" ở đầu chunk_001 là epigraph từ tác giả nào?
- Còn 366 chunks chưa được đọc (chunk_013 đến chunk_378)

---

## 2026-06-27 — Ingest lần hai (chunk_007 đến chunk_012)

**Nguồn**: raw/chunk_007.txt đến raw/chunk_012.txt (Prologue — Chunk 7–12/378)

**Trang tạo mới**:
- `marie-ernestine.md` — arrière-grand-mère, née Proust (27/08/1885), đầy ắp ảnh, "đường lực" của câu chuyện
- `andre-chichery.md` — ông nội, "beau-père tyrannique", biến mất rồi tái xuất sau Marguerite mất
- `francois-ancetre.md` — tổ tiên Napoléon, chết năm 22, gốc rễ gia sản bị thần thoại hóa và quên lãng
- `firmin-proust.md` — cha Marie-Ernestine, địa chủ tư sản, hình ảnh còn trong một ảnh duy nhất

**Trang cập nhật**:
- `marguerite.md` — thêm: xóa toàn bộ ảnh (không chỉ cắt mặt), khoảng trống đồ vật tuyệt đối, Marie-Ernestine coi bà là "honte", Henriette còn sống 2022
- `jules-chichery.md` — thêm: ngày cưới 17/06/1905, nhẫn cưới chìm trong bùn cote 304, cha vợ Firmin Proust
- `ky-uc-va-do-vat.md` — thêm: bảng địa tầng commode (người kể → cha → André → VOID Marguerite → Marie-Ernestine)
- `su-xoa-bo.md` — thêm: xóa bỏ toàn bộ ảnh + đồ vật, không chỉ cắt mặt
- `bi-mat-gia-dinh.md` — thêm: lớp bí mật thứ tư (nguồn gốc gia sản bị quên), cập nhật bảng thế hệ

**Chủ đề mới nổi bật**:
- "Ligne de force": Marie-Ernestine (năng lực) → Marguerite (im lặng) → Cha (cái chết thô bạo)
- Commode như "địa tầng khảo cổ" của 4 thế hệ
- Quên lãng có cấu trúc vs. che giấu có chủ đích
- Paradox: sự vắng mặt tuyệt đối tạo ra hiện diện mạnh hơn sự đầy ắp

**Câu hỏi mở còn lại**:
- Marguerite là "honte" (nỗi ô nhục) của Marie-Ernestine vì lý do gì cụ thể?
- André có vai trò gì trong bi kịch Marguerite?
- Còn 366 chunks chưa đọc (chunk_013 đến chunk_378)

---

## 2026-06-27 — Cập nhật phả hệ gia đình

**Tác vụ**: Cập nhật `phe-he-gia-dinh.html` và tạo mới `phe-he-gia-dinh.md`

**Thay đổi trong HTML**:
- Mở rộng từ 4 → 6 thế hệ (viewBox 620 → 790)
- Thêm: François (tổ tiên Napoléon) với đường đứt nối sang Firmin
- Thêm: Firmin Proust (Thế hệ I) và vợ
- Cập nhật: "Ông nội (unknown)" → "André Chichery" với thông tin đầy đủ
- Sửa: Colette là con riêng Marceline (vợ 2 André), không phải "cha dượng của ông nội"
- Cập nhật: Marie-Ernestine sinh 27/08/1885, ngày cưới 17/06/1905
- Thêm: nhẫn cưới Jules chìm trong bùn Cote 304
- Mở rộng timeline (từ 1916 lên ~1800)
- Thêm notes: "Ligne de force", nhẫn cưới, commode, Colette

**File mới tạo** (`phe-he-gia-dinh.md`):
- Sơ đồ ASCII 6 thế hệ
- Bảng hồ sơ từng nhân vật (8 nhân vật)
- Địa tầng commode dạng ASCII
- Bảng dòng thời gian đầy đủ
- Bảng "Ligne de force" 3 điểm
