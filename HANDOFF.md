# Handoff: apps

Shared notes for every AI that works here (Claude Code, Codex, Antigravity, Developer Tools). Read this first. After every change, rewrite **Now** and add a **Log** entry at the top. No keys, tokens, passwords or personal data.

## Now

- **State:** How-to guides for 8 Android apps (`guides/<slug>/guide.md` + `shots/`, format in `GUIDE-FORMAT.md`) and the website built from them in `docs/` by the Developer Tools dashboard (Guides screen). Git repo on `main` with `origin` set; published once (2026-11-10 23:02, `fd0dcb3`). Pages workflow uploads `docs/` only.
  - AppLock pictures (2026-11-10 23:10): `03-permissions.png`, `05-accessibility-disclosure.png`, `06-lock-apps.png` and `07-intruder-photos.png` were one identical capture of the Unit Converter app (taken 22:48 while that app was on the emulator) and went live with the 23:02 publish. Fixed locally: 03 is the real Permissions picture again, and 05–07 are real AppLock screens captured 23:50 from a current debug build (`io.github.varian1.applock`, versionCode 6) on emulator m3test; `docs/` is rebuilt. Not committed or pushed, so the live site still shows the wrong pictures.
  - About those three pictures: `06-lock-apps.png` has "t" typed in the search field (it keeps an old `com.applock` test install out of the list; the rows are the developer's own apps). `07-intruder-photos.png` shows three plain silhouette sample pictures drawn for the guide, not camera photos (the emulator's front camera only gives the Android test pattern), and its captions are package IDs because the app shows those for these entries today. 05–07 are 720×1600; 01–04 are 720×1280.
  - That rebuild also carries site changes still being worked on in Developer Tools (QR code, share links); look at the Publish… file list before confirming.
- **Next:** Developer: Publish… from the dashboard to correct the live AppLock page; set the support email in `site.json` (Guides → Site details). Fill the 18 "Needs screenshot" slots (Steady and Text Toolkit have no pictures yet; AppLock has none left). The emulator now has a debug `io.github.varian1.applock` install set up with the standard test PIN (it needs Metro from "AppLock Without Dashboad" to start); use it to retake `04-settings.png`.
- **Not verified:** Guide claims the writers could not confirm: QR and Unit Converter Premium purchase (not active in current builds); Photo Toolkit background removal on a real Android phone; AppLock intruder photo / fake crash / disguise; TapLock interstitial timing; Steady and Text Toolkit ads (ad units blank / ads off). Pictures to retake: AppLock `04-settings.png`, TapLock `02-setup.png` (older builds), TapLock shots show a test-ad banner, QR `03-link.png` shows a real shortener domain.

## Log

Older entries are in `HANDOFF-archive.md`, newest first. Read it only when you need that history.

<!-- Newest first. Each entry looks like this (without the leading spaces):
    ### YYYY-MM-DD HH:MM · <tool> · <model> · <short title>
    - **Changed:** what and why
    - **Files:** paths
    - **Checked:** commands run and their results, or "not run"
    - **Next:** what the next AI should do
-->

### 2026-11-25 23:08 · Developer Tools · Published the guides site
- **Changed:** Pushed main to origin after the developer confirmed in the app.
- **Files:** none
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 22:48 · Developer Tools · Saved the qr-barcode-toolkit guide
- **Changed:** Saved the guide for QRBarcode and toolkit from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/qr-barcode-toolkit/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 22:45 · Developer Tools · Saved the virtual-button guide
- **Changed:** Saved the guide for virtual-button from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/virtual-button/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:55 · Developer Tools · Saved the currency-converter guide
- **Changed:** Saved the guide for currency-converter from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/currency-converter/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:54 · Developer Tools · Saved the steady guide
- **Changed:** Saved the guide for steady healthy app from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/steady/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:53 · Developer Tools · Saved the applock guide
- **Changed:** Saved the guide for AppLock Without Dashboad from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/applock/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:14 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/applock/index.html`, `M docs/apps.json`, `M docs/ar/applock/index.html`, `M docs/ar/currency-converter/index.html`, `M docs/ar/index.html`, `M docs/ar/ocrscanner/index.html`, `M docs/ar/photo-image-toolkit/index.html`, `M docs/ar/qr-barcode-toolkit/index.html`, `M docs/ar/steady/index.html`, `M docs/ar/taplock/index.html`, `M docs/ar/text-toolkit/index.html`, `M docs/ar/unit-converter/index.html`, `M docs/ar/virtual-button/index.html`, `M docs/currency-converter/index.html`, `M docs/de/applock/index.html`, `M docs/de/currency-converter/index.html`, `M docs/de/index.html`, `M docs/de/ocrscanner/index.html`, `M docs/de/photo-image-toolkit/index.html`, `M docs/de/qr-barcode-toolkit/index.html`, `M docs/de/steady/index.html`, `M docs/de/taplock/index.html`, `M docs/de/text-toolkit/index.html`, `M docs/de/unit-converter/index.html`, `M docs/de/virtual-button/index.html`, `M docs/es/applock/index.html`, `M docs/es/currency-converter/index.html`, `M docs/es/index.html`, `M docs/es/ocrscanner/index.html`, `M docs/es/photo-image-toolkit/index.html`, `M docs/es/qr-barcode-toolkit/index.html`, `M docs/es/steady/index.html`, `M docs/es/taplock/index.html`, `M docs/es/text-toolkit/index.html`, `M docs/es/unit-converter/index.html`, `M docs/es/virtual-button/index.html`, `M docs/fr/applock/index.html`, `M docs/fr/currency-converter/index.html`, `M docs/fr/index.html`, `M docs/fr/ocrscanner/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 20:14 · Developer Tools · Saved the text-toolkit guide
- **Changed:** Saved the guide for text-toolkit from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/text-toolkit/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:13 · Developer Tools · Saved the taplock guide
- **Changed:** Saved the guide for LOCKAPPONLY from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/taplock/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:11 · Developer Tools · Saved the photo-image-toolkit guide
- **Changed:** Saved the guide for photo-image-toolkit from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/photo-image-toolkit/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:10 · Developer Tools · Saved the unit-converter guide
- **Changed:** Saved the guide for all-in-one-unit-converter from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/unit-converter/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 20:07 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/internet-speed-test/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `docs/internet-speed-test/shots/03-quality-monitor.png`, `guides/internet-speed-test/shots/03-quality-monitor.png`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 20:02 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/internet-speed-test/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `docs/internet-speed-test/shots/01-test-result.png`, `docs/internet-speed-test/shots/02-history.png`, `guides/internet-speed-test/shots/01-test-result.png`, `guides/internet-speed-test/shots/02-history.png`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:55 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/internet-speed-test/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:27 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `docs/internet-speed-test/index.html`, `guides/internet-speed-test/guide.md`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:27 · Developer Tools · Saved the internet-speed-test guide
- **Changed:** Saved the guide for internet-speed-test from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/internet-speed-test/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 19:26 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/ocrscanner/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `M guides/ocrscanner/guide.md`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:26 · Developer Tools · Saved the ocrscanner guide
- **Changed:** Saved the guide for OCRScanner from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/ocrscanner/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 19:10 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:10 · Developer Tools · Saved the wifi-analyzer guide
- **Changed:** Saved the guide for wifi-analyzer from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/wifi-analyzer/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 19:07 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `docs/wifi-analyzer/index.html`, `guides/wifi-analyzer/guide.md`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-25 19:07 · Developer Tools · Saved the wifi-analyzer guide
- **Changed:** Saved the guide for wifi-analyzer from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/wifi-analyzer/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-25 18:51 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-22 10:26 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/apps.json`, `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-22 09:08 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/applock/index.html`, `M docs/apps.json`, `M docs/ar/applock/index.html`, `M docs/ar/currency-converter/index.html`, `M docs/ar/index.html`, `M docs/ar/ocrscanner/index.html`, `M docs/ar/photo-image-toolkit/index.html`, `M docs/ar/qr-barcode-toolkit/index.html`, `M docs/ar/steady/index.html`, `M docs/ar/taplock/index.html`, `M docs/ar/text-toolkit/index.html`, `M docs/ar/unit-converter/index.html`, `M docs/ar/virtual-button/index.html`, `M docs/currency-converter/index.html`, `M docs/de/applock/index.html`, `M docs/de/currency-converter/index.html`, `M docs/de/index.html`, `M docs/de/ocrscanner/index.html`, `M docs/de/photo-image-toolkit/index.html`, `M docs/de/qr-barcode-toolkit/index.html`, `M docs/de/steady/index.html`, `M docs/de/taplock/index.html`, `M docs/de/text-toolkit/index.html`, `M docs/de/unit-converter/index.html`, `M docs/de/virtual-button/index.html`, `M docs/es/applock/index.html`, `M docs/es/currency-converter/index.html`, `M docs/es/index.html`, `M docs/es/ocrscanner/index.html`, `M docs/es/photo-image-toolkit/index.html`, `M docs/es/qr-barcode-toolkit/index.html`, `M docs/es/steady/index.html`, `M docs/es/taplock/index.html`, `M docs/es/text-toolkit/index.html`, `M docs/es/unit-converter/index.html`, `M docs/es/virtual-button/index.html`, `M docs/fr/applock/index.html`, `M docs/fr/currency-converter/index.html`, `M docs/fr/index.html`, `M docs/fr/ocrscanner/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-22 09:00 · Claude Code · Sonnet 5.5 · Site brand Kitvara + support email
- **Changed:** `site.json`: developer "Our" → "Kitvara", `supportEmail` set to the address the developer typed in chat. `docs/` not rebuilt, nothing committed or pushed.
- **Files:** `M site.json`
- **Checked:** not run (site rebuild is done by the dashboard).
- **Next:** Developer: Guides → Publish… in the dashboard to rebuild `docs/` and push; the live site still shows "Our apps".

### 2026-11-22 08:19 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`, `docs/apps.json`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-21 21:54 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-21 19:45 · Developer Tools · Archived old Log entries
- **Changed:** Moved the 194 oldest Log entries to HANDOFF-archive.md so every AI reads less at the start of a session (HANDOFF.md 83 KB → 9 KB). Nothing was deleted.
- **Files:** `HANDOFF.md`, `HANDOFF-archive.md`
- **Checked:** not run
- **Next:** Continue from **Now**.

### 2026-11-21 19:38 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/ar/index.html`, `M docs/de/index.html`, `M docs/es/index.html`, `M docs/fr/index.html`, `M docs/hi/index.html`, `M docs/id/index.html`, `M docs/index.html`, `M docs/it/index.html`, `M docs/ja/index.html`, `M docs/ko/index.html`, `M docs/ms/index.html`, `M docs/nl/index.html`, `M docs/pt/index.html`, `M docs/ru/index.html`, `M docs/th/index.html`, `M docs/tl/index.html`, `M docs/tr/index.html`, `M docs/vi/index.html`, `M docs/zh/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-21 19:38 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/applock/index.html`, `M docs/ar/applock/index.html`, `M docs/ar/currency-converter/index.html`, `M docs/ar/index.html`, `M docs/ar/ocrscanner/index.html`, `M docs/ar/photo-image-toolkit/index.html`, `M docs/ar/qr-barcode-toolkit/index.html`, `M docs/ar/steady/index.html`, `M docs/ar/taplock/index.html`, `M docs/ar/text-toolkit/index.html`, `M docs/ar/unit-converter/index.html`, `M docs/ar/virtual-button/index.html`, `M docs/assets/styles.css`, `M docs/currency-converter/index.html`, `M docs/de/applock/index.html`, `M docs/de/currency-converter/index.html`, `M docs/de/index.html`, `M docs/de/ocrscanner/index.html`, `M docs/de/photo-image-toolkit/index.html`, `M docs/de/qr-barcode-toolkit/index.html`, `M docs/de/steady/index.html`, `M docs/de/taplock/index.html`, `M docs/de/text-toolkit/index.html`, `M docs/de/unit-converter/index.html`, `M docs/de/virtual-button/index.html`, `M docs/es/applock/index.html`, `M docs/es/currency-converter/index.html`, `M docs/es/index.html`, `M docs/es/ocrscanner/index.html`, `M docs/es/photo-image-toolkit/index.html`, `M docs/es/qr-barcode-toolkit/index.html`, `M docs/es/steady/index.html`, `M docs/es/taplock/index.html`, `M docs/es/text-toolkit/index.html`, `M docs/es/unit-converter/index.html`, `M docs/es/virtual-button/index.html`, `M docs/fr/applock/index.html`, `M docs/fr/currency-converter/index.html`, `M docs/fr/index.html`, `M docs/fr/ocrscanner/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-21 18:38 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/applock/index.html`, `M docs/ar/applock/index.html`, `M docs/ar/currency-converter/index.html`, `M docs/ar/index.html`, `M docs/ar/ocrscanner/index.html`, `M docs/ar/photo-image-toolkit/index.html`, `M docs/ar/qr-barcode-toolkit/index.html`, `M docs/ar/steady/index.html`, `M docs/ar/taplock/index.html`, `M docs/ar/text-toolkit/index.html`, `M docs/ar/unit-converter/index.html`, `M docs/ar/virtual-button/index.html`, `M docs/assets/styles.css`, `M docs/currency-converter/index.html`, `M docs/de/applock/index.html`, `M docs/de/currency-converter/index.html`, `M docs/de/index.html`, `M docs/de/ocrscanner/index.html`, `M docs/de/photo-image-toolkit/index.html`, `M docs/de/qr-barcode-toolkit/index.html`, `M docs/de/steady/index.html`, `M docs/de/taplock/index.html`, `M docs/de/text-toolkit/index.html`, `M docs/de/unit-converter/index.html`, `M docs/de/virtual-button/index.html`, `M docs/es/applock/index.html`, `M docs/es/currency-converter/index.html`, `M docs/es/index.html`, `M docs/es/ocrscanner/index.html`, `M docs/es/photo-image-toolkit/index.html`, `M docs/es/qr-barcode-toolkit/index.html`, `M docs/es/steady/index.html`, `M docs/es/taplock/index.html`, `M docs/es/text-toolkit/index.html`, `M docs/es/unit-converter/index.html`, `M docs/es/virtual-button/index.html`, `M docs/fr/applock/index.html`, `M docs/fr/currency-converter/index.html`, `M docs/fr/index.html`, `M docs/fr/ocrscanner/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.

### 2026-11-21 18:22 · Developer Tools · Published the guides site
- **Changed:** Committed and pushed main to origin after the developer confirmed in the app.
- **Files:** `M docs/applock/index.html`, `M docs/ar/index.html`, `M docs/ar/ocrscanner/index.html`, `M docs/ar/photo-image-toolkit/index.html`, `M docs/ar/qr-barcode-toolkit/index.html`, `M docs/assets/styles.css`, `M docs/currency-converter/index.html`, `M docs/de/applock/index.html`, `M docs/de/index.html`, `M docs/de/ocrscanner/index.html`, `M docs/de/photo-image-toolkit/index.html`, `M docs/de/qr-barcode-toolkit/index.html`, `M docs/es/applock/index.html`, `M docs/es/index.html`, `M docs/es/ocrscanner/index.html`, `M docs/es/photo-image-toolkit/index.html`, `M docs/es/qr-barcode-toolkit/index.html`, `M docs/fr/applock/index.html`, `M docs/fr/index.html`, `M docs/fr/ocrscanner/index.html`, `M docs/fr/photo-image-toolkit/index.html`, `M docs/fr/qr-barcode-toolkit/index.html`, `M docs/hi/index.html`, `M docs/hi/ocrscanner/index.html`, `M docs/hi/photo-image-toolkit/index.html`, `M docs/hi/qr-barcode-toolkit/index.html`, `M docs/id/applock/index.html`, `M docs/id/index.html`, `M docs/id/ocrscanner/index.html`, `M docs/id/photo-image-toolkit/index.html`, `M docs/id/qr-barcode-toolkit/index.html`, `M docs/index.html`, `M docs/it/applock/index.html`, `M docs/it/index.html`, `M docs/it/ocrscanner/index.html`, `M docs/it/photo-image-toolkit/index.html`, `M docs/it/qr-barcode-toolkit/index.html`, `M docs/ja/index.html`, `M docs/ja/ocrscanner/index.html`, `M docs/ja/photo-image-toolkit/index.html`
- **Checked:** git push succeeded; use "Check live site" to confirm the page
- **Next:** GitHub Pages rebuilds in a minute or two; check the live site.
