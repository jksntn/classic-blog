---
title: Alasan Saya Berhenti Menulis di Medium
date: 2019-07-02
description: Cerita bagaimana saya mulai tidak lagi menulis di Medium
slug: alasan-saya-berhenti-menulis-di-medium
images: 
 - /2019/07/alasan-saya-berhenti-menulis-di-medium/featured.jpg
categories:
 - personal
tags:
 - medium
 - writing
---

Setelah beberapa minggu akun medium saya kena soft banned, saya memutuskan untuk menghapus akun saya dan mulai mencari platform menulis lainnya. 

Alasan mengapa saya kena soft banned [medium][medium] memang masih jadi misteri sampai sekarang. Soft banned ini sendiri adalah akun saya bisa saya buka, namun orang lain tidak akan menemukan akun saya dan tulisan-tulisannya. Apabila ada orang lain yang mengakses link post tulisan saya, maka akan diarahkan ke halaman *not found*. 

<!--more-->

Kalau saya cari hal serupa di google, hanya ada kemungkinan yaitu saya melanggar terms and conditions Medium, tapi yang mana? Tidak ada kejelasan. Kalaupun ada post yang saya import, toh itu juga tulisan saya sendiri. 

Dengan adanya hal ini membuat saya memutuskan untuk mengakhiri akun medium saya, walaupun cukup banyak pembaca dari medium itu. Dengan ini pula saya tidak berniat berlangganan di medium, karena saya tau [cara membaca tulisan premium di Medium tanpa berlangganan $5 per bulan (secara legal).][unlimited]

Tak bisa dipungkiri, tujuan saya sebelumnya menulis di Medium adalah karena ada pembacanya. Ini seperti mendapatkan pembaca secara gratis, selain itu saya tidak perlu pusing memikirkan hosting, beli domain, setting meta untuk SEO, dan memilih template.

Sebenarnya ketika kamu menulis di Medium itu, kamu menulis di platform orang lain, kamu tak memiliki sepenuhnya blog yang kamu miliki di medium. Kamu juga tak memiliki kuasa kalau tiba-tiba medium menutup websitenya, ya kamu hanya bisa menyelamatkan tulisan-tulisan milikimu, tapi tidak dengan blogmu.

Selanjutnya, saya akan menjelaskan beberapa platform yang saya gunakan setelah berhenti menggunakan [medium][medium].

### Telegra.ph

Telegraph mirip banget dengan medium, bedanya adalah kita tak perlu setup atau registrasi untuk mulai menulis, selain itu bisa [instant view][telegraph] apabila memposting di telegram. 

Tapi kelemahannya adalah kita tak bisa mengakses postingannya kalau tak tau linknya, jadi ini hanya bergantung pada link saja. Tanpa ada home seperti website atau blog pada umumnya. 

### Write.as

Selain itu ada [Write.as][writeas], platform blogging yang bisa memecahkan masalah utama saya, yaitu simpel dan support markdown. Ya, tanpa adanya tombol format (rich text), kamu cukup menggunakan [Markdown Syntax][markdown] saja. Selain itu write.as benar-benar simpel, secara gratis kamu bisa menggunakan layanan ini dengan fitur yang sudah cukup untuk membangun blog sendiri. 

Seperti medium, tak perlu setup hosting, tema, dan meta untuk seo. Untuk upload gambar, saya menguploadnya ke layanan [imgur][imgur]. Namun memang saya belum mencoba untuk embed video 😅.

Saking simpelnya, saya bisa blogging menggunakan smartphone saya. Dan membuka dashboard write.as saya di browser chrome. Kemudian untuk menulis format markdown dengan cepat, saya menggunakan aplikasi iA Writer di Android.

Sayangnya, untuk bisa menambahkan halaman about dan halaman lain, saya harus merogoh kocek tambahan. Selain itu ada kemungkinana foto yang diupload di imgur tadi bisa dihapus. Menulis di writeas memang sangat mudah, tidak perlu pusing dengan hosting, domain, dan hal-hal lainnya, sayangnya terlalu simpel dan tidak bisa dicustom tampilannya.

### Tumblr

Setelah akhirnya pemerintah kita [membatalkan blokir terhadap tumblr][tumblr], ada kemungkinan tumblr mulai digunakan lagi oleh anak-anak muda Indonesia, karena memang platform blogging tumblr pas banget buat yang suka showoff hasil karya foto, lukisan, atau ilustrasi, intinya banyak seniman muda yang lebih suka memposting di tumblr ketimbang di Instagram.

Selain itu saya bisa menggunakan custom domain yang saya punya untuk diarahkan ke halaman blog tumblr saya. Bahkan tumblr juga support Markdown.

Sayangnya ada beberapa kekurangan tumblr yang suka menjadi perhatian saya. Walau bisa diedit file html-css nya, namun tumblr tetap memiliki keterbatasan dalam pengeditan, misalnya tidak adanya keleluasaan support meta untuk mempercantik tampilan link post yang kita share, juga kesulitan dalam menambahkan gambar besar di post kita, karena biasanya selalu diresize oleh tumblr. 

Hal-hal tersebut membuat saya berpikir ulang untuk terus menulis di tumblr.

### Static Site Generator (Hugo)

Saat ini emang lagi ramai penggunaan **static site generator** untuk membuat blog dan website secara cepat dan mudah. Dan menariknya lagi, karena nanti websitenya menjadi static, maka load website yang dibuat menjadi sangat, sangaaaat cepat. 

Static web generator ini memang selayaknya menulis website di html, css, dan javascript, tapi dibuat sehingga kita tak perlu mengupdate banyak halaman .html untuk mengedit keseluruhan halaman web kita. Perbedaan antara SSG dan website dinamyc (php, dsb) adalah SSG tidak membutuhkan database untuk menaruh file-file postingan kita.

Saya pernah menggunakan [Jekyll][jekyll], [Gridsome][gridsome], dan [Hugo][hugo]. Kebetulan blog ini dibuat menggunakan Hugo + Netlify. Saya menggunakan Hugo karena mudah diinstall di windows, dokumentasinya mudah dipahami, dan banyak yang menggunakan, sehingga kalau ada kesulitan bisa tanya-tanya.

Walaupun menjadi sangat cepat, namun buat yang awam dengan pemrograman terutama html + css dan javascript, mungkin agak kesulitan kalau harus mengelola website static site generator ini sendirian. 

Buat yang malas harus mengupdate blog melalui code editor seperti notepad++, sublime text, dan Visual Studio Code, bisa menginstall [netlify cms][netlifycms] atau menggunakan layanan [forestry.io][forestry], karena tampilannya sangat familiar dan mudah untuk digunakan posting blog atau page. 

{{< notice note >}}
Bagi pengguna Hugo yang menaruh file .jpeg, .png, dan file apapun itu di dalam folder content posts, maka agak sulit apabila menggunakan Forestry atau Netlify CMS ini, saran saya tetap menggunakan text editor seperti sublime text, atom, dan visual studio code untuk mengedit kontennya. 
{{< /notice >}}

Menggunakan static web generator untuk saat ini menjadi pilihan terakhir saya untuk tetap mempertahankan blog saya ini. Untungnya ada cara untuk mengimport tulisan ke hugo yang bisa digunakan apabila kamu mau memindahkan tulisan kamu tadi dari platform lainnya.

**Bye bye 👍 Medium 🤣**.


[medium]: https://medium.com/
[telegraph]: https://instantview.telegram.org/
[writeas]: https://write.as/
[markdown]: https://daringfireball.net/projects/markdown/syntax
[imgur]: http://imgur.com/
[blokir]: https://tekno.kompas.com/read/2018/12/26/12490027/blokir-resmi-dicabut-tumblr-bisa-diakses-lagi-di-indonesia
[jekyll]: https://jekyllrb.com/
[gridsome]: https://gridsome.org/
[hugo]: https://gohugo.io/
[netlifycms]: https://www.netlifycms.org/
[forestry]: https://forestry.io/
[unlimited]: https://medium-unlimited.ml/

