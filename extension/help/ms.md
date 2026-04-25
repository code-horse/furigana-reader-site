---
layout: bare
title: Furigana Reader — Panduan pengguna
lang: ms
---

# Furigana Reader — Panduan pengguna

> Versi: v1.4.3

## Pengenalan

Furigana Reader ialah sambungan pelayar untuk pelajar bahasa Jepun. Dikuasakan oleh penganalisis morfologi WASM (Lindera + IPAdic) dengan sandaran JavaScript, ia menambah furigana (nota bacaan) pada kanji di halaman web dan PDF dengan tepat. Ia juga termasuk kamus bahasa Jepun terbina dalam, teks ke pertuturan, dan ciri terjemahan — membantu anda mempelajari sebutan bahasa Jepun dengan lebih mudah.

---

## Ciri utama

- **Mod furigana seluruh halaman** — Satu klik untuk menambah furigana pada semua kanji di halaman
- **Kamus apungan** — Arahkan ke aksara beranotasi untuk melihat takrifan JMdict (lebih 180 ribu entri), bacaan, lencana tahap JLPT (N5–N1), dan butang sebutan; pilih mod Kamus, Bacaan, atau Mati
- **Pembaca PDF** — Pembaca PDF terbina dalam dengan furigana, kamus, pertuturan, dan terjemahan; menyokong seret dan lepas, pemuatan URL, serta pengesanan PDF automatik dengan lencongan pintar
- **Tiga gaya bacaan** — Paparan hiragana, katakana, dan romaji
- **Pemisahan okurigana** — Memisahkan okurigana (送り仮名) daripada batang kanji dengan tepat
- **Sokongan jukujikun** — Bacaan yang betul untuk sebatian berbilang kanji dengan bacaan khas (熟字訓)
- **Teks ke pertuturan (TTS)** — Klik butang pembesar suara untuk mendengar sebutan bahasa Jepun
- **Pertuturan pilihan dengan karaoke** — Pilih sebarang teks bahasa Jepun; bar alat padat muncul dengan butang bercakap dan terjemah; semasa dibacakan, setiap perkataan atau aksara diserlahkan secara masa nyata (kesan karaoke) disegerakkan dengan audio
- **Terjemahan pilihan** — Pilih sebarang teks, klik butang terjemah di bar alat untuk terjemahan serta-merta melalui Bing Translate atau Google Translate, dipaparkan dalam gelembung sebaris
- **Pintasan papan kekunci** — Akses pantas kepada ciri teras melalui pintasan yang boleh disesuaikan
- **Antara muka pelbagai bahasa** — Menyokong 38 bahasa antara muka

---

## Cara penggunaan

### Langkah 1: Pasang sambungan

Pasang **Furigana Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara tempatan dalam mod pembangun.

### Langkah 2: Buka mana-mana halaman web

Lawati halaman yang mengandungi kandungan bahasa Jepun.

### Langkah 3: Dayakan furigana

Klik ikon sambungan di bar alat pelayar. Hidupkan «Dayakan furigana», kemudian hidupkan «Furigana seluruh halaman» untuk menganotasi semua kanji. Anda juga boleh menggunakan butang terapung di kanan bawah.

### Langkah 4: Lihat furigana

Arahkan ke aksara untuk melihat tooltip furigana dengan bacaan dan takrifan kamus. Klik ikon pembesar suara untuk mendengar sebutan.

### Langkah 5: Baca dan terjemah teks terpilih

Pilih teks bahasa Jepun dengan tetikus. Bar alat padat muncul berhampiran pilihan dengan dua butang:
- **🔊 Bercakap** — Membaca teks terpilih dengan serlahan gaya karaoke
- **🌐 Terjemah** — Memaparkan gelembung terjemahan sebaris di bawah bar alat

Anda juga boleh klik kanan dan pilih «Furigana Reader > Baca pilihan dengan kuat» atau «Furigana Reader > Terjemah pilihan».

> **Petua:** Klik ikon sambungan untuk membuka panel tetapan dan laraskan gaya furigana, mod apungan, kadar pertuturan, enjin terjemahan, dan banyak lagi.

---

## Kamus apungan

Sambungan ini termasuk kamus bahasa Jepun terbina dalam berdasarkan JMdict (lebih 180,000 entri). Dalam tetapan anda boleh memilih beberapa mod apungan:

| Mod | Tingkah laku |
|-----|----------------|
| **Kamus** | Apungan menunjukkan bacaan + takrifan + tahap JLPT + butang sebutan |
| **Bacaan** | Apungan menunjukkan bacaan + butang sebutan (tiada takrifan) |
| **Mati** | Tiada kesan apungan |

Dalam mod **Kamus**, tooltip memaparkan:
- Perkataan dan bacaannya (furigana)
- Butang sebutan (klik untuk mendengar)
- Takrifan bahasa Jepun dari JMdict
- Lencana tahap JLPT (N5–N1) apabila tersedia

> **Petua:** Data kamus dimuat atas permintaan apabila mod Kamus dihidupkan, dan dibuang apabila bertukar ke mod lain untuk menjimatkan memori.

---

## Pembaca PDF

Furigana Reader menyertakan pembaca PDF terbina dalam supaya anda boleh membaca dokumen PDF dengan furigana, kamus, pertuturan, dan terjemahan — semua ciri yang anda gunakan di halaman web, kini untuk PDF.

### Membuka PDF

**Kaedah 1: Dari popup**  
Klik ikon sambungan, kemudian «Buka pembaca PDF». Seret dan lepas fail PDF atau klik «Pilih fail» untuk membuka PDF tempatan. Anda juga boleh tampal URL PDF.

**Kaedah 2: Menu konteks**  
Klik kanan pautan `.pdf` di halaman dan pilih «Buka PDF dengan Furigana Reader».

**Kaedah 3: Pengesanan automatik**  
Apabila «Pengesanan pintar PDF» didayakan dalam tetapan, sambungan melencongkan URL `.pdf` ke pembaca terbina dalam. Jika PDF dikesan tetapi tidak dilencongkan (cth. pemapar terbina dalam Chrome), anda akan melihat pemberitahuan dan gesaan untuk membukanya dalam Furigana Reader.

### Ciri pembaca PDF

- **Anotasi furigana** — Semua ciri furigana berfungsi pada teks PDF, termasuk mod seluruh halaman dan tooltip apungan
- **Lima mod furigana** — Hiragana, katakana, romaji, hanya apungan, dan Mati
- **Kamus klik** — Klik mana-mana perkataan untuk melihat takrifan JMdict (dalam PDF klik digunakan berbanding apungan untuk pengalaman membaca tanpa gangguan)
- **Bar alat pilihan** — Pilih teks untuk bercakap, terjemah, atau salin
- **Bar sisi** — Rangka kandungan dan imej kecil halaman
- **Carian** — Carian teks penuh dalam PDF
- **Tema** — Tema membaca gelap, terang, dan sepia
- **Zum** — Pelbagai tahap zum termasuk furigana adaptif zum
- **Pintasan papan kekunci** — Anak panah untuk navigasi, +/- untuk zum, Ctrl/Cmd+F untuk carian

---

## Pertuturan pilihan dan karaoke

Ciri pertuturan pilihan membolehkan anda memilih sebarang teks bahasa Jepun dan membacakannya dengan satu klik — sesuai untuk latihan sebutan ayat dan membaca.

**Kaedah 1: Bar alat pilihan**  
Pilih teks bahasa Jepun dengan tetikus. Bar padat muncul berhampiran pilihan dengan butang 🔊 bercakap dan 🌐 terjemah. Klik bercakap. Semasa teks dibacakan, setiap perkataan atau aksara diserlahkan secara masa nyata (kesan karaoke).

**Kaedah 2: Menu klik kanan**  
Selepas memilih teks bahasa Jepun, klik kanan dan pilih «Furigana Reader > Baca pilihan dengan kuat».

**Kaedah 3: Pintasan papan kekunci**  
Pilih teks dan tekan `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Petua:** Serlahan karaoke berfungsi paling baik apabila pelayar menyokong peristiwa sempadan perkataan TTS. Jika tidak disokong, sambungan menggunakan sandaran berasaskan masa untuk serlahan lancar.

---

## Terjemahan

Pilih sebarang teks di halaman dan gunakan ciri terjemahan untuk mendapatkan terjemahan serta-merta.

**Kaedah 1: Bar alat pilihan**  
Pilih teks, kemudian klik butang 🌐 terjemah di bar alat. Gelembung terjemahan muncul di bawah dengan hasil dan butang salin.

**Kaedah 2: Menu klik kanan**  
Pilih teks, klik kanan dan pilih «Furigana Reader > Terjemah pilihan».

**Kaedah 3: Pintasan papan kekunci**  
Pilih teks dan tekan `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Enjin terjemahan:**
- **Bing Translate** (lalai) — Microsoft Translator
- **Google Translate** — Google

Kedua-duanya menyokong **108 bahasa sasaran**.

Anda boleh menukar enjin terjemahan dan bahasa sasaran dalam tetapan sambungan. Bahasa sasaran dikesan automatik daripada bahasa pelayar.

> **Petua:** Klik di luar bar alat atau gelembung untuk menutupnya.

---

## Pintasan papan kekunci

| Pintasan | Pintasan Mac | Tindakan |
|----------|--------------|----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Togol anotasi furigana hidup/mati |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Baca teks terpilih dengan kuat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Terjemah teks terpilih |

> **Petua:** Sesuaikan pintasan ini dalam Chrome di `chrome://extensions/shortcuts`.

---

## Panduan tetapan

| Tetapan | Penerangan |
|---------|------------|
| **Dayakan furigana** | Suis utama untuk menghidupkan atau mematikan ciri anotasi furigana |
| **Furigana seluruh halaman** | Apabila didayakan, memaparkan furigana untuk semua kanji (boleh menjejaskan susun atur halaman) |
| **Mod apungan** | Pilih tingkah laku apungan: Kamus (bacaan + takrifan + JLPT + audio), Bacaan (bacaan + audio), atau Mati |
| **Gaya furigana** | Hiragana, katakana, atau romaji |
| **Kadar pertuturan** | Melaraskan kelajuan pembacaan ayat |
| **Enjin terjemahan** | Pilih Bing Translate atau Google Translate |
| **Bahasa sasaran** | Tetapkan bahasa sasaran terjemahan (dikesan automatik daripada bahasa pelayar) |
| **Pengesanan pintar PDF** | Apabila didayakan, melencongkan URL PDF ke pembaca terbina dalam secara automatik dan memaparkan pemberitahuan apabila PDF dikesan |

---

## Soalan lazim

**T: Mengapa tidak berfungsi di sesetengah halaman?**  
J: Atas sebab keselamatan, sambungan tidak boleh berjalan di halaman khas seperti `chrome://`, tetapan pelayar, atau Chrome Web Store.

**T: Bagaimana jika furigana tidak tepat?**  
J: Sesetengah perkataan jarang atau bacaan khas (熟字訓) mungkin mempunyai ralat. Kami sentiasa menambah baik. Sila kongsi kes khusus untuk membantu kami.

**T: Tiada bunyi daripada TTS?**  
J: Semak kelantangan sistem dan pastikan pakej suara bahasa Jepun dipasang. Sokongan pertuturan berbeza mengikut pelayar dan sistem pengendalian.

**T: Mod seluruh halaman menjejaskan susun atur?**  
J: Furigana memerlukan ruang tambahan yang mungkin menjejaskan susun atur asal. Jika mengganggu, matikan mod seluruh halaman dan gunakan tooltip apungan.

**T: Terjemahan tidak berfungsi?**  
J: Terjemahan memerlukan sambungan internet. Jika Bing Translate gagal, cuba tukar ke Google Translate dalam tetapan. Sesetengah persekitaran rangkaian mungkin menyekat akses kepada perkhidmatan terjemahan.

**T: Bagaimana membuka PDF dengan Furigana Reader?**  
J: Anda boleh membuka PDF beberapa cara: klik «Buka pembaca PDF» dalam popup, klik kanan pautan PDF dan pilih «Buka PDF dengan Furigana Reader», atau dayakan «Pengesanan pintar PDF» dalam tetapan untuk melencongkan URL PDF ke pembaca terbina dalam secara automatik.

**T: Pengesanan pintar PDF didayakan tetapi sesetengah PDF tidak dilencongkan?**  
J: Lencongan automatik berfungsi untuk URL yang berakhir dengan `.pdf`. Untuk PDF dihidangkan tanpa sambungan `.pdf` atau dipapar dalam pemapar terbina dalam Chrome, anda akan melihat pemberitahuan dan lencana yang menggesa membuka dalam Furigana Reader.

**T: Bolehkah saya menggunakan kamus luar talian?**  
J: Ya. Kamus JMdict (lebih 180,000 entri) dibundel sepenuhnya dalam sambungan. Semua carian dilakukan secara tempatan tanpa sambungan rangkaian.

---

## Pautan berkaitan

- [Dasar privasi](../privacy-policy)
- [Sokongan & maklum balas](../support)

---
