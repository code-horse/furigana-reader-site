---
layout: bare
title: Privacy Policy — Furigana Reader Extension
---

# Privacy Policy — Furigana Reader Extension

**Last updated**: March 24, 2026

**Effective date**: March 24, 2026

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
- **No third-party data sharing** — We do not share any data with third parties.
- **No browsing history recording** — We do not record or transmit the URLs you visit.

### 3. Data Stored Locally in Your Browser

The Extension stores the following data **locally in your browser only** (via Chrome Storage API):

| Data Type | Purpose | Storage |
|-----------|---------|---------|
| Extension settings | Preferences (enable/disable, furigana style, speech rate, etc.) | Browser local storage |
| UI language preference | Remember your chosen interface language | Browser local storage |

**Important**: All data listed above exists **only in your browser**. It is never uploaded to any server. If you uninstall the extension, this data will be permanently deleted.

### 4. Permissions Explained

The Extension requests the following browser permissions:

| Permission | Purpose |
|------------|---------|
| `storage` | Store user settings (enable/disable state, furigana style, speech rate, etc.) |
| `tts` | Use Chrome's built-in Text-to-Speech to read Japanese pronunciation |
| `scripting` | Execute scripts in web pages to add furigana annotations |
| `contextMenus` | Add right-click menu option to speak selected Japanese text |
| `<all_urls>` | Add furigana annotations to kanji characters on any webpage |

### 5. How Furigana Processing Works

All furigana conversion is performed **entirely locally** within your browser:

- The Extension uses a morphological analyzer (Lindera WASM) bundled within the extension, with a JavaScript fallback engine.
- Kanji recognition and furigana annotation happen on-device.
- **No text is sent to any external server** for processing.

### 6. Text-to-Speech

The Extension uses Chrome's built-in TTS (Text-to-Speech) API:

- Speech synthesis is handled by your browser's built-in engine.
- No audio data is recorded or transmitted.

### 7. Children's Privacy

The Extension does not knowingly collect personal information from children under 13 years of age. Since we do not collect any personal information from any users, the Extension is safe for users of all ages.

### 8. Data Deletion

To remove all Extension data:

- Uninstalling the extension will permanently remove all associated settings from your browser.
- You can also clear extension data via Chrome Settings > Extensions > Furigana Reader > Details > Clear Data.

### 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last updated" date at the top of this page.

### 10. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

- **Email**: 2008-horse@163.com

---

*This privacy policy applies to the Furigana Reader browser extension.*
