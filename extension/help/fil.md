---
layout: bare
title: Furigana Reader Extension - Gabay ng gumagamit
lang: fil
---

# Furigana Reader - Gabay ng gumagamit

> Bersyon: v2.0.0

## Panimula

Ang Furigana Reader ay isang extension sa browser para sa mga natututo ng Hapones. Gamit ang WASM morphological analyzer (Lindera) na may fallback sa JavaScript, tumpak nitong idinadagdag ang furigana (mga tala sa pagbasa) sa mga karakter na kanji sa mga pahina sa web, upang mas madaling matutunan ang bigkas ng Hapones.

---

## Mga pangunahing tampok

- **Anotasyon sa piniling teksto** — Pumili ng tekstong Hapones sa mga pahina upang awtomatikong ipakita ang furigana at mga button ng pagsasalita
- **Buong pahina na furigana** — Magdagdag ng furigana sa lahat ng kanji sa isang click
- **Text-to-speech** — I-click ang icon ng speaker upang marinig ang bigkas
- **Pagbasa ng piniling bahagi** — Pumili ng teksto, i-click ang lumulutang na button o i-right-click at piliin ang «Basahin nang malakas ang pinili»
- **Mga tooltip kapag naka-hover** — I-hover ang mga may anotasyon upang makita ang furigana at mga button ng bigkas
- **Iba’t ibang istilo ng furigana** — Suporta para sa Hiragana, Katakana, at Romaji
- **Maraming wika sa interface** — 38 na wika ng interface

---

## Paano gamitin

### Hakbang 1: I-install ang extension

I-install ang **Furigana Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang anumang pahina

Bisitahin ang anumang pahinang may nilalamang Hapones.

### Hakbang 3: Pumili ng teksto o gamitin ang lumulutang na button

Pumili ng tekstong Hapones na nais mong anotahan, o i-click ang lumulutang na button sa kanang ibaba upang paganahin ang buong pahina na furigana.

### Hakbang 4: Tingnan ang furigana

I-hover ang mga karakter upang makita ang mga tooltip; i-click ang icon ng speaker upang marinig ang bigkas.

### Hakbang 5: Basahin ang piniling teksto

Pumili ng tekstong Hapones gamit ang mouse, i-click ang lumulutang na speaker, o i-right-click at piliin ang «Basahin nang malakas ang pinili».

> **Tip:** I-click ang icon ng extension sa toolbar upang buksan ang mga setting at ayusin ang istilo ng furigana, bilis ng pagsasalita, atbp.

---

## Gabay sa mga setting

| Setting | Paglalarawan |
|---------|----------------|
| **Paganahin ang furigana** | Pangunahing switch para buksan o isara ang furigana |
| **Buong pahina na furigana** | Kapag naka-on, ipinapakita ang furigana sa lahat ng kanji (maaaring makaapekto sa layout) |
| **Istilo ng furigana** | Pumili ng Hiragana, Katakana, o Romaji |
| **Bilis ng pagsasalita** | Ayusin ang bilis ng pagbasa ng pangungusap |
| **Mga tooltip kapag naka-hover** | Ipakita ang furigana kapag naka-hover ang mouse |

---

## Mga madalas itanong

**T: Bakit hindi ito gumagana sa ilang pahina?**  
S: Dahil sa seguridad, hindi maaaring tumakbo ang mga extension sa mga espesyal na pahina tulad ng `chrome://`, mga setting ng browser, o Chrome Web Store.

**T: Paano kung hindi tumpak ang furigana?**  
S: Maaaring may mali ang ilang bihirang salita o espesyal na pagbasa (熟字訓). Patuloy naming pinapabuti ito — ibahagi ang mga partikular na halimbawa.

**T: Walang tunog mula sa text-to-speech?**  
S: Suriin ang volume ng sistema at kung naka-install ang mga boses na Hapones. Iba-iba ang suporta ayon sa browser at OS.

**T: Naaapektuhan ba ng buong pahina ang layout?**  
S: Kailangan ng furigana ng karagdagang espasyo at maaaring baguhin ang layout. Kung nakakaabala, i-off ang buong pahina at gumamit ng mga tooltip sa halip.

---

## Kaugnay na mga link

- [Patakaran sa privacy](../privacy-policy)
- [Suporta at feedback](../support)

---
</think>


<｜tool▁calls▁begin｜><｜tool▁call▁begin｜>
StrReplace