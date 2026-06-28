# Log

Nhật ký thao tác — 5 entries gần nhất. Entries cũ hơn ở [[log-archive]].

---

## 2026-06-28 — Ingest lần ba (chunk_013 đến chunk_017)

**Nguồn**: raw/chunk_013.txt đến raw/chunk_017.txt (Prologue kết thúc + Chương I mở đầu — Chunk 13–17/378)

**Trang tạo mới**:
- `femme-de-firmin.md` — vợ vô danh của Firmin, nạn nhân bạo lực gia đình, kháng cự thầm lặng
- `paul-proust.md` — anh cả Marie-Ernestine, đi tu theo kế hoạch Firmin
- `anatole-proust.md` — anh thứ hai, "calamité", lên Paris; đồng tính gợi ý

**Trang cập nhật**:
- `firmin-proust.md`, `marie-ernestine.md`, `francois-ancetre.md`, `la-maison.md`, `bi-mat-gia-dinh.md`, `phe-he-gia-dinh.md`, `index.md`

**Điểm cấu trúc**: Chunk 014 — hết Prologue, bắt đầu Chương I. *"C'est avec Marie-Ernestine que tout commence."*

**Chunks đã xử lý**: 001–017 / 378

---

## 2026-06-28 — Tối ưu hóa token

**Tác vụ**: Tái cấu trúc workflow để giảm token consumption

**Thay đổi**:
- `map.md` — tạo mới: routing table để chọn đúng file cần đọc
- `log-archive.md` — tạo mới: archive entries cũ từ log.md
- `phe-he-gia-dinh.md` — xóa bảng hồ sơ nhân vật (đã có trang riêng)
- `CLAUDE.md` — viết lại ingest workflow theo token-optimized protocol
- `index.md` — thêm map.md, log-archive.md
