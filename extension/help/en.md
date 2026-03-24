---
layout: bare
title: Furigana Reader Extension - User Guide
lang: en
---

# Furigana Reader - User Guide

> Version: v2.0.0

## Introduction

Furigana Reader is a browser extension designed for Japanese learners. Powered by a WASM morphological analyzer (Lindera) with JavaScript fallback, it accurately adds furigana reading annotations to kanji characters on web pages, helping you learn Japanese pronunciation more easily.

---

## Main Features

- **Text Selection Annotation** — Select Japanese text on web pages to automatically display furigana and speech buttons
- **Whole Page Furigana Mode** — Add furigana annotations to all kanji characters on the page with one click
- **Text-to-Speech** — Click the speaker button to hear Japanese pronunciation
- **Selection Speech** — Select any Japanese text, click the floating button or right-click "Read aloud selection" to read aloud
- **Hover Tooltips** — Hover over annotated characters to see furigana and pronunciation buttons
- **Multiple Furigana Styles** — Support for Hiragana, Katakana, and Romaji display
- **Multilingual Interface** — Supports 38 interface languages

---

## How to Use

### Step 1: Install the Extension

Install **Furigana Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any web page containing Japanese content.

### Step 3: Select Text or Use Floating Button

Select Japanese text you want to annotate, or click the floating button at the bottom right to enable whole page furigana mode.

### Step 4: View Furigana

Hover over characters to see furigana tooltips, click the speaker icon to hear pronunciation.

### Step 5: Speak Selected Text

Select any Japanese text with mouse, click the floating speaker button to speak; or right-click and choose "Read aloud selection".

> **Tip:** Click the extension icon in your browser toolbar to open the settings panel and adjust furigana style, speech rate, and more.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable Furigana** | Master switch to enable or disable the furigana annotation feature |
| **Whole Page Furigana** | When enabled, displays furigana for all kanji characters (may affect page layout) |
| **Furigana Style** | Choose between Hiragana, Katakana, or Romaji display |
| **Speech Rate** | Adjust the speed of sentence reading |
| **Hover Tooltips** | Show furigana tooltip on mouse hover |

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

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
