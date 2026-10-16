# Catatan Pengujian
Tanggal pemeriksaan otomatis: 2026-10-16. Kolom **Status** yang berisi "BELUM" harus diisi kelompok setelah diuji manual 

## Pengujian layout (Chromium, tanpa scroll horizontal)
| Viewport | Hasil | Status |
|---|---|---|
| 360 px | scrollWidth 360, tidak ada overflow | Lulus |
| 390 px | scrollWidth 390, tidak ada overflow | Lulus |
| 768 px | scrollWidth 768, tidak ada overflow | Lulus |
| 1366 px | scrollWidth 1366, tidak ada overflow | Lulus |

## Pengujian terhadap kriteria penerimaan
| ID | Pemeriksaan | Status |
|---|---|---|
| F-01 | Empat kartu menampilkan nama, deskripsi, harga | Lulus |
| F-02 | Tiga anchor (#beranda, #katalog, #kontak) cocok dengan ID | Lulus |
| F-03 | Alamat, jam buka, telepon, email, tautan Google Maps ada | Lulus |
| NF-01 | Tidak ada scroll horizontal | Lulus (lihat tabel di atas) |
| NF-02 | Keyboard: Tab melewati tautan, fokus terlihat | BELUM |
| NF-03 | Validator HTML tanpa error | BELUM |
| NF-04 | Lighthouse Accessibility dan Best Practices >= 90 | BELUM |
| NF-05 | CSS terpisah, README ada | Lulus |
| - | Semua gambar punya teks alternatif; path aset ada | Lulus |
| - | Tampilan di Firefox | BELUM |

## Temuan dan keputusan kualitas
1. Foto asli memuat tombol panah dan garis hitam dari tangkapan layar; foto dipotong agar bersih.
2. Empat menu pada desktop ditampilkan empat kolom agar tidak ada kartu yatim; kalau untuk tablet dua kolom.
3. Tautan "Lewati ke menu" ditambahkan untuk pengguna keyboard.
