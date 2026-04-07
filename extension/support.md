---
layout: bare
title: Furigana Reader Extension - Support
---

# Furigana Reader Extension - Support

## About Furigana Reader Extension

Furigana Reader is a Chrome browser extension that adds furigana (reading annotations) to kanji characters on any web page and PDF. It features a WASM-powered morphological analyzer (Lindera + IPAdic) with JavaScript fallback, whole-page furigana mode, a built-in Japanese dictionary (JMdict, 180K+ entries) with JLPT level badges, hover tooltips, text-to-speech, selection speech with karaoke highlighting, translation via Bing or Google, a built-in PDF reader, and supports 38 interface languages.

---

## Frequently Asked Questions

### General

**Q: Do I need to create an account?**  
A: No. Furigana Reader Extension works entirely locally and does not require any account registration.

**Q: Is my data stored on a server?**  
A: No. All your settings are stored locally in your browser. We do not operate any servers. The only exception is the optional translation feature, which sends selected text to Bing or Google Translate when you explicitly use it.

**Q: Does the extension contain ads?**  
A: No. Furigana Reader Extension is ad-free.

**Q: Which browsers are supported?**  
A: Furigana Reader Extension is designed for Google Chrome and Chromium-based browsers (Edge, Brave, etc.).

### Furigana & Annotations

**Q: How do I enable furigana annotations?**  
A: Click the Furigana Reader icon in your browser toolbar, then toggle "Enable Furigana" on. You can also click the floating button on the bottom-right of any page to toggle whole-page furigana mode.

**Q: Why are some characters annotated incorrectly?**  
A: Japanese has many words with special readings (熟字訓, jukujikun). Our engine covers common cases, but some rare combinations may still be inaccurate. Please report specific cases to help us improve.

**Q: Can I choose between hiragana, katakana, and romaji?**  
A: Yes. Open the extension popup and change "Furigana Style" to switch between Hiragana, Katakana, and Romaji display.

**Q: Why doesn't it work on some pages?**  
A: For security reasons, browser extensions cannot run on special pages like `chrome://`, `edge://`, browser settings, or the Chrome Web Store.

### Dictionary

**Q: How does the hover dictionary work?**  
A: The extension includes a built-in Japanese dictionary powered by JMdict (180,000+ entries). Set the "Hover Mode" to "Dictionary" in the settings, then hover over any annotated character to see its reading, definition, JLPT level, and pronunciation button.

**Q: What are the hover mode options?**  
A: You can choose from three modes: Dictionary (reading + definitions + JLPT + audio), Reading (reading + audio), or Off (no hover effect).

**Q: Does the dictionary work offline?**  
A: Yes. The JMdict dictionary is fully bundled within the extension. All lookups are performed locally without any network connection.

### PDF Reader

**Q: How do I open a PDF with Furigana Reader?**  
A: There are several ways: click "Open PDF Reader" in the popup, right-click a PDF link and choose "Open PDF with Furigana Reader", or enable "PDF Smart Detection" in settings to automatically redirect PDF URLs.

**Q: What is PDF Smart Detection?**  
A: When enabled, the extension automatically redirects `.pdf` URLs to the built-in reader. For PDFs that aren't auto-redirected (e.g. Chrome's built-in viewer), you'll see notifications and badge prompts.

**Q: What features does the PDF reader have?**  
A: The PDF reader supports furigana annotations, five furigana modes (hiragana, katakana, romaji, hover, off), click-to-lookup dictionary, text-to-speech, translation, sidebar with table of contents and thumbnails, text search, three reading themes (dark/light/sepia), and zoom-adaptive furigana.

**Q: Can I open local PDF files?**  
A: Yes. Click "Open PDF Reader" in the popup, then drag & drop a PDF file or click "Choose File" to open a local PDF.

### Text-to-Speech

**Q: How do I hear the pronunciation of a character?**  
A: Hover over an annotated character to see the tooltip, then click the speaker button.

**Q: How do I read aloud a sentence?**  
A: Select any Japanese text on the page. A floating toolbar will appear with a speaker button — click it to read aloud with karaoke-style word highlighting. You can also right-click and choose "Read aloud selection".

**Q: Can I adjust the speech rate?**  
A: Yes. The "Speech Rate" setting in the popup controls the speed for sentence reading.

**Q: No sound from text-to-speech?**  
A: Please check your system volume. TTS quality depends on your operating system's Japanese voice support. On some systems, you may need to install a Japanese voice pack.

### Translation

**Q: How do I translate text?**  
A: Select any text, then click the translate button in the selection toolbar, right-click and choose "Translate Selection", or press Alt+Shift+T (Mac: Ctrl+Shift+T).

**Q: Which translation engines are available?**  
A: Bing Translate (default) and Google Translate. Both support 108 target languages.

**Q: Translation not working?**  
A: Translation requires an internet connection. If Bing Translate fails, try switching to Google Translate in the settings.

### Troubleshooting

**Q: The extension icon is grayed out.**  
A: This usually means you're on a page where extensions cannot run (e.g., `chrome://` pages). Navigate to a regular web page.

**Q: Annotations are not showing after enabling.**  
A: Try refreshing the page. If the page was loaded before the extension was enabled, it may need a refresh.

---

## Contact Us

If you have questions, feedback, or need assistance, please reach out to us:

- **Email**: [2008-horse@163.com](mailto:2008-horse@163.com)

We typically respond within 2 business days.

---

## Related Links

- [Extension Privacy Policy](./privacy-policy)
- [App Privacy Policy](../privacy-policy)
- [App Support](../support)
