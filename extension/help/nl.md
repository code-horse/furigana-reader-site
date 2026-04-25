---
layout: bare
title: Furigana Reader — Gebruikershandleiding
lang: nl
---

# Furigana Reader — Gebruikershandleiding

> Versie: v1.4.3

## Introductie

Furigana Reader is een browserextensie voor wie Japans leert. Aangedreven door een WASM-morfologische analyzer (Lindera + IPAdic) met JavaScript-fallback voegt het nauwkeurig furigana (uitleesnotities) toe aan kanji op webpagina’s en in PDF-bestanden. Er is ook een ingebouwde Japans woordenboek, tekst-naar-spraak en vertaling — zodat je de uitspraak makkelijker leert.

---

## Belangrijkste functies

- **Furigana voor de hele pagina** — Voeg met één klik furigana toe aan alle kanji op de pagina
- **Hover-woordenboek** — Beweeg over geannoteerde tekens om JMdict-definities (180.000+ lemma’s), lezingen, JLPT-niveaubadges (N5–N1) en uitspraakknoppen te zien; kies Dictionary-modus, Reading-modus of Uit
- **PDF-lezer** — Ingebouwde PDF-lezer met furigana, woordenboek, spraak en vertaling; ondersteunt slepen en neerzetten, URL-laden en automatische PDF-detectie met slimme omleiding
- **Drie furigana-stijlen** — Hiragana, katakana en romaji
- **Okurigana-splitsing** — Splits okurigana (送り仮名) nauwkeurig af van kanji-stammen
- **Ondersteuning voor jukujikun** — Juiste lezingen voor meerkantige verbindingen met speciale lezingen (熟字訓)
- **Tekst-naar-spraak** — Klik op het luidsprekerpictogram om de Japanse uitspraak te horen
- **Selectiespraak met karaoke** — Selecteer Japanse tekst; een compacte werkbalk verschijnt met spreek- en vertaalknoppen; spraak met woord-voor-woord of teken-voor-teken markering in realtime (karaoke), gesynchroniseerd met audio
- **Selectievertaling** — Selecteer tekst, klik op de vertaalknop in de werkbalk voor directe vertaling via Bing of Google Translate, weergegeven in een inline-bubbel
- **Sneltoetsen** — Snelle toegang tot kernfuncties via aanpasbare sneltoetsen
- **Meertalige interface** — 38 interfacetalen

---

## Gebruik

### Stap 1: Installeer de extensie

Installeer **Furigana Reader** uit de [Chrome Web Store](https://chromewebstore.google.com/), of laad hem lokaal in ontwikkelaarsmodus.

### Stap 2: Open een webpagina

Bezoek een pagina met Japanse inhoud.

### Stap 3: Schakel furigana in

Klik op het extensiepictogram in de werkbalk. Zet «Furigana inschakelen» aan, daarna «Furigana voor hele pagina» om alle kanji te annoteren. Je kunt ook de zwevende knop rechtsonder gebruiken.

### Stap 4: Bekijk furigana

Beweeg over tekens om tooltips met lezingen en woordenboekdefinities te zien. Klik op het luidsprekerpictogram om de uitspraak te horen.

### Stap 5: Selectie voorlezen en vertalen

Selecteer Japanse tekst met de muis. Een compacte werkbalk verschijnt bij de selectie met twee knoppen:
- **🔊 Voorlezen** — Leest de selectie hardop voor met karaoke-achtige markering
- **🌐 Vertalen** — Toont een inline-vertaalbubbel onder de werkbalk

Je kunt ook rechtsklikken en «Furigana Reader > Selectie voorlezen» of «Furigana Reader > Selectie vertalen» kiezen.

> **Tip:** Klik op het extensiepictogram om het instellingenpaneel te openen en furigana-stijl, hovermodus, spreeksnelheid, vertaalengine enz. aan te passen.

---

## Hover-woordenboek

De extensie bevat een ingebouwd Japans woordenboek op basis van JMdict (180.000+ lemma’s). Je kunt de hovermodus in de instellingen kiezen:

| Modus | Gedrag |
|-------|--------|
| **Dictionary** | Hover toont lezing + definitie + JLPT-niveau + uitspraakknop |
| **Reading** | Hover toont lezing + uitspraakknop (geen definities) |
| **Uit** | Geen hover-effect |

In **Dictionary**-modus toont de tooltip:
- Het woord en de lezing (furigana)
- Een uitspraakknop (klik om te horen)
- Japanse definities uit JMdict
- JLPT-badge (N5–N1) indien beschikbaar

> **Tip:** Woordenboekgegevens worden on demand geladen als Dictionary-modus aan staat en vrijgegeven bij andere modi om geheugen te besparen.

---

## PDF-lezer

Furigana Reader heeft een ingebouwde PDF-lezer: je leest PDF-documenten met furigana, woordenboek, spraak en vertaling — dezelfde functies als op webpagina’s, nu voor PDF.

### Een PDF openen

**Methode 1: Vanuit de popup**  
Klik op het extensiepictogram en daarna op «PDF-lezer openen». Sleep een PDF-bestand of klik op «Bestand kiezen» voor een lokale PDF. Je kunt ook een PDF-URL plakken.

**Methode 2: Contextmenu**  
Rechtsklik op een `.pdf`-link op een pagina en kies «PDF openen met Furigana Reader».

**Methode 3: Automatische detectie**  
Als «PDF Smart Detection» in de instellingen aan staat, leidt de extensie `.pdf`-URL’s automatisch om naar de ingebouwde lezer. Als een PDF wordt gedetecteerd maar niet omgeleid (bijv. ingebouwde Chrome-viewer), zie je meldingen en prompts om in Furigana Reader te openen.

### Functies van de PDF-lezer

- **Furigana** — Alle furigana-functies werken op PDF-tekst, inclusief hele-pagina-modus en hover-tooltips
- **Vijf furigana-modi** — Hiragana, katakana, romaji, Alleen hover en Uit
- **Klik-woordenboek** — Klik op een woord voor de JMdict-definitie (in PDF wordt klik i.p.v. hover gebruikt voor rustig lezen)
- **Selectiewerkbalk** — Selecteer tekst om voor te lezen, te vertalen of te kopiëren
- **Zijbalk** — Inhoudsopgave en paginaminiaturen
- **Zoeken** — Volledige tekstzoekactie in de PDF
- **Thema’s** — Donker, licht en sepia
- **Zoom** — Meerdere zoomniveaus, inclusief zoom-aangepaste furigana
- **Sneltoetsen** — Pijltoetsen voor navigatie, +/- voor zoom, Ctrl/Cmd+F voor zoeken

---

## Selectiespraak en karaoke

Selecteer Japanse tekst en laat die met één klik voorlezen — handig voor zinsuitspraak en leesoefening.

**Methode 1: Selectiewerkbalk**  
Selecteer Japanse tekst. Een compacte werkbalk verschijnt met 🔊 spreken en 🌐 vertalen. Klik op de spreekknop. Tijdens het voorlezen wordt elk woord of teken in realtime gemarkeerd (karaoke).

**Methode 2: Contextmenu**  
Na selectie van Japanse tekst: rechtsklik en kies «Furigana Reader > Selectie voorlezen».

**Methode 3: Sneltoets**  
Selecteer tekst en druk op `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) om voor te lezen.

> **Tip:** Karaoke-markering werkt het best als de browser TTS-woordgrenzen ondersteunt. Zo niet, dan gebruikt de extensie een tijdgebaseerde fallback.

---

## Vertaling

Selecteer tekst op de pagina en gebruik vertaling voor directe resultaten.

**Methode 1: Selectiewerkbalk**  
Selecteer tekst en klik op 🌐 vertalen in de werkbalk. Een vertaalbubbel verschijnt eronder met resultaat en kopieerknop.

**Methode 2: Contextmenu**  
Selecteer tekst, rechtsklik en kies «Furigana Reader > Selectie vertalen».

**Methode 3: Sneltoets**  
Selecteer tekst en druk op `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) om te vertalen.

**Vertaalengines:**
- **Bing Translate** (standaard) — Microsoft Translator
- **Google Translate** — Google

Beide engines ondersteunen **108 doeltalen**.

Je kunt vertaalengine en doeltaal in de extensie-instellingen wijzigen. De doeltaal wordt automatisch afgeleid van de browsertaal.

> **Tip:** Klik buiten de werkbalk of bubbel om ze te sluiten.

---

## Sneltoetsen

| Sneltoets | Mac-sneltoets | Actie |
|-----------|---------------|-------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Furigana aan/uit |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Selectie voorlezen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Selectie vertalen |

> **Tip:** Pas sneltoetsen aan in Chrome via `chrome://extensions/shortcuts`.

---

## Instellingengids

| Instelling | Beschrijving |
|------------|--------------|
| **Furigana inschakelen** | Hoofdschakelaar voor furigana |
| **Furigana voor hele pagina** | Toont furigana voor alle kanji (kan de lay-out beïnvloeden) |
| **Hovermodus** | Dictionary (lezing + definities + JLPT + audio), Reading (lezing + audio) of Uit |
| **Furigana-stijl** | Hiragana, katakana of romaji |
| **Spreeksnelheid** | Snelheid van zinsvoorlezing |
| **Vertaalengine** | Bing Translate of Google Translate |
| **Doeltaal** | Doeltaal voor vertaling (automatisch uit browsertaal) |
| **PDF Smart Detection** | Leidt PDF-URL’s automatisch om naar de ingebouwde lezer en toont meldingen bij PDF-detectie |

---

## Veelgestelde vragen

**Q: Waarom werkt het niet op sommige pagina’s?**  
A: Om veiligheidsredenen kunnen extensies niet draaien op speciale pagina’s zoals `chrome://`, browserinstellingen of de Chrome Web Store.

**Q: Wat als furigana onnauwkeurig is?**  
A: Zeldzame woorden of speciale lezingen (熟字訓) kunnen fout zijn. We verbeteren voortdurend. Deel concrete voorbeelden.

**Q: Geen geluid bij tekst-naar-spraak?**  
A: Controleer het systeemvolume en of Japanse stemmen zijn geïnstalleerd. Ondersteuning verschilt per browser en besturingssysteem.

**Q: Beïnvloedt de hele-pagina-modus de lay-out?**  
A: Furigana vraagt extra ruimte. Schakel hele pagina uit en gebruik hover-tooltips als het stoort.

**Q: Vertaling werkt niet?**  
A: Vertaling vereist internet. Als Bing faalt, probeer Google in de instellingen. Sommige netwerken blokkeren de diensten.

**Q: Hoe open ik een PDF met Furigana Reader?**  
A: Klik op «PDF-lezer openen» in de popup, rechtsklik op een PDF-link en kies «PDF openen met Furigana Reader», of schakel «PDF Smart Detection» in voor automatische omleiding.

**Q: PDF Smart Detection staat aan maar sommige PDF’s worden niet omgeleid?**  
A: Auto-omleiding geldt voor URL’s die eindigen op `.pdf`. PDF’s zonder `.pdf` in de URL of in de Chrome-viewer krijgen een melding en badge om in Furigana Reader te openen.

**Q: Kan ik het woordenboek offline gebruiken?**  
A: Ja. Het JMdict-woordenboek (180.000+ lemma’s) zit volledig in de extensie. Alle opzoekingen gebeuren lokaal zonder netwerk.

---

## Gerelateerde links

- [Privacybeleid](../privacy-policy)
- [Ondersteuning en feedback](../support)

---
