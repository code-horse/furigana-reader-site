---
layout: bare
title: Furigana Reader — Guia d'usuari
lang: ca
---

# Furigana Reader — Guia d'usuari

> Versió: v1.4.0

## Introducció

Furigana Reader és una extensió del navegador per a qui aprèn japonès. Amb un analitzador morfològic WASM (Lindera + IPAdic) i reserva en JavaScript, afegeix furigana (notes de lectura) als kanji de les pàgines web i dels PDF amb precisió. També inclou un diccionari japonès integrat, text a veu i traducció — facilitant l’aprenentatge de la pronunciació japonesa.

---

## Funcions principals

- **Mode furigana de pàgina sencera** — Amb un sol clic, furigana per a tots els kanji de la pàgina
- **Diccionari en passar el cursor** — Passa el cursor sobre caràcters anotats per veure definicions JMdict (més de 180.000 entrades), lectures, insígnies de nivell JLPT (N5–N1) i botons de pronunciació; tria mode Diccionari, Lectura o Desactivat
- **Lector PDF** — Lector PDF integrat amb furigana, diccionari, veu i traducció; arrossega i deixa anar, càrrega per URL i detecció automàtica de PDF amb redirecció intel·ligent
- **Tres estils de furigana** — Hiragana, katakana i Romaji
- **Separació d’okurigana** — Separa amb precisió l’okurigana (送り仮名) de l’arrel del kanji
- **Suport jukujikun** — Lectures correctes en compostos de diversos kanji amb lectures especials (熟字訓)
- **Text a veu** — Fes clic a la icona d’altaveu per escoltar la pronunciació
- **Veu de la selecció amb efecte karaoke** — Selecciona qualsevol text japonès; apareix una barra compacta amb parlar i traduir; la lectura en veu alta va amb ressaltat paraula a paraula o caràcter a caràcter (karaoke) sincronitzat amb l’àudio
- **Traducció de la selecció** — Selecciona text, fes clic al botó de traduir de la barra per obtenir traducció immediata amb Bing o Google Translate, en una bombolla integrada
- **Dreceres de teclat** — Accés ràpid a les funcions principals amb dreceres configurables
- **Interfície multilingüe** — 38 idiomes d’interfície

---

## Com utilitzar-ho

### Pas 1: Instal·lar l’extensió

Instal·la **Furigana Reader** des del [Chrome Web Store](https://chromewebstore.google.com/), o carrega’l en mode desenvolupador.

### Pas 2: Obre qualsevol pàgina web

Visita una pàgina amb contingut en japonès.

### Pas 3: Activa la furigana

Fes clic a la icona de l’extensió a la barra d’eines. Activa «Activar furigana» i després «Furigana de pàgina sencera» per anotar tots els kanji. També pots usar el botó flotant a la part inferior dreta.

### Pas 4: Veure la furigana

Passa el cursor sobre els caràcters per veure consells amb lectures i definicions del diccionari. Fes clic a l’altaveu per escoltar la pronunciació.

### Pas 5: Parlar i traduir la selecció

Selecciona text japonès amb el ratolí. Apareix una barra compacta a prop de la selecció amb dos botons:
- **🔊 Parlar** — Llegeix la selecció en veu alta amb ressaltat tipus karaoke
- **🌐 Traduir** — Mostra una bombolla de traducció sota la barra

També pots fer clic dret i triar «Furigana Reader > Llegeix en veu alta la selecció» o «Furigana Reader > Traduir la selecció».

> **Consell:** Fes clic a la icona de l’extensió per obrir el panell de configuració: estil de furigana, mode de passar el cursor, velocitat de veu, motor de traducció, etc.

---

## Diccionari en passar el cursor

L’extensió inclou un diccionari japonès integrat basat en JMdict (més de 180.000 entrades). A la configuració pots triar el mode de passar el cursor:

| Mode | Comportament |
|------|--------------|
| **Diccionari** | En passar el cursor: lectura + definició + JLPT + botó de pronunciació |
| **Lectura** | En passar el cursor: lectura + botó de pronunciació (sense definicions) |
| **Desactivat** | Sense efecte en passar el cursor |

En mode **Diccionari**, el consell mostra:
- La paraula i la seva lectura (furigana)
- Botó de pronunciació (clic per escoltar)
- Definicions en japonès de JMdict
- Insígnia de nivell JLPT (N5–N1) quan n’hi hagi

> **Consell:** Les dades del diccionari es carreguen sota demanda quan el mode Diccionari està actiu i s’alliberen en altres modes per estalviar memòria.

---

## Lector PDF

Furigana Reader inclou un lector PDF integrat per llegir documents amb furigana, diccionari, veu i traducció — les mateixes funcions que a la web, ara per als PDF.

### Obrir un PDF

**Mètode 1: Des del popup**  
Fes clic a la icona de l’extensió i després a «Obrir lector PDF». Arrossega i deixa anar un PDF o fes clic a «Trieu un fitxer». També pots enganxar un URL de PDF.

**Mètode 2: Menú contextual**  
Clic dret en un enllaç `.pdf` i «Obrir PDF amb Furigana Reader».

**Mètode 3: Detecció automàtica**  
Amb «Detecció intel·ligent de PDF» activada a la configuració, l’extensió redirigeix automàticament els URL que acaben en `.pdf` al lector integrat. Si el PDF es detecta sense redirigir (p. ex. el visor integrat de Chrome), veuràs notificacions per obrir-lo a Furigana Reader.

### Funcions del lector PDF

- **Furigana** — Totes les funcions de furigana sobre el text del PDF, inclòs el mode de pàgina sencera i els consells
- **Cinc modes de furigana** — Hiragana, katakana, Romaji, Només passar el cursor i Desactivat
- **Diccionari amb clic** — Clic en una paraula per veure la definició JMdict (al PDF s’usa el clic en lloc del cursor per una lectura més tranquil·la)
- **Barra de selecció** — Selecciona text per parlar, traduir o copiar
- **Barra lateral** — Índex i miniatures de pàgines
- **Cerca** — Cerca de text complet al PDF
- **Temes** — Fosc, clar i sèpia
- **Zoom** — Diversos nivells de zoom, inclosa furigana adaptada al zoom
- **Dreceres** — Fletxes per navegar, +/- per zoom, Ctrl/Cmd+F per cercar

---

## Veu de la selecció i karaoke

La veu de la selecció permet seleccionar qualsevol text japonès i escoltar-lo amb un clic — ideal per practicar pronunciació i lectura.

**Mètode 1: Barra de selecció**  
Selecciona text japonès. Apareix una barra amb botó 🔊 de parlar i 🌐 de traduir. Clica parlar; mentre sona, cada paraula o caràcter es ressalta en temps real (karaoke).

**Mètode 2: Menú de clic dret**  
Després de seleccionar, clic dret i «Furigana Reader > Llegeix en veu alta la selecció».

**Mètode 3: Drecera de teclat**  
Selecciona text i prem `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) per parlar.

> **Consell:** El karaoke funciona millor si el navegador admet esdeveniments de límit de paraula del TTS. Si no, l’extensió usa un reemplaçament basat en temps.

---

## Traducció

Selecciona qualsevol text de la pàgina i usa la traducció per obtenir resultats immediats.

**Mètode 1: Barra de selecció**  
Selecciona text i fes clic al botó 🌐 de traduir. Apareix una bombolla amb el resultat i un botó per copiar.

**Mètode 2: Menú de clic dret**  
Selecciona text, clic dret i «Furigana Reader > Traduir la selecció».

**Mètode 3: Drecera**  
Selecciona text i prem `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) per traduir.

**Motors de traducció:**
- **Bing Translate** (per defecte) — Microsoft Translator
- **Google Translate** — Google

Tots dos admeten **108 idiomes de destinació**.

Canvia el motor i l’idioma de destinació a la configuració de l’extensió. L’idioma de destinació es detecta automàticament des de l’idioma del navegador.

> **Consell:** Fes clic fora de la barra o la bombolla per tancar-les.

---

## Dreceres de teclat

| Drecera | Mac | Acció |
|---------|-----|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Activa o desactiva les anotacions de furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Parlar el text seleccionat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduir el text seleccionat |

> **Consell:** Pots personalitzar les dreceres a Chrome a `chrome://extensions/shortcuts`.

---

## Guia de configuració

| Opció | Descripció |
|-------|------------|
| **Activar furigana** | Interruptor principal de la funció de furigana |
| **Furigana de pàgina sencera** | Furigana per a tots els kanji (pot afectar el disseny) |
| **Mode de passar el cursor** | Comportament: Diccionari (lectura + definicions + JLPT + àudio), Lectura (lectura + àudio) o Desactivat |
| **Estil de furigana** | Hiragana, katakana o Romaji |
| **Velocitat de veu** | Velocitat de la lectura en veu alta |
| **Motor de traducció** | Bing Translate o Google Translate |
| **Idioma de destinació** | Idioma de la traducció (detecció automàtica des de l’idioma del navegador) |
| **Detecció intel·ligent de PDF** | Redirigeix automàticament els URL PDF al lector integrat i mostra notificacions quan es detecta un PDF |

---

## Preguntes freqüents

**P: Per què no funciona en algunes pàgines?**  
R: Per motius de seguretat, les extensions no s’executen en pàgines especials com `chrome://`, la configuració del navegador o la Chrome Web Store.

**P: I si la furigana no és precisa?**  
R: Paraules rares o lectures especials (熟字訓) poden tenir errors. Millorem contínuament; envia casos concrets.

**P: No sento so del text a veu?**  
R: Comprova el volum del sistema i els paquets de veu en japonès. El suport varia segons navegador i sistema operatiu.

**P: El mode de pàgina sencera afecta el disseny?**  
R: La furigana necessita espai i pot alterar la pàgina. Si molesta, desactiva el mode sencer i usa consells en passar el cursor.

**P: La traducció no funciona?**  
R: Cal connexió a Internet. Si falla Bing, prova Google a la configuració. Algunes xarxes bloquegen els serveis de traducció.

**P: Com obro un PDF amb Furigana Reader?**  
R: «Obrir lector PDF» al popup, clic dret en enllaç PDF «Obrir PDF amb Furigana Reader», o activa «Detecció intel·ligent de PDF» per redirigir automàticament.

**P: La detecció intel·ligent de PDF està activa però alguns PDF no es redirigeixen?**  
R: La redirecció automàtica s’aplica als URL que acaben en `.pdf`. Per PDF sense extensió o al visor integrat de Chrome, apareixerà una notificació per obrir-los a Furigana Reader.

**P: Puc usar el diccionari sense connexió?**  
R: Sí. El diccionari JMdict (més de 180.000 entrades) va dins l’extensió. Totes les cerques són locals sense xarxa.

---

## Enllaços relacionats

- [Política de privadesa](../privacy-policy)
- [Suport i comentaris](../support)

---
