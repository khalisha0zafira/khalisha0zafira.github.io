---
layout: post
title: "Java script dan config.yml"
---

JAVASCRIPT DAN CONFIG YML

1. JavaScript:

   Java script adalah bahasa pemograman yang digunakan untuk membuat halaman web
   menjadi interaktif, misalnya saat kita klik tombol muncul pesan, ada gambar
   yang berubah otomatis teks bisa bergerak atau berubah warna, dalam proyek jekyll kita dapat
   menambahkan file javascript ke dalam folder assets/js

   - Buat folder dan file javascript
     jika belum ada, buat struktur folder berikut dalam proyek jekyll mu assets/js

   - Lalu di dalam nya buat file java script: assets/js/script.js  
   - isi file javascript kamu contoh isi script.js:

 function myfunction() {
    alert("kan sudah bilang jangan di klik!");
} 

2. Config YML

   File config.yml adalah file pengaturan (konfigurasi) yang digunakan dalam proyek
   seperti jekyll, github pages, dan lainnya, untuk mengatur informasi penting
   dari website tanpa harus mengubah langsung kodenya file ini biasanya bernama: _config.yml

   isi file config.yml:

   url: 'https://khalisha0zafira.github.io'

 plugins:
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-seo-tag


