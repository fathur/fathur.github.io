---
layout: single 
title:  "Selamat Datang!"
classes: wide
date: 2021-03-29 11:22:54 +0700
author: Fathur
# toc: true
header:
#   overlay_color: "#333"
  image: https://images.unsplash.com/photo-1580191947416-62d35a55e71d?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=3302&q=80&h=1000
  caption: Photo by <a href="https://unsplash.com/@timmossholder?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Mossholder</a> on <a href="https://unsplash.com/s/photos/welcome?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
---

Setelah mencoba beberapa kali, semoga ini blog yang terakhir dan terupdate yang pernah kubuat.

Kalo dilihat dari *statement* saya diatas, sudah terlihat bahwa ini bukan pertama kali saya membuat
situs-blog. Yang keberapa? Saya juga lupa 🤷🏻. Kalo kamu fans saya, mungkin pernah tahu [catatan.rohman.pro](catatan.rohman.pro), [kakakung.blogspot.com](kakakung.blogspot.com). 

## Apa Sih Masalahnya?

Ada beberapa kendala mengapa saya sering ganti blog dan alamat url-nya.

Pertama, saya lebih suka hosting di VPS (*Virtual Private Server*). Tetapi masalahnya VPS bayarnya bulanan dan bayarnya dengan dolar 💰 💸 (saya sudah coba di AWS, GCP atau DigitalOcean). Karena hal tersebut blog saya bisa saja hilang karena di *suspend* tidak bayar, atau saya matikan karena boros. Mungkin dari pembaca ada pertanyaan, "Kan bisa dibuat di *shared hosting*?" Maaf, *shared hosting* bukan favorit saya, saya bisa lebih bebas di VPS.

Kedua *mood*, menulis itu butuh *mood*. Jika kamu melihat tulisan ini, berarti *mood* saya lagi bagus. Dan masalahnya *mood* saya kadang bagus kadang jelek, banyakan jeleknya sih. Ya mungkin kamu juga sama seperti saya.

Ketiga, ide. Sebenarnya ide banyak sekali, sayangnya ide-nya tidak terkatagorisasi atau tidak dalam satu topik. Kadang topik yang ingin saya tulis bermuatan *tech*, kadang bermuatan sosial, kadang bermuatan pribadi. Dan ini membuat saya bimbang, mau dituliskan dimana? Buat situs-blog lagi dengan topik yang berbeda; atau satu situs-blog dengan kategori bermacam-macam, tapi... tapi... nanti campur aduk blognya. Hingga ujung-ujungnya tidak jadi nulis saking bimbangnya.

Keempat, konsistensi. Seminggu sekali, sebulan 2 kali, sebulan sekali, atau setahun sekali. Ini sungguh berat, bahkan saya sudah pernah membuat jadwal seminggu sekali, tetapi tetap tidak bisa dijalankan. Terdapat beberapa faktor yang sih menurut saya soal konsistensi: niat, waktu dan dompet.

Bahkan saya pernah nge-tweet lo pada 10 Oktober 2020, semoga konsisten tiap senin.

<blockquote class="twitter-tweet"><p lang="in" dir="ltr">Ini catatan pertama, catatan-catatan selanjutnya akan rutin setiap senin. Insya Allah...<a href="https://t.co/eQ9VWNODyh">https://t.co/eQ9VWNODyh</a></p>&mdash; Fathur Rohman (@__rohman__) <a href="https://twitter.com/__rohman__/status/1336849791020503040?ref_src=twsrc%5Etfw">December 10, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Ujung-ujungnya kontennya cuma satu dan situsnya mati 🥲.

## Mungkin Ini Solusinya

Ok, cukup keluh kesahnya, sekarang kita masuk bagaimana cara mengatasi masalah-masalah tersebut.

Pertama, VPS sepertinya bukan tempat yang tepat untuk *blogging system*, atau *platform* yang berbayar. Jadi saya berencana untuk menyingkirkan opsi yang berbayar, dan masuk ke yang gratisan 🎊. Masuk deh ke [Github Pages](https://pages.github.com/) dengan custom domain. Github Pages menggunakan [Jekyll](https://jekyllrb.com) untuk generate kontennya, sempat berfikir pindah ke Hugo yang lagi booming. Tapi Github Pages belum support Hugo, jika dipaksakan ke [Hugo](https://gohugo.io) nanti ujung-ujungnya VPS lagi. 

Keuntungan di Github Pages, kontennya di masukin di git, jika kamu penasaran perubahan post saya dapat dilihat [disana](https://github.com/fathur/fathur.github.io).
Dan jika domain ini sudah habis atau mati, konten masih dapat diakses di [fathur.github.io](https://fathur.github.io).

Sempat kepikiran juga masukin aja di Facebook Notes, tapi saya rasa bukan pilihan yang tepat.Sebenarnya masih ada satu lagi di Medium, meskipun popular oleh developer dan non-developer, tetapi disana bukan tempat yang ramah untuk developer menurut saya.

> VPS sepertinya bukan tempat yang tepat untuk *blogging system*, atau *platform* yang berbayar.

Untuk mood management, mungkin saya harus baca beberapa solusi dari beberapa pakar. Bahkan saya menemukan sebuah paper berjudul ["Mood Management Theory"](https://www.researchgate.net/publication/319265020_Mood_Management_Theory) oleh Leonard Reinecke dari Johannes Gutenberg-Universität Mainz yang di publish pada Juli 2016.

Kemudian masuk ke ide, setelah saya renungkan sesaat, sepertinya cukup satu situs-blog saja dengan kategori yang bermacam-macam. Kenapa? Karena *maintenance* lebih mudah. Jika banyak situs-blog, *maintenance*-nya akan lebih sulit. Toh, pembacanya cuma saya. Nah, kalo pembacanya sudah banyak dan ada *demand* untuk dipisah, barulah dipisah per situs-blog per topik.

Konsistensi ini juga susah, tapi  saya mencoba membuat jadwal agar rutin di *publish*.
Setiap *weekend*, ketika sudah tidak bekerja, saya luangkan waktu sedikit untuk menulis. Yaitu selama dua hari merancang dan memperbaiki tulisan, kemudian Senin di *publish* sehingga memiliki kualitas. Saya yakin bahwa tulisan berkualitas itu tulisan yang bukan hanya sekali ketik langsung jadi, tapi harus melalui proses riset dan review.

Sudah demikian celotehan saya hari ini, semoga apa yang saya tulis diatas dapat terwujud. Dan... selamat menikmati blog baru saya. 😉

Fathur Rohman

