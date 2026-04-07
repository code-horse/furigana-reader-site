---
layout: bare
title: Rozšírenie Furigana Reader - Používateľská príručka
lang: sk
---

# Furigana Reader - Používateľská príručka

> Verzia: v1.4.1

## Úvod

Furigana Reader je rozšírenie prehliadača pre študentov japončiny. Pomocou WASM morfologického analyzátora (Lindera + IPAdic) s zálohou v JavaScripte presne pridáva furigana (čítacie poznámky) ku znakom kanji na webových stránkach a v súboroch PDF. Obsahuje aj vstavaný japonský slovník, prevod textu na reč (TTS) a preklad — aby ste sa ľahšie naučili výslovnosť.

---

## Hlavné funkcie

- **Furigana celej stránky** — Pridajte furigana všetkým znakom kanji jedným kliknutím
- **Slovník pri ukázaní** — Najeďte na anotované znaky pre definície z JMdict (180 000+ záznamov), čítania, odznaky úrovne JLPT (N5–N1) a tlačidlá výslovnosti; vyberte režim Dictionary, Reading alebo Off
- **Čítačka PDF** — Vstavaná čítačka PDF s furiganou, slovníkom, rečou a prekladom; podpora pretiahnutia súboru, načítania z URL a automatického rozpoznania PDF so smart presmerovaním
- **Tri štýly čítania** — Hiragana, Katakana a Romaji
- **Rozdelenie okurigany** — Presne oddelí okuriganu (送り仮名) od kmeňa kanji
- **Podpora jukudžikunu** — Správne čítania pre viacznakové zloženiny so špeciálnym čítaním (熟字訓)
- **Prevod textu na reč** — Kliknite na ikonu reproduktora pre japonskú výslovnosť
- **Reč výberu s karaoke efektom** — Vyberte japonský text; zobrazí sa kompaktný panel s tlačidlami reči a prekladu; počas prehrávania sa slová alebo znaky v reálnom čase zvýrazňujú (karaoke) synchronizovane s audiom
- **Preklad výberu** — Vyberte text, kliknite na preklad na paneli pre okamžitý výsledok cez Bing alebo Google Translate v inline bublinke
- **Klávesové skratky** — Rýchly prístup k hlavným funkciám cez prispôsobiteľné skratky
- **Viacjazyčné rozhranie** — 38 jazykov rozhrania

---

## Použitie

### Krok 1: Nainštalujte rozšírenie

Nainštalujte **Furigana Reader** z [Chrome Web Store](https://chromewebstore.google.com/) alebo ho načítajte lokálne v režime vývojára.

### Krok 2: Otvorte ľubovoľnú stránku

Navštívte stránku s japonským obsahom.

### Krok 3: Zapnite furiganu

Kliknite na ikonu rozšírenia na paneli nástrojov. Zapnite „Enable Furigana“, potom „Whole Page Furigana“ pre anotáciu všetkých kanji. Môžete použiť aj plávajúce tlačidlo vpravo dole.

### Krok 4: Prezerajte furiganu

Najeďte myšou na znaky pre nápovedy s čítaním a definíciami zo slovníka. Kliknite na ikonu reproduktora pre výslovnosť.

### Krok 5: Prečítajte a preložte výber

Vyberte japonský text myšou. Pri výbere sa zobrazí kompaktný panel s dvoma tlačidlami:
- **🔊 Speak** — Prečíta výber nahlas so zvýraznením v štýle karaoke
- **🌐 Translate** — Zobrazí inline bublinu prekladu pod panelom

Môžete aj pravým klikom zvoliť „Furigana Reader > Read aloud selection“ alebo „Furigana Reader > Translate Selection“.

> **Tip:** Kliknite na ikonu rozšírenia pre nastavenia: štýl furigany, režim ukázania, rýchlosť reči, prekladový engine a ďalšie.

---

## Slovník pri ukázaní

Rozšírenie obsahuje vstavaný japonský slovník na báze JMdict (180 000+ záznamov). V nastaveniach vyberiete režim ukázania:

| Režim | Správanie |
|-------|-----------|
| **Dictionary** | Ukázanie: čítanie + definícia + JLPT + tlačidlo výslovnosti |
| **Reading** | Ukázanie: čítanie + tlačidlo výslovnosti (bez definícií) |
| **Off** | Žiadny efekt pri ukázaní |

V režime **Dictionary** nápoveda zobrazuje:
- Slovo a jeho čítanie (furigana)
- Tlačidlo výslovnosti (klik pre zvuk)
- Japonské definície z JMdict
- Odznak úrovne JLPT (N5–N1), ak je k dispozícii

> **Tip:** Dáta slovníka sa načítavajú na požiadanie v režime Dictionary a uvoľňujú sa v iných režimoch na šetrenie pamäte.

---

## Čítačka PDF

Furigana Reader má vstavanú čítačku PDF s furiganou, slovníkom, rečou a prekladom — rovnaké funkcie ako na webových stránkach, teraz aj pre PDF.

### Otvorenie PDF

**Metóda 1: Z vyskakovacieho okna**  
Kliknite na ikonu rozšírenia, potom na „Open PDF Reader“. Pretiahnite PDF alebo kliknite na „Choose File“ pre lokálny súbor. Môžete vložiť aj URL PDF.

**Metóda 2: Kontextová ponuka**  
Pravý klik na odkaz `.pdf` a zvoľte „Open PDF with Furigana Reader“.

**Metóda 3: Automatické rozpoznanie**  
Keď je v nastaveniach zapnuté „PDF Smart Detection“, rozšírenie automaticky presmeruje URL končiace na `.pdf` do vstavanej čítačky. Ak je PDF zistené, ale nepresmerované (napr. vstavaný prehliadač Chrome), zobrazia sa upozornenia na otvorenie vo Furigana Reader.

### Funkcie čítačky PDF

- **Anotácie furigany** — Všetky funkcie furigany na texte PDF vrátane režimu celej stránky a nápoved
- **Päť režimov furigany** — Hiragana, Katakana, Romaji, len ukázanie a vypnuté
- **Slovník kliknutím** — Kliknite na slovo pre definíciu z JMdict (v PDF sa namiesto ukázania používa klik pre nerušivé čítanie)
- **Panel výberu** — Vyberte text na reč, preklad alebo kopírovanie
- **Bočný panel** — Obsah a miniatúry strán
- **Vyhľadávanie** — Fulltextové vyhľadávanie v PDF
- **Témy** — Tmavá, svetlá a sépia
- **Priblíženie** — Viac úrovní vrátane furigany prispôsobenej zoomu
- **Klávesové skratky** — Šípky na navigáciu, +/- na zoom, Ctrl/Cmd+F na vyhľadávanie

---

## Reč výberu a karaoke

Funkcia reči umožní vybrať japonský text a prehrať ho jedným kliknutím — vhodné na výslovnosť viet a čítanie.

**Metóda 1: Panel výberu**  
Vyberte japonský text. Zobrazí sa panel s tlačidlami 🔊 speak a 🌐 translate. Kliknite na speak. Počas prehrávania sa slová alebo znaky v reálnom čase zvýrazňujú (karaoke).

**Metóda 2: Kontextová ponuka**  
Po výbere pravý klik: „Furigana Reader > Read aloud selection“.

**Metóda 3: Klávesová skratka**  
Vyberte text a stlačte `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Tip:** Karaoke najlepšie funguje, ak prehliadač podporuje TTS udalosti hraníc slov. Inak sa používa časová záloha pre plynulé zvýraznenie.

---

## Preklad

Vyberte ľubovoľný text na stránke a použite preklad pre okamžitý výsledok.

**Metóda 1: Panel výberu**  
Vyberte text, potom kliknite na 🌐 translate na paneli. Pod panelom sa zobrazí bublina s výsledkom a tlačidlom kopírovania.

**Metóda 2: Kontextová ponuka**  
Vyberte text, pravý klik: „Furigana Reader > Translate Selection“.

**Metóda 3: Klávesová skratka**  
Vyberte text a stlačte `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Prekladové enginy:**
- **Bing Translate** (predvolené) — Microsoft Translator
- **Google Translate** — Google

Oba podporujú **108 cieľových jazykov**.

Engine a cieľový jazyk zmeníte v nastaveniach rozšírenia. Cieľový jazyk sa zvyčajne automaticky zistí z jazyka prehliadača.

> **Tip:** Kliknite mimo panel alebo bubliny na zatvorenie.

---

## Klávesové skratky

| Skratka | Na Macu | Akcia |
|---------|---------|-------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Zapnúť/vypnúť anotácie furigany |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Prečítať vybraný text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Preložiť vybraný text |

> **Tip:** Skratky prispôsobíte v Chrome na `chrome://extensions/shortcuts`.

---

## Sprievodca nastaveniami

| Nastavenie | Popis |
|------------|-------|
| **Enable Furigana** | Hlavný prepínač funkcie furigana |
| **Whole Page Furigana** | Zapnuté zobrazí furigana pre všetky kanji (môže ovplyvniť rozloženie) |
| **Hover Mode** | Správanie pri ukázaní: Dictionary (čítanie + definície + JLPT + zvuk), Reading (čítanie + zvuk) alebo Off |
| **Furigana Style** | Hiragana, Katakana alebo Romaji |
| **Speech Rate** | Rýchlosť čítania viet |
| **Translation Engine** | Bing Translate alebo Google Translate |
| **Target Language** | Cieľový jazyk prekladu (automaticky z jazyka prehliadača) |
| **PDF Smart Detection** | Zapnuté automaticky presmeruje PDF URL do vstavanej čítačky a zobrazí upozornenia pri zistení PDF |

---

## Často kladené otázky

**O: Prečo to na niektorých stránkach nefunguje?**  
O: Z bezpečnostných dôvodov rozšírenia nebežia na špeciálnych stránkach ako `chrome://`, nastaveniach prehliadača alebo Chrome Web Store.

**O: Čo ak je furigana nepresná?**  
O: Zriedkavé slová alebo špeciálne čítania (熟字訓) môžu byť chybné. Stále vylepšujeme. Pošlite konkrétne prípady.

**O: Žiadny zvuk z TTS?**  
O: Skontrolujte hlasitosť systému a nainštalované japonské hlasy. Podpora závisí od prehliadača a OS.

**O: Režim celej stránky mení rozloženie?**  
O: Furigana potrebuje extra priestor. Ak prekáža, vypnite celú stránku a použite nápovedy pri ukázaní.

**O: Preklad nefunguje?**  
O: Potrebujete internet. Ak Bing zlyhá, skúste Google v nastaveniach. Niektoré siete môžu blokovať prekladové služby.

**O: Ako otvorím PDF vo Furigana Reader?**  
O: „Open PDF Reader“ vo vyskakovacom okne, pravý klik na PDF odkaz — „Open PDF with Furigana Reader“, alebo zapnite „PDF Smart Detection“ pre automatické presmerovanie.

**O: PDF Smart Detection je zapnuté, ale niektoré PDF sa nepresmerujú?**  
O: Automatické presmerovanie funguje pre URL končiace na `.pdf`. Pre PDF bez prípony v URL alebo vo vstavanom prehliadači sa zobrazí upozornenie a odznak na otvorenie vo Furigana Reader.

**O: Dá sa používať slovník offline?**  
O: Áno. JMdict (180 000+ záznamov) je plne súčasťou rozšírenia. Všetky vyhľadávania sú lokálne bez siete.

---

## Súvisiace odkazy

- [Zásady ochrany osobných údajov](../privacy-policy)
- [Podpora a spätná väzba](../support)

---
