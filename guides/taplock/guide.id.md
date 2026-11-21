---
title: Kunci Layar HP Satu Ketuk
name: TapLock
tagline: Kunci HP dengan satu ketukan. Buka dengan sidik jari dan wajah tetap bisa.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Fungsi aplikasi

TapLock menaruh satu tombol **Lock** besar di layar. Ketuk tombol itu dan HP langsung terkunci, sama seperti menekan tombol daya. Cocok kalau tombol daya sulit dijangkau, aus, atau rusak.

- Dengan Accessibility lock, Anda membuka kunci seperti biasa memakai sidik jari, wajah, PIN, atau pola.
- Device Admin lock adalah cara kedua untuk mengunci tanpa Accessibility.
- Satu layar, satu tombol. Tanpa akun dan tanpa login.
- Gratis dengan iklan.

## Mulai memakai

1. Buka TapLock. Saat pertama kali, tulisan di bawah tombol **Lock** berbunyi "One-time setup needed (about a minute)."
2. Ketuk **Set up TapLock**. Layar **Lock setup** terbuka.
3. Pilih salah satu dari dua cara mengunci:
   - **Accessibility lock** (disarankan, Android 9 atau lebih baru): mengunci seperti tombol daya, dan buka kunci dengan sidik jari serta wajah tetap berfungsi.
   - **Device Admin lock**: berfungsi tanpa Accessibility. Android akan meminta PIN, pola, atau kata sandi Anda saat berikutnya Anda membuka kunci.
4. Ikuti langkah di bawah sesuai pilihan Anda.

Anda bisa membuka **Lock setup** lagi kapan saja lewat ikon pengaturan di kanan atas layar utama.

## Mengaktifkan Accessibility lock

1. Di **Lock setup**, pada kartu **Accessibility lock**, ketuk **Turn on Accessibility lock**.
2. Sebuah dialog menanyakan **Allow TapLock to use Accessibility?** Baca bagaimana TapLock menggunakannya.
3. Ketuk **Agree** untuk melanjutkan. Jika Anda mengetuk **Decline**, tidak ada yang berubah dan Accessibility lock tetap mati.
4. Pengaturan Aksesibilitas Android terbuka. Cari TapLock, biasanya di bawah "Downloaded apps".
5. Aktifkan "Use TapLock", ketuk **Allow**, lalu kembali ke TapLock.
6. Kartu kini menampilkan **On**, dan **You're all set** muncul di bagian atas. Ketuk **Back to Lock**.

![Dialog "Allow TapLock to use Accessibility?" dengan tombol Decline dan Agree](shots/04-accessibility-consent.png)

**Mengapa TapLock meminta izin Accessibility.** TapLock memakai Accessibility Service API hanya untuk mengunci layar saat Anda mengetuk tombol **Lock**, sama seperti menekan tombol daya. Karena itu buka kunci dengan sidik jari dan wajah tetap berfungsi. TapLock tidak membaca layar Anda, tidak melihat apa yang Anda ketik, dan tidak mengumpulkan, menyimpan, atau membagikan data pribadi lewat izin ini. Anda memilih **Agree** atau **Decline** sebelum pengaturan Android terbuka, dan Anda bisa mematikannya lagi kapan saja.

Jika kartu menampilkan **Starting** lebih dari beberapa detik, matikan TapLock lalu nyalakan lagi di pengaturan Aksesibilitas. Jika sakelar di pengaturan Android berwarna abu-abu dan tidak bisa dipakai, ketuk **Switch greyed out?** di **Lock setup** dan ikuti petunjuknya.

## Memakai Device Admin lock

1. Di **Lock setup**, pada kartu **Device Admin lock**, ketuk **Enable Device Admin**.
2. Android meminta Anda mengonfirmasi. TapLock memakai izin ini hanya untuk mengunci layar saat Anda mengetuk tombol **Lock**.
3. Kartu kini menampilkan **On**.

![Layar Lock setup: kartu Accessibility lock menampilkan On, dan kartu Device Admin lock memiliki tombol Enable Device Admin](shots/02-setup.png)

Dengan cara mengunci ini, Android meminta PIN, pola, atau kata sandi Anda saat berikutnya Anda membuka kunci, bukan sidik jari atau wajah. Jika kedua cara aktif, TapLock memakai Accessibility lock.

## Mengunci layar

1. Buka TapLock. Tulisan di bawah tombol diawali "Ready."
2. Ketuk **Lock**. Layar langsung terkunci.
3. Buka kunci HP seperti biasa.

![Layar utama dengan tombol Lock bulat dan tulisan "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Memakai mode gelap

1. Aktifkan tema gelap di pengaturan Android pada HP Anda.
2. Buka TapLock. Aplikasi mengikuti HP Anda dan beralih ke tampilan gelap dengan sendirinya. Tidak ada pengaturan terpisah di dalam aplikasi.

![Layar utama TapLock dalam mode gelap](shots/03-dark-mode.png)

## Mengganti bahasa

1. Di layar utama, ketuk ikon pengaturan untuk membuka **Lock setup**.
2. Buka pemilih bahasa.
3. Pilih salah satu dari 31 bahasa, atau biarkan bawaan sistem agar TapLock mengikuti bahasa HP Anda.

![Pemilih bahasa dengan daftar bahasa](shots/06-language.png)

Bahasa Arab, Urdu, dan Ibrani ditampilkan dari kanan ke kiri. Di Android 13 atau lebih baru, Anda juga bisa mengganti bahasa TapLock di pengaturan bahasa aplikasi Android.

## Mematikan metode kunci atau menghapus aplikasi

1. Di layar utama, ketuk ikon pengaturan untuk membuka **Lock setup**.
2. Untuk mematikan Accessibility lock, ketuk **Manage in Accessibility settings** dan matikan TapLock di sana.
3. Untuk mematikan Device Admin lock, ketuk **Turn off Device Admin**.
4. Matikan Device Admin sebelum Anda menghapus TapLock. Android tidak mengizinkan penghapusan aplikasi yang masih menjadi admin perangkat aktif.

![Lock setup dengan kartu "You're all set" dan tombol untuk mematikan Device Admin](shots/05-device-admin-on.png)

## Pertanyaan

**Mengapa TapLock butuh izin Accessibility?**
Hanya untuk mengunci layar saat Anda mengetuk **Lock**, sama seperti menekan tombol daya. TapLock tidak membaca layar atau melihat apa yang Anda ketik. Jika Anda tidak ingin mengizinkannya, pakai Device Admin lock.

**Sidik jari saya tidak berfungsi setelah mengunci dengan TapLock. Kenapa?**
Anda memakai Device Admin lock, yang membuat Android meminta PIN, pola, atau kata sandi satu kali. Aktifkan Accessibility lock agar buka kunci dengan sidik jari dan wajah tetap berfungsi.

**Saya tidak bisa menghapus TapLock. Apa yang bisa saya lakukan?**
Buka **Lock setup**, ketuk **Turn off Device Admin**, lalu hapus aplikasinya.

**Saya butuh Android versi berapa?**
Accessibility lock membutuhkan Android 9 atau lebih baru. Di versi yang lebih lama, pakai Device Admin lock.

**Bisakah saya memakai TapLock dalam bahasa saya sendiri?**
Bisa. TapLock tersedia dalam 31 bahasa. Pilih bahasa Anda di **Lock setup**, atau biarkan bawaan sistem.

## Privasi

TapLock memakai izin Accessibility dan Device Admin hanya untuk mengunci layar Anda, dan tidak mengumpulkan data pribadi lewat izin tersebut. Aplikasi menampilkan iklan dari Google AdMob; jika diwajibkan, Anda bisa mengubah pilihan iklan lewat **Privacy settings** di **Lock setup**. Baca [kebijakan privasi](https://varian1.github.io/LockAppOnlyWeb/privacy.html) selengkapnya.
