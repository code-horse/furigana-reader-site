---
layout: bare
title: Estensione Furigana Reader - Guida utente
lang: it
---

# Furigana Reader - Guida utente

> Versione: v1.4.3

## Introduzione

Furigana Reader è un’estensione del browser per chi studia giapponese. Grazie a un analizzatore morfologico WASM (Lindera + IPAdic) con fallback JavaScript, aggiunge con precisione furigana (annotazioni di lettura) ai kanji nelle pagine web e nei PDF. Include anche un dizionario giapponese integrato, sintesi vocale e traduzione, per imparare la pronuncia giapponese più facilmente.

---

## Funzionalità principali

- **Modalità furigana su tutta la pagina** — Aggiungi furigana a tutti i kanji con un clic
- **Dizionario al passaggio del mouse** — Passa il mouse sui caratteri annotati per vedere definizioni JMdict (oltre 180.000 voci), letture, badge di livello JLPT (N5–N1) e pulsanti di pronuncia; scegli tra modalità Dizionario, Lettura o Disattivato
- **Lettore PDF** — Lettore PDF integrato con furigana, dizionario, voce e traduzione; supporta drag & drop, caricamento da URL e rilevamento automatico dei PDF con reindirizzamento intelligente
- **Tre stili di lettura** — Hiragana, katakana e rōmaji
- **Separazione dell’okurigana** — Separa correttamente l’okurigana (送り仮名) dal tronco in kanji
- **Supporto jukujikun** — Letture corrette per composti di più kanji con letture speciali (熟字訓)
- **Sintesi vocale** — Clicca sul pulsante altoparlante per ascoltare la pronuncia giapponese
- **Lettura della selezione con effetto karaoke** — Seleziona qualsiasi testo giapponese; compare una barra compatta con parlare e tradurre; la voce va con evidenziazione parola per parola o carattere per carattere in tempo reale (effetto karaoke) sincronizzata all’audio
- **Traduzione della selezione** — Seleziona testo, clicca traduci nella barra per una traduzione istantanea con Bing o Google Translate, in una bolla in linea
- **Scorciatoie da tastiera** — Accesso rapido alle funzioni principali tramite scorciatoie personalizzabili
- **Interfaccia multilingue** — 38 lingue dell’interfaccia

---

## Come usarla

### Passo 1: Installare l’estensione

Installa **Furigana Reader** dal [Chrome Web Store](https://chromewebstore.google.com/) o caricala in locale in modalità sviluppatore.

### Passo 2: Aprire una pagina web

Apri una pagina con contenuto in giapponese.

### Passo 3: Abilitare i furigana

Clicca sull’icona dell’estensione nella barra degli strumenti. Attiva «Abilita furigana», poi «Furigana su tutta la pagina» per annotare tutti i kanji. Puoi anche usare il pulsante fluttuante in basso a destra.

### Passo 4: Visualizzare i furigana

Passa il mouse sui caratteri per vedere i tooltip con letture e definizioni dal dizionario. Clicca sull’icona dell’altoparlante per la pronuncia.

### Passo 5: Parlare e tradurre il testo selezionato

Seleziona testo giapponese con il mouse. Vicino alla selezione compare una barra compatta con due pulsanti:
- **🔊 Parla** — Legge il testo ad alta voce con evidenziazione in stile karaoke
- **🌐 Traduci** — Mostra una bolla di traduzione in linea sotto la barra

Puoi anche fare clic destro e scegliere «Furigana Reader > Leggi ad alta voce la selezione» o «Furigana Reader > Traduci la selezione».

> **Suggerimento:** Clicca sull’icona dell’estensione per aprire le impostazioni e regolare stile furigana, modalità al passaggio del mouse, velocità della voce, motore di traduzione e altro.

---

## Dizionario al passaggio del mouse

L’estensione include un dizionario giapponese integrato basato su JMdict (oltre 180.000 voci). Nelle impostazioni puoi scegliere tra più modalità al passaggio del mouse:

| Modalità | Comportamento |
|----------|---------------|
| **Dizionario** | Al passaggio: lettura + definizione + livello JLPT + pulsante pronuncia |
| **Lettura** | Al passaggio: lettura + pulsante pronuncia (senza definizioni) |
| **Disattivato** | Nessun effetto al passaggio del mouse |

In modalità **Dizionario**, il tooltip mostra:
- La parola e la sua lettura (furigana)
- Un pulsante di pronuncia (clic per ascoltare)
- Definizioni in giapponese da JMdict
- Badge di livello JLPT (N5–N1) quando disponibile

> **Suggerimento:** I dati del dizionario si caricano on demand quando la modalità Dizionario è attiva e vengono scaricati passando ad altre modalità per risparmiare memoria.

---

## Lettore PDF

Furigana Reader include un lettore PDF integrato per leggere documenti PDF con furigana, dizionario, voce e traduzione: le stesse funzioni delle pagine web, ora anche sui PDF.

### Aprire un PDF

**Metodo 1: Dal popup**  
Clicca sull’icona dell’estensione, poi su «Apri lettore PDF». Trascina un file PDF o clicca «Scegli file» per aprire un PDF locale. Puoi anche incollare un URL di un PDF.

**Metodo 2: Menu contestuale**  
Clic destro su un link `.pdf` e scegli «Apri PDF con Furigana Reader».

**Metodo 3: Rilevamento automatico**  
Con «Rilevamento intelligente PDF» attivo nelle impostazioni, l’estensione reindirizza automaticamente gli URL `.pdf` al lettore integrato. Se un PDF viene rilevato ma non reindirizzato (ad es. nel visualizzatore integrato di Chrome), vedrai notifiche e inviti ad aprirlo in Furigana Reader.

### Funzioni del lettore PDF

- **Furigana** — Tutte le funzioni furigana sul testo del PDF, inclusa la modalità pagina intera e i tooltip
- **Cinque modalità furigana** — Hiragana, katakana, rōmaji, solo al passaggio del mouse e disattivato
- **Dizionario al clic** — Clic su una parola per la definizione JMdict (nel PDF si usa il clic invece del passaggio del mouse per una lettura meno invasiva)
- **Barra di selezione** — Seleziona testo per parlare, tradurre o copiare
- **Barra laterale** — Indice e miniature di pagina
- **Ricerca** — Ricerca full-text nel PDF
- **Temi** — Scuro, chiaro e seppia
- **Zoom** — Più livelli di zoom, incluso furigana adattivo allo zoom
- **Scorciatoie da tastiera** — Frecce per navigare, +/- per zoom, Ctrl/Cmd+F per cercare

---

## Lettura della selezione e karaoke

La lettura della selezione consente di selezionare qualsiasi testo giapponese e ascoltarlo con un clic: ideale per la pronuncia delle frasi e la pratica di lettura.

**Metodo 1: Barra di selezione**  
Seleziona testo giapponese con il mouse. Compare una barra compatta con 🔊 parla e 🌐 traduci. Clicca parla per riprodurre. Durante la lettura, ogni parola o carattere viene evidenziato in tempo reale (effetto karaoke).

**Metodo 2: Menu contestuale**  
Dopo aver selezionato testo giapponese, clic destro e «Furigana Reader > Leggi ad alta voce la selezione».

**Metodo 3: Scorciatoia da tastiera**  
Seleziona testo e premi `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) per parlare.

> **Suggerimento:** L’evidenziazione karaoke funziona meglio se il browser supporta gli eventi di confine delle parole TTS. In caso contrario, l’estensione usa un fallback basato sul tempo.

---

## Traduzione

Seleziona qualsiasi testo nella pagina e usa la traduzione per ottenere risultati immediati.

**Metodo 1: Barra di selezione**  
Seleziona testo, poi clicca 🌐 traduci nella barra. Sotto compare una bolla con il risultato e un pulsante copia.

**Metodo 2: Menu contestuale**  
Seleziona testo, clic destro e «Furigana Reader > Traduci la selezione».

**Metodo 3: Scorciatoia da tastiera**  
Seleziona testo e premi `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) per tradurre.

**Motori di traduzione:**
- **Bing Translate** (predefinito) — Microsoft Translator
- **Google Translate** — Google

Entrambi supportano **108 lingue di destinazione**.

Puoi cambiare motore e lingua di destinazione nelle impostazioni dell’estensione. La lingua di destinazione viene rilevata automaticamente dalla lingua del browser.

> **Suggerimento:** Clicca fuori dalla barra o dalla bolla per chiuderle.

---

## Scorciatoie da tastiera

| Scorciatoia | Scorciatoia Mac | Azione |
|-------------|-----------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Attiva/disattiva le annotazioni furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Leggi ad alta voce il testo selezionato |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduci il testo selezionato |

> **Suggerimento:** Puoi personalizzare queste scorciatoie in Chrome su `chrome://extensions/shortcuts`.

---

## Guida alle impostazioni

| Impostazione | Descrizione |
|--------------|-------------|
| **Abilita furigana** | Interruttore principale per attivare o disattivare i furigana |
| **Furigana su tutta la pagina** | Se attivo, mostra i furigana per tutti i kanji (può influire sul layout) |
| **Modalità al passaggio del mouse** | Comportamento al passaggio: Dizionario (lettura + definizioni + JLPT + audio), Lettura (lettura + audio) o Disattivato |
| **Stile furigana** | Hiragana, katakana o rōmaji |
| **Velocità della voce** | Velocità della lettura ad alta voce |
| **Motore di traduzione** | Bing Translate o Google Translate |
| **Lingua di destinazione** | Lingua in cui tradurre (rilevata automaticamente dalla lingua del browser) |
| **Rilevamento intelligente PDF** | Se attivo, reindirizza automaticamente gli URL PDF al lettore integrato e mostra notifiche quando vengono rilevati PDF |

---

## Domande frequenti

**D: Perché non funziona su alcune pagine?**  
R: Per motivi di sicurezza le estensioni non girano su pagine speciali (`chrome://`), impostazioni del browser o Chrome Web Store.

**D: E se i furigana non sono accurati?**  
R: Parole rare o letture speciali (jukujikun) possono essere errate. Miglioriamo continuamente; casi specifici ci aiutano.

**D: Nessun audio nella sintesi vocale?**  
R: Controlla il volume di sistema e le voci giapponese installate. Il supporto varia tra browser e sistema operativo.

**D: La modalità pagina intera altera il layout?**  
R: I furigana richiedono spazio aggiuntivo. Se ostacola la lettura, disattiva la modalità pagina intera e usa i tooltip.

**D: La traduzione non funziona?**  
R: La traduzione richiede una connessione internet. Se Bing Translate fallisce, prova Google Translate nelle impostazioni. Alcune reti possono bloccare i servizi di traduzione.

**D: Come apro un PDF con Furigana Reader?**  
R: Puoi aprire i PDF in diversi modi: «Apri lettore PDF» nel popup, clic destro su un link PDF e «Apri PDF con Furigana Reader», oppure abilita «Rilevamento intelligente PDF» per reindirizzare automaticamente gli URL PDF al lettore integrato.

**D: Il rilevamento intelligente PDF è attivo ma alcuni PDF non vengono reindirizzati**  
R: Il reindirizzamento automatico funziona per URL che terminano in `.pdf`. Per PDF serviti senza estensione `.pdf` o aperti nel visualizzatore integrato di Chrome, vedrai una notifica o un badge per aprirli in Furigana Reader.

**D: Posso usare il dizionario offline?**  
R: Sì. Il dizionario JMdict (oltre 180.000 voci) è incluso nell’estensione. Tutte le ricerche sono locali, senza rete.

---

## Link correlati

- [Informativa sulla privacy](../privacy-policy)
- [Supporto e feedback](../support)

---
