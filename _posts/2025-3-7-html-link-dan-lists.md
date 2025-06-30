---
layout: post
title: "Membuat index html dan menjalankan jekyll serve"
---

Cara menjalankan jekyll serve

- setelah membuat sebuah repository dengan nama sendiri lalu clone repository tersebut ke lokal
- kemudian masuk ke dalam folder repository tersebut dan install melalui terminal vscode dengan perintah
  berikut: gem install jekyll bundle
           bundle init
- kemudian masuk ke folder gemfile yang muncul dan tambahkan gem "jekyll" di baris baru
- tambahkan file baru dengan nama index.html dan isi dengan kode berikut:    
  <!DOCTYPE html>
  <html>
  <head>
  <meta charset="utf-8">
  <title>home</title>
  </head>
  <body>
  <h1>My World!</h1>
  </body>
  </html>

- lalu ketik "jekyll build" di terminal agar menghasilkan directory _site dan jalankan 
  "jekyll serve" dan klik url http://127.0.0.1:4000 yang muncul

- jika web sudah berhasil dinuka berikut untuk push ke ripository github  
    - git add
    - git commit -m "nama folder nya"
    - git push         