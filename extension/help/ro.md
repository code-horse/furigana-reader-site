---
layout: bare
title: Extensia Furigana Reader - Ghid de utilizare
lang: ro
---

# Furigana Reader - Ghid de utilizare

> Versiune: v1.4.3

## Introducere

Furigana Reader este o extensie de browser pentru cei care învață japoneză. Cu un analizator morfologic WASM (Lindera + IPAdic) și rezervă JavaScript, adaugă cu precizie furigana (note de citire) deasupra caracterelor kanji pe paginile web și în PDF-uri. Include și un dicționar japonez integrat, sinteză vocală (TTS) și traducere — pentru a învăța mai ușor pronunția.

---

## Funcții principale

- **Furigana pe întreaga pagină** — Adăugați furigana la toate kanji-urile cu un singur clic
- **Dicționar la hover** — Treceți peste caracterele adnotate pentru definiții JMdict (peste 180 000 de intrări), citiri, insignele nivelului JLPT (N5–N1) și butoane de pronunțare; alegeți modul Dictionary, Reading sau Off
- **Cititor PDF** — Cititor PDF integrat cu furigana, dicționar, vorbire și traducere; glisare și plasare, încărcare din URL și detectare automată PDF cu redirecționare inteligentă
- **Trei stiluri de citire** — Hiragana, Katakana și Romaji
- **Separarea okuriganei** — Separă corect okurigana (送り仮名) de rădăcina kanji
- **Suport jukujikun** — Citiri corecte pentru compuși multi-kanji cu citiri speciale (熟字訓)
- **Text în vorbire** — Faceți clic pe pictograma difuzorului pentru pronunția în japoneză
- **Vorbire pe selecție cu efect karaoke** — Selectați text japonez; apare o bară compactă cu butoane de vorbire și traducere; în timpul redării, cuvintele sau caracterele sunt evidențiate în timp real (karaoke), sincron cu audio
- **Traducere pe selecție** — Selectați text, faceți clic pe traducere în bară pentru rezultat instant prin Bing sau Google Translate, într-o bulă inline
- **Scurtături de tastatură** — Acces rapid la funcțiile esențiale prin scurtături personalizabile
- **Interfață multilingvă** — 38 de limbi pentru interfață

---

## Cum se folosește

### Pasul 1: Instalați extensia

Instalați **Furigana Reader** din [Chrome Web Store](https://chromewebstore.google.com/) sau încărcați-o local în modul dezvoltator.

### Pasul 2: Deschideți orice pagină

Accesați o pagină cu conținut în japoneză.

### Pasul 3: Activați furigana

Faceți clic pe pictograma extensiei din bara de instrumente. Activați „Enable Furigana”, apoi „Whole Page Furigana” pentru a adnota toate kanji-urile. Puteți folosi și butonul plutitor din dreapta jos.

### Pasul 4: Vizualizați furigana

Treceți peste caractere pentru sfaturi cu citiri și definiții din dicționar. Faceți clic pe pictograma difuzorului pentru pronunțare.

### Pasul 5: Vorbiți și traduceți selecția

Selectați text japonez cu mouse-ul. Lângă selecție apare o bară compactă cu două butoane:
- **🔊 Speak** — Citește selecția cu evidențiere tip karaoke
- **🌐 Translate** — Afișează o bulă de traducere sub bară

Puteți și clic dreapta: „Furigana Reader > Read aloud selection” sau „Furigana Reader > Translate Selection”.

> **Sfat:** Faceți clic pe pictograma extensiei pentru panoul de setări: stil furigana, mod hover, viteză vorbire, motor de traducere etc.

---

## Dicționar la hover

Extensia include un dicționar japonez integrat bazat pe JMdict (peste 180 000 de intrări). În setări puteți alege modul de hover:

| Mod | Comportament |
|-----|--------------|
| **Dictionary** | Hover: citire + definiție + JLPT + buton pronunțare |
| **Reading** | Hover: citire + buton pronunțare (fără definiții) |
| **Off** | Fără efect la hover |

În modul **Dictionary**, sfatul afișează:
- Cuvântul și citirea sa (furigana)
- Buton de pronunțare (clic pentru audio)
- Definiții japoneze din JMdict
- Insigna nivelului JLPT (N5–N1) când este disponibilă

> **Sfat:** Datele dicționarului se încarcă la cerere în modul Dictionary și se eliberează în alte moduri pentru a economisi memoria.

---

## Cititor PDF

Furigana Reader include un cititor PDF integrat cu furigana, dicționar, vorbire și traducere — aceleași funcții ca pe paginile web, acum și pentru PDF.

### Deschiderea unui PDF

**Metoda 1: Din popup**  
Faceți clic pe pictograma extensiei, apoi pe „Open PDF Reader”. Glisați un PDF sau faceți clic pe „Choose File” pentru un fișier local. Puteți lipi și un URL PDF.

**Metoda 2: Meniu contextual**  
Clic dreapta pe un link `.pdf` și alegeți „Open PDF with Furigana Reader”.

**Metoda 3: Detectare automată**  
Când „PDF Smart Detection” este activat în setări, extensia redirecționează automat URL-urile care se termină în `.pdf` către cititorul integrat. Dacă PDF-ul este detectat dar nu redirecționat (ex. vizualizatorul Chrome), apar notificări pentru deschidere în Furigana Reader.

### Funcții ale cititorului PDF

- **Adnotări furigana** — Toate funcțiile furigana pe textul PDF, inclusiv modul întreaga pagină și sfaturile la hover
- **Cinci moduri furigana** — Hiragana, Katakana, Romaji, doar hover și oprit
- **Dicționar la clic** — Faceți clic pe un cuvânt pentru definiția JMdict (în PDF se folosește clicul în locul hover pentru lectură fără distrageri)
- **Bară selecție** — Selectați text pentru vorbire, traducere sau copiere
- **Panou lateral** — Cuprins și miniaturi pagini
- **Căutare** — Căutare text integral în PDF
- **Teme** — Întunecat, luminos și sepia
- **Zoom** — Mai multe niveluri, inclusiv furigana adaptată la zoom
- **Scurtături** — Săgeți pentru navigare, +/- pentru zoom, Ctrl/Cmd+F pentru căutare

---

## Vorbire pe selecție și karaoke

Funcția de vorbire permite selectarea oricărui text japonez și redarea cu un singur clic — utilă pentru pronunția propozițiilor și exercițiul de citire.

**Metoda 1: Bară selecție**  
Selectați text japonez. Apare bara cu butoanele 🔊 speak și 🌐 translate. Faceți clic pe speak. În timpul redării, cuvintele sau caracterele sunt evidențiate în timp real (karaoke).

**Metoda 2: Meniu contextual**  
După selecție, clic dreapta: „Furigana Reader > Read aloud selection”.

**Metoda 3: Scurtătură**  
Selectați text și apăsați `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Sfat:** Evidențierea karaoke funcționează cel mai bine când browserul suportă evenimente de graniță cuvânt TTS. Altfel se folosește o evidențiere de rezervă bazată pe timp.

---

## Traducere

Selectați orice text pe pagină și folosiți traducerea pentru rezultate instantanee.

**Metoda 1: Bară selecție**  
Selectați text, apoi faceți clic pe 🌐 translate în bară. Sub bară apare o bulă cu rezultatul și buton de copiere.

**Metoda 2: Meniu contextual**  
Selectați text, clic dreapta: „Furigana Reader > Translate Selection”.

**Metoda 3: Scurtătură**  
Selectați text și apăsați `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motoare de traducere:**
- **Bing Translate** (implicit) — Microsoft Translator
- **Google Translate** — Google

Ambele suportă **108 limbi țintă**.

Motorul și limba țintă se schimbă în setările extensiei. Limba țintă este detectată automat din limba browserului.

> **Sfat:** Faceți clic în afara barei sau bulei pentru a le închide.

---

## Scurtături de tastatură

| Scurtătură | Mac | Acțiune |
|------------|-----|---------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Comută adnotările furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Citește textul selectat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduce textul selectat |

> **Sfat:** Personalizați scurtăturile în Chrome la `chrome://extensions/shortcuts`.

---

## Ghid setări

| Setare | Descriere |
|--------|-----------|
| **Enable Furigana** | Comutator principal pentru funcția furigana |
| **Whole Page Furigana** | Furigana pentru toate kanji-urile (poate afecta aspectul paginii) |
| **Hover Mode** | Comportament la hover: Dictionary (citire + definiții + JLPT + audio), Reading (citire + audio) sau Off |
| **Furigana Style** | Hiragana, Katakana sau Romaji |
| **Speech Rate** | Viteza citirii propozițiilor |
| **Translation Engine** | Bing Translate sau Google Translate |
| **Target Language** | Limba țintă a traducerii (auto din limba browserului) |
| **PDF Smart Detection** | Redirecționare automată a URL-urilor PDF către cititorul integrat și notificări la detectarea PDF |

---

## Întrebări frecvente

**Î: De ce nu funcționează pe unele pagini?**  
R: Din motive de securitate, extensiile nu rulează pe pagini speciale precum `chrome://`, setările browserului sau Chrome Web Store.

**Î: Ce fac dacă furigana este inexactă?**  
R: Cuvinte rare sau citiri speciale (熟字訓) pot fi eronate. Îmbunătățim continuu. Trimiteți cazuri concrete.

**Î: Nu există sunet de la TTS?**  
R: Verificați volumul sistemului și pachetele vocale japoneze. Suportul variază după browser și sistem de operare.

**Î: Modul întreaga pagină afectează aspectul?**  
R: Furigana necesită spațiu suplimentar. Dacă deranjează, dezactivați modul și folosiți sfaturi la hover.

**Î: Traducerea nu merge?**  
R: Este necesară conexiunea la internet. Dacă Bing eșuează, încercați Google în setări. Unele rețele pot bloca serviciile de traducere.

**Î: Cum deschid un PDF în Furigana Reader?**  
R: „Open PDF Reader” din popup, clic dreapta pe link PDF — „Open PDF with Furigana Reader”, sau activați „PDF Smart Detection” pentru redirecționare automată.

**Î: PDF Smart Detection este activat, dar unele PDF nu se redirecționează?**  
R: Redirecționarea automată funcționează pentru URL-uri care se termină în `.pdf`. Pentru PDF fără extensie în URL sau în vizualizatorul Chrome, apar notificări și o insignă pentru deschidere în Furigana Reader.

**Î: Pot folosi dicționarul offline?**  
R: Da. JMdict (peste 180 000 de intrări) este inclus integral în extensie. Toate căutările sunt locale, fără rețea.

---

## Linkuri conexe

- [Politica de confidențialitate](../privacy-policy)
- [Suport și feedback](../support)

---
