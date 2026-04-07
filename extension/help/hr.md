---
layout: bare
title: Proširenje Furigana Reader - Korisnički priručnik
lang: hr
---

# Furigana Reader - Korisnički priručnik

> Verzija: v1.4.0

## Uvod

Furigana Reader je proširenje preglednika za učenje japanskog. Pokreće ga WASM morfološki analizator (Lindera + IPAdic) s JavaScript rezervom; točno dodaje furigana (čitanja) iznad kanji znakova na web stranicama i u PDF-ovima. Uključuje i ugrađeni japanski rječnik, pretvorbu teksta u govor (TTS) i prijevod — kako biste lakše učili izgovor.

---

## Glavne značajke

- **Furigana cijele stranice** — Jednim klikom dodajte furiganu svim kanji znakovima na stranici
- **Rječnik pri lebdenju** — Prijeđite mišem preko anotiranih znakova za definicije iz JMdict-a (180 000+ unosa), čitanja, oznake razine JLPT (N5–N1) i gumbe za izgovor; odaberite način Dictionary, Reading ili Off
- **PDF čitač** — Ugrađeni PDF čitač s furiganom, rječnikom, govorom i prijevodom; podrška za povuci-i-pusti, učitavanje URL-om i automatsko otkrivanje PDF-a s pametnim preusmjeravanjem
- **Tri stila čitanja** — Hiragana, Katakana i Romaji
- **Razdvajanje okurigane** — Točno odvaja okuriganu (送り仮名) od kanji korijena
- **Podrška za jukujikun** — Ispravna čitanja za višekanjske izraze s posebnim čitanjem (熟字訓)
- **Pretvorba teksta u govor** — Kliknite ikonu zvučnika za japanski izgovor
- **Govor odabira s karaoke efektom** — Odaberite japanski tekst; pojavljuje se kompaktna alatna traka s gumbima za govor i prijevod; tijekom reprodukcije riječi ili znakovi se ističu u stvarnom vremenu (karaoke) sinkronizirano sa zvukom
- **Prijevod odabira** — Odaberite tekst, kliknite prijevod na traci za trenutni rezultat putem Binga ili Google Translatea u ugrađenom oblačiću
- **Tipkovnički prečaci** — Brz pristup glavnim značajkama putem prilagodljivih prečaca
- **Višejezično sučelje** — 38 jezika sučelja

---

## Kako koristiti

### Korak 1: Instalirajte proširenje

Instalirajte **Furigana Reader** iz [Chrome Web Storea](https://chromewebstore.google.com/) ili učitajte lokalno u načinu za razvojne programere.

### Korak 2: Otvorite bilo koju stranicu

Posjetite stranicu s japanskim sadržajem.

### Korak 3: Uključite furiganu

Kliknite ikonu proširenja na alatnoj traci. Uključite „Enable Furigana”, zatim „Whole Page Furigana” za anotaciju svih kanji-ja. Možete koristiti i plutajući gumb dolje desno.

### Korak 4: Pregledajte furiganu

Prijeđite mišem preko znakova za opise s čitanjem i definicijama iz rječnika. Kliknite ikonu zvučnika za izgovor.

### Korak 5: Govorite i prevedite odabrano

Odaberite japanski tekst mišem. Pojavljuje se kompaktna traka s dva gumba:
- **🔊 Speak** — Čita odabrano naglas s karaoke istakom
- **🌐 Translate** — Prikazuje ugrađeni oblačić prijevoda ispod trake

Možete i desnim klikom odabrati „Furigana Reader > Read aloud selection” ili „Furigana Reader > Translate Selection”.

> **Savjet:** Kliknite ikonu proširenja za postavke: stil furigane, način lebdenja, brzina govora, mehanizam prijevoda itd.

---

## Rječnik pri lebdenju

Proširenje uključuje ugrađeni japanski rječnik temeljen na JMdict-u (180 000+ unosa). U postavkama birate način lebdenja:

| Način | Ponašanje |
|-------|-----------|
| **Dictionary** | Lebdenje: čitanje + definicija + JLPT + gumb za izgovor |
| **Reading** | Lebdenje: čitanje + gumb za izgovor (bez definicija) |
| **Off** | Bez efekta pri lebdenju |

U načinu **Dictionary** opis prikazuje:
- Riječ i njeno čitanje (furigana)
- Gumb za izgovor (kliknite za zvuk)
- Japanske definicije iz JMdict-a
- Oznaku razine JLPT (N5–N1) kad je dostupna

> **Savjet:** Podaci rječnika učitavaju se po potrebi u načinu Dictionary i oslobađaju u drugim načinima radi uštede memorije.

---

## PDF čitač

Furigana Reader ima ugrađeni PDF čitač s furiganom, rječnikom, govorom i prijevodom — iste značajke kao na web stranicama, sada i za PDF.

### Otvaranje PDF-a

**Način 1: Iz skočnog prozora**  
Kliknite ikonu proširenja, zatim „Open PDF Reader”. Povucite i ispustite PDF ili kliknite „Choose File” za lokalnu datoteku. Možete zalijepiti URL PDF-a.

**Način 2: Kontekstni izbornik**  
Desni klik na `.pdf` poveznicu i odaberite „Open PDF with Furigana Reader”.

**Način 3: Automatsko otkrivanje**  
Kad je u postavkama uključeno „PDF Smart Detection”, proširenje automatski preusmjerava URL-ove koji završavaju na `.pdf` na ugrađeni čitač. Kad je PDF otkriven, ali nije preusmjeren (npr. ugrađeni preglednik Chromea), pojavljuju se obavijesti s pozivom na otvaranje u Furigana Readeru.

### Značajke PDF čitača

- **Furigana anotacije** — Sve funkcije furigane na PDF tekstu, uključujući cijelu stranicu i opise
- **Pet načina furigane** — Hiragana, Katakana, Romaji, samo lebdenje i isključeno
- **Rječnik klikom** — Kliknite riječ za definiciju iz JMdict-a (u PDF-u se koristi klik umjesto lebdenja radi mirnijeg čitanja)
- **Traka odabira** — Odaberite tekst za govor, prijevod ili kopiranje
- **Bočna traka** — Sadržaj i minijature stranica
- **Pretraživanje** — Pretraga cijelog teksta u PDF-u
- **Teme** — Tamna, svijetla i sepija
- **Zum** — Više razina zumiranja, uključujući furiganu prilagođenu zumu
- **Tipkovnički prečaci** — Strelice za navigaciju, +/- za zum, Ctrl/Cmd+F za pretragu

---

## Govor odabira i karaoke

Funkcija govora omogućuje odabir japanskog teksta i reprodukciju jednim klikom — korisno za izgovor rečenica i vježbu čitanja.

**Način 1: Traka odabira**  
Odaberite japanski tekst. Pojavljuje se traka s gumbima 🔊 speak i 🌐 translate. Kliknite speak. Tijekom reprodukcije riječi ili znakovi se ističu u stvarnom vremenu (karaoke).

**Način 2: Kontekstni izbornik**  
Nakon odabira desni klik i „Furigana Reader > Read aloud selection”.

**Način 3: Tipkovnički prečac**  
Odaberite tekst i pritisnite `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Savjet:** Karaoke najbolje radi kad preglednik podržava TTS događaje granica riječi. Inače se koristi rezervno vremensko istaknuće.

---

## Prijevod

Odaberite bilo koji tekst na stranici i koristite prijevod za trenutni rezultat.

**Način 1: Traka odabira**  
Odaberite tekst, zatim kliknite 🌐 translate na traci. Ispod se pojavljuje oblačić s rezultatom i gumbom za kopiranje.

**Način 2: Kontekstni izbornik**  
Odaberite tekst, desni klik i „Furigana Reader > Translate Selection”.

**Način 3: Tipkovnički prečac**  
Odaberite tekst i pritisnite `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Mehanizmi prijevoda:**
- **Bing Translate** (zadano) — Microsoft Translator
- **Google Translate** — Google

Oba podržavaju **108 ciljnih jezika**.

Mehanizam i ciljni jezik mijenjate u postavkama proširenja. Ciljni jezik se automatski prepoznaje iz jezika preglednika.

> **Savjet:** Kliknite izvan trake ili oblačića da ih zatvorite.

---

## Tipkovnički prečaci

| Prečac | Na Macu | Radnja |
|--------|---------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Uključi/isključi furigana anotacije |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Pročitaj odabrani tekst naglas |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Prevedi odabrani tekst |

> **Savjet:** Prečace prilagodite u Chromeu na `chrome://extensions/shortcuts`.

---

## Vodič kroz postavke

| Postavka | Opis |
|----------|------|
| **Enable Furigana** | Glavni prekidač za furiganu |
| **Whole Page Furigana** | Furigana za sve kanji (može utjecati na raspored) |
| **Hover Mode** | Ponašanje pri lebdenju: Dictionary (čitanje + definicije + JLPT + audio), Reading (čitanje + audio) ili Off |
| **Furigana Style** | Hiragana, Katakana ili Romaji |
| **Speech Rate** | Brzina čitanja rečenica |
| **Translation Engine** | Bing Translate ili Google Translate |
| **Target Language** | Ciljni jezik prijevoda (automatski iz jezika preglednika) |
| **PDF Smart Detection** | Automatsko preusmjeravanje PDF URL-ova na ugrađeni čitač i obavijesti pri otkrivanju PDF-a |

---

## FAQ

**P: Zašto ne radi na nekim stranicama?**  
O: Iz sigurnosnih razloga proširenja ne rade na posebnim stranicama poput `chrome://`, postavki preglednika ili Chrome Web Storea.

**P: Što ako je furigana netočna?**  
O: Rijetke riječi ili posebna čitanja (熟字訓) mogu biti pogrešna. Stalno poboljšavamo. Pošaljite konkretne primjere.

**P: Nema zvuka iz TTS-a?**  
O: Provjerite glasnoću sustava i instalirane japanske glasove. Podrška ovisi o pregledniku i OS-u.

**P: Način cijele stranice mijenja raspored?**  
O: Furigana treba dodatni prostor. Ako smeta, isključite cijelu stranicu i koristite opise pri lebdenju.

**P: Prijevod ne radi?**  
O: Potrebna je internetska veza. Ako Bing ne uspije, probajte Google u postavkama. Neke mreže mogu blokirati usluge prijevoda.

**P: Kako otvoriti PDF u Furigana Readeru?**  
O: „Open PDF Reader” u skočnom prozoru, desni klik na PDF poveznicu — „Open PDF with Furigana Reader”, ili uključite „PDF Smart Detection” za automatsko preusmjeravanje.

**P: PDF Smart Detection je uključen, ali neki PDF se ne preusmjeravaju?**  
O: Automatsko preusmjeravanje radi za URL-ove koji završavaju na `.pdf`. Za PDF bez ekstenzije u URL-u ili u ugrađenom pregledniku pojavit će se obavijest i značka za otvaranje u Furigana Readeru.

**P: Mogu li koristiti rječnik izvan mreže?**  
O: Da. JMdict (180 000+ unosa) u potpunosti je ugrađen u proširenje. Sva traženja su lokalna, bez mreže.

---

## Povezane poveznice

- [Politika privatnosti](../privacy-policy)
- [Podrška i povratne informacije](../support)

---
