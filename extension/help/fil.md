---
layout: bare
title: Furigana Reader Extension - Gabay ng gumagamit
lang: fil
---

# Furigana Reader - Gabay ng gumagamit

> Bersyon: v1.4.3

## Panimula

Ang Furigana Reader ay isang extension sa browser para sa mga natututo ng Hapones. Gamit ang WASM morphological analyzer (Lindera + IPAdic) na may fallback sa JavaScript, tumpak nitong idinadagdag ang furigana (mga tala sa pagbasa) sa mga karakter na kanji sa mga pahina sa web at sa mga PDF. May built-in ding Japanese dictionary, text-to-speech, at pagsasalin — upang mas madaling matutunan ang bigkas ng Hapones.

---

## Mga pangunahing tampok

- **Buong pahina na furigana** — Magdagdag ng furigana sa lahat ng kanji sa isang click
- **Dictionary kapag naka-hover** — I-hover ang mga may anotasyon upang makita ang mga kahulugan mula sa JMdict (180K+ na entry), mga pagbasa, mga badge ng antas ng JLPT (N5–N1), at mga button ng bigkas; pumili sa pagitan ng Dictionary, Reading, o Off
- **PDF Reader** — Built-in na PDF reader na may furigana, dictionary, speech, at pagsasalin; sumusuporta sa drag & drop, pag-load ng URL, at awtomatikong pagtukoy ng PDF na may smart redirect
- **Tatlong istilo ng furigana** — Hiragana, Katakana, at Romaji
- **Paghahati ng okurigana** — Tumpak na hinahati ang okurigana (送り仮名) mula sa mga stem ng kanji
- **Suporta sa jukujikun** — Tamang pagbasa para sa mga compound na multi-kanji na may espesyal na pagbasa (熟字訓)
- **Text-to-speech** — I-click ang icon ng speaker upang marinig ang bigkas ng Hapones
- **Speech sa pinili na may karaoke** — Pumili ng anumang tekstong Hapones; may lumilitaw na compact toolbar na may speak at translate; ang speech ay may real-time na salita-sa-salita o character-sa-character na highlight (karaoke effect) na naka-sync sa audio
- **Pagsasalin ng pinili** — Pumili ng anumang teksto, i-click ang translate sa toolbar para sa agarang pagsasalin sa pamamagitan ng Bing o Google Translate, ipinapakita sa inline na bubble
- **Mga shortcut sa keyboard** — Mabilis na access sa core features sa pamamagitan ng mga nako-customize na shortcut
- **Maraming wika sa interface** — 38 na wika ng interface

---

## Paano gamitin

### Hakbang 1: I-install ang extension

I-install ang **Furigana Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang anumang pahina sa web

Bisitahin ang anumang pahina na may nilalamang Hapones.

### Hakbang 3: Paganahin ang furigana

I-click ang icon ng extension sa toolbar. I-on ang «Enable Furigana», pagkatapos i-on ang «Whole Page Furigana» upang i-annotate ang lahat ng kanji. Maaari mo ring gamitin ang lumulutang na button sa kanang ibaba.

### Hakbang 4: Tingnan ang furigana

I-hover ang mga character upang makita ang mga tooltip na may mga pagbasa at kahulugan mula sa dictionary. I-click ang icon ng speaker upang marinig ang bigkas.

### Hakbang 5: Basahin nang malakas at isalin ang piniling teksto

Pumili ng tekstong Hapones gamit ang mouse. May lumilitaw na compact toolbar malapit sa pinili na may dalawang button:
- **🔊 Speak** — Binibigkas ang piniling teksto na may karaoke-style na highlight
- **🌐 Translate** — Nagpapakita ng inline na translation bubble sa ilalim ng toolbar

Maaari ka ring mag-right-click at piliin ang «Furigana Reader > Read aloud selection» o «Furigana Reader > Translate Selection».

> **Tip:** I-click ang icon ng extension upang buksan ang panel ng mga setting at ayusin ang istilo ng furigana, hover mode, bilis ng speech, translation engine, at iba pa.

---

## Hover Dictionary

Kasama sa extension ang built-in na Japanese dictionary na pinapagana ng JMdict (180,000+ na entry). Maaari kang pumili ng hover mode sa mga setting:

| Mode | Kilos |
|------|-------|
| **Dictionary** | Ang hover ay nagpapakita ng pagbasa + kahulugan + antas ng JLPT + button ng bigkas |
| **Reading** | Ang hover ay nagpapakita ng pagbasa + button ng bigkas (walang mga kahulugan) |
| **Off** | Walang epekto sa hover |

Sa **Dictionary** mode, ang tooltip ay nagpapakita ng:
- Ang salita at ang pagbasa nito (furigana)
- Button ng bigkas (i-click upang pakinggan)
- Mga kahulugan sa Hapones mula sa JMdict
- Badge ng antas ng JLPT (N5–N1) kapag available

> **Tip:** Ang data ng dictionary ay na-load on-demand kapag naka-on ang Dictionary mode, at ina-unload kapag lumipat sa ibang mode upang makatipid ng memory.

---

## PDF Reader

Kasama sa Furigana Reader ang built-in na PDF reader upang magbasa ng mga dokumentong PDF na may furigana, dictionary, speech, at pagsasalin — ang mga feature na ginagamit mo sa web pages, available na rin para sa PDF.

### Pagbubukas ng PDF

**Paraan 1: Mula sa popup**  
I-click ang icon ng extension, pagkatapos i-click ang «Open PDF Reader». I-drag & drop ang PDF file o i-click ang «Choose File» upang buksan ang lokal na PDF. Maaari mo ring i-paste ang URL ng PDF.

**Paraan 2: Context menu**  
I-right-click ang anumang `.pdf` link sa pahina at piliin ang «Open PDF with Furigana Reader».

**Paraan 3: Awtomatikong pagtukoy**  
Kapag naka-on ang «PDF Smart Detection» sa mga setting, awtomatikong ina-redirect ng extension ang mga `.pdf` URL sa built-in reader. Kapag natukoy ang PDF ngunit hindi na-redirect (hal. built-in viewer ng Chrome), makikita mo ang mga notification at prompt upang buksan ito sa Furigana Reader.

### Mga feature ng PDF Reader

- **Furigana annotations** — Gumagana ang lahat ng furigana features sa teksto ng PDF, kasama ang whole-page mode at hover tooltips
- **Limang furigana mode** — Hiragana, Katakana, Romaji, Hover only, at Off
- **Click dictionary** — I-click ang anumang salita upang makita ang kahulugan mula sa JMdict (sa PDF, click ang ginagamit sa halip na hover para sa distraction-free na pagbabasa)
- **Selection toolbar** — Pumili ng teksto upang magsalita, magsalin, o kopyahin
- **Sidebar** — Outline ng table of contents at mga thumbnail ng pahina
- **Search** — Full-text search sa PDF
- **Themes** — Dark, Light, at Sepia na mga tema sa pagbabasa
- **Zoom** — Maraming antas ng zoom kasama ang zoom-adaptive na furigana
- **Mga shortcut sa keyboard** — Arrow keys para sa navigation, +/- para sa zoom, Ctrl/Cmd+F para sa search

---

## Selection speech at karaoke

Ang selection speech ay nagpapahintulot na pumili ng anumang tekstong Hapones at basahin ito nang malakas sa isang click — mainam para sa bigkas ng pangungusap at pagsasanay sa pagbabasa.

**Paraan 1: Selection toolbar**  
Pumili ng tekstong Hapones. May lumilitaw na compact toolbar na may 🔊 speak at 🌐 translate. I-click ang speak button. Habang binibigkas ang teksto, bawat salita o character ay naka-highlight nang real time (karaoke effect).

**Paraan 2: Right-click menu**  
Pagkatapos pumili ng tekstong Hapones, mag-right-click at piliin ang «Furigana Reader > Read aloud selection».

**Paraan 3: Shortcut sa keyboard**  
Pumili ng teksto at pindutin ang `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) upang magsalita.

> **Tip:** Pinakamahusay ang karaoke highlight kapag sinusuportahan ng browser ang TTS word boundary events. Kung hindi, gumagamit ang extension ng timing-based na fallback para sa maayos na highlight.

---

## Pagsasalin

Pumili ng anumang teksto sa pahina at gamitin ang translation feature para sa agarang pagsasalin.

**Paraan 1: Selection toolbar**  
Pumili ng teksto, pagkatapos i-click ang 🌐 translate sa toolbar. May lumilitaw na translation bubble sa ibaba na may resulta at copy button.

**Paraan 2: Right-click menu**  
Pumili ng teksto, mag-right-click at piliin ang «Furigana Reader > Translate Selection».

**Paraan 3: Shortcut sa keyboard**  
Pumili ng teksto at pindutin ang `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) upang magsalin.

**Mga translation engine:**
- **Bing Translate** (default) — Pinapagana ng Microsoft Translator
- **Google Translate** — Pinapagana ng Google

Parehong sumusuporta ang dalawang engine sa **108 target languages**.

Maaari mong palitan ang translation engine at target language sa mga setting ng extension. Awtomatikong natutukoy ang target language mula sa wika ng browser.

> **Tip:** I-click ang kahit saan sa labas ng toolbar o bubble upang isara ang mga ito.

---

## Mga shortcut sa keyboard

| Shortcut | Mac shortcut | Aksyon |
|----------|--------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | I-toggle ang furigana on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Basahin nang malakas ang piniling teksto |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Isalin ang piniling teksto |

> **Tip:** Maaari mong i-customize ang mga shortcut sa Chrome sa `chrome://extensions/shortcuts`.

---

## Gabay sa mga setting

| Setting | Paglalarawan |
|---------|--------------|
| **Enable Furigana** | Master switch para paganahin o huwag paganahin ang furigana |
| **Whole Page Furigana** | Kapag naka-on, nagpapakita ng furigana para sa lahat ng kanji (maaaring makaapekto sa layout ng pahina) |
| **Hover Mode** | Pumili ng kilos sa hover: Dictionary (pagbasa + mga kahulugan + JLPT + audio), Reading (pagbasa + audio), o Off |
| **Furigana Style** | Pumili sa pagitan ng Hiragana, Katakana, o Romaji |
| **Speech Rate** | Ayusin ang bilis ng pagbabasa ng pangungusap |
| **Translation Engine** | Pumili sa pagitan ng Bing Translate at Google Translate |
| **Target Language** | Itakda ang target language ng pagsasalin (awtomatikong natutukoy mula sa wika ng browser) |
| **PDF Smart Detection** | Kapag naka-on, awtomatikong ina-redirect ang mga PDF URL sa built-in reader at nagpapakita ng notification kapag natukoy ang PDF |

---

## FAQ

**Q: Bakit hindi ito gumagana sa ilang pahina?**  
A: Dahil sa seguridad, hindi maaaring tumakbo ang mga extension sa mga espesyal na pahina tulad ng `chrome://`, mga setting ng browser, o Chrome Web Store.

**Q: Paano kung hindi tumpak ang furigana?**  
A: Maaaring magkamali ang ilang bihirang salita o espesyal na pagbasa (熟字訓). Patuloy naming pinapabuti. Pakibahagi ang mga partikular na kaso upang matulungan kaming umunlad.

**Q: Walang tunog mula sa text-to-speech?**  
A: Pakitingnan ang volume ng system at tiyaking naka-install ang mga Japanese voice pack. Nag-iiba ang suporta sa pagitan ng mga browser at operating system.

**Q: Naaapektuhan ng whole page mode ang layout?**  
A: Ang furigana ay nangangailangan ng karagdagang espasyo, na maaaring makaapekto sa orihinal na layout. Kung naaabala ang pagbabasa, i-off ang whole page mode at gumamit ng hover tooltips sa halip.

**Q: Hindi gumagana ang pagsasalin?**  
A: Ang pagsasalin ay nangangailangan ng koneksyon sa internet. Kung nabigo ang Bing Translate, subukan ang Google Translate sa mga setting. Maaaring harangan ng ilang network ang access sa mga serbisyo ng pagsasalin.

**Q: Paano ko bubuksan ang PDF gamit ang Furigana Reader?**  
A: Maaari mong buksan ang PDF sa maraming paraan: i-click ang «Open PDF Reader» sa popup, i-right-click ang PDF link at piliin ang «Open PDF with Furigana Reader», o paganahin ang «PDF Smart Detection» sa mga setting upang awtomatikong i-redirect ang mga PDF URL sa built-in reader.

**Q: Naka-on ang PDF Smart Detection ngunit hindi na-redirect ang ilang PDF?**  
A: Ang auto-redirect ay gumagana para sa mga URL na nagtatapos sa `.pdf`. Para sa mga PDF na inihahatid nang walang `.pdf` extension o tinitingnan sa built-in viewer ng Chrome, makikita mo ang notification at badge na nag-uudyok na buksan ito sa Furigana Reader.

**Q: Maaari ko bang gamitin ang dictionary offline?**  
A: Oo. Ang JMdict dictionary (180,000+ na entry) ay buong nakabundle sa extension. Lahat ng lookup ay ginagawa nang lokal nang walang network connection.

---

## Kaugnay na mga link

- [Patakaran sa privacy](../privacy-policy)
- [Suporta at feedback](../support)

---
