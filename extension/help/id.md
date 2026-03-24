---
layout: bare
title: Furigana Reader — Panduan pengguna
lang: id
---

# Furigana Reader — Panduan pengguna

> Versi: v2.0.0

## Pengantar

Furigana Reader adalah ekstensi peramban untuk pembelajar bahasa Jepang. Menggunakan penganalisis morfologis WASM (Lindera) dengan cadangan JavaScript, ekstensi ini menambahkan furigana (anotasi bacaan) pada kanji di halaman web secara akurat sehingga Anda lebih mudah mempelajari pelafalan.

---

## Fitur utama

- **Anotasi teks terpilih** — Pilih teks Jepang di halaman untuk menampilkan furigana dan tombol bicara secara otomatis
- **Mode furigana seluruh halaman** — Satu klik untuk menambahkan furigana ke semua kanji di halaman
- **Teks ke ucapan (TTS)** — Klik ikon speaker untuk mendengarkan pelafalan
- **Ucapan pilihan** — Pilih teks Jepang, gunakan tombol mengambang atau klik kanan «Bacakan pilihan»
- **Tooltip saat arahkan kursor** — Arahkan ke karakter yang diberi anotasi untuk melihat furigana dan tombol pelafalan
- **Beberapa gaya furigana** — Hiragana, katakana, atau romaji
- **Antarmuka multibahasa** — Mendukung 38 bahasa antarmuka

---

## Cara menggunakan

### Langkah 1: Pasang ekstensi

Pasang **Furigana Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara lokal dalam mode pengembang.

### Langkah 2: Buka halaman web

Kunjungi halaman yang berisi konten bahasa Jepang.

### Langkah 3: Pilih teks atau gunakan tombol mengambang

Pilih teks yang ingin dianotasi, atau klik tombol mengambang di kanan bawah untuk mode furigana seluruh halaman.

### Langkah 4: Lihat furigana

Arahkan kursor ke karakter untuk tooltip; klik ikon speaker untuk mendengarkan.

### Langkah 5: Bacakan teks terpilih

Pilih teks dengan mouse, klik tombol speaker mengambang, atau klik kanan dan pilih «Bacakan pilihan».

> **Tips:** Klik ikon ekstensi di bilah alat untuk membuka pengaturan — gaya furigana, kecepatan bicara, dll.

---

## Panduan pengaturan

| Pengaturan | Deskripsi |
|------------|-----------|
| **Aktifkan furigana** | Saklar utama untuk menyalakan atau mematikan fitur furigana |
| **Furigana seluruh halaman** | Jika aktif, menampilkan furigana untuk semua kanji (dapat memengaruhi tata letak) |
| **Gaya furigana** | Hiragana, katakana, atau romaji |
| **Kecepatan bicara** | Mengatur kecepatan pembacaan kalimat |
| **Tooltip saat arahkan** | Menampilkan tooltip furigana saat kursor diarahkan |

---

## FAQ

**T: Mengapa tidak berfungsi di beberapa halaman?**  
J: Demi keamanan, ekstensi tidak berjalan di halaman khusus seperti `chrome://`, pengaturan peramban, atau Chrome Web Store.

**T: Bagaimana jika furigana tidak akurat?**  
J: Kata jarang atau bacaan khusus (熟字訓, jukujikun) bisa salah. Kami terus memperbaiki — kirimkan contoh konkret.

**T: Tidak ada suara dari TTS?**  
J: Periksa volume sistem dan paket suara bahasa Jepang. Dukungan berbeda menurut peramban dan sistem operasi.

**T: Mode seluruh halaman mengganggu tata letak?**  
J: Furigana membutuhkan ruang ekstra dan dapat mengubah tata letak. Jika mengganggu, nonaktifkan mode tersebut dan gunakan tooltip.

---

## Tautan terkait

- [Kebijakan privasi](../privacy-policy)
- [Dukungan & masukan](../support)

---
