# Handoff: apps

Shared notes for every AI that works here (Claude Code, Codex, Antigravity, Developer Tools). Read this first. After every change, rewrite **Now** and add a **Log** entry at the top. No keys, tokens, passwords or personal data.

## Now

- **State:** How-to guides for 8 Android apps (`guides/<slug>/guide.md` + `shots/`, format in `GUIDE-FORMAT.md`) and the website built from them in `docs/` by the Developer Tools dashboard (Guides screen). Git repo on `main`, nothing committed, no remote yet. Pages workflow uploads `docs/` only.
- **Next:** Developer: set the support email in `site.json` (Guides → Site details), create the public GitHub repo `apps`, add it as `origin`, turn on Pages (Source: GitHub Actions), then Publish… from the dashboard. Fill the 21 "Needs screenshot" slots (Steady and Text Toolkit have no pictures yet).
- **Not verified:** Guide claims the writers could not confirm: QR and Unit Converter Premium purchase (not active in current builds); Photo Toolkit background removal on a real Android phone; AppLock intruder photo / fake crash / disguise; TapLock interstitial timing; Steady and Text Toolkit ads (ad units blank / ads off). Pictures to retake: AppLock `04-settings.png`, TapLock `02-setup.png` (older builds), TapLock shots show a test-ad banner, QR `03-link.png` shows a real shortener domain.

## Log

<!-- Newest first. Each entry looks like this (without the leading spaces):
    ### YYYY-MM-DD HH:MM · <tool> · <model> · <short title>
    - **Changed:** what and why
    - **Files:** paths
    - **Checked:** commands run and their results, or "not run"
    - **Next:** what the next AI should do
-->

### 2026-11-10 22:49 · Developer Tools · Saved the applock guide
- **Changed:** Saved the guide for AppLock Without Dashboad from the Developer Tools app (reviewed in the app before saving).
- **Files:** `guides/applock/guide.md`
- **Checked:** not run
- **Next:** Build the site and publish it when the guide and its pictures are right.

### 2026-11-10 22:05 · Claude Code · claude-opus-5-5 · Wrote the first 8 guides
- **Changed:** Wrote guides for OCRScanner, QR & Barcode Toolkit, Photo & Image Toolkit, AppLock (from "AppLock Without Dashboad"), Unit Converter, TapLock, Text Toolkit and Steady from each app's docs, store listing, screen files and existing screenshots (downscaled to 720 px). Built the site into `docs/`.
- **Files:** `guides/*/guide.md`, `guides/*/shots/*.png`, `site.json`, `GUIDE-FORMAT.md`, `README.md`, `docs/`
- **Checked:** site preview in the browser at desktop and phone width, light and dark; every built image answers 200.
- **Next:** see Now.

### 2026-11-10 21:59 · Developer Tools · Set up the app guides folder
- **Changed:** Created the guides folder's starter files and made it a git repository on main.
- **Files:** `.github/workflows/static.yml`, `.gitignore`
- **Checked:** not run
- **Next:** Create the public GitHub repo, add it as origin, and set Settings → Pages → Source to GitHub Actions.
