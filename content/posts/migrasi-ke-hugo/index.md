---
title: Migrasi ke Hugo
date: 2020-04-11
description: Cerita saya pindahan blog ke Static Site Generator Hugo
slug: migrasi-ke-hugo
images:
 - /migrasi-ke-hugo/featured.png
categories:
 - stories
tags:
 - hugo
 - static site generator
 - blog
---

Pada tahun 2020 ini saya kembali menggunakan static site generator untuk membuat blog jksntn ini, dan saya memilih Hugo sebagai frameworknya, karena mudah digunakan di Windows.

Setelah saya menggunakan berbagai macam platform untuk ngeblog, mulai dari [wordpress.com][wordpress.com], [blogspot][blogspot], [tumblr][tumblr], [postach.io][postach], kemudian self hosting menggunakan [wordpress.org][wordpress.org], dan juga self hosting menggunakan [jekyll][jekyll]. Kemudian mencoba platform ajaib [medium.com][medium], [write.as][writeas], dan [telegraph][telegraph].

<!--more-->

Akhirnya saya kembali lagi untuk self hosting menggunakan [Hugo][hugo]. 

Hugo ini adalah framework web development yang menggunakan sistem Static Site Generated. Artinya website ini tidak memerlukan database atau server database dalam membuat websitenya. 

Keuntungan menggunakan SSG dari segi penggunaan adalah kecepatan, setelah itu adalah keamanan, karena kalaupun ada yang dibobol, adalah akses github atau akses hostingnya. Bisa di cpanel atau di [Netlify][netlify]. 

Karena sebenarnya kamu bisa hosting menggunakan layanan gratis seperti Netlify, firebase, atau github pages, jadi investasi membuat website menggunakan Hugo ini cukup investasi membeli domain saja, karena hostingnya bisa gratis. 

{{< notice note >}}

Netlify ini gratis untuk 100GB bandwith/bulan dan 300 build minutes/bulan. Apabila websitemu lebih dari itu, maka kamu musti upgrade ke Plan Pro seharga $45/bulan. Atau cek [halaman Pricing mereka](https://netlify.com/pricing).

Apabila dibandingkan dengan membeli hosting murah di Indonesia, dan membutuhkan bandwith lebih besar dari 100GB/bulan, maka bisa dibilang menyewa shared hosting Cpanel lebih murah dibandingkan plan pro Netlify.

Gunakan sesuai kebutuhanmu. 👍

{{< /notice >}}

Kalau dari sisi development, menggunakan SSG itu enaknya mudah untuk maintenance, dan mudah didevelop. Apalagi kalau menggunakan windows, maka saya lebih menyarankan menggunakan Hugo ini saja. 

### Membuat Platform Sendiri

Membuat website dan hosting sendiri adalah sebuah pilihan yang menurut saya udah paling benar, karena kamu memiliki kuasa penuh terhadap website kamu itu. Kecuali hostingnya tidak kamu perpanjang. 

Nasib websitemu ada di tanganmu sendiri.

Kamu juga bebas menentukan seperti apa websitemu, karena membuat di platform orang lain pasti terkendala dan adanya batasan-batasan tertentu.

Dengan menggunakan platform SSG dan hosting sendiri memberikan saya kebebasan untuk membuat seperti apa website saya itu. 

Coba bayangkan tulisanmu yang kamu posting di [Medium.com][medium] atau di [wordpress.com][wordpress.com], bayangkan kalau sewaktu-waktu mereka bubar (seperti band) dan sampai disitulah riwayat blog/ website milikmu itu. 

Buat platformmu sendiri.

### Final Verdict

Kalau bisa disebut kekurangan, Hugo ini cukup sulit buat orang awam yang tidak memahami bagaimana web server bekerja, atau tidak memahami HTML, CSS, dan Javascript. Atau tidak memahami bagaimana cara kerja Git.

Kalau kamu paham tapi bukan expert, kamu bisa belajar otodidak dan menggunakan template-template yang tinggal digunakan [di sini][hugo theme].

Untuk lebih memahami struktur, cara kerja dari [Hugo][hugo] kamu bisa mempelajarinya di [halaman docs ini][hugo docs].

Saya sendiri menggunakan template orang lain dan mengubahnya sesuai kebutuhan dan kemauan saya. 

Jadi tak ada alasan untuk tetap mempertaruhkan blog/website kamu di tangan orang lain, buatlah platformmu sendiri.

Selamat berkoding ria 💪💪.

[netlify]:  https://www.netlify.com/
[hugo theme]:  https://themes.gohugo.io/
[hugo]: https://gohugo.io/ 
[hugo docs]: https://gohugo.io/getting-started/
[wordpress.com]: https://wordpress.com
[wordpress.org]: https://wordpress.org
[medium]: https://medium.com
[writeas]: https://write.as
[blogspot]: https://blogger.com 
[tumblr]: https://tumblr.com 
[jekyll]: https://jekyllrb.com 
[postach]: https://postach.io 
[telegraph]: https://telegraph.telegram.org