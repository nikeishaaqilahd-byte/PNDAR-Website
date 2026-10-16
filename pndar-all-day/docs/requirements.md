# Dokumen Kebutuhan: Website Profil PNDAR All Day

> Seluruh deskripsi menu pada proyek ini adalah **data simulasi pembelajaran**. Nama usaha, harga, alamat, dan jam buka berasal dari Google Maps dan belum dikonfirmasi pemilik usaha.

## 1. Masalah usaha
Calon pelanggan belum punya satu tempat yang jelas untuk melihat menu, harga, lokasi, dan jam buka PNDAR All Day sebelum berkunjung.

## 2. Pengguna sasaran
Mahasiswa dan pekerja di sekitar Kukusan, Beji, Depok yang mencari ruang untuk bekerja, berkolaborasi, atau bersantai.

## 3. Tujuan website
Memudahkan calon pelanggan memperoleh informasi usaha dan menemukan lokasi.

## 4. Ruang lingkup
- Dikerjakan: satu landing page (beranda, katalog, kontak).
- Tidak dikerjakan: login, keranjang, pembayaran, database pesanan.

## 5. Kebutuhan fungsional dan nonfungsional

| ID | Jenis | Kebutuhan | Kriteria penerimaan |
|----|-------|-----------|---------------------|
| F-01 | Fungsional | Pengguna dapat melihat empat menu | Nama, deskripsi, dan harga tampil pada setiap kartu |
| F-02 | Fungsional | Navigasi menuju bagian halaman | Semua anchor menuju ID yang benar (#beranda, #katalog, #kontak) |
| F-03 | Fungsional | Kontak mudah ditemukan | Alamat, jam buka,telepon, email dan tautan Google Maps tersedia |
| NF-01 | Nonfungsional | Layout responsif | Tidak ada scroll horizontal pada 360, 390, 768, 1366 px |
| NF-02 | Nonfungsional | Navigasi dapat digunakan lewat keyboard | Tautan dapat difokuskan dan diaktifkan, fokus terlihat |
| NF-03 | Nonfungsional | Markup valid | Tidak ada error HTML pada validator |
| NF-04 | Nonfungsional | Audit otomatis memadai | Accessibility dan Best Practices >= 90 (target praktikum) |
| NF-05 | Nonfungsional | Proyek mudah dipelihara | CSS terpisah dan README tersedia |

## 6. Informasi simulasi
- Deskripsi singkat tiap menu ditulis kelompok sebagai contoh.
- Tautan kontak hanya Google Maps; Instagram belum tersedia dan tidak dikarang.
- Pengenalan usaha, alamat, jam buka, telepon, email, nama menu, dan harga berasal dari data yang didapatkan di Google Maps; belum konfirmasi pemilik.

## 7. Kebutuhan teknis
Viewport uji (CSS pixel): 360, 390, 768, 1366. Browser: Chrome dan Firefox. HTML dan CSS tanpa framework. Foto: diambil dari google maps belum berizin dan belum konfirmasi izin pemakaian foto kepada pemilik.

## 8. Latihan: dari "website harus bagus" menjadi dapat diuji
"Pada viewport 360 px, judul, katalog, dan kontak dapat dibaca tanpa menggulir halaman ke samping."
