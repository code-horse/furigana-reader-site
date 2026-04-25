---
layout: bare
title: Privacy Policy — Furigana Reader Extension
---

# Privacy Policy — Furigana Reader Extension

**Last updated**: April 13, 2026

**Effective date**: April 13, 2026

---

## Privacy Policy for Furigana Reader Browser Extension

### 1. Introduction

Welcome to Furigana Reader Extension ("we", "our", "us"). We are committed to protecting your privacy. This Privacy Policy explains how our Chrome browser extension ("Furigana Reader" or "the Extension") handles your information.

**Developer**: code-horse  
**Contact**: 2008-horse@163.com

### 2. Information We Do NOT Collect

Furigana Reader Extension is designed with privacy as a core principle:

- **No account registration required** — You can use all features without creating an account.
- **No personal data collection** — We do not collect, store, or transmit any personal information to external servers.
- **No analytics or tracking** — We do not use any analytics SDKs or tracking tools.
- **No advertising** — The extension contains no advertisements or ad-related tracking.
- **No browsing history recording** — We do not record or transmit the URLs you visit.

### 3. Data Stored Locally in Your Browser

The Extension stores the following data **locally in your browser only** (via Chrome Storage API):

| Data Type | Purpose | Storage |
|-----------|---------|---------|
| Extension settings | Preferences (enable/disable, furigana style, hover mode, speech rate, translation engine, target language, PDF detection, etc.) | Browser local storage |
| UI language preference | Remember your chosen interface language | Browser local storage |

**Important**: All data listed above exists **only in your browser**. It is never uploaded to any server. If you uninstall the extension, this data will be permanently deleted.

### 4. How Furigana Processing Works

All furigana conversion is performed **entirely locally** within your browser:

- The Extension uses a morphological analyzer (Lindera WASM with IPAdic dictionary) bundled within the extension, with a JavaScript fallback engine.
- Kanji recognition and furigana annotation happen on-device.
- **No text is sent to any external server** for furigana processing.

### 5. Dictionary Feature (JMdict)

The Extension includes a built-in Japanese dictionary powered by **JMdict** (a free Japanese-multilingual dictionary project):

- The dictionary contains **180,000+** entries stored locally within the extension.
- All dictionary lookups are performed **entirely offline** — no network requests are made.
- The dictionary data is loaded on-demand and unloaded when disabled to conserve memory.

### 6. PDF Reader

The Extension includes a built-in PDF reader powered by **PDF.js** (Mozilla's open-source PDF rendering library):

- PDF files are rendered and processed **entirely in your browser**. No PDF content is sent to any external server.
- When PDF Smart Detection is enabled, the extension uses Chrome's `declarativeNetRequest` API to redirect `.pdf` URLs to the built-in reader. This redirect happens **locally** within your browser — no data leaves your device.
- All furigana annotation, dictionary lookup, and text-to-speech features within the PDF reader operate locally.

### 7. Translation Feature & Third-Party Services

The Extension includes an optional translation feature that sends selected text to third-party translation services for processing:

| Service | Provider | Data Sent |
|---------|----------|-----------|
| Bing Translate | Microsoft Corporation | Selected text only |
| Google Translate | Google LLC | Selected text only |

**Important**:
- Translation is triggered **only when you explicitly click the translate button** or use the translate keyboard shortcut / context menu. Text is never sent automatically.
- Only the **selected text** is transmitted — no URLs, browsing history, personal data, or other page content is sent.
- The text is sent directly to the translation provider's API. We do not relay, store, or log any translation requests or responses on our servers.
- Please refer to [Microsoft's Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement) and [Google's Privacy Policy](https://policies.google.com/privacy) for details on how these providers handle data.

### 8. Text-to-Speech

The Extension uses Chrome's built-in TTS (Text-to-Speech) API:

- Speech synthesis is handled by your browser's built-in engine.
- No audio data is recorded or transmitted.

### 9. Permissions Explained

The Extension requests the following browser permissions:

| Permission | Purpose |
|------------|---------|
| `storage` | Store user settings (enable/disable state, furigana style, hover mode, speech rate, translation preferences, PDF detection, etc.) |
| `tts` | Use Chrome's built-in Text-to-Speech to read Japanese pronunciation |
| `scripting` | Execute scripts in web pages to add furigana annotations |
| `contextMenus` | Add right-click menu options to speak and translate selected text, and to open PDF links in the built-in reader |
| `notifications` | Show a notification when a PDF page is detected, allowing quick access to the built-in PDF reader |
| `declarativeNetRequest` | Redirect PDF URLs to the built-in PDF reader for furigana annotation (when PDF Smart Detection is enabled) |
| `declarativeNetRequestWithHostAccess` | Required for PDF redirect rules to work on any website |
| `<all_urls>` | Add furigana annotations to kanji characters on any webpage; proxy translation requests to third-party APIs from the background service worker; intercept PDF URLs for the built-in reader |

### 10. Third-Party Libraries

| Library | Purpose | Data Handling |
|---------|---------|---------------|
| PDF.js (Mozilla) | Render PDF documents | Runs entirely locally |
| JMdict | Japanese dictionary definitions | Pre-built data bundled locally |
| Lindera (WASM) | Morphological analysis | Runs entirely locally |

### 11. Children's Privacy

The Extension does not knowingly collect personal information from children under 13 years of age. Since we do not collect any personal information from any users, the Extension is safe for users of all ages.

### 12. Data Deletion

To remove all Extension data:

- Uninstalling the extension will permanently remove all associated settings from your browser.
- You can also clear extension data via Chrome Settings > Extensions > Furigana Reader > Details > Clear Data.

### 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last updated" date at the top of this page.

### 14. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

- **Email**: 2008-horse@163.com

---

*This privacy policy applies to the Furigana Reader browser extension. For the Furigana Reader mobile app privacy policy, please see [App Privacy Policy](../privacy-policy).*
