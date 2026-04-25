---
layout: bare
title: Furigana Reader-Erweiterung - Benutzerhandbuch
lang: de
---

# Furigana Reader - Benutzerhandbuch

> Version: v1.4.3

## Einführung

Furigana Reader ist eine Browser-Erweiterung für Japanischlernende. Angetrieben von einem WASM-Morphologieanalysator (Lindera + IPAdic) mit JavaScript-Fallback fügt sie Webseiten und PDFs präzise Furigana-Leseannotationen bei Kanji-Zeichen hinzu. Außerdem enthält sie ein integriertes Japanisch-Wörterbuch, Text-zu-Sprache und Übersetzungsfunktionen – damit lernen Sie die japanische Aussprache leichter.

---

## Hauptfunktionen

- **Furigana für die ganze Seite** — Mit einem Klick Furigana-Annotationen für alle Kanji auf der Seite
- **Hover-Wörterbuch** — Bewegen Sie die Maus über annotierte Zeichen, um JMdict-Definitionen (über 180.000 Einträge), Lesungen, JLPT-Stufen-Badges (N5–N1) und Aussprache-Buttons zu sehen; wahlweise Wörterbuchmodus, Lesemodus oder Aus
- **PDF-Reader** — Integrierter PDF-Reader mit Furigana, Wörterbuch, Sprachausgabe und Übersetzung; unterstützt Drag & Drop, URL-Laden sowie automatische PDF-Erkennung mit intelligenter Weiterleitung
- **Drei Lesestile** — Darstellung in Hiragana, Katakana und Romaji
- **Okurigana-Trennung** — Trennt Okurigana (送り仮名) zuverlässig von den Kanji-Stämmen
- **Jukujikun-Unterstützung** — Korrekte Lesungen für mehrkanjiige Verbindungen mit Sonderlesungen (熟字訓)
- **Text-zu-Sprache** — Klicken Sie auf den Lautsprecher-Button, um die japanische Aussprache zu hören
- **Auswahl vorlesen mit Karaoke-Effekt** — Markieren Sie beliebigen japanischen Text; eine kompakte Symbolleiste mit Vorlesen- und Übersetzen-Buttons erscheint; die Sprachausgabe hebt Wort für Wort oder Zeichen für Zeichen in Echtzeit hervor (Karaoke-Effekt), synchron zur Audioausgabe
- **Auswahl übersetzen** — Markieren Sie beliebigen Text, klicken Sie in der Symbolleiste auf Übersetzen, um eine sofortige Übersetzung über Bing oder Google Translate in einer eingebetteten Sprechblase zu erhalten
- **Tastenkürzel** — Schneller Zugriff auf Kernfunktionen über anpassbare Tastenkürzel
- **Mehrsprachige Oberfläche** — Unterstützt 38 Oberflächensprachen

---

## Verwendung

### Schritt 1: Erweiterung installieren
Installieren Sie **Furigana Reader** aus dem [Chrome Web Store](https://chromewebstore.google.com/), oder laden Sie sie lokal im Entwicklermodus.

### Schritt 2: Beliebige Webseite öffnen
Besuchen Sie eine Webseite mit japanischen Inhalten.

### Schritt 3: Furigana aktivieren
Klicken Sie auf das Erweiterungssymbol in der Browser-Symbolleiste. Schalten Sie „Furigana aktivieren“ ein, dann „Furigana für ganze Seite“, um alle Kanji auf der Seite zu annotieren. Sie können auch den schwebenden Button unten rechts nutzen.

### Schritt 4: Furigana ansehen
Bewegen Sie die Maus über Zeichen, um Furigana-Tooltips mit Lesungen und Wörterbuchdefinitionen zu sehen. Klicken Sie auf das Lautsprecher-Symbol für die Aussprache.

### Schritt 5: Auswahl vorlesen und übersetzen
Markieren Sie japanischen Text mit der Maus. Eine kompakte Symbolleiste erscheint in der Nähe der Auswahl mit zwei Buttons:
- **🔊 Vorlesen** — Liest den markierten Text mit Karaoke-Hervorhebung vor
- **🌐 Übersetzen** — Zeigt eine eingebettete Übersetzungsblase unter der Symbolleiste

Sie können auch mit der rechten Maustaste „Furigana Reader > Auswahl vorlesen“ oder „Furigana Reader > Auswahl übersetzen“ wählen.

> **Tipp:** Klicken Sie auf das Erweiterungssymbol, um das Einstellungsfenster zu öffnen und Furigana-Stil, Hover-Modus, Sprechgeschwindigkeit, Übersetzungs-Engine und mehr anzupassen.

---

## Hover-Wörterbuch

Die Erweiterung enthält ein integriertes Japanisch-Wörterbuch auf Basis von JMdict (über 180.000 Einträge). In den Einstellungen können Sie mehrere Hover-Modi wählen:

| Modus | Verhalten |
|-------|-----------|
| **Wörterbuch** | Hover zeigt Lesung + Definition + JLPT-Stufe + Aussprache-Button |
| **Lesen** | Hover zeigt Lesung + Aussprache-Button (ohne Definitionen) |
| **Aus** | Kein Hover-Effekt |

Im **Wörterbuchmodus** zeigt der Tooltip:
- Das Wort und seine Lesung (Furigana)
- Einen Aussprache-Button (Klick zum Abspielen)
- Japanische Definitionen aus JMdict
- Ein JLPT-Stufen-Badge (N5–N1), sofern vorhanden

> **Tipp:** Die Wörterbuchdaten werden bei aktiviertem Wörterbuchmodus bei Bedarf geladen und bei Wechsel zu anderen Modi entladen, um Speicher zu sparen.

---

## PDF Reader

Furigana Reader enthält einen integrierten PDF-Reader, mit dem Sie PDFs mit Furigana, Wörterbuch, Sprachausgabe und Übersetzung lesen können – dieselben Funktionen wie auf Webseiten, jetzt für PDFs.

### PDF öffnen

**Methode 1: Über das Popup**  
Klicken Sie auf das Erweiterungssymbol, dann auf „PDF-Reader öffnen“. Ziehen Sie eine PDF-Datei per Drag & Drop oder klicken Sie auf „Datei wählen“, um eine lokale PDF zu öffnen. Sie können auch eine PDF-URL einfügen.

**Methode 2: Kontextmenü**  
Klicken Sie mit der rechten Maustaste auf einen `.pdf`-Link und wählen Sie „PDF mit Furigana Reader öffnen“.

**Methode 3: Automatische Erkennung**  
Ist „PDF Smart Detection“ in den Einstellungen aktiviert, leitet die Erweiterung `.pdf`-URLs automatisch in den integrierten Reader um. Wird ein PDF erkannt, aber nicht umgeleitet (z. B. Chromes integrierter Viewer), erscheinen Hinweise, es in Furigana Reader zu öffnen.

### Funktionen des PDF-Readers

- **Furigana-Annotationen** — Alle Furigana-Funktionen gelten für PDF-Text, einschließlich Vollseitenmodus und Hover-Tooltips
- **Fünf Furigana-Modi** — Hiragana, Katakana, Romaji, nur Hover und Aus
- **Klick-Wörterbuch** — Klicken Sie auf ein Wort für die JMdict-Definition (in PDFs wird statt Hover geklickt, um Ablenkung zu vermeiden)
- **Auswahl-Symbolleiste** — Text markieren zum Vorlesen, Übersetzen oder Kopieren
- **Seitenleiste** — Inhaltsverzeichnis und Seitenminiaturen
- **Suche** — Volltextsuche im PDF
- **Themes** — Dunkel, Hell und Sepia
- **Zoom** — Mehrere Zoomstufen inkl. zoom-adaptivem Furigana
- **Tastenkürzel** — Pfeiltasten zur Navigation, +/- für Zoom, Strg/Cmd+F für Suche

---

## Auswahl vorlesen & Karaoke

Mit der Auswahl-Vorlesefunktion markieren Sie japanischen Text und lassen ihn mit einem Klick vorlesen – ideal für Satzaussprache und Leseübung.

**Methode 1: Auswahl-Symbolleiste**  
Markieren Sie japanischen Text. Eine kompakte Symbolleiste mit 🔊 Vorlesen und 🌐 Übersetzen erscheint. Klicken Sie auf Vorlesen. Während der Wiedergabe werden Wörter oder Zeichen in Echtzeit hervorgehoben (Karaoke-Effekt).

**Methode 2: Kontextmenü**  
Nach der Auswahl: Rechtsklick und „Furigana Reader > Auswahl vorlesen“.

**Methode 3: Tastenkürzel**  
Text markieren und `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) drücken.

> **Tipp:** Die Karaoke-Hervorhebung funktioniert am besten, wenn der Browser TTS-Wortgrenzen unterstützt. Andernfalls nutzt die Erweiterung einen zeitbasierten Fallback.

---

## Übersetzung

Markieren Sie beliebigen Text und nutzen Sie die Übersetzungsfunktion für sofortige Übersetzungen.

**Methode 1: Auswahl-Symbolleiste**  
Text markieren, dann 🌐 Übersetzen in der Symbolleiste klicken. Eine Übersetzungsblase erscheint darunter mit Ergebnis und Kopier-Button.

**Methode 2: Kontextmenü**  
Text markieren, Rechtsklick und „Furigana Reader > Auswahl übersetzen“.

**Methode 3: Tastenkürzel**  
Text markieren und `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) drücken.

**Übersetzungs-Engines:**
- **Bing Translate** (Standard) — Microsoft Translator
- **Google Translate** — Google

Beide unterstützen **108 Zielsprachen**.

Engine und Zielsprache ändern Sie in den Erweiterungseinstellungen. Die Zielsprache wird aus der Browser-Sprache abgeleitet.

> **Tipp:** Klicken Sie außerhalb von Symbolleiste oder Blase, um sie zu schließen.

---

## Tastenkürzel

| Kürzel | Mac-Kürzel | Aktion |
|--------|------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Furigana-Annotationen ein/aus |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Markierten Text vorlesen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Markierten Text übersetzen |

> **Tipp:** Unter `chrome://extensions/shortcuts` in Chrome können Sie die Kürzel anpassen.

---

## Einstellungen

| Einstellung | Beschreibung |
|-------------|--------------|
| **Furigana aktivieren** | Hauptschalter für die Furigana-Annotation |
| **Furigana für ganze Seite** | Zeigt Furigana für alle Kanji (kann das Layout beeinflussen) |
| **Hover-Modus** | Hover-Verhalten: Wörterbuch (Lesung + Definitionen + JLPT + Audio), Lesen (Lesung + Audio) oder Aus |
| **Furigana-Stil** | Hiragana, Katakana oder Romaji |
| **Sprechgeschwindigkeit** | Geschwindigkeit der Vorlesefunktion |
| **Übersetzungs-Engine** | Bing Translate oder Google Translate |
| **Zielsprache** | Zielsprache der Übersetzung (automatisch aus der Browser-Sprache) |
| **PDF Smart Detection** | Leitet PDF-URLs in den integrierten Reader um und zeigt Hinweise bei erkannten PDFs |

---

## FAQ

**F: Warum funktioniert es auf manchen Seiten nicht?**  
A: Aus Sicherheitsgründen können Erweiterungen nicht auf speziellen Seiten wie `chrome://`, Browsereinstellungen oder dem Chrome Web Store ausgeführt werden.

**F: Was tun, wenn Furigana ungenau ist?**  
A: Seltene Wörter oder Sonderlesungen (熟字訓) können fehlerhaft sein. Wir verbessern kontinuierlich. Bitte melden Sie konkrete Fälle.

**F: Kein Ton bei der Sprachausgabe?**  
A: Prüfen Sie die Systemlautstärke und ob japanische Stimmpakete installiert sind. Die Unterstützung variiert je nach Browser und Betriebssystem.

**F: Beeinflusst der Vollseitenmodus das Layout?**  
A: Furigana-Annotationen brauchen Platz und können das ursprüngliche Layout verändern. Wenn das stört, deaktivieren Sie den Vollseitenmodus und nutzen Sie nur Hover-Tooltips.

**F: Übersetzung funktioniert nicht?**  
A: Übersetzung erfordert eine Internetverbindung. Wenn Bing Translate fehlschlägt, wechseln Sie in den Einstellungen zu Google Translate. Manche Netzwerke blockieren Übersetzungsdienste.

**F: Wie öffne ich ein PDF mit Furigana Reader?**  
A: Über „PDF-Reader öffnen“ im Popup, Rechtsklick auf einen PDF-Link „PDF mit Furigana Reader öffnen“, oder aktivieren Sie „PDF Smart Detection“, um `.pdf`-URLs automatisch in den integrierten Reader zu leiten.

**F: PDF Smart Detection ist an, aber manche PDFs werden nicht umgeleitet?**  
A: Die automatische Weiterleitung gilt für URLs, die mit `.pdf` enden. Für PDFs ohne diese Endung oder in Chromes integrierter Viewer erscheinen Benachrichtigung und Hinweis, es in Furigana Reader zu öffnen.

**F: Kann ich das Wörterbuch offline nutzen?**  
A: Ja. Das JMdict-Wörterbuch (über 180.000 Einträge) ist vollständig in der Erweiterung enthalten. Alle Abfragen erfolgen lokal ohne Netzwerk.

---

## Verwandte Links

- [Datenschutzerklärung](../privacy-policy)
- [Support und Feedback](../support)

---
</think>
Fixing a corrupted settings table in `de.md`.

<｜tool▁calls▁begin｜><｜tool▁call▁begin｜>
StrReplace