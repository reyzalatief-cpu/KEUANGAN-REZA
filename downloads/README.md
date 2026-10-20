# Keuangan Reza 3.1 — dengan Impor Excel

Unduh `Keuangan-Reza-v3.1.0.zip`, ekstrak seluruh isinya, lalu baca `MULAI-DI-SINI.md`.

- Fitur baru: menu **Impor Excel** bagi pemilik, pembacaan `.xlsx`, pilihan kolom, pratinjau dan validasi server.
- Mendukung jurnal/saldo awal, kas masuk/keluar, kontak, produk, akun, serta mutasi bank.
- Template kosong tersedia di menu Impor Excel dan `templates/impor-excel.xlsx`.
- Node.js 24.13–24.x. Windows: `MULAI-WINDOWS.cmd`; Linux/macOS: `bash mulai.sh`.
- Tanpa AI, CDN, atau instalasi dependensi npm runtime. Akun pemilik dibuat sendiri.

## Jika sudah menggunakan versi 3.0

Buat cadangan dan hentikan server lama dengan Ctrl+C. Ekstrak versi baru ke folder terpisah. Salin folder `data` beserta seluruh isinya dan `.env` dari folder lama ke folder baru, lalu jalankan versi baru. Pertahankan folder lama sebagai cadangan. Jika `DATA_DIR` menunjuk lokasi khusus, gunakan lokasi yang sama. Muat ulang browser dan masuk dengan akun pemilik.

Paket terbaru berisi 52 file source, launcher, template, lisensi, panduan, serta pengujian. Database pengguna, `.env`, dan kunci autentikasi tidak disertakan. Paket versi sebelumnya tetap tersedia.

Validasi: 62 tes unit/API + 14 tes browser lulus; ZIP dan aset Excel dalam paket diperiksa.

SHA-256 v3.1.0: `b72cc065e71f17026228b9d45f799b357ca0ca7b326274977dd648f9ea5d3780`

Cabang ini khusus pengiriman paket; aplikasi lengkap berada di dalam ZIP. Cabang utama tidak diubah.
