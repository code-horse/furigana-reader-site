---
layout: bare
title: Furigana Reader — Panduan pengguna
lang: id
---

# Furigana Reader — Panduan pengguna

> Versi: v1.4.1

## Pengantar

Furigana Reader adalah ekstensi peramban untuk pembelajar bahasa Jepang. Menggunakan penganalisis morfologis WASM (Lindera + IPAdic) dengan cadangan JavaScript, ekstensi ini menambahkan furigana (anotasi bacaan) pada kanji di halaman web dan PDF secara akurat. Fitur yang disertakan meliputi kamus bahasa Jepang bawaan, teks ke ucapan, dan terjemahan — membantu Anda mempelajari pelafalan bahasa Jepang dengan lebih mudah.

---

## Fitur utama

- **Mode furigana seluruh halaman** — Satu klik untuk menambahkan furigana ke semua kanji di halaman
- **Kamus saat arahkan kursor** — Arahkan ke karakter yang diberi anotasi untuk melihat definisi JMdict (lebih dari 180 ribu entri), bacaan, lencana tingkat JLPT (N5–N1), dan tombol pelafalan; pilih mode Kamus, Bacaan, atau Mati
- **Pembaca PDF** — Pembaca PDF bawaan dengan furigana, kamus, ucapan, dan terjemahan; mendukung seret dan lepas, pemuatan URL, serta deteksi PDF otomatis dengan pengalihan cerdas
- **Tiga gaya bacaan** — Tampilan hiragana, katakana, dan romaji
- **Pemisahan okurigana** — Memisahkan okurigana (送り仮名) dari batang kanji dengan tepat
- **Dukungan jukujikun** — Bacaan yang benar untuk gabungan multi-kanji dengan bacaan khusus (熟字訓)
- **Teks ke ucapan (TTS)** — Klik tombol speaker untuk mendengar pelafalan bahasa Jepang
- **Ucapan pilihan dengan karaoke** — Pilih teks bahasa Jepang apa pun; bilah alat ringkas muncul dengan tombol bicara dan terjemahan; saat dibacakan, setiap kata atau aksara disorot secara real time (efek karaoke) disinkronkan dengan audio
- **Terjemahan pilihan** — Pilih teks apa pun, klik tombol terjemahan di bilah alat untuk terjemahan instan melalui Bing Translate atau Google Translate, ditampilkan dalam gelembung sebaris
- **Pintasan keyboard** — Akses cepat ke fitur inti melalui pintasan yang dapat disesuaikan
- **Antarmuka multibahasa** — Mendukung 38 bahasa antarmuka

---

## Cara menggunakan

### Langkah 1: Instal ekstensi

Instal **Furigana Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara lokal dalam mode pengembang.

### Langkah 2: Buka halaman web apa pun

Kunjungi halaman yang berisi konten bahasa Jepang.

### Langkah 3: Aktifkan furigana

Klik ikon ekstensi di bilah alat peramban. Aktifkan «Aktifkan furigana», lalu aktifkan «Furigana seluruh halaman» untuk menganotasi semua kanji. Anda juga dapat menggunakan tombol mengambang di kanan bawah.

### Langkah 4: Lihat furigana

Arahkan kursor ke karakter untuk melihat tooltip furigana dengan bacaan dan definisi kamus. Klik ikon speaker untuk mendengar pelafalan.

### Langkah 5: Bicarakan dan terjemahkan teks terpilih

Pilih teks bahasa Jepang dengan mouse. Bilah alat ringkas muncul di dekat pilihan dengan dua tombol:
- **🔊 Bicara** — Membacakan teks terpilih dengan sorotan bergaya karaoke
- **🌐 Terjemahkan** — Menampilkan gelembung terjemahan sebaris di bawah bilah alat

Anda juga dapat klik kanan dan memilih «Furigana Reader > Bacakan pilihan» atau «Furigana Reader > Terjemahkan pilihan».

> **Tips:** Klik ikon ekstensi untuk membuka panel pengaturan dan menyesuaikan gaya furigana, mode arahan, kecepatan bicara, mesin terjemahan, dan lainnya.

---

## Kamus saat arahkan kursor

Ekstensi menyertakan kamus bahasa Jepang bawaan berbasis JMdict (lebih dari 180.000 entri). Di pengaturan Anda dapat memilih beberapa mode arahan:

| Mode | Perilaku |
|------|----------|
| **Kamus** | Arahkan untuk menampilkan bacaan + definisi + tingkat JLPT + tombol pelafalan |
| **Bacaan** | Arahkan untuk menampilkan bacaan + tombol pelafalan (tanpa definisi) |
| **Mati** | Tidak ada efek saat arahkan |

Dalam mode **Kamus**, tooltip menampilkan:
- Kata dan bacaannya (furigana)
- Tombol pelafalan (klik untuk mendengar)
- Definisi bahasa Jepang dari JMdict
- Lencana tingkat JLPT (N5–N1) bila tersedia

> **Tips:** Data kamus dimuat sesuai permintaan saat mode Kamus diaktifkan, dan dibongkar saat beralih ke mode lain untuk menghemat memori.

---

## Pembaca PDF

Furigana Reader menyertakan pembaca PDF bawaan sehingga Anda dapat membaca dokumen PDF dengan furigana, kamus, ucapan, dan terjemahan — semua fitur yang Anda gunakan di halaman web, kini untuk PDF.

### Membuka PDF

**Metode 1: Dari popup**  
Klik ikon ekstensi, lalu «Buka pembaca PDF». Seret dan lepas file PDF atau klik «Pilih file» untuk membuka PDF lokal. Anda juga dapat menempel URL PDF.

**Metode 2: Menu konteks**  
Klik kanan tautan `.pdf` di halaman dan pilih «Buka PDF dengan Furigana Reader».

**Metode 3: Deteksi otomatis**  
Saat «Deteksi cerdas PDF» diaktifkan di pengaturan, ekstensi mengalihkan URL `.pdf` ke pembaca bawaan. Jika PDF terdeteksi tetapi tidak dialihkan (mis. penampil bawaan Chrome), Anda akan melihat notifikasi dan perintah untuk membukanya di Furigana Reader.

### Fitur pembaca PDF

- **Anotasi furigana** — Semua fitur furigana berfungsi pada teks PDF, termasuk mode seluruh halaman dan tooltip saat arahkan
- **Lima mode furigana** — Hiragana, katakana, romaji, hanya saat arahkan, dan Mati
- **Kamus klik** — Klik kata apa pun untuk melihat definisi JMdict (di PDF digunakan klik, bukan arahan, agar membaca lebih fokus)
- **Bilah alat pilihan** — Pilih teks untuk bicara, terjemahkan, atau salin
- **Bilah sisi** — Kerangka isi dan gambar mini halaman
- **Pencarian** — Pencarian teks penuh dalam PDF
- **Tema** — Tema membaca gelap, terang, dan sepia
- **Zoom** — Beberapa tingkat zoom termasuk furigana adaptif zoom
- **Pintasan keyboard** — Panah untuk navigasi, +/- untuk zoom, Ctrl/Cmd+F untuk pencarian

---

## Ucapan pilihan dan karaoke

Fitur ucapan pilihan memungkinkan Anda memilih teks bahasa Jepang apa pun dan membacakannya dengan satu klik — cocok untuk latihan pelafalan kalimat dan membaca.

**Metode 1: Bilah alat pilihan**  
Pilih teks bahasa Jepang dengan mouse. Bilah ringkas muncul di dekat pilihan dengan tombol 🔊 bicara dan 🌐 terjemahan. Klik bicara. Saat teks dibacakan, setiap kata atau aksara disorot secara real time (efek karaoke).

**Metode 2: Menu klik kanan**  
Setelah memilih teks bahasa Jepang, klik kanan dan pilih «Furigana Reader > Bacakan pilihan».

**Metode 3: Pintasan keyboard**  
Pilih teks dan tekan `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Tips:** Sorotan karaoke paling baik saat peramban mendukung peristiwa batas kata TTS. Jika tidak didukung, ekstensi menggunakan cadangan berbasis waktu untuk sorotan yang halus.

---

## Terjemahan

Pilih teks apa pun di halaman dan gunakan fitur terjemahan untuk mendapatkan terjemahan instan.

**Metode 1: Bilah alat pilihan**  
Pilih teks, lalu klik tombol 🌐 terjemahan di bilah alat. Gelembung terjemahan muncul di bawah dengan hasil dan tombol salin.

**Metode 2: Menu klik kanan**  
Pilih teks, klik kanan dan pilih «Furigana Reader > Terjemahkan pilihan».

**Metode 3: Pintasan keyboard**  
Pilih teks dan tekan `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Mesin terjemahan:**
- **Bing Translate** (default) — Microsoft Translator
- **Google Translate** — Google

Keduanya mendukung **108 bahasa target**.

Anda dapat mengganti mesin terjemahan dan bahasa target di pengaturan ekstensi. Bahasa target terdeteksi otomatis dari bahasa peramban.

> **Tips:** Klik di luar bilah alat atau gelembung untuk menutupnya.

---

## Pintasan keyboard

| Pintasan | Pintasan Mac | Tindakan |
|----------|--------------|----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Aktif/nonaktifkan anotasi furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Bacakan teks terpilih |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Terjemahkan teks terpilih |

> **Tips:** Sesuaikan pintasan ini di Chrome di `chrome://extensions/shortcuts`.

---

## Panduan pengaturan

| Pengaturan | Deskripsi |
|------------|-----------|
| **Aktifkan furigana** | Sakelar utama untuk mengaktifkan atau menonaktifkan fitur anotasi furigana |
| **Furigana seluruh halaman** | Saat diaktifkan, menampilkan furigana untuk semua kanji (dapat memengaruhi tata letak halaman) |
| **Mode arahan** | Pilih perilaku arahan: Kamus (bacaan + definisi + JLPT + audio), Bacaan (bacaan + audio), atau Mati |
| **Gaya furigana** | Hiragana, katakana, atau romaji |
| **Kecepatan bicara** | Menyesuaikan kecepatan pembacaan kalimat |
| **Mesin terjemahan** | Pilih Bing Translate atau Google Translate |
| **Bahasa target** | Mengatur bahasa target terjemahan (terdeteksi otomatis dari bahasa peramban) |
| **Deteksi cerdas PDF** | Saat diaktifkan, mengalihkan URL PDF ke pembaca bawaan secara otomatis dan menampilkan notifikasi saat PDF terdeteksi |

---

## FAQ

**T: Mengapa tidak berfungsi di beberapa halaman?**  
J: Demi keamanan, ekstensi tidak dapat berjalan di halaman khusus seperti `chrome://`, pengaturan peramban, atau Chrome Web Store.

**T: Bagaimana jika furigana tidak akurat?**  
J: Beberapa kata langka atau bacaan khusus (熟字訓) mungkin salah. Kami terus memperbaiki. Silakan bagikan contoh konkret.

**T: Tidak ada suara dari TTS?**  
J: Periksa volume sistem dan pastikan paket suara bahasa Jepang terpasang. Dukungan ucapan bervariasi menurut peramban dan sistem operasi.

**T: Mode seluruh halaman memengaruhi tata letak?**  
J: Furigana memerlukan ruang ekstra yang dapat memengaruhi tata letak asli. Jika mengganggu, nonaktifkan mode seluruh halaman dan gunakan tooltip saat arahkan.

**T: Terjemahan tidak berfungsi?**  
J: Terjemahan memerlukan koneksi internet. Jika Bing Translate gagal, coba beralih ke Google Translate di pengaturan. Beberapa jaringan mungkin memblokir layanan terjemahan.

**T: Bagaimana membuka PDF dengan Furigana Reader?**  
J: Klik «Buka pembaca PDF» di popup, klik kanan tautan PDF dan pilih «Buka PDF dengan Furigana Reader», atau aktifkan «Deteksi cerdas PDF» di pengaturan untuk pengalihan otomatis URL PDF ke pembaca bawaan.

**T: Deteksi cerdas PDF aktif tetapi beberapa PDF tidak dialihkan?**  
J: Pengalihan otomatis berlaku untuk URL yang berakhiran `.pdf`. Untuk PDF tanpa ekstensi atau yang dibuka di penampil bawaan Chrome, Anda akan melihat notifikasi dan lencana yang mengajak membuka di Furigana Reader.

**T: Bisakah menggunakan kamus luring?**  
J: Ya. Kamus JMdict (lebih dari 180.000 entri) sepenuhnya disertakan dalam ekstensi. Semua pencarian dilakukan secara lokal tanpa koneksi jaringan.

---

## Tautan terkait

- [Kebijakan privasi](../privacy-policy)
- [Dukungan & masukan](../support)

---
</think>
Fixing the Indonesian settings table: correcting malformed rows.

<｜tool▁calls▁begin｜><｜tool▁call▁begin｜>
StrReplace