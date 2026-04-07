---
layout: bare
title: Furigana Reader-udvidelse - Brugervejledning
lang: da
---

# Furigana Reader - Brugervejledning

> Version: v1.4.1

## Introduktion

Furigana Reader er en browserudvidelse til folk, der lærer japansk. Med en WASM-morfologisk analyser (Lindera + IPAdic) og JavaScript-fallback tilføjer den præcist furigana (læseannotationer) til kanji på websider og i PDF-filer. Den har også en indbygget japansk ordbog, tekst-til-tale og oversættelse — så du lettere kan lære japansk udtale.

---

## Hovedfunktioner

- **Furigana for hele siden** — Tilføj furigana til alle kanji på siden med ét klik
- **Hover-ordbog** — Hold musen over annoterede tegn for at se JMdict-definitioner (180.000+ poster), læsninger, JLPT-niveaumærker (N5–N1) og udtaleknapper; vælg mellem tilstandene Ordbog, Læsning eller Fra
- **PDF-læser** — Indbygget PDF-læser med furigana, ordbog, oplæsning og oversættelse; understøtter træk og slip, URL-indlæsning og automatisk PDF-detektion med smart omdirigering
- **Tre furigana-stilarter** — Hiragana, Katakana og Romaji
- **Okurigana-opdeling** — Opdeler okurigana (送り仮名) fra kanji-stammer præcist
- **Understøttelse af jukujikun** — Korrekte læsninger for flerkanji-forbindelser med særlige læsninger (熟字訓)
- **Tekst-til-tale** — Klik på højttalerknappen for at høre japansk udtale
- **Oplæsning af markering med karaoke** — Marker japansk tekst; en kompakt værktøjslinje vises med oplæsning og oversættelse; oplæsning med ord- eller tegnvis fremhævning i realtid (karaoke) synkroniseret med lyden
- **Oversættelse af markering** — Marker tekst, klik på oversættelsesknappen i værktøjslinjen for øjeblikkelig oversættelse via Bing eller Google Translate, vist i en inline-boble
- **Tastaturgenveje** — Hurtig adgang til kernefunktioner via tilpasselige genveje
- **Flersproget grænseflade** — 38 grænsefladesprog

---

## Sådan bruger du udvidelsen

### Trin 1: Installer udvidelsen

Installer **Furigana Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller indlæs den lokalt i udviklertilstand.

### Trin 2: Åbn en webside

Besøg en side med japansk indhold.

### Trin 3: Aktivér furigana

Klik på udvidelsesikonet i værktøjslinjen. Slå «Aktivér furigana» til, derefter «Furigana for hele siden» for at annotere alle kanji. Du kan også bruge den flydende knap nederst til højre.

### Trin 4: Se furigana

Hold musen over tegn for at se værktøjstips med læsninger og ordbogsdefinitioner. Klik på højttalerikonet for at høre udtale.

### Trin 5: Læs og oversæt markeret tekst

Marker japansk tekst med musen. En kompakt værktøjslinje vises nær markeringen med to knapper:
- **🔊 Læs højt** — Læser den markerede tekst højt med karaoke-lignende fremhævning
- **🌐 Oversæt** — Viser en inline-oversættelsesboble under værktøjslinjen

Du kan også højreklikke og vælge «Furigana Reader > Læs markering højt» eller «Furigana Reader > Oversæt markering».

> **Tip:** Klik på udvidelsesikonet for at åbne indstillinger og justere furigana-stil, hover-tilstand, talehastighed, oversættelsesmotor med mere.

---

## Hover-ordbog

Udvidelsen har en indbygget japansk ordbog baseret på JMdict (180.000+ poster). Du kan vælge hover-tilstand i indstillingerne:

| Tilstand | Adfærd |
|----------|--------|
| **Ordbog** | Hover viser læsning + definition + JLPT-niveau + udtaleknap |
| **Læsning** | Hover viser læsning + udtaleknap (ingen definitioner) |
| **Fra** | Ingen hover-effekt |

I **Ordbog**-tilstand viser værktøjstippet:
- Ordet og dets læsning (furigana)
- En udtaleknap (klik for at høre)
- Japanske definitioner fra JMdict
- JLPT-niveaumærke (N5–N1) når tilgængeligt

> **Tip:** Ordbogsdata indlæses efter behov, når Ordbog er aktiv, og frigives ved skift til andre tilstande for at spare hukommelse.

---

## PDF-læser

Furigana Reader har en indbygget PDF-læser, så du kan læse PDF med furigana, ordbog, oplæsning og oversættelse — de samme funktioner som på websider, nu til PDF.

### Åbn en PDF

**Metode 1: Fra popup**  
Klik på udvidelsesikonet og derefter «Åbn PDF-læser». Træk og slip en PDF-fil eller klik «Vælg fil» for at åbne en lokal PDF. Du kan også indsætte en PDF-URL.

**Metode 2: Kontekstmenu**  
Højreklik på et `.pdf`-link på en side og vælg «Åbn PDF med Furigana Reader».

**Metode 3: Automatisk detektion**  
Når «PDF Smart Detection» er slået til i indstillingerne, omdirigerer udvidelsen automatisk `.pdf`-URL'er til den indbyggede læser. Hvis en PDF registreres uden omdirigering (f.eks. Chromes indbyggede visning), vises notifikationer og opfordringer til at åbne i Furigana Reader.

### Funktioner i PDF-læseren

- **Furigana** — Alle furigana-funktioner virker på PDF-tekst, inkl. hele siden og hover-værktøjstips
- **Fem furigana-tilstande** — Hiragana, Katakana, Romaji, Kun hover og Fra
- **Klik-ordbog** — Klik på et ord for JMdict-definition (i PDF bruges klik i stedet for hover for forstyrrelsesfri læsning)
- **Markeringsværktøjslinje** — Marker tekst for at læse højt, oversætte eller kopiere
- **Sidepanel** — Indholdsfortegnelse og sideskabeloner
- **Søgning** — Fuldtekstsøgning i PDF
- **Temaer** — Mørkt, lyst og sepia
- **Zoom** — Flere zoomniveauer inkl. zoom-tilpasset furigana
- **Tastaturgenveje** — Piletaster til navigation, +/- til zoom, Ctrl/Cmd+F til søgning

---

## Oplæsning af markering og karaoke

Marker japansk tekst og læs den højt med ét klik — godt til sætningsudtale og læsetræning.

**Metode 1: Markeringsværktøjslinje**  
Marker japansk tekst. En kompakt værktøjslinje vises med 🔊 oplæsning og 🌐 oversættelse. Klik på oplæsningsknappen. Under oplæsning fremhæves hvert ord eller tegn i realtid (karaoke).

**Metode 2: Kontekstmenu**  
Efter markering af japansk tekst, højreklik og vælg «Furigana Reader > Læs markering højt».

**Metode 3: Tastaturgenvej**  
Marker tekst og tryk `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) for oplæsning.

> **Tip:** Karaoke-fremhævning fungerer bedst, når browseren understøtter TTS-ordgrænsehændelser. Ellers bruger udvidelsen et tidsbaseret fallback.

---

## Oversættelse

Marker tekst på siden og brug oversættelsesfunktionen for øjeblikkelige resultater.

**Metode 1: Markeringsværktøjslinje**  
Marker tekst og klik på 🌐 oversæt i værktøjslinjen. En oversættelsesboble vises under med resultat og kopieringsknap.

**Metode 2: Kontekstmenu**  
Marker tekst, højreklik og vælg «Furigana Reader > Oversæt markering».

**Metode 3: Tastaturgenvej**  
Marker tekst og tryk `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) for oversættelse.

**Oversættelsesmotorer:**
- **Bing Translate** (standard) — Microsoft Translator
- **Google Translate** — Google

Begge motorer understøtter **108 målsprog**.

Du kan skifte oversættelsesmotor og målsprog i udvidelsesindstillingerne. Målsprog detekteres automatisk fra browsersproget.

> **Tip:** Klik uden for værktøjslinjen eller boblen for at lukke dem.

---

## Tastaturgenveje

| Genvej | Mac-genvej | Handling |
|--------|------------|----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Slå furigana til/fra |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Læs markeret tekst højt |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversæt markeret tekst |

> **Tip:** Tilpas genveje i Chrome under `chrome://extensions/shortcuts`.

---

## Indstillingsguide

| Indstilling | Beskrivelse |
|-------------|-------------|
| **Aktivér furigana** | Hovedkontakt for furigana |
| **Furigana for hele siden** | Viser furigana for alle kanji (kan påvirke layout) |
| **Hover-tilstand** | Ordbog (læsning + definitioner + JLPT + lyd), Læsning (læsning + lyd) eller Fra |
| **Furigana-stil** | Hiragana, Katakana eller Romaji |
| **Talehastighed** | Hastighed for sætningsoplæsning |
| **Oversættelsesmotor** | Bing Translate eller Google Translate |
| **Målsprog** | Målsprog for oversættelse (auto fra browser) |
| **PDF Smart Detection** | Omdirigerer automatisk PDF-URL'er til den indbyggede læser og viser notifikationer ved PDF-detektion |

---

## Ofte stillede spørgsmål

**Q: Hvorfor virker det ikke på nogle sider?**  
A: Af sikkerhedsmæssige årsager kan udvidelser ikke køre på sider som `chrome://`, browserindstillinger eller Chrome Web Store.

**Q: Hvad hvis furigana er unøjagtig?**  
A: Sjældne ord eller særlige læsninger (熟字訓) kan være forkerte. Vi forbedrer løbende. Del gerne konkrete eksempler.

**Q: Ingen lyd fra tekst-til-tale?**  
A: Tjek systemlydstyrke og at japanske stemmer er installeret. Understøttelse varierer mellem browser og OS.

**Q: Hele siden påvirker layout?**  
A: Furigana kræver ekstra plads. Slå hele siden fra og brug hover-værktøjstips, hvis det forstyrrer.

**Q: Oversættelse virker ikke?**  
A: Oversættelse kræver internet. Hvis Bing fejler, prøv Google i indstillinger. Nogle netværk blokerer tjenesterne.

**Q: Hvordan åbner jeg en PDF i Furigana Reader?**  
A: Klik «Åbn PDF-læser» i popup, højreklik på et PDF-link og vælg «Åbn PDF med Furigana Reader», eller aktivér «PDF Smart Detection» for automatisk omdirigering.

**Q: PDF Smart Detection er til, men nogle PDF'er omdirigeres ikke?**  
A: Auto-omdirigering gælder URL'er, der ender på `.pdf`. PDF'er uden `.pdf` i URL eller i Chromes visning får notifikation og badge for at åbne i Furigana Reader.

**Q: Kan jeg bruge ordbogen offline?**  
A: Ja. JMdict (180.000+ poster) er fuldt indlejret i udvidelsen. Alle opslag sker lokalt uden netværk.

---

## Relaterede links

- [Privatlivspolitik](../privacy-policy)
- [Support og feedback](../support)

---
