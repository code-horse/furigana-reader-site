---
layout: bare
title: Furigana Reader-tillägg - Användarguide
lang: sv
---

# Furigana Reader - Användarguide

> Version: v1.4.3

## Introduktion

Furigana Reader är ett webbläsartillägg för dig som lär dig japanska. Med en WASM-morfologisk analysator (Lindera + IPAdic) och JavaScript-reserv lägger det till korrekta furigana-läsnoteringar över kanji på webbsidor och i PDF-filer. Det innehåller också en inbyggd japansk ordbok, text-till-tal och översättning — så att du enklare kan lära dig japansk uttal.

---

## Huvudfunktioner

- **Furigana för hela sidan** — Lägg till furigana för alla kanji på sidan med ett klick
- **Hovringsordbok** — Hovra över annoterade tecken för att se definitioner från JMdict (180 000+ poster), läsningar, JLPT-nivåmärken (N5–N1) och uttalsknappar; välj mellan läget Ordbok, Läsning eller Av
- **PDF-läsare** — Inbyggd PDF-läsare med furigana, ordbok, uppläsning och översättning; stöd för dra och släpp, URL-laddning och automatisk PDF-detektering med smart omdirigering
- **Tre furigana-stilar** — Hiragana, Katakana och Romaji
- **Okurigana-delning** — Delar okurigana (送り仮名) från kanji-stammar med hög precision
- **Stöd för jukujikun** — Korrekta läsningar för flerkanjisammansättningar med särskilda läsningar (熟字訓)
- **Text till tal** — Klicka på högtalarikonen för att höra japansk uttal
- **Uppläsning av markering med karaoke** — Markera valfri japansk text; en kompakt verktygsrad visas med knappar för uppläsning och översättning; uppläsningen spelas med ord- eller teckenvis markering i realtid (karaoke) synkad med ljudet
- **Översättning av markering** — Markera valfri text, klicka på översättningsknappen i verktygsraden för omedelbar översättning via Bing eller Google Translate, visas i en bubbla inline
- **Tangentbordsgenvägar** — Snabb åtkomst till kärnfunktioner via anpassningsbara genvägar
- **Flerspråkigt gränssnitt** — 38 gränssnittsspråk

---

## Så använder du tillägget

### Steg 1: Installera tillägget

Installera **Furigana Reader** från [Chrome Web Store](https://chromewebstore.google.com/), eller ladda det lokalt i utvecklarläge.

### Steg 2: Öppna valfri webbsida

Besök en sida med japanskt innehåll.

### Steg 3: Aktivera furigana

Klicka på tilläggsikonen i verktygsfältet. Slå på «Aktivera furigana», slå sedan på «Furigana för hela sidan» för att annotera alla kanji. Du kan också använda den flytande knappen nere till höger.

### Steg 4: Visa furigana

Hovra över tecken för att se verktygstips med läsningar och ordboksdefinitioner. Klicka på högtalarikonen för att höra uttal.

### Steg 5: Läs upp och översätt markerad text

Markera japansk text med musen. En kompakt verktygsrad visas nära markeringen med två knappar:
- **🔊 Läs upp** — Läser upp den markerade texten med karaoke-liknande markering
- **🌐 Översätt** — Visar en inline-översättningsbubbla under verktygsraden

Du kan också högerklicka och välja «Furigana Reader > Läs upp markering» eller «Furigana Reader > Översätt markering».

> **Tips:** Klicka på tilläggsikonen för att öppna inställningar och justera furigana-stil, hovringsläge, talhastighet, översättningsmotor med mera.

---

## Hovringsordbok

Tillägget har en inbyggd japansk ordbok baserad på JMdict (180 000+ poster). Du kan välja hovringsläge i inställningarna:

| Läge | Beteende |
|------|----------|
| **Ordbok** | Hovring visar läsning + definition + JLPT-nivå + uttalsknapp |
| **Läsning** | Hovring visar läsning + uttalsknapp (inga definitioner) |
| **Av** | Ingen hovringseffekt |

I **Ordbok**-läget visar verktygstipset:
- Ordet och dess läsning (furigana)
- En uttalsknapp (klicka för att höra)
- Japanska definitioner från JMdict
- JLPT-nivåmärke (N5–N1) när det finns

> **Tips:** Ordboksdata laddas vid behov när Ordbok-läge är aktivt och avlastas vid byte till andra lägen för att spara minne.

---

## PDF-läsare

Furigana Reader har en inbyggd PDF-läsare så att du kan läsa PDF med furigana, ordbok, uppläsning och översättning — samma funktioner som på webbsidor, nu för PDF.

### Öppna en PDF

**Metod 1: Från popup**  
Klicka på tilläggsikonen och sedan «Öppna PDF-läsare». Dra och släpp en PDF-fil eller klicka «Välj fil» för att öppna en lokal PDF. Du kan också klistra in en PDF-URL.

**Metod 2: Snabbmeny**  
Högerklicka på en `.pdf`-länk på en sida och välj «Öppna PDF med Furigana Reader».

**Metod 3: Automatisk detektering**  
När «PDF Smart Detection» är aktiverat i inställningarna omdirigerar tillägget automatiskt `.pdf`-URL:er till den inbyggda läsaren. Om en PDF upptäcks men inte omdirigeras (t.ex. Chromes inbyggda visare) visas aviseringar och uppmaningar att öppna i Furigana Reader.

### Funktioner i PDF-läsaren

- **Furigana** — Alla furigana-funktioner fungerar på PDF-text, inklusive hela sidan och hovringsverktygstips
- **Fem furigana-lägen** — Hiragana, Katakana, Romaji, Endast hovring och Av
- **Klickordbok** — Klicka på ett ord för JMdict-definition (i PDF används klick i stället för hovring för störningsfri läsning)
- **Markeringsverktygsrad** — Markera text för att läsa upp, översätta eller kopiera
- **Sidopanel** — Innehållsförteckning och miniatyrer av sidor
- **Sök** — Fulltextsökning i PDF
- **Teman** — Mörkt, ljust och sepia
- **Zoom** — Flera zoomnivåer inklusive zoom-anpassad furigana
- **Tangentbordsgenvägar** — Piltangenter för navigering, +/- för zoom, Ctrl/Cmd+F för sök

---

## Uppläsning av markering och karaoke

Markera valfri japansk text och läs upp med ett klick — bra för meningsuttal och lästräning.

**Metod 1: Markeringsverktygsrad**  
Markera japansk text. En kompakt verktygsrad visas med 🔊 uppläsning och 🌐 översättning. Klicka på uppläsningsknappen. Under uppläsning markeras varje ord eller tecken i realtid (karaoke) så du kan följa med.

**Metod 2: Snabbmeny**  
Efter att du markerat japansk text, högerklicka och välj «Furigana Reader > Läs upp markering».

**Metod 3: Tangentbordsgenväg**  
Markera text och tryck `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) för uppläsning.

> **Tips:** Karaoke-markering fungerar bäst när webbläsaren stödjer TTS-ordgränshändelser. Annars använder tillägget en tidsbaserad reserv för jämn markering.

---

## Översättning

Markera valfri text på sidan och använd översättning för omedelbar översättning.

**Metod 1: Markeringsverktygsrad**  
Markera text och klicka på 🌐 översätt i verktygsraden. En översättningsbubbla visas under med resultat och kopieringsknapp.

**Metod 2: Snabbmeny**  
Markera text, högerklicka och välj «Furigana Reader > Översätt markering».

**Metod 3: Tangentbordsgenväg**  
Markera text och tryck `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) för översättning.

**Översättningsmotorer:**
- **Bing Translate** (standard) — Microsoft Translator
- **Google Translate** — Google

Båda motorerna stödjer **108 målspråk**.

Du kan byta översättningsmotor och målspråk i tilläggsinställningarna. Målspråket upptäcks automatiskt från webbläsarens språk.

> **Tips:** Klicka utanför verktygsraden eller bubblan för att stänga dem.

---

## Tangentbordsgenvägar

| Genväg | Mac-genväg | Åtgärd |
|--------|------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Slå furigana av/på |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Läs upp markerad text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Översätt markerad text |

> **Tips:** Anpassa genvägar i Chrome under `chrome://extensions/shortcuts`.

---

## Inställningsguide

| Inställning | Beskrivning |
|-------------|-------------|
| **Aktivera furigana** | Huvudbrytare för furigana |
| **Furigana för hela sidan** | Visar furigana för alla kanji (kan påverka sidlayout) |
| **Hovringsläge** | Ordbok (läsning + definitioner + JLPT + ljud), Läsning (läsning + ljud) eller Av |
| **Furigana-stil** | Hiragana, Katakana eller Romaji |
| **Talhastighet** | Hastighet för meningsuppläsning |
| **Översättningsmotor** | Bing Translate eller Google Translate |
| **Målspråk** | Målspråk för översättning (auto från webbläsaren) |
| **PDF Smart Detection** | Omdirigerar automatiskt PDF-URL:er till den inbyggda läsaren och visar aviseringar när PDF:er upptäcks |

---

## Vanliga frågor

**Q: Varför fungerar det inte på vissa sidor?**  
A: Av säkerhetsskäl kan tillägg inte köras på sidor som `chrome://`, webbläsarinställningar eller Chrome Web Store.

**Q: Vad gör jag om furigana är fel?**  
A: Sällsynta ord eller särskilda läsningar (熟字訓) kan vara fel. Vi förbättrar kontinuerligt. Skicka gärna exempel.

**Q: Inget ljud från text-till-tal?**  
A: Kontrollera systemvolym och att japanska röster är installerade. Stöd varierar mellan webbläsare och OS.

**Q: Hela sidan påverkar layout?**  
A: Furigana behöver extra utrymme. Stäng av hela sidan och använd hovringsverktygstips om det stör.

**Q: Översättning fungerar inte?**  
A: Översättning kräver internet. Om Bing misslyckas, prova Google i inställningar. Vissa nätverk blockerar tjänsterna.

**Q: Hur öppnar jag en PDF i Furigana Reader?**  
A: Klicka «Öppna PDF-läsare» i popup, högerklicka på en PDF-länk och välj «Öppna PDF med Furigana Reader», eller aktivera «PDF Smart Detection» för automatisk omdirigering.

**Q: PDF Smart Detection är på men vissa PDF:er omdirigeras inte?**  
A: Auto-omdirigering gäller URL:er som slutar på `.pdf`. PDF:er utan `.pdf` i URL eller i Chromes visare får avisering och märke för att öppna i Furigana Reader.

**Q: Fungerar ordboken offline?**  
A: Ja. JMdict (180 000+ poster) är fullt inbakat i tillägget. Alla uppslag sker lokalt utan nätverk.

---

## Relaterade länkar

- [Integritetspolicy](../privacy-policy)
- [Support och feedback](../support)

---
