---
layout: bare
title: Furigana Reader-utvidelse - Brukerveiledning
lang: no
---

# Furigana Reader - Brukerveiledning

> Versjon: v1.4.3

## Introduksjon

Furigana Reader er en nettleserutvidelse for deg som lærer japansk. Med en WASM morfologisk analyser (Lindera + IPAdic) og JavaScript-reserve legger den nøyaktig til furigana (leseannotasjoner) over kanji på nettsider og i PDF-filer. Den har også en innebygd japansk ordbok, tekst-til-tale og oversettelse — slik at du lettere kan lære japansk uttale.

---

## Hovedfunksjoner

- **Furigana for hele siden** — Legg til furigana for alle kanji med ett klikk
- **Pekeordbok** — Hold pekeren over annoterte tegn for å se JMdict-definisjoner (180 000+ oppføringer), lesninger, JLPT-nivåmerker (N5–N1) og uttaleknapper; velg mellom modusene Ordbok, Lesning eller Av
- **PDF-leser** — Innebygd PDF-leser med furigana, ordbok, opplesning og oversettelse; støtter dra og slipp, URL-lasting og automatisk PDF-gjenkjenning med smart omdirigering
- **Tre furigana-stiler** — Hiragana, Katakana og Romaji
- **Okurigana-deling** — Deler okurigana (送り仮名) fra kanji-stammer presist
- **Støtte for jukujikun** — Korrekte lesninger for flerkanji-forbindelser med spesielle lesninger (熟字訓)
- **Tekst-til-tale** — Klikk på høyttalerikonet for å høre japansk uttale
- **Opplesning av utvalg med karaoke** — Marker japansk tekst; en kompakt verktøylinje vises med opplesning og oversettelse; opplesning med ord- eller tegnvis markering i sanntid (karaoke) synkronisert med lyden
- **Oversettelse av utvalg** — Marker tekst, klikk oversettelsesknappen i verktøylinjen for øyeblikkelig oversettelse via Bing eller Google Translate, vist i en inline-boble
- **Hurtigtaster** — Rask tilgang til kjernefunksjoner med tilpassbare snarveier
- **Flerspråklig grensesnitt** — 38 grensesnittspråk

---

## Slik bruker du utvidelsen

### Trinn 1: Installer utvidelsen

Installer **Furigana Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller last den lokalt i utviklermodus.

### Trinn 2: Åpne en nettside

Besøk en side med japansk innhold.

### Trinn 3: Aktiver furigana

Klikk på utvidelsesikonet i verktøylinjen. Slå på «Aktiver furigana», deretter «Furigana for hele siden» for å annotere alle kanji. Du kan også bruke den flytende knappen nederst til høyre.

### Trinn 4: Se furigana

Hold pekeren over tegn for å se verktøytips med lesninger og ordboksdefinisjoner. Klikk på høyttalerikonet for å høre uttale.

### Trinn 5: Les høyt og oversett merket tekst

Marker japansk tekst med musen. En kompakt verktøylinje vises nær markeringen med to knapper:
- **🔊 Les høyt** — Leser den markerte teksten høyt med karaoke-lignende markering
- **🌐 Oversett** — Viser en inline-oversettelsesboble under verktøylinjen

Du kan også høyreklikke og velge «Furigana Reader > Les valg høyt» eller «Furigana Reader > Oversett utvalg».

> **Tips:** Klikk på utvidelsesikonet for å åpne innstillinger og justere furigana-stil, pekemodus, talehastighet, oversettelsesmotor med mer.

---

## Pekeordbok

Utvidelsen har en innebygd japansk ordbok basert på JMdict (180 000+ oppføringer). Du kan velge pekemodus i innstillingene:

| Modus | Oppførsel |
|-------|-----------|
| **Ordbok** | Peking viser lesning + definisjon + JLPT-nivå + uttaleknapp |
| **Lesning** | Peking viser lesning + uttaleknapp (ingen definisjoner) |
| **Av** | Ingen pekeeffekt |

I **Ordbok**-modus viser verktøytipset:
- Ordet og dets lesning (furigana)
- En uttaleknapp (klikk for å høre)
- Japanske definisjoner fra JMdict
- JLPT-nivåmerke (N5–N1) når tilgjengelig

> **Tips:** Ordboksdata lastes ved behov når Ordbok-modus er aktiv, og frigjøres ved bytte til andre moduser for å spare minne.

---

## PDF-leser

Furigana Reader har en innebygd PDF-leser slik at du kan lese PDF med furigana, ordbok, opplesning og oversettelse — de samme funksjonene som på nettsider, nå for PDF.

### Åpne en PDF

**Metode 1: Fra popup**  
Klikk på utvidelsesikonet og deretter «Åpne PDF-leser». Dra og slipp en PDF-fil eller klikk «Velg fil» for å åpne en lokal PDF. Du kan også lime inn en PDF-URL.

**Metode 2: Kontekstmeny**  
Høyreklikk på en `.pdf`-lenke på en side og velg «Åpne PDF med Furigana Reader».

**Metode 3: Automatisk gjenkjenning**  
Når «PDF Smart Detection» er slått på i innstillingene, omdirigerer utvidelsen automatisk `.pdf`-URL-er til den innebygde leseren. Hvis en PDF oppdages uten omdirigering (f.eks. Chromes innebygde visning), vises varsler og oppfordringer om å åpne i Furigana Reader.

### Funksjoner i PDF-leseren

- **Furigana** — Alle furigana-funksjoner fungerer på PDF-tekst, inkludert hele siden og pekeverktøytips
- **Fem furigana-moduser** — Hiragana, Katakana, Romaji, Kun peking og Av
- **Klikkordbok** — Klikk på et ord for JMdict-definisjon (i PDF brukes klikk i stedet for peking for forstyrrelsesfri lesing)
- **Utvalgsverktøylinje** — Marker tekst for å lese høyt, oversette eller kopiere
- **Sidepanel** — Innholdsfortegnelse og sideminiatyrer
- **Søk** — Fulltekstsøk i PDF
- **Temaer** — Mørkt, lyst og sepia
- **Zoom** — Flere zoomnivåer inkludert zoom-tilpasset furigana
- **Hurtigtaster** — Piltaster for navigering, +/- for zoom, Ctrl/Cmd+F for søk

---

## Opplesning av utvalg og karaoke

Marker japansk tekst og les den høyt med ett klikk — nyttig for setningsuttale og lesetrening.

**Metode 1: Utvalgsverktøylinje**  
Marker japansk tekst. En kompakt verktøylinje vises med 🔊 opplesning og 🌐 oversettelse. Klikk på opplesingsknappen. Under opplesning markeres hvert ord eller tegn i sanntid (karaoke).

**Metode 2: Kontekstmeny**  
Etter at du har markert japansk tekst, høyreklikk og velg «Furigana Reader > Les valg høyt».

**Metode 3: Hurtigtast**  
Marker tekst og trykk `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) for opplesning.

> **Tips:** Karaoke-markering fungerer best når nettleseren støtter TTS-ordgrensehendelser. Ellers bruker utvidelsen et tidsbasert reserveopplegg.

---

## Oversettelse

Marker tekst på siden og bruk oversettelsesfunksjonen for øyeblikkelige resultater.

**Metode 1: Utvalgsverktøylinje**  
Marker tekst og klikk på 🌐 oversett i verktøylinjen. En oversettelsesboble vises under med resultat og kopieringsknapp.

**Metode 2: Kontekstmeny**  
Marker tekst, høyreklikk og velg «Furigana Reader > Oversett utvalg».

**Metode 3: Hurtigtast**  
Marker tekst og trykk `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) for oversettelse.

**Oversettelsesmotorer:**
- **Bing Translate** (standard) — Microsoft Translator
- **Google Translate** — Google

Begge motorene støtter **108 målspråk**.

Du kan bytte oversettelsesmotor og målspråk i utvidelsesinnstillingene. Målspråk oppdages automatisk fra nettleserspråket.

> **Tips:** Klikk utenfor verktøylinjen eller boblen for å lukke dem.

---

## Hurtigtaster

| Snarvei | Mac-snarvei | Handling |
|---------|-------------|----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Slå furigana av/på |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Les markert tekst høyt |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversett markert tekst |

> **Tips:** Tilpass snarveier i Chrome under `chrome://extensions/shortcuts`.

---

## Innstillingsguide

| Innstilling | Beskrivelse |
|-------------|-------------|
| **Aktiver furigana** | Hovedbryter for furigana |
| **Furigana for hele siden** | Viser furigana for alle kanji (kan påvirke sidelayout) |
| **Pekemodus** | Ordbok (lesning + definisjoner + JLPT + lyd), Lesning (lesning + lyd) eller Av |
| **Furigana-stil** | Hiragana, Katakana eller Romaji |
| **Talehastighet** | Hastighet for setningsopplesning |
| **Oversettelsesmotor** | Bing Translate eller Google Translate |
| **Målspråk** | Målspråk for oversettelse (auto fra nettleser) |
| **PDF Smart Detection** | Omdirigerer automatisk PDF-URL-er til den innebygde leseren og viser varsler når PDF-er oppdages |

---

## Ofte stilte spørsmål

**Q: Hvorfor fungerer det ikke på enkelte sider?**  
A: Av sikkerhetsgrunner kan ikke utvidelser kjøre på sider som `chrome://`, nettleserinnstillinger eller Chrome Web Store.

**Q: Hva hvis furigana er unøyaktig?**  
A: Sjeldne ord eller spesielle lesninger (熟字訓) kan være feil. Vi forbedrer kontinuerlig. Del gjerne konkrete eksempler.

**Q: Ingen lyd fra tekst-til-tale?**  
A: Sjekk systemvolum og at japanske stemmer er installert. Støtte varierer mellom nettleser og OS.

**Q: Hele siden påvirker layout?**  
A: Furigana trenger ekstra plass. Slå av hele siden og bruk pekeverktøytips hvis det forstyrrer.

**Q: Oversettelse fungerer ikke?**  
A: Oversettelse krever internett. Hvis Bing feiler, prøv Google i innstillinger. Noen nettverk blokkerer tjenestene.

**Q: Hvordan åpner jeg en PDF i Furigana Reader?**  
A: Klikk «Åpne PDF-leser» i popup, høyreklikk på en PDF-lenke og velg «Åpne PDF med Furigana Reader», eller slå på «PDF Smart Detection» for automatisk omdirigering.

**Q: PDF Smart Detection er på, men enkelte PDF-er omdirigeres ikke?**  
A: Auto-omdirigering gjelder URL-er som slutter på `.pdf`. PDF-er uten `.pdf` i URL eller i Chromes visning får varsel og merke for å åpne i Furigana Reader.

**Q: Kan jeg bruke ordboken offline?**  
A: Ja. JMdict (180 000+ oppføringer) er fullt innebygd i utvidelsen. Alle oppslag skjer lokalt uten nettverk.

---

## Relaterte lenker

- [Personvernerklæring](../privacy-policy)
- [Support og tilbakemelding](../support)

---
