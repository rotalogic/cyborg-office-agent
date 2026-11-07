> **© 2026 Wildan / RotaLogic — PROPRIETARY.** Sistem CYBORG dan seluruh isi folder ini milik Wildan / RotaLogic. Penggunaan terbatas untuk Tim RotaLogic; lihat `LICENSE` dan `NOTICE.md`. Build ID: CYBORG-WB-2026-10-30-ROTALOGIC

# CYBORG — Office Agent (Challenge B)

Proyek WorkBuddy untuk "AI CAN DO IT" Tencent Cloud Hackathon Indonesia 2026 — Tim RotaLogic.

**Cara pakai:** buka folder ini sebagai workspace di WorkBuddy, lalu beri tugas lewat chat.
Perilaku agent diatur oleh `AGENTS.md` di folder ini (konstitusi akuntabilitas, direktori perusahaan, aturan operasional, alur rencana → klarifikasi → validasi → konfirmasi → eksekusi simulasi → audit).

Struktur (mengikuti bentuk proyek WorkBuddy dari meetup resmi 29 Okt 2026):

| Folder/file | Isi |
|---|---|
| `AGENTS.md` | Instruksi perilaku agent (master prompt CYBORG) |
| `input/` | Bahan uji sintetis: voice note, dokumen berisi instruksi tersisip, permintaan email |
| `output/` | Hasil kerja agent: rencana pending, audit log, hasil eksekusi simulasi, screenshot bukti |
| `tests/` | Test case (JSON), laporan hasil uji prototipe lokal (10/10), lembar uji percakapan |

Aturan keras: agent tidak memiliki tool sungguhan; tidak ada tindakan sebelum pengguna mengetik SETUJU; penolakan = 0 eksekusi; semua tercatat di `output/audit-log.md`.
