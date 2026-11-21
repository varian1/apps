---
title: Penghitung Kata: Text Toolkit
name: Text Toolkit
tagline: Hitung kata, ubah huruf, rapikan, urutkan, dan bandingkan teks tanpa internet.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Fungsi aplikasi

Text Toolkit adalah satu layar dengan sembilan alat teks. Ketik atau tempel teks di kotak paling atas, pilih alat, lalu salin atau bagikan hasilnya. Aplikasi ini bisa menghitung kata, mengubah huruf besar dan kecil, merapikan spasi, mengurutkan baris, mencari dan mengganti, membalik, melakukan encode, memformat JSON, dan membandingkan dua teks.

- Semua alat berjalan di perangkat Anda dan bisa dipakai tanpa internet.
- Tanpa akun. Teks Anda tidak pernah diunggah, dan aplikasi tidak memakai kamera, foto, kontak, atau lokasi Anda.
- Teks Anda tidak disimpan. Teks hilang saat aplikasi ditutup.
- Gratis. Iklan banner mungkin tampil di bagian bawah layar.

## Mulai memakai

1. Buka Text Toolkit. Kotak **YOUR TEXT** berisi contoh teks singkat agar Anda bisa mencoba setiap alat.
2. Ketuk **Clear** lalu ketik teks Anda sendiri, atau ketuk **Paste** untuk mengganti teks dengan yang Anda salin dari aplikasi lain. **Sample** mengembalikan contoh teks.
3. Pilih alat di baris bawah kotak: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format**, atau **Diff**. Geser baris ke samping untuk melihat semuanya.

![Layar utama: kotak YOUR TEXT dengan Paste, Sample, dan Clear, baris alat, dan angka Counter](shots/01-home.png)

Aplikasi mengikuti bahasa ponsel Anda. Tersedia dalam 11 bahasa: Inggris, Spanyol, Portugis, Jerman, Prancis, Hindi, Indonesia, Arab, Italia, Rusia, dan Turki.

## Hitung kata dan karakter

1. Ketuk **Counter**.
2. Baca angkanya: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines**, dan **Reading time**.
3. Lihat **TOP WORDS** di bawahnya untuk mengetahui kata yang paling sering Anda pakai, hingga delapan kata, masing-masing dengan jumlahnya.

Angka berubah saat Anda mengetik. Waktu baca dihitung dari 200 kata per menit.

## Ubah huruf besar dan kecil

1. Ketuk **Case**.
2. Gulir kartunya. Setiap kartu menampilkan teks Anda dalam gaya lain: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE**, dan **URL slug**.
3. Ketuk **Copy** pada kartu yang Anda inginkan.

![Alat Case: kartu UPPERCASE, lowercase, dan Title Case, masing-masing dengan Use input, Share, dan Copy](shots/02-case.png)

## Rapikan teks

1. Ketuk **Clean**.
2. Ketuk salah satu aksi:
   - **Clean all**: menghapus tab, spasi ganda, spasi di ujung baris, baris kosong, dan baris berulang sekaligus.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates**, atau **Remove tabs**: hanya melakukan satu hal itu.
   - Aksi pemisah baris: menghapus pemisah baris dari teks Anda.
3. Lihat hasilnya di bawah **CLEANED RESULT**. Teks asli di kotak tetap seperti semula.

![Alat Clean: tombol pembersih dan kartu CLEANED RESULT](shots/03-clean.png)

## Urutkan atau balik

1. Ketuk **Lines** untuk mengolah baris utuh: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates**, atau **Reverse characters**. Pengurutan mengabaikan huruf kapital dan spasi di awal baris.
2. Ketuk **Reverse** untuk membalik teks: **Entire text**, **Each word**, **Word order**, **Line order**, atau **Characters per line**.
3. Hasilnya tampil di kartu di bawah tombol.

## Cari dan ganti

1. Ketuk **Replace**.
2. Ketik teks yang dicari di **Find** dan teks penggantinya di **Replace with**.
3. Ketuk opsi untuk menyalakan atau mematikannya: **Replace all** (jika mati, hanya kecocokan pertama yang diganti), **Case sensitive**, dan **Whole word**.
4. Periksa jumlah penggantian dan **REPLACEMENT PREVIEW**. Keduanya diperbarui saat Anda mengetik.

![Alat Replace: kolom Find dan Replace with, tiga tombol opsi, jumlah penggantian, dan pratinjau](shots/04-replace.png)

Pencarian mencari persis apa yang Anda ketik. Pencarian tidak memakai pola atau karakter pengganti (wildcard).

## Encode, decode, dan format

1. Ketuk **Encode**, pilih **URL**, **Base64**, atau **HTML Entities**, lalu ketuk **Encode** atau **Decode**.
2. Ketuk **Format** dan pilih **Format JSON** untuk menjorokkan JSON dengan dua spasi, **Minify JSON** untuk menjadikannya satu baris, atau **Strip Markdown** untuk mengubah Markdown menjadi teks biasa.
3. Jika JSON memiliki kesalahan, satu baris di dekat bagian atas layar diawali "Invalid JSON" dan menjelaskan apa yang salah.

## Bandingkan dua teks

1. Taruh versi pertama di **YOUR TEXT** lalu ketuk **Diff**.
2. Ketik atau tempel versi kedua ke **COMPARE WITH**.
3. Baca **DIFF COMPARISON**. Baris yang hanya ada di versi kedua berwarna hijau dengan tanda **+**. Baris yang hanya ada di versi pertama berwarna merah dengan tanda **-**. Baris yang sama tidak diberi tanda.
4. Ketuk **Copy Diff** untuk menyalin perbandingan beserta tanda + dan -.

![Alat Diff: kotak COMPARE WITH dan kartu DIFF COMPARISON dengan satu baris hijau yang ditambahkan dan satu baris merah yang dihapus](shots/05-diff.png)

## Salin, bagikan, atau lanjutkan bekerja

1. Ketuk **Copy** pada kartu hasil untuk menaruhnya di clipboard.
2. Ketuk **Share** untuk mengirimnya ke aplikasi lain.
3. Ketuk **Use input** untuk memindahkan hasil ke **YOUR TEXT**, sehingga Anda bisa menjalankan alat lain padanya.

## Premium

Semua alat gratis. Satu pembelian opsional sekali bayar akan menghapus iklan. Anda membayar sekali saja; ini bukan langganan.

## Pertanyaan

**Apakah bisa dipakai tanpa internet?**
Bisa. Kesembilan alat berjalan di ponsel Anda. Hanya iklan dan pembelian untuk menghapusnya yang memakai koneksi internet.

**Apakah teks saya disimpan?**
Tidak. Aplikasi menyimpan teks Anda hanya selama aplikasi terbuka. Salin atau bagikan hasil yang ingin Anda simpan.

**Mengapa hasilnya kosong setelah saya berpindah alat?**
Clean, Lines, Reverse, Encode, dan Format memakai satu kartu hasil yang sama, dan kartu itu dikosongkan saat Anda berganti alat. Ketuk aksinya lagi. Lakukan hal yang sama setelah Anda mengubah teks. Counter, Case, Replace, dan Diff diperbarui otomatis.

**Apakah mengikuti mode gelap?**
Ya. Aplikasi memakai tema terang atau gelap sesuai pengaturan ponsel Anda.

**Di mana lisensinya?**
Gulir ke bagian bawah dan ketuk **Open-source licenses**. **Privacy policy** ada di sebelahnya.

## Privasi

Teks Anda diproses di ponsel dan tidak pernah diunggah atau disimpan. Aplikasi mungkin menampilkan iklan dari Google AdMob; jika hukum mewajibkan, Anda akan ditanya pilihan Anda lebih dulu dan dapat mengubahnya lewat **Ad privacy choices** di layar utama. Baca [kebijakan privasi](https://varian1.github.io/text-toolkit/privacy.html) selengkapnya.
