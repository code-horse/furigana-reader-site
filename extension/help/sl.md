---
layout: bare
title: Razširitev Furigana Reader - Uporabniški priročnik
lang: sl
---

# Furigana Reader - Uporabniški priročnik

> Različica: v1.4.3

## Uvod

Furigana Reader je razširitev brskalnika za učenje japonščine. Z WASM morfološkim analizatorjem (Lindera + IPAdic) in rezervo v JavaScriptu natančno doda furigano (bralne oznake) nad znake kanji na spletnih straneh in v datotekah PDF. Vključuje tudi vgrajen japonski slovar, besedilo v govor in prevod — lažje se učite izgovorjave.

---

## Glavne funkcije

- **Furigana za celo stran** — Z enim klikom furigana za vse znake kanji na strani
- **Slovar ob lebdenju** — Z miško nad označenimi znaki: definicije JMdict (180.000+ zapisov), branja, značke ravni JLPT (N5–N1) in gumbi za izgovorjavo; način Slovar / Branje / Izklop
- **Bralnik PDF** — Vgrajen bralnik PDF z furigano, slovarjem, govorom in prevodom; povleci in spusti, nalaganje z URL in samodejno zaznavanje PDF s pametnim preusmerjanjem
- **Trije slogi furigane** — Hiragana, Katakana in Romaji
- **Razdelitev okurigane** — Natančno loči okurigano (送り仮名) od stebla kanji
- **Podpora jukujikun** — Pravilna branja za večznakovne sestavke s posebnimi branji (熟字訓)
- **Besedilo v govor** — Klik na ikono zvočnika za izgovorjavo
- **Govor izbora s karaoke učinkom** — Izberite japonsko besedilo; pri izboru se prikaže orodna vrstica z govorom in prevodom; ob predvajanju se besede ali znaki v realnem času poudarijo (karaoke), usklajeno z zvokom
- **Prevod izbora** — Izberite besedilo, kliknite prevod v vrstici za takojšen prevod prek Bing ali Google Translate v vgrajenem oblačku
- **Bližnjice na tipkovnici** — Hiter dostop do osnovnih funkcij z nastavljivimi bližnjicami
- **Večjezični vmesnik** — 38 jezikov vmesnika

---

## Uporaba

### Korak 1: Namestitev razširitve

Namestite **Furigana Reader** iz [Chrome Web Store](https://chromewebstore.google.com/) ali jo naložite lokalno v razvijalskem načinu.

### Korak 2: Odprite poljubno spletno stran

Obiščite stran z japonsko vsebino.

### Korak 3: Vklop furigane

Kliknite ikono razširitve v orodni vrstici. Vklopite »Omogoči furigano«, nato »Furigana za celo stran«, da označite vse kanji. Lahko tudi plavajoči gumb spodaj desno.

### Korak 4: Ogled furigane

Z miško nad znake za namige z branji in definicijami iz slovarja. Klik na zvočnik za izgovorjavo.

### Korak 5: Govor in prevod izbora

Z miško izberite japonsko besedilo. Pri izboru se prikaže kompaktna vrstica z dvema gumboma:
- **🔊 Govori** — Prebere izbor naglas s karaoke poudarjanjem
- **🌐 Prevedi** — Pokaže oblaček s prevodom pod vrstico

Lahko tudi desni klik: »Furigana Reader > Preberi izbor naglas« ali »Furigana Reader > Prevedi izbor«.

> **Nasvet:** Kliknite ikono razširitve za nastavitve: slog furigane, način ob lebdenju, hitrost govora, prevajalski mehanizem itd.

---

## Slovar ob lebdenju

Razširitev vključuje vgrajen japonski slovar na osnovi JMdict (več kot 180.000 zapisov). V nastavitvah izberete način ob lebdenju:

| Način | Obnašanje |
|-------|-----------|
| **Slovar** | Ob lebdenju: branje + definicija + JLPT + gumb za izgovorjavo |
| **Branje** | Ob lebdenju: branje + gumb za izgovorjavo (brez definicij) |
| **Izklop** | Brez učinka ob lebdenju |

V načinu **Slovar** namig prikaže:
- Besedo in njeno branje (furigana)
- Gumb za izgovorjavo (klik za predvajanje)
- Japonske definicije iz JMdict
- Značko ravni JLPT (N5–N1), če je na voljo

> **Nasvet:** Podatki slovarja se naložijo po potrebi, ko je vklopljen način Slovar, in se sprostijo pri drugih načinih za varčevanje s pomnilnikom.

---

## Bralnik PDF

Furigana Reader vključuje vgrajen bralnik PDF za dokumente z furigano, slovarjem, govorom in prevodom — enake funkcije kot na spletu, zdaj tudi za PDF.

### Odpiranje PDF

**Način 1: Iz pojavnega okna**  
Kliknite ikono razširitve, nato »Odpri bralnik PDF«. Povlecite datoteko PDF ali »Izberi datoteko«. Lahko prilepite URL PDF.

**Način 2: Kontekstni meni**  
Desni klik na povezavo `.pdf` in »Odpri PDF s Furigana Reader«.

**Način 3: Samodejno zaznavanje**  
Če je v nastavitvah vklopljeno »Pametno zaznavanje PDF«, razširitev samodejno preusmeri URL, ki se končajo z `.pdf`, v vgrajeni bralnik. Če PDF ni preusmerjen (npr. vgrajeni pregledovalnik Chrome), se prikažejo obvestila za odpiranje v Furigana Reader.

### Funkcije bralnika PDF

- **Furigana** — Vse funkcije furigane na besedilu PDF, vključno s celotno stranjo in namigi
- **Pet načinov furigane** — Hiragana, Katakana, Romaji, Samo lebdenje in Izklop
- **Slovar s klikom** — Klik na besedo za definicijo JMdict (pri PDF namesto lebdenja klik za mirnejše branje)
- **Vrstica izbora** — Izberite besedilo za govor, prevod ali kopiranje
- **Stranska vrstica** — Kazalo in sličice strani
- **Iskanje** — Iskanje po celotnem besedilu PDF
- **Teme** — Temna, svetla in sepia
- **Povečava** — Več ravni povečave, vključno s furigano, prilagojeno povečavi
- **Bližnjice** — Puščice za krmarjenje, +/- za povečavo, Ctrl/Cmd+F za iskanje

---

## Govor izbora in karaoke

Govor izbora omogoča izbrati japonsko besedilo in ga s klikom poslušati — primerno za izgovorjavo stavkov in branje.

**Način 1: Vrstica izbora**  
Izberite japonsko besedilo. Pojavi se vrstica z gumbom 🔊 govori in 🌐 prevedi. Kliknite govori; med predvajanjem se beseda ali znak v realnem času poudari (karaoke).

**Način 2: Desni klik**  
Po izboru: desni klik in »Furigana Reader > Preberi izbor naglas«.

**Način 3: Bližnjica**  
Izberite besedilo in pritisnite `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) za govor.

> **Nasvet:** Karaoke deluje najbolje, če brskalnik podpira TTS dogodke mej besed. Sicer razširitev uporabi časovno nadomestno poudarjanje.

---

## Prevod

Izberite poljubno besedilo na strani in uporabite prevod za takojšnje rezultate.

**Način 1: Vrstica izbora**  
Izberite besedilo, kliknite 🌐 prevedi. Pod vrstico se prikaže oblaček z rezultatom in gumbom za kopiranje.

**Način 2: Desni klik**  
Izbor besedila, desni klik in »Furigana Reader > Prevedi izbor«.

**Način 3: Bližnjica**  
Izberite besedilo in pritisnite `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) za prevod.

**Prevajalski mehanizmi:**
- **Bing Translate** (privzeto) — Microsoft Translator
- **Google Translate** — Google

Oba podpirata **108 ciljnih jezikov**.

Mehanizem in ciljni jezik spremenite v nastavitvah razširitve. Ciljni jezik se samodejno zazna iz jezika brskalnika.

> **Nasvet:** Klik izven vrstice ali oblačka jih zapre.

---

## Bližnjice na tipkovnici

| Bližnjica | Mac | Dejanje |
|-----------|-----|---------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Vklop/izklop furiganovih oznak |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Govori izbrano besedilo |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Prevedi izbrano besedilo |

> **Nasvet:** Bližnjice prilagodite v Chrome na `chrome://extensions/shortcuts`.

---

## Vodnik po nastavitvah

| Nastavitev | Opis |
|------------|------|
| **Omogoči furigano** | Glavno stikalo za funkcijo furigane |
| **Furigana za celo stran** | Furigana za vse kanji (lahko vpliva na postavitev) |
| **Način ob lebdenju** | Obnašanje: Slovar (branje + definicije + JLPT + zvok), Branje (branje + zvok) ali Izklop |
| **Slog furigane** | Hiragana, Katakana ali Romaji |
| **Hitrost govora** | Hitrost branja stavkov |
| **Prevajalski mehanizem** | Bing Translate ali Google Translate |
| **Ciljni jezik** | Jezik prevoda (samodejno iz jezika brskalnika) |
| **Pametno zaznavanje PDF** | Samodejno preusmerjanje URL PDF v vgrajeni bralnik in obvestila ob zaznanem PDF |

---

## Pogosta vprašanja

**V: Zakaj na nekaterih straneh ne deluje?**  
O: Zaradi varnosti razširitve ne delujejo na posebnih straneh, kot so `chrome://`, nastavitve brskalnika ali Chrome Web Store.

**V: Kaj če je furigana netočna?**  
O: Redke besede ali posebna branja (熟字訓) lahko vsebujejo napake. Izboljšujemo; sporočite konkretne primere.

**V: Ni zvoka pri TTS?**  
O: Preverite sistemsko glasnost in nameščene japonske glasove. Podpora se razlikuje po brskalniku in OS.

**V: Način cele strani vpliva na postavitev?**  
O: Furigana potrebuje prostor in lahko spremeni stran. Če moti, izklopite celostranski način in uporabite namige ob lebdenju.

**V: Prevod ne deluje?**  
O: Potrebna je internetna povezava. Če Bing ne uspe, poskusite Google v nastavitvah. Nekatera omrežja blokirajo storitve.

**V: Kako odprem PDF s Furigana Reader?**  
O: »Odpri bralnik PDF« v pojavnem oknu, desni klik na povezavo PDF »Odpri PDF s Furigana Reader«, ali vklopite »Pametno zaznavanje PDF« za samodejno preusmeritev.

**V: Pametno zaznavanje je vklopljeno, a nekateri PDF se ne preusmerijo?**  
O: Samodejno preusmerjanje velja za URL, ki se končajo z `.pdf`. Za PDF brez končnice ali v vgrajenem pregledovalniku Chrome se prikaže obvestilo za odpiranje v Furigana Reader.

**V: Ali lahko uporabljam slovar brez povezave?**  
O: Da. Slovar JMdict (180.000+ zapisov) je v celoti v razširitvi. Vsa iskanja potekajo lokalno brez omrežja.

---

## Sorodne povezave

- [Pravilnik o zasebnosti](../privacy-policy)
- [Podpora in povratne informacije](../support)

---
