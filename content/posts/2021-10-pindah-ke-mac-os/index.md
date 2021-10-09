---
title: "Pindah Ke macOS"
date: 2021-10-09
author: jksntn
slug: pindah-ke-mac-os
images: 
 - /2021/10/pindah-ke-mac-os/featured.jpg
description: Pengalaman saya pindah OS dari windows ke macOS
draft: false
categories:
  - personal
tags:
  - hackintosh
  - macos
  - operating system
  - big sur
---
Sebenernya sudah cukup lama saya memikirkan untuk pindah OS ke macOS (menggunakan hackintosh) pada laptop non mac. Karena pada 2021 ini cukup banyak kisah success story orang-orang yang moveon ke macOS. Kalaupun ada bug, biasanya karena chipset wifi dan bluetoothnya engga support, dan bisa disiasati menggunakan wifi/bluetooth external.

Akhirnya setelah ada orang lain yang berhasil [menginstall hackintosh di thinkpad X250](https://github.com/exxncss/x250-hackintosh) (thanks mas bro exxncss), saya pun memberanikan diri mencoba OS ini. 

<!--more-->

Engga tanggung-tanggung, saya langsung pindah menggunakan Big Sur (macOS 11). Sedikit rasa menyesal, karena ternyata [Big Sur tidak mendukung aplikasi 32 bit](https://support.apple.com/en-us/HT208436), artinya banyak game steam saya yang ga bisa dimainin. 🥲

{{< figure src="counterstrike.jpg" alt="Counterstrike" caption="Salah satu game yang ga bisa dimainin di Big Sur" >}}

### Apa yang ga berfungsi?

- **Bluetooth**. Chipset Intel AC-7265 sayangnya masih belum support untuk AirDrop maupun Handoff. Padahal cukup berguna kalau mau pindahin data besar tanpa kabel/sync ke iCloud.
- **Audio Bluetooth**. Sepertinya memang masih jadi bugnya dari chipset Intel AC-7265, kalau wifi tersambung jadinya suka tersendat-sendat. Kalau wifi off, audio bluetooth dari TWS saya ga ada masalah.
- **VGA port**. Vga port dari thinkpad x250 saya jadi ga kedetect, dan solusinya adalah menggunakan kabel tambahan display port ke hdmi. 
- **Card Reader**. Ini kayaknya dari bro exxncns yang saya ambil EFI nya blm melakukan [patch untuk card reader](https://github.com/FIRSTPLATO/cardreader-kext). Nanti kalo sempet saya beresin sih kayaknya.
- **Jack 35mm**. Ini kejadian yang jarang banget, audio dari jack 35mm kadang suka mati, dan solusinya adalah sleep dan bangunin laptopnya kembali. 

### Mau Coba Install Hackintosh? 

Cara paling mudah dipahami adalah:

- Menyiapkan instalan dan EFI untuk boot flashdisk, tutorialnya bisa dilihat [di sini](https://github.com/exxncss/x250-hackintosh#buat-installer-macos). Untuk bahan-bahan apabila di web Oralia engga bisa didownload, dari komunitas Hackintosh udah melakukan mirroring file recovery OS nya [di sini](https://drive.google.com/drive/u/2/folders/1nF71xPbhiyuS8vQOi-E6wHS-tSknvoZo).
- Melakukan instalasi mac (recovery macOS ke HDD/SSD kita). Tutorialnya bisa ditonton [di sini](https://www.youtube.com/watch?v=olBn3HQP4yc).
- Melakukan penyesuaian, patch, dll. Kalo ini bisa langsung ditanya aja ke grup/dm di forum, dll.

Kalau ada kesulitan, mentok, dll, bisa kunjungi ini saja.

- [Grup Telegram Hackintosh Indonesia](https://t.me/HackintoshLover)
- [Forum Tonymacx86](https://www.tonymacx86.com/)

### Apakah Worth it?

Pasti 😅, macOS itu enak banget. 

Experiencenya jauh banget dengan menggunakan windows dan linux. Untungnya udah biasa menggunakan terminal linux, jadi ga kagok pas pake terminal mac. 

