---
title: Kunci Skrin Satu Ketik
name: TapLock
tagline: Kunci telefon dengan satu ketikan. Cap jari dan wajah masih berfungsi.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Apa yang aplikasi ini boleh buat

TapLock meletakkan satu butang **Lock** yang besar pada skrin anda. Ketik butang itu dan telefon terkunci serta-merta, sama seperti menekan butang kuasa. Ia berguna apabila butang kuasa sukar dicapai, haus atau rosak.

- Dengan **Accessibility lock**, anda membuka kunci seperti biasa menggunakan cap jari, wajah, PIN atau corak.
- **Device Admin lock** ialah cara kedua untuk mengunci tanpa Accessibility.
- Satu skrin, satu butang. Tiada akaun dan tiada log masuk.
- Percuma dengan iklan.

## Mulakan

1. Buka TapLock. Pada kali pertama, baris di bawah butang **Lock** berbunyi "One-time setup needed (about a minute)."
2. Ketik **Set up TapLock**. Skrin **Lock setup** akan dibuka.
3. Pilih satu daripada dua cara mengunci:
   - **Accessibility lock** (disyorkan, Android 9 atau lebih baharu): mengunci seperti butang kuasa, dan buka kunci dengan cap jari serta wajah masih berfungsi.
   - **Device Admin lock**: berfungsi tanpa Accessibility. Android akan meminta PIN, corak atau kata laluan anda pada kali seterusnya anda membuka kunci.
4. Ikuti langkah di bawah untuk pilihan anda.

Anda boleh membuka **Lock setup** semula pada bila-bila masa melalui ikon tetapan di penjuru kanan atas skrin utama.

## Hidupkan Accessibility lock

1. Pada **Lock setup**, dalam kad **Accessibility lock**, ketik **Turn on Accessibility lock**.
2. Satu dialog bertanya **Allow TapLock to use Accessibility?** Baca bagaimana TapLock menggunakannya.
3. Ketik **Agree** untuk teruskan. Jika anda ketik **Decline**, tiada apa yang berubah dan **Accessibility lock** kekal tidak aktif.
4. Tetapan Accessibility Android akan dibuka. Cari TapLock, selalunya di bawah "Downloaded apps".
5. Hidupkan "Use TapLock", ketik **Allow**, kemudian kembali ke TapLock.
6. Kad itu kini menunjukkan **On**, dan **You're all set** muncul di bahagian atas. Ketik **Back to Lock**.

![Dialog "Allow TapLock to use Accessibility?" dengan butang Decline dan Agree](shots/04-accessibility-consent.png)

**Mengapa TapLock meminta kebenaran Accessibility.** TapLock menggunakan Accessibility Service API hanya untuk mengunci skrin apabila anda mengetik butang **Lock**, sama seperti menekan butang kuasa. Inilah sebabnya buka kunci dengan cap jari dan wajah masih berfungsi. TapLock tidak membaca skrin anda, tidak melihat apa yang anda taip, dan tidak mengumpul, menyimpan atau berkongsi sebarang data peribadi melalui kebenaran ini. Anda memilih **Agree** atau **Decline** sebelum tetapan Android dibuka, dan anda boleh mematikannya semula pada bila-bila masa.

Jika kad itu menunjukkan **Starting** lebih daripada beberapa saat, matikan TapLock dan hidupkannya semula dalam tetapan Accessibility. Jika suis dalam tetapan Android berwarna kelabu dan tidak boleh ditekan, ketik **Switch greyed out?** pada **Lock setup** dan ikuti petunjuk di situ.

## Gunakan Device Admin lock

1. Pada **Lock setup**, dalam kad **Device Admin lock**, ketik **Enable Device Admin**.
2. Android meminta anda mengesahkan. TapLock menggunakan kebenaran ini hanya untuk mengunci skrin apabila anda mengetik butang **Lock**.
3. Kad itu kini menunjukkan **On**.

![Skrin Lock setup: kad Accessibility lock menunjukkan On, dan kad Device Admin lock mempunyai butang Enable Device Admin](shots/02-setup.png)

Dengan cara mengunci ini, Android akan meminta PIN, corak atau kata laluan anda pada kali seterusnya anda membuka kunci, bukan cap jari atau wajah. Jika kedua-dua cara dihidupkan, TapLock menggunakan **Accessibility lock**.

## Kunci skrin anda

1. Buka TapLock. Baris di bawah butang bermula dengan "Ready."
2. Ketik **Lock**. Skrin terkunci serta-merta.
3. Buka kunci telefon anda seperti biasa.

![Skrin utama dengan butang Lock yang bulat dan baris "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Guna mod gelap

1. Hidupkan tema gelap dalam tetapan Android telefon anda.
2. Buka TapLock. Aplikasi ini mengikut telefon anda dan bertukar ke mod gelap dengan sendirinya. Tiada tetapan berasingan dalam aplikasi.

![Skrin utama TapLock dalam mod gelap](shots/03-dark-mode.png)

## Tukar bahasa

1. Pada skrin utama, ketik ikon tetapan untuk membuka **Lock setup**.
2. Buka pemilih bahasa.
3. Pilih satu daripada 31 bahasa, atau kekalkan lalai sistem supaya TapLock mengikut bahasa telefon anda.

![Pemilih bahasa dengan senarai bahasa](shots/06-language.png)

Bahasa Arab, Urdu dan Ibrani dipaparkan dari kanan ke kiri. Pada Android 13 atau lebih baharu, anda juga boleh menukar bahasa TapLock dalam tetapan bahasa aplikasi Android.

## Matikan cara mengunci atau nyahpasang

1. Pada skrin utama, ketik ikon tetapan untuk membuka **Lock setup**.
2. Untuk mematikan **Accessibility lock**, ketik **Manage in Accessibility settings** dan matikan TapLock di sana.
3. Untuk mematikan **Device Admin lock**, ketik **Turn off Device Admin**.
4. Matikan Device Admin sebelum anda menyahpasang TapLock. Android tidak membenarkan aplikasi dinyahpasang selagi ia masih menjadi pentadbir peranti yang aktif.

![Lock setup dengan kad "You're all set" dan butang untuk mematikan Device Admin](shots/05-device-admin-on.png)

## Soalan lazim

**Mengapa TapLock memerlukan kebenaran Accessibility?**
Hanya untuk mengunci skrin apabila anda mengetik **Lock**, sama seperti menekan butang kuasa. Ia tidak membaca skrin anda dan tidak melihat apa yang anda taip. Jika anda tidak mahu membenarkannya, gunakan **Device Admin lock**.

**Cap jari saya tidak berfungsi selepas saya mengunci dengan TapLock. Kenapa?**
Anda menggunakan **Device Admin lock**, yang menyebabkan Android meminta PIN, corak atau kata laluan anda sekali. Hidupkan **Accessibility lock** supaya buka kunci dengan cap jari dan wajah terus berfungsi.

**Saya tidak dapat menyahpasang TapLock. Apa yang boleh saya buat?**
Buka **Lock setup**, ketik **Turn off Device Admin**, kemudian nyahpasang.

**Versi Android yang manakah saya perlukan?**
**Accessibility lock** memerlukan Android 9 atau lebih baharu. Pada versi yang lebih lama, gunakan **Device Admin lock**.

**Bolehkah saya guna TapLock dalam bahasa saya sendiri?**
Boleh. TapLock tersedia dalam 31 bahasa. Pilih bahasa anda pada **Lock setup**, atau kekalkan lalai sistem.

## Privasi

TapLock menggunakan kebenaran Accessibility dan Device Admin hanya untuk mengunci skrin anda, dan tidak mengumpul data peribadi melalui kebenaran itu. Aplikasi ini memaparkan iklan daripada Google AdMob; jika diperlukan, anda boleh menukar pilihan iklan anda melalui **Privacy settings** pada **Lock setup**. Baca [dasar privasi](https://varian1.github.io/LockAppOnlyWeb/privacy.html) yang lengkap.
