---
layout: bare
title: Furigana Reader Extension - User Guide
lang: en
---

# Furigana Reader - User Guide

> Version: v1.4.3

## Introduction

Furigana Reader is a browser extension designed for Japanese learners. Powered by a WASM morphological analyzer (Lindera + IPAdic) with JavaScript fallback, it accurately adds furigana reading annotations to kanji characters on web pages and PDFs. It also includes a built-in Japanese dictionary, text-to-speech, and translation features — helping you learn Japanese pronunciation more easily.

---

## Main Features

- **Whole Page Furigana Mode** — Add furigana annotations to all kanji characters on the page with one click
- **Hover Dictionary** — Hover over annotated characters to see JMdict definitions (180K+ entries), readings, JLPT level badges (N5–N1), and pronunciation buttons; choose between Dictionary mode, Reading mode, or Off
- **PDF Reader** — Built-in PDF reader with furigana annotations, dictionary, speech, and translation; supports drag & drop, URL loading, and automatic PDF detection with smart redirect
- **Three Reading Styles** — Support for Hiragana, Katakana, and Romaji display
- **Okurigana Splitting** — Accurately splits okurigana (送り仮名) from kanji stems
- **Jukujikun Support** — Correct readings for multi-kanji compounds with special readings (熟字訓)
- **Text-to-Speech** — Click the speaker button to hear Japanese pronunciation
- **Selection Speech with Karaoke Effect** — Select any Japanese text; a compact toolbar appears with speak and translate buttons; speech plays with real-time word-by-word or character-by-character highlighting (karaoke effect) synced to the audio
- **Selection Translation** — Select any text, click the translate button in the toolbar to get instant translation via Bing or Google Translate, displayed in an inline bubble
- **Keyboard Shortcuts** — Quick access to core features via customizable keyboard shortcuts
- **Multilingual Interface** — Supports 38 interface languages

---

## How to Use

### Step 1: Install the Extension

Install **Furigana Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any web page containing Japanese content.

### Step 3: Enable Furigana

Click the extension icon in your browser toolbar. Toggle "Enable Furigana" on, then toggle "Whole Page Furigana" to annotate all kanji on the page. You can also click the floating button at the bottom right.

### Step 4: View Furigana

Hover over characters to see furigana tooltips with readings and dictionary definitions. Click the speaker icon to hear pronunciation.

### Step 5: Speak and Translate Selected Text

Select any Japanese text with your mouse. A compact toolbar appears near the selection with two buttons:
- **🔊 Speak** — Reads the selected text aloud with karaoke-style highlighting
- **🌐 Translate** — Shows an inline translation bubble below the toolbar

You can also right-click and choose "Furigana Reader > Read aloud selection" or "Furigana Reader > Translate Selection".

> **Tip:** Click the extension icon in your browser toolbar to open the settings panel and adjust furigana style, hover mode, speech rate, translation engine, and more.

---

## Hover Dictionary

The extension includes a built-in Japanese dictionary powered by JMdict (180,000+ entries). You can choose from multiple hover modes in the settings:

| Mode | Behavior |
|------|----------|
| **Dictionary** | Hover shows reading + definition + JLPT level + pronunciation button |
| **Reading** | Hover shows reading + pronunciation button (no definitions) |
| **Off** | No hover effect |

In **Dictionary mode**, the tooltip displays:
- The word and its reading (furigana)
- A pronunciation button (click to hear)
- Japanese definitions from JMdict
- JLPT level badge (N5–N1) when available

> **Tip:** The dictionary data is loaded on-demand when Dictionary mode is enabled, and unloaded when switched to other modes to conserve memory.

---

## PDF Reader

Furigana Reader includes a built-in PDF reader that allows you to read PDF documents with furigana annotations, dictionary, speech, and translation — all the features you enjoy on web pages, now available for PDFs.

### Opening a PDF

**Method 1: From the Popup**  
Click the extension icon, then click "Open PDF Reader". Drag & drop a PDF file or click "Choose File" to open a local PDF. You can also paste a PDF URL.

**Method 2: Context Menu**  
Right-click any `.pdf` link on a web page and choose "Open PDF with Furigana Reader".

**Method 3: Automatic Detection**  
When "PDF Smart Detection" is enabled in settings, the extension automatically redirects `.pdf` URLs to the built-in reader. When a PDF is detected but not redirected (e.g. Chrome's built-in viewer), you'll see notifications and prompts to open it in Furigana Reader.

### PDF Reader Features

- **Furigana Annotations** — All furigana features work on PDF text, including whole-page mode and hover tooltips
- **Five Furigana Modes** — Hiragana, Katakana, Romaji, Hover only, and Off
- **Click Dictionary** — Click on any word to see its JMdict definition (in PDF, click is used instead of hover for a distraction-free reading experience)
- **Selection Toolbar** — Select text to speak, translate, or copy
- **Sidebar** — Table of contents outline and page thumbnails
- **Search** — Full-text search in the PDF
- **Themes** — Dark, Light, and Sepia reading themes
- **Zoom** — Multiple zoom levels including zoom-adaptive furigana
- **Keyboard Shortcuts** — Arrow keys for navigation, +/- for zoom, Ctrl/Cmd+F for search

---

## Selection Speech & Karaoke

The selection speech feature allows you to select any Japanese text and read it aloud with one click — perfect for learning sentence pronunciation and reading practice.

**Method 1: Selection Toolbar**  
Select Japanese text with your mouse. A compact toolbar appears near the selection with a 🔊 speak button and a 🌐 translate button. Click the speak button to play. As the text is read aloud, each word or character is highlighted in real time (karaoke effect), helping you follow along.

**Method 2: Right-Click Menu**  
After selecting Japanese text, right-click and choose "Furigana Reader > Read aloud selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) to speak.

> **Tip:** The karaoke highlighting effect works best when your browser supports TTS word boundary events. If not supported, the extension uses a timing-based fallback for smooth highlighting.

---

## Translation

Select any text on the page and use the translation feature to get instant translations.

**Method 1: Selection Toolbar**  
Select text, then click the 🌐 translate button in the toolbar. A translation bubble appears below showing the result, with a copy button.

**Method 2: Right-Click Menu**  
Select text, right-click and choose "Furigana Reader > Translate Selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) to translate.

**Translation Engines:**
- **Bing Translate** (default) — Powered by Microsoft Translator
- **Google Translate** — Powered by Google

Both engines support **108 target languages**.

You can switch the translation engine and target language in the extension settings. The target language is automatically detected from your browser language.

> **Tip:** Click anywhere outside the toolbar or bubble to dismiss them.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Action |
|----------|-------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Toggle furigana annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Speak selected text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Translate selected text |

> **Tip:** You can customize these shortcuts in Chrome at `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable Furigana** | Master switch to enable or disable the furigana annotation feature |
| **Whole Page Furigana** | When enabled, displays furigana for all kanji characters (may affect page layout) |
| **Hover Mode** | Choose hover behavior: Dictionary (reading + definitions + JLPT + audio), Reading (reading + audio), or Off |
| **Furigana Style** | Choose between Hiragana, Katakana, or Romaji display |
| **Speech Rate** | Adjust the speed of sentence reading |
| **Translation Engine** | Choose between Bing Translate and Google Translate |
| **Target Language** | Set the translation target language (auto-detected from browser language) |
| **PDF Smart Detection** | When enabled, automatically redirects PDF URLs to the built-in reader and shows notifications when PDFs are detected |

---

## FAQ

**Q: Why doesn't it work on some pages?**  
A: For security reasons, browser extensions cannot run on special pages like `chrome://`, browser settings, or the Chrome Web Store.

**Q: What if furigana is inaccurate?**  
A: Some rare words or special readings (熟字訓) may have errors. We're continuously improving. Please share specific cases to help us improve.

**Q: No sound from text-to-speech?**  
A: Please check your system volume settings and ensure Japanese voice packs are installed. Speech support varies across browsers and operating systems.

**Q: Whole page mode affects layout?**  
A: Furigana annotations require extra space, which may affect the original page layout. If it affects reading, disable whole page mode and use hover tooltips instead.

**Q: Translation not working?**  
A: Translation requires an internet connection. If Bing Translate fails, try switching to Google Translate in the settings. Some network environments may block access to translation services.

**Q: How do I open a PDF with Furigana Reader?**  
A: You can open PDFs in several ways: click "Open PDF Reader" in the popup, right-click a PDF link and choose "Open PDF with Furigana Reader", or enable "PDF Smart Detection" in settings to automatically redirect PDF URLs to the built-in reader.

**Q: PDF Smart Detection is enabled but some PDFs don't redirect?**  
A: Auto-redirect works for URLs ending in `.pdf`. For PDFs served without a `.pdf` extension or viewed in Chrome's built-in viewer, you'll see a notification and badge prompting you to open it in Furigana Reader.

**Q: Can I use the dictionary offline?**  
A: Yes. The JMdict dictionary (180,000+ entries) is fully bundled within the extension. All lookups are performed locally without any network connection.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
