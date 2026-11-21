---
title: Pengimbas OCR: Gambar ke Teks
name: OCRScanner
tagline: Imbas dokumen jadi teks boleh edit di telefon. Cari, salin, kongsi sebagai PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Fungsi apl ini

OCRScanner menggambar halaman kertas, meluruskannya dan membaca teksnya terus di telefon anda. Anda boleh mengedit dan menyalin teks itu, mencari dalam semua imbasan anda, dan berkongsi imbasan sebagai PDF yang boleh dicari, fail teks atau imej.

- Pengecaman teks berjalan pada peranti anda dan berfungsi tanpa internet.
- Tanpa akaun. Imbasan anda kekal di telefon dan tidak pernah dimuat naik.
- Import PDF, atau kongsi imej dari apl lain pada Android.
- Percuma dengan iklan. Pembelian Premium sekali bayar membuang iklan dan menambah lebih banyak bahasa.

## Mulakan

1. Buka OCRScanner. Senarai **Scans** kosong pada kali pertama.
2. Ketik **Scan** untuk menggunakan kamera, atau **Import** untuk memilih foto yang sudah ada.
3. Benarkan kamera apabila Android bertanya. Import tidak memerlukan akses kepada seluruh pustaka foto anda.

![Senarai Scans dengan butang Scan dan Import](shots/01-home.png)

## Imbas satu halaman

1. Ketik **Scan** dan halakan kamera ke arah halaman. Ketik butang pengatup untuk mengambil foto.
2. Pada **Review**, tepi halaman dikesan untuk anda. Seret sudut biru jika sesuatu tepi tersasar, atau ketik **Full page** untuk mengekalkan keseluruhan foto.
3. Pilih penapis untuk membersihkan halaman: **Original**, **Magic**, **Gray** atau **B&W**.
4. Ketik **Rotate 90°** jika halaman terbalik ke tepi, atau **Retake** untuk mengambil fotonya semula.
5. Ketik **Recognize text**.

![Skrin Review dengan sudut halaman, penapis dan butang Recognize text](shots/02-review.png)

Untuk mengimbas beberapa halaman ke dalam satu dokumen, buka imbasan itu kemudian, ketik **⋯** dan pilih **Add pages**.

## Import PDF

OCRScanner membaca sehingga 20 halaman daripada satu PDF, atau 50 halaman dengan Premium. Setiap halaman dibaca sebagai imej, jadi teks yang sudah ada dalam PDF tidak digunakan.

1. Pilih satu PDF dalam pemilih fail telefon anda. Tiada kebenaran storan diperlukan.
2. Pada **Review**, semak halaman-halaman itu. Jika PDF melebihi had, Review akan memberitahu anda berapa halaman yang ditinggalkan.
3. Ketik **Recognize text**.

## Kongsi imej dari apl lain

Ini berfungsi pada Android.

1. Dalam galeri anda atau apl lain, pilih sehingga 20 imej dan ketik kongsi.
2. Pilih OCRScanner.
3. Buka kunci apl jika **App lock** dihidupkan. Imej dibuka pada **Review** sebagai imbasan baharu.

Jika anda mempunyai halaman yang belum disimpan, apl akan bertanya dahulu sebelum menggantikannya.

## Baca, edit dan salin teks

1. Selepas pengecaman, **Result** menunjukkan halaman di atas dan teksnya di bawah.
2. Ketik satu baris teks untuk melihat kedudukannya pada halaman. Ketik satu perkataan pada halaman untuk melompat ke barisnya.
3. Baris yang apl kurang pasti diserlahkan, supaya anda tahu apa yang perlu disemak.
4. Ketik **Edit** untuk membetulkan teks, **Copy** untuk menyalinnya, atau **Share** untuk menghantarnya.
5. Ketik **Save** untuk menyimpan imbasan dalam senarai anda.

![Skrin Result: halaman di atas, teks yang dikenali di bawah, dengan Edit, Copy, Share dan Save](shots/03-result.png)

## Cari imbasan melalui teksnya

1. Pada **Scans**, ketik **Search text in your scans**.
2. Taip satu perkataan. Setiap imbasan yang mengandunginya disenaraikan, dengan padanan ditebalkan.
3. Ketik satu hasil untuk membuka imbasan pada padanan itu.

![Mencari perkataan "lighting" menemui imbasan yang mengandunginya](shots/04-search.png)

Untuk melihat hanya imbasan dengan satu tag, ketik tag itu di bawah ruang carian. Carian kemudian hanya melihat dalam imbasan tersebut. Ketik tag itu sekali lagi untuk melihat semua imbasan.

## Kongsi atau eksport

1. Buka satu imbasan dan ketik butang kongsi.
2. Pilih format:
   - **PDF**: imej halaman dengan teks yang boleh dicari di belakangnya.
   - **Text file**: teks biasa (.txt).
   - **Page image**: simpan ke Photos atau hantar.
3. Pilih apl untuk menghantarnya.

![Helaian kongsi atau eksport dengan PDF, Text file dan Page image](shots/05-share.png)

## Namakan semula, letak tag dan padam

1. Buka satu imbasan dan ketik **⋯**.
2. Pilih **Rename** untuk menukar tajuk, atau **Edit tags** untuk menambah tag yang dipisahkan dengan koma.
3. Pilih **Recognize text again** untuk membaca semula halaman dalam bahasa teks yang lain. Teks yang telah anda edit akan diganti.
4. Pilih **Delete scan** untuk membuangnya daripada telefon anda.

## Sandar dan pulihkan imbasan anda

1. Pada **Scans**, ketik ikon tetapan di bahagian kanan atas.
2. Di bawah **Storage**, ketik **Back up scans**. Semua imbasan anda dibungkus ke dalam satu fail.
3. Pilih tempat untuk menyimpan atau menghantar fail itu. Fail ini tidak disulitkan, jadi simpan di tempat yang selamat.
4. Pada telefon baharu, ketik **Restore from backup** dan pilih fail itu. Apl akan bertanya dahulu sebelum menggantikan semua imbasan di telefon dengan imbasan dalam sandaran.

## Kunci apl dan tukar tetapan

1. Pada **Scans**, ketik ikon tetapan di bahagian kanan atas.
2. Hidupkan **App lock** untuk memerlukan cap jari, wajah atau kunci skrin anda sebelum imbasan dibuka.
3. Di bawah **Text language (OCR)**, pilih skrip dokumen anda. **Latin** meliputi bahasa Inggeris, Sepanyol, Perancis, Jerman, Indonesia dan banyak lagi. Apl mencadangkan skrip yang digunakan oleh bahasa telefon anda.
4. Ketik **App language** untuk menggunakan apl dalam bahasa yang berbeza daripada telefon anda.
5. Pilih **Image quality** (Balanced atau Full) dan **Theme** (System, Light atau Dark).

![Tetapan: Premium, App lock, Text language (OCR) dan Image quality](shots/06-settings.png)

## Premium

Premium ialah satu bayaran sekali sahaja, bukan langganan. Buka **Settings** dan ketik **See Premium**. Ia memberi anda:

- Tanpa iklan.
- Teks Cina, Jepun dan Korea, serta teks Hindi dan Devanagari lain pada Android.
- Menggabungkan beberapa imbasan ke dalam satu PDF atau fail teks.
- Import PDF yang lebih panjang: sehingga 50 halaman, bukan 20.

Jika anda pernah membeli Premium, ketik **Restore purchase** pada skrin Premium.

## Soalan lazim

**Adakah ia berfungsi tanpa internet?**
Ya. Pengimbasan, pengecaman teks, carian dan eksport semuanya berjalan pada telefon anda.

**Di mana imbasan saya disimpan?**
Hanya pada peranti anda. Jika anda menyahpasang apl, imbasan turut terbuang, jadi ketik **Back up scans** dalam Settings dahulu untuk menyimpannya.

**Teks ada kesilapan. Apa yang boleh saya buat?**
Ambil semula foto dalam cahaya yang baik dengan halaman diletakkan rata, cuba penapis **Magic** atau **B&W**, dan semak bahawa **Text language (OCR)** sepadan dengan dokumen. Anda juga boleh membetulkan perkataan tertentu dengan **Edit**.

**Bolehkah ia membaca tulisan tangan?**
Ia dibuat untuk teks bercetak. Tulisan tangan sering dibaca dengan salah.

## Privasi

Dokumen anda tidak pernah dimuat naik. Versi percuma memaparkan iklan daripada Google AdMob. Baca [dasar privasi](https://varian1.github.io/ocrscanner/privacy.html) yang penuh.
