# Generator Formulir SKEM PENS

Aplikasi web satu file (HTML) untuk menyusun dan mengunduh formulir SKEM (Surat Keterangan Kegiatan Mahasiswa) dalam format A4 siap cetak atau PDF, dengan tampilan bertema navy dan kuning sesuai identitas PENS.

## Pembuat

| Keterangan | Data |
|---|---|
| Nama | Febrian Catur Wahyu Fibisono |
| NRP | 3125600035 |
| Program Studi | S.Tr. Teknik Informatika |
| Departemen | Departemen Teknik Informatika dan Komputer |
| Kota | Surabaya |

## Fitur

- **Isian terstruktur** dalam beberapa bagian: identitas mahasiswa, kegiatan, dan dokumen pendukung.
- **Pratinjau langsung** dalam format A4. Pratinjau diperbarui saat isian berubah.
- **Unduh PDF** dengan resolusi tinggi, dibuat langsung di browser tanpa server.
- **Lampiran gambar** yang diperkecil otomatis agar ringan.
- **Penyimpanan otomatis** di browser (localStorage), sehingga isian tidak hilang saat halaman ditutup.
- **Ringan di HP**: tanpa efek blur dan tanpa animasi latar yang berjalan terus-menerus.

## Cara Menggunakan

1. Buka file `skem-tema-navi-kuning.html` di browser (disarankan Chrome, Edge, atau Safari versi terbaru).
2. Isi setiap bagian formulir. Data default sudah terisi sesuai pembuat.
3. Periksa hasil pada bagian pratinjau.
4. Tekan tombol **unduh PDF** atau cetak dari browser.

Catatan: data disimpan hanya di browser perangkat yang digunakan. Gunakan tombol reset untuk menghapus isian.

## Teknologi

- HTML, CSS, dan JavaScript murni, dalam satu file.
- Font: Plus Jakarta Sans (Google Fonts).
- Pustaka PDF: html2canvas 1.4.1 dan jsPDF 2.5.1 (dimuat dari CDN, dengan `defer`).

## Riwayat Versi

| Versi | Keterangan |
|---|---|
| `skem-generator-glass.html` | Versi awal dengan tampilan kaca (glassmorphism). |
| `skem-generator-glass-ringan.html` | Optimasi performa untuk HP. |
| `skem-generator-glass-ringan-v2.html` | Header kaca transparan. |
| `skem-tema-navi-kuning.html` | Tema navy-kuning, versi paling ringan. Direkomendasikan. |

## Catatan Pengembangan

- Koneksi internet diperlukan untuk memuat font dan pustaka PDF pada pertama kali dibuka.
- Pratinjau dan unduhan PDF sudah diuji secara logika, tetapi perlu dicek ulang di perangkat nyata, terutama HP.
