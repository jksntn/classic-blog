---
title: Cara Transfer eBook DRM
date: 2020-03-20
author: jksntn
description: Bagaimana cara saya transfer eBook ber drm ke eBook Reader lain
slug: cara-transfer-ebook-drm
categories:
  - buku
tags: 
  - ebook
  - ebook reader
  - tips
---
Karena saya termasuk warga negara yang baik, maka saya sangat menghindari namanya pembajakan buku. Namun alasan saya tidak membajak buku tersebut sebenarnya bukan karena rasa kemanusiaan sih, tapi karena engga nemu aja bajakannya 🙈.

Nah, di tulisan saya kali ini, saya mau menceritakan bagaimana saya memindahkan buku-buku DRM habis beli di [Google Play Books](https://play.google.com/store/books) atau Store Online lain seperti [Kobo.com](https://kobo.com), ke eBook reader seperti aplikasi di Android, Kobo eReader, Kindle eReader, dll.

<!--more-->

Mengapa harus dipindahin sih? Karena saya mungkin tidak membeli eBook hanya di satu Store saja. Juga karena aplikasi reader bawaan store seperti Kobo Store atau Google Play Books di Android punya plus minus. Jadi mending saya satukan di satu tempat saja. Dalam hal ini saya menggunakan [PocketBook Reader](https://play.google.com/store/apps/details?id=com.obreey.reader) (Android), karena ringan, gratis, dan bisa membuka file DRM. Tapi kamu harus AUTHORIZE menggunakan [Adobe ID](https://helpx.adobe.com/manage-account/using/create-update-adobe-id.html) dulu biar bisa dibaca di ebook reader tersebut! Caranya penggunaan Adobe ID ini akan saya jelaskan di bawah.

Cara download ebook kamu dari Store seperti Kobo dan Google Play Books sangatlah mudah. Kamu tinggal masuk ke dalam Library kamu di web, dan kemudian download bukunya. Tapi engga bisa langsung dibaca begitu saja, karena harus didownload dulu menggunakan [Adobe Digital Editions](https://www.adobe.com/solutions/ebook/digital-editions/download.html). (Tenang saja, adobe digital editions ini gratis kok).

{{< figure src="drm-ke-ebook-001.jpg" caption="Download file .acsm di Kobo" >}}

Buka Kobo, pilih my books. Pada halaman ini, Pilih Download ebook yang mau didownload. Nanti bakal ada file .acsm, filenya kecil sekitar 2kb. File tersebut hanya link saja. Nanti bukunya akan didownload menggunakan Adobe Digital Editions.

{{< figure src="drm-ke-ebook-002.jpg" caption="Download file .acsm di Google Play" >}}

Untuk di Google Play Books juga sama, masuk ke My Books, kemudian pilih Download EPUB. nanti akan kedownload file .acsm nya. Dibuka menggunakan Adobe Digital Editions.

{{< figure src="drm-ke-ebook-003.jpg" caption="Adobe Digital Editions ini Gratis lho ya." >}}

Hal yang terpenting sebelum kamu memasukkan file .acsm tadi ke Adobe Digital Editions adalah, kamu musti AUTHORIZE Adobe Digital Editionsnya menggunakan Adobe ID. Adobe ID ini buatnya gratis kok. Bikinnya tinggal masuk ke adobe.com.  

{{< notice warning >}}
Hal yang yang harus diingat adalah, kamu harus menggunakan Adobe ID yang sama yang kamu buka di PC dengan di eBook, sehingga, bukunya bisa dibaca di eBook Reader kamu. Kalo engga, bukunya bakal engga bisa dibaca, karena buku ber DRM tersebut hanya bisa digunakan di satu Adobe ID yang sama!
{{< /notice >}}

Saya pernah melakukan kesalahan ini ketika pembelian buku di Google Play Books saya masukkan ke Adobe Digital Editions tanpa ter-AUTHORIZE ke Adobe ID. sehingga ketika dibuka di ebook reader ga bakal bisa kebaca. (Kecuali DRM-nya kamu hapus, dan ini bukan rekomendasi saya untuk menghapus DRM-nya). 

Pada tahapan ini, sebenarnya tinggal copas file saja (untuk eBook Reader Android). 

{{< figure src="drm-ke-ebook-004.jpg" caption="Supaya tau lokasi file .epub nya." >}}

Setelah itu tinggal copas saja ke storage Smartphone Android kamu.

Nah, untuk eBook Reader yang saya gunakan adalah [PocketBook Reader](https://play.google.com/store/apps/details?id=com.obreey.reader). Karena bisa buka adobe ID di eBook reader ini.

{{< figure src="drm-ke-ebook-005.jpg" caption="Tampilan PocketBook Reader" >}}

Setelah menginstall PocketBook reader, hal yang harus dilakukan adalah AUTHORIZE Adobe ID kamu. Baru setelah itu scan tempat kamu copas file .epub tadi. Maka ebooknya bisa dibaca di eBook Reader tadi.

Penting untuk diingat, Adobe ID ini harus sama antara yang di eBook reader dan PC kamu membuka Adobe Digital Editions tadi. Kalau lupa, kamu tinggal reset password saja. 

## Troubleshoot

Kalau kamu tak sengaja memasukkan file .acsm ke dalam Adobe Digital Editions tanpa authorizarion ke Adobe ID, dan akhirnya ketika kamu baru inget untuk memasukkan Adobe ID kamu tersebut, dan mendapati error: 

`E_GOOGLE_DEVICE_LIMIT_REACHED`

atau 

`E_LIC_ALREADY_FULFILLED_BY_ANOTHER_USER`

Jangan khawatir, kamu bisa meminta support Google untuk mereset token Download eBook-mu di Google Play Books, caranya cukup kunjungi [halaman Google Book Partner ini](https://support.google.com/books/partner/contact/default). Setelah itu masukkan beberapa informasi penting terkait permasalahan yang kamu alami, masukkan data nama, email yang kamu gunakan saat membeli ebook tersebut, keterangan buku ISBN atau GGKEY (ISBN bisa kamu cek dengan membuka link ebooknya, ada di keterangan di bawah dari halaman), isi keterangan tambahan, dan Upload screenshot tampilan error saat kamu tak bisa memasukkan buku tadi ke Adobe Digital Editions.

Saya sendiri cukup waktu satu hari baru kemudian ada balasan dari support google kalau token download bukunya sudah direset. Padahal sebelumnya saya protes melalui halaman [My Books](https://play.google.com/books), dan panjang lebar menjelaskan ke support tersebut tanpa ada jawaban yang memuaskan. Hingga akhirnya saya tau cara untuk reset token ini 🙈.

Selamat Membaca!

### Untuk lebih memahami fungsi Adobe Digital Editions, Baca Ini
- [Transfer eBook to eReader in Adobe Digital Editions](https://helpx.adobe.com/digital-editions/kb/transfer-ebook-ereader-digital-editions.html)
- [How to transfer an eBook from Adobe Digital Edition to iPad Mini](https://community.adobe.com/t5/digital-editions/how-to-transfer-an-ebook-from-adobe-digital-edition-to-ipad-mini/td-p/4746930)