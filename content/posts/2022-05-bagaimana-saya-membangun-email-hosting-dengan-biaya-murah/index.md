---
title: "Bagaimana Saya Membangun Email Hosting dengan Biaya Murah"
date: 2022-05-28
author: jksntn
slug: bagaimana-saya-membangun-email-hosting-dengan-biaya-murah
description: Beberapa cara yang saya lakukan untuk membangun email hosting yang murah
draft: false
categories:
  - produktivitas
tags:
  - email
  - hosting
  - personal project
---

Setelah cukup bingung memilih hosting untuk email dengan domain sendiri yang murah, akhirnya saya melakukan hal ini.

<!--more-->

{{< figure src="Untitled-2022-03-13-0157.png" alt="" caption="infrastruktur email saya di jaka@jksntn.my.id" >}}

Sebelum menjelaskan ini, perlu kalian ketahui dulu kalau email hosting itu cukup mahal, bahkan yang gratisan seperti zoho dan Yandex membatasi fitur gratisnya, sehingga ada hal yang menyebalkan seperti email engga kekirim dan banyak hal lainnya.

Email hosting berbayar yang bagus dan paling murahpun sebenernya masih mahal, untuk Google sendiri seharga $4.20, yang termurah mungkin adalah Zoho lite, itu seharga $1. Dan yang untuk lokal sendiri (Niagahoster) seharga Rp80.000. Kalau kalian concern sekali dengan service lainnya seperti google workplace yang banyak sekali fiturnya seperti google docs, meet, dll. mending pilih Google aja, tapi perhatikan itu $4.20 hanya untuk 1 orang/alamat email ya, kalau usernya ada 20 orang tinggal dihitung saja 😅.

{{< figure src="Untitled-2022-05-28-0816.png" alt="" caption="Perbandingan harga email hosting yang rekomended" >}}

Tapi kalau kalian hanya butuh email yang bisa digunakan untuk bisnis/ menggunakan domain kalian sendiri, saya menyarankan hal ini.

Supaya email hosting biayanya bisa saya tekan lebih murah lagi, saya menggunakan:
1. Domain (my.id seharga Ro10.000/tahun)
2. DNS/Domain manager menggunakan [Netlify](https://www.netlify.com/) (gratis)
3. Shared hosting (gratis, saya numpang addon domain doang ke temen 😅)
4. Email gratisan dari google sebagai storagenya.

Kalau melihat di gambar awal, ada 3 infrastruktur, yaitu DNS manager (Netlify), Shared hosting (sebagai server email), dan Email google gratisan (Storage dan email alias). 

## Setup DNS

Di Netlify saya menambahkan mx record yang diarahkan ke ip server shared hosting saya. Dengan catatan, di shared hosting tadi harus sudah menambah addon domain jksntn.my.id saya. Sisanya seperti SPF dan DKIM nya saya tambahkan record txt nya di DNS manager (di Netlify).

Supaya tidak ada masalah, pastikan IPnya mengarah ke shared hosting, karena kalau salah atau IP Shared hostingnya berubah, servernya bakal error engga bisa menerima dan mengirim email.

{{< figure src="Untitled-2022-05-28-0844.png" alt="" caption="Setup DNS record" >}}

## Setup di Server Shared Hosting

Di shared hostingnya, hal yang perlu dilakukan adalah menambahkan (addon) domain di shared hostingnya (kalau yang saya pake cpanel). Kalau sudah, langsung cek aja Deliverability (seperti di gambar), pastikan alamat IP servernya sudah ditambah di mx record DNS managementnya. 

Kalau masih ada error, tambahkan/pastikan SPF dan DKIM record sudah ditambah recordnya di DNS management. 

{{< figure src="Untitled-2022-05-28-0903.png" alt="" caption="Pastikan Emailnya bisa terkirim oleh server (Email Deliverability)" >}}

Setelah itu tinggal ditambah alamat emailnya di Shared hosting ini, nanti akan ada email awal yang masuk berisikan instruksi setup/credential apabila mau dipasang di Client Email (smtp,pop3, port, dll). 

{{< figure src="Untitled-2022-05-28-0856.png" alt="" caption="Setup Email di Shared Hosting, Cuman 0 Bytes!" >}}

## Setup di Email Google gratisan

Nah fungsi Email Google gratisan adalah supaya memudahkan mengecek email yang masuk, dan yang terpenting sebagai pengganti email storage yang masuk (pastiin setup pop3nya jangan save copy email ke server, supaya hanya masuk ke email gratisan google kita).

{{< figure src="Untitled-2022-05-28-0851.png" alt="" caption="Setup di Email Google" >}}

{{< figure src="Untitled-2022-05-28-0954.png" alt="" caption="Setup di Email Google" >}}

## Final Verdict

Nah gaes, dengan cara ini saya bisa hemat banget pengeluaran untuk membangun email hosting. Ini juga bisa digunakan untuk membangun email bisnis awal-awal apabila kalian membangun bisnis sendiri. 

Semoga bermanfaat. 👌