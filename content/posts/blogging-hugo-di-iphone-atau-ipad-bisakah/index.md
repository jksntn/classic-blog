---
title: "Blogging Hugo di iPhone atau iPad, Bisakah?"
date: 2021-06-24
author: jksntn
slug: blogging-hugo-di-iphone-atau-ipad-bisakah
description: Menjawab pertanyaan ini cukup mudah, untuk keperluan bloggingnya bikin tulisan baru, hapus, dan edit, tentu saja bisa. 
draft: false
categories:
  - tools tips
tags:
  - hugo
  - web development
  - blogging
---
Menjawab pertanyaan ini cukup mudah, untuk keperluan bloggingnya: bikin tulisan baru, hapus, dan edit, tentu saja bisa. 

<!--more-->

Bahkan kalau kamu mau mengubah layout, code html atau css di dalam [Hugo](/migrasi-ke-hugo/) juga bisa. Tapi sayangnya kamu tidak bisa menjalankan `hugo server` untuk mengecek hasil kodingan kamu, tapi kamu bisa melihat preview markdown (menggunakan aplikasi [iA Writer](https://ia.net/writer), [Textastic](https://www.textasticapp.com/), atau [Working Copy](https://workingcopyapp.com/). 

Tentu saja markup kode selain markdown tidak akan ke-generate ya, karena kamu perlu menjalankan hugo di local (iphone, dan itu cukup mustahil) untuk bisa melihat previewnya.

### Flow

{{< figure src="flow.jpg" caption="Gambaran work flow menggunakan Working Copy dan iA Writer untuk ngeblog di iPhone atau iPad" >}}

Untuk bisa mengedit tulisan atau kodingan website kita, tentu kita membutuhkan Git Clone dari Github (apabila kamu menggunakan github) ke iPhone atau iPad, ada aplikasi untuk melakukan ini yang menurut saya sangat bagus sekali, yaitu [Working Copy](https://workingcopyapp.com/), sayangnya harganya cukup mahal 😅, sekitar 400rb kalau dirupiahkan. Itu juga harus bayar sekitar 50-100ribuan apabila ada fitur pro yang baru rilis. 

Repot ya? Kalau penasaran kamu bisa trial 10 harian fitur pronya.

Setelah menggunakan working copy untuk cloning, kamu bisa gunakan langsung editor yang ada di working copy, tapi saya lebih senang menggunakan [iA Writer](https://ia.net/writer), karena saya lebih banyak mengedit tulisan berformat .md/markdown. 

Setelah selesai mengedit di iA Writer, baru kemudian saya kembali ke apps Working Copynya, tinggal commit, dan git push, selesai. Tulisan kamu pun akan update di blogmu.

Saya juga menggunakan Netlify untuk mengelola domain (.my.id) saya dan menjalankan hugonya. Jadi nanti ketika ada perubahan di Git-nya, maka akan mentrigger Netlify untuk mengupdate website/blog sesuai Git yang terbaru. 

### It is Necessary? 

Nah, sebenernya agak berlebihan sih untuk saya apabila harus ngeblog sekalian ngepublish postingan di iPhone atau iPad, karena pertama, apps Working Copy berbayar, dan itu cukup mahal sih apabila saya cuman gunain untuk ngeblog Hugo doang. Karena saya bisa melakukannya di laptop dengan gratis. 

Sebenernya untuk text editingnya menggunakan working copy saja sudah cukup, tapi apabila kamu *Zen writer* seperti saya (ah lebay), maka menulis di iA Writer itu menyenangkan sekali dan sangat mudah (apabila hapal markdown). Apalagi aplikasi iA Writer yang sangat ringan, dan terpenting, bisa offline mode 😁. 

FYI iA Writer juga aplikasi berbayar (sekitar 150rb rupiah), dan untungnya dulu waktu tahun 2014 an, saya pernah beli dengan harga cukup $1 saja 😅. 

Jadi apabila kamu masih bisa buka laptop sih sebenernya 'ngeblog' menggunakan Working Copy engga..... perlu 😂.

### Tapi, Bagaimana Kalau mau jalanin Hugo di Android?

Bisa, [cek di sini aja](https://gist.github.com/bep/a0d8a26cf6b4f8bc992729b8e50b480b#gistcomment-3624139) 😁. Untuk Git clonenya kamu cukup menggunakan aplikasi Termux. 

Dan editornya karena  ini berformat markdown, kamu bisa menginstall iA Writer di Android (namun sayangnya berbayar juga 😅). 

Atau mungkin kamu mau mencoba menggunakan salah satu editor di tulisan ini: [10 Aplikasi Code Editor Untuk Ngoding di Android](https://www.codepolitan.com/10-aplikasi-code-editor-untuk-ngoding-di-android-5b35c560965d2).

Semoga bermanfaat 🙏.

