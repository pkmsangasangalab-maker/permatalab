# PERMATA LAB
UPTD Puskesmas Sanga-sanga 2026

Situs statis, dipublikasikan lewat GitHub Pages.
Letakkan semua file di folder yang sama (index.html, PKM1.jpg, LOGO_PKM_SANGASANGA.jpg, _nojekyll).

## Yang diatur admin (di index.html, cari "PENGATURAN TAMBAHAN")
- DATA_DIPERBARUI : tanggal data laporan diperbarui admin (opsional)
- PANDUAN         : isi panduan / SOP
- STOK_CSV        : link CSV publik dari tab ringkasan stok
- STOK_DATA       : alternatif, ketik manual bila tidak memakai Google Sheets

## Peringatan ketersediaan reagen (kedaluwarsa tidak dipakai)
Kolom di tab ringkasan (baris pertama, huruf kecil): nama, stok, min, satuan, keterangan
- Jika "keterangan" berisi kata "order"/"habis" -> tampil sebagai peringatan
- Jika "keterangan" berisi "aman" -> dianggap aman
- Jika "keterangan" kosong -> peringatan dihitung dari stok <= min, atau stok 0
Nama kolom alternatif juga dikenali: "nama reagen", "stok akhir".

Login, kode pemulihan, dan nomor WhatsApp admin (ADMIN_WA) tidak diubah.
