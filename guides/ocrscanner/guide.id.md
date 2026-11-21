---
title: OCR Scanner: Gambar ke Teks
name: OCRScanner
tagline: Pindai dokumen jadi teks yang bisa diedit. Cari, salin, bagikan sebagai PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Fitur utama

OCRScanner memotret halaman kertas, meluruskannya, lalu membaca teksnya langsung di ponsel Anda. Anda bisa mengedit dan menyalin teks, mencari di semua hasil pindai, dan membagikan hasil pindai sebagai PDF yang bisa dicari, file teks, atau gambar.

- Pengenalan teks berjalan di perangkat Anda dan tidak butuh internet.
- Tanpa akun. Hasil pindai tetap di ponsel Anda dan tidak pernah diunggah.
- Impor PDF, atau bagikan gambar dari aplikasi lain di Android.
- Gratis dengan iklan. Pembelian Premium sekali bayar menghapus iklan dan menambah bahasa.

## Mulai menggunakan

1. Buka OCRScanner. Daftar **Scans** masih kosong saat pertama kali dibuka.
2. Ketuk **Scan** untuk memakai kamera, atau **Import** untuk memilih foto yang sudah ada.
3. Izinkan kamera saat Android meminta. Fitur impor tidak memerlukan akses ke seluruh galeri foto Anda.

![Daftar Scans dengan tombol Scan dan Import](shots/01-home.png)

## Pindai satu halaman

1. Ketuk **Scan** dan arahkan kamera ke halaman. Ketuk tombol rana untuk mengambil foto.
2. Di **Review**, tepi halaman dikenali otomatis. Seret sudut biru jika ada tepi yang meleset, atau ketuk **Full page** untuk memakai seluruh foto.
3. Pilih filter untuk membersihkan halaman: **Original**, **Magic**, **Gray**, atau **B&W**.
4. Ketuk **Rotate 90°** jika halaman miring ke samping, atau **Retake** untuk memotret ulang.
5. Ketuk **Recognize text**.

![Layar Review dengan sudut halaman, filter, dan tombol Recognize text](shots/02-review.png)

Untuk memindai beberapa halaman menjadi satu dokumen, buka hasil pindai nanti, ketuk **⋯**, lalu pilih **Add pages**.

## Impor PDF

OCRScanner membaca hingga 20 halaman dari satu PDF, atau 50 halaman dengan Premium. Setiap halaman dibaca sebagai gambar, jadi teks yang sudah ada di dalam PDF tidak dipakai.

1. Pilih satu PDF di pemilih file ponsel Anda. Izin penyimpanan tidak diperlukan.
2. Di **Review**, periksa halamannya. Jika PDF melebihi batas, Review memberi tahu berapa halaman yang tidak disertakan.
3. Ketuk **Recognize text**.

## Bagikan gambar dari aplikasi lain

Fitur ini tersedia di Android.

1. Di galeri atau aplikasi lain, pilih hingga 20 gambar lalu ketuk bagikan.
2. Pilih OCRScanner.
3. Buka kunci aplikasi jika **App lock** aktif. Gambar terbuka di **Review** sebagai hasil pindai baru.

Jika ada halaman yang belum disimpan, aplikasi akan bertanya dulu sebelum menggantinya.

## Baca, edit, dan salin teks

1. Setelah pengenalan selesai, **Result** menampilkan halaman di atas dan teksnya di bawah.
2. Ketuk satu baris teks untuk melihat posisinya di halaman. Ketuk satu kata di halaman untuk langsung ke barisnya.
3. Baris yang diragukan aplikasi ditandai, jadi Anda tahu bagian mana yang perlu dicek.
4. Ketuk **Edit** untuk memperbaiki teks, **Copy** untuk menyalinnya, atau **Share** untuk mengirimnya.
5. Ketuk **Save** untuk menyimpan hasil pindai di daftar Anda.

![Layar Result: halaman di atas, teks hasil pengenalan di bawah, dengan Edit, Copy, Share, dan Save](shots/03-result.png)

## Cari hasil pindai lewat teksnya

1. Di **Scans**, ketuk **Search text in your scans**.
2. Ketik sebuah kata. Semua hasil pindai yang memuatnya akan ditampilkan, dengan kata yang cocok dicetak tebal.
3. Ketuk satu hasil untuk membuka hasil pindai tepat di bagian yang cocok.

![Mencari kata "lighting" menemukan hasil pindai yang memuatnya](shots/04-search.png)

Untuk melihat hanya hasil pindai dengan satu tag, ketuk tag itu di bawah kolom pencarian. Pencarian lalu hanya mencari di dalam hasil pindai tersebut. Ketuk tag itu lagi untuk melihat semua hasil pindai.

## Bagikan atau ekspor

1. Buka hasil pindai dan ketuk tombol bagikan.
2. Pilih format:
   - **PDF**: gambar halaman dengan teks yang bisa dicari di baliknya.
   - **Text file**: teks biasa (.txt).
   - **Page image**: simpan ke Foto atau kirim.
3. Pilih aplikasi tujuan pengiriman.

![Lembar bagikan atau ekspor dengan PDF, Text file, dan Page image](shots/05-share.png)

## Ganti nama, beri tag, dan hapus

1. Buka hasil pindai dan ketuk **⋯**.
2. Pilih **Rename** untuk mengubah judul, atau **Edit tags** untuk menambah tag yang dipisahkan koma.
3. Pilih **Recognize text again** untuk membaca ulang halaman dalam bahasa teks lain. Teks yang sudah Anda edit akan diganti.
4. Pilih **Delete scan** untuk menghapusnya dari ponsel Anda.

## Cadangkan dan pulihkan hasil pindai

1. Di **Scans**, ketuk ikon pengaturan di pojok kanan atas.
2. Di bagian **Storage**, ketuk **Back up scans**. Semua hasil pindai Anda dikemas dalam satu file.
3. Pilih tempat menyimpan atau mengirim file. File ini tidak dienkripsi, jadi simpan di tempat yang aman.
4. Di ponsel baru, ketuk **Restore from backup** lalu pilih file tersebut. Aplikasi akan bertanya dulu sebelum mengganti semua hasil pindai di ponsel dengan yang ada di cadangan.

## Kunci aplikasi dan ubah pengaturan

1. Di **Scans**, ketuk ikon pengaturan di pojok kanan atas.
2. Aktifkan **App lock** agar sidik jari, wajah, atau kunci layar diminta sebelum hasil pindai terbuka.
3. Di **Text language (OCR)**, pilih aksara dokumen Anda. **Latin** mencakup bahasa Inggris, Spanyol, Prancis, Jerman, Indonesia, dan lainnya. Aplikasi menyarankan pilihan yang sesuai dengan bahasa ponsel Anda.
4. Ketuk **App language** untuk memakai aplikasi dalam bahasa yang berbeda dari bahasa ponsel Anda.
5. Pilih **Image quality** (Balanced atau Full) dan **Theme** (System, Light, atau Dark).

![Pengaturan: Premium, App lock, Text language (OCR), dan Image quality](shots/06-settings.png)

## Premium

Premium adalah sekali bayar, bukan langganan. Buka **Settings** dan ketuk **See Premium**. Premium memberi Anda:

- Tanpa iklan.
- Teks Mandarin, Jepang, dan Korea, serta Hindi dan teks Devanagari lainnya di Android.
- Menggabungkan beberapa hasil pindai menjadi satu PDF atau file teks.
- Impor PDF yang lebih panjang: hingga 50 halaman, bukan 20.

Jika Anda pernah membeli Premium, ketuk **Restore purchase** di layar Premium.

## Pertanyaan umum

**Apakah bisa dipakai tanpa internet?**
Bisa. Pemindaian, pengenalan teks, pencarian, dan ekspor semuanya berjalan di ponsel Anda.

**Di mana hasil pindai saya disimpan?**
Hanya di perangkat Anda. Jika aplikasi dihapus, hasil pindai ikut terhapus, jadi ketuk **Back up scans** di Settings terlebih dahulu untuk menyimpannya.

**Teksnya banyak yang salah. Apa yang bisa saya lakukan?**
Foto ulang di tempat yang terang dengan halaman terletak rata, coba filter **Magic** atau **B&W**, dan pastikan **Text language (OCR)** sesuai dengan dokumen. Anda juga bisa memperbaiki kata satu per satu dengan **Edit**.

**Apakah bisa membaca tulisan tangan?**
Aplikasi ini dibuat untuk teks cetak. Tulisan tangan sering terbaca salah.

## Privasi

Dokumen Anda tidak pernah diunggah. Versi gratis menampilkan iklan dari Google AdMob. Baca selengkapnya di [kebijakan privasi](https://varian1.github.io/ocrscanner/privacy.html).
