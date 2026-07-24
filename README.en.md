# Scholaread4Chrome

[中文](README.md) | **English**

A Chrome extension (Manifest V3) that detects downloadable PDF resources on any web page in real time, then lets you download them or add them to your Scholaread reading list with one click — optionally into a folder of your choice.

> ⚠️ **Disclaimer**: This is an unofficial, third-party extension, not affiliated with or endorsed by Scholaread / Nutstore. It reuses your existing Scholaread web login session in the browser — no passwords or API keys required. For personal study and research use only.

## 📥 Download & install (2 minutes)

1. Open the **[Releases page](../../releases)** and download the latest `Scholaread4Chrome-vX.X.X.zip`;
2. Extract it anywhere (e.g. `D:\Scholaread4Chrome`);
3. Visit `chrome://extensions` in Chrome and enable **Developer mode**;
4. Click **Load unpacked** and select the extracted folder;
5. Log in at [scholaread.cn](https://www.scholaread.cn) — you're ready.

## ✨ Features

- **Real-time PDF detection**: `.pdf` links, `/pdf` paths, `citation_pdf_url` meta tags, embedded PDFs, arXiv and IEEE Xplore abstract pages — verified on arXiv, IEEE Xplore, MDPI, Wiley, EuropePMC and more;
- **Floating capsule**: icon + count badge + one-click "Add" button, draggable, expandable list;
- **One-click add to Scholaread**: papers go straight into your reading list and open in the reader; access-controlled PDFs (e.g. IEEE via institutional access) are downloaded in your browser first and uploaded as real files — no more "added but won't open";
- **Optional folder on add**: pick an existing folder or create a new one (default: none);
- **Progress feedback**: ring progress on the capsule (blue/green/amber/red), bar progress in the popup;
- **One-click download** for every detected PDF;
- **Login status sync** in the popup, one-click jump to sign in.

## 📖 Quick usage

1. Log in at [scholaread.cn](https://www.scholaread.cn) first;
2. Open any paper page — the capsule appears at bottom-right;
3. Click "Add" to save the paper, or expand the list for per-item actions (with folder choice);
4. Click the toolbar icon for login status, the current page's PDF list, and settings.

## 🆕 Changelog

- **v1.1.1**: fixes "added paper is an unopenable HTML file" on access-controlled sites (IEEE etc.) — real PDFs are now downloaded in-browser and uploaded. Note: from this version the extension requests all-sites access (for cross-site PDF fetching); Chrome will ask you to re-approve;
- **v1.1.0**: IEEE Xplore support (abstract-page PDF synthesis, stamp viewer detection); arXiv direct-PDF fallback fix;
- **v1.0.0**: first stable release.

## 🔒 Privacy

- Nothing is collected or uploaded; account-related requests go only to `*.scholaread.cn`;
- Login cookies never leave your browser;
- No analytics or tracking.

## ⚠️ Known limitations

- No capsule on Chrome's built-in PDF viewer pages (badge & popup still work);
- Depends on Scholaread's web-app internals — site changes may require an extension update;
- Not available on `chrome://` pages or the Chrome Web Store.

## 📄 License & liability

Distributed as freeware for learning and technical exchange only; resale is prohibited. "Scholaread" and related names/trademarks belong to their respective owners. Users must comply with Scholaread's terms of service and bear any consequences of use. If Scholaread considers this project infringing, please contact the author for removal.
