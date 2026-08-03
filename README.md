# Tumbuh

Aplikasi web satu berkas untuk mendampingi orang tua menaikkan berat badan anak: jadwal makan harian, catatan per tanggal, dan kurva berat menurut umur standar WHO.

**Buka:** https://calvin-aziszam-s.github.io/tumbuh/

## Isi

- **Hari Ini** — enam waktu makan dengan menu harian, kalori, dan takaran susu. Ketuk kartu untuk menandai selesai. Strip minggu di atas untuk berpindah tanggal.
- **Menu** — menu tujuh hari yang berulang tiap minggu, plus acuan porsi sekali makan besar.
- **Kalender** — catatan makan per tanggal dengan cincin kemajuan, navigasi bulanan, dan rekap bulan berjalan. Tanggal yang sudah lewat masih bisa diisi.
- **Berat** — kurva berat menurut umur (WHO, anak laki-laki, 12–60 bulan) dengan pita −3SD sampai +2SD, riwayat penimbangan, dan pembacaan status otomatis.
- **Panduan** — penambah kalori, aturan pemberian makan, dan tanda-tanda yang perlu diperiksakan ke dokter.

## Catatan teknis

- Satu berkas `index.html`, tanpa dependensi eksternal — semua CSS, JavaScript, dan ilustrasi SVG tertanam di dalamnya. Jalan sepenuhnya offline.
- Data tersimpan di `localStorage` perangkat masing-masing. Tidak ada server, tidak ada akun, tidak ada data yang dikirim ke mana pun.
- Kunci tanggal memakai waktu lokal, bukan UTC, supaya pergantian hari tepat di zona waktu Indonesia.
- Mendukung mode terang dan gelap, dan sudah disiapkan untuk dipasang ke Layar Utama iPhone (Safari → Bagikan → Tambahkan ke Layar Utama).

## Menjalankan secara lokal

Cukup buka `index.html` di peramban. Tidak ada langkah build.

## Penafian

Panduan gizi umum berdasarkan standar WHO dan Kemenkes. Bukan pengganti pemeriksaan dokter anak atau posyandu.
