# Guide format

Every app has one guide: `guides/<slug>/guide.md`, with its pictures in `guides/<slug>/shots/`. The website in `docs/` is built from these files by the Developer Tools dashboard, so the layout below is fixed. `guides/ocrscanner/guide.md` is the model to copy.

## Front matter

Plain `key: value` lines between two `---` lines. No quotes, no nesting.

| Key | Meaning |
|---|---|
| `title` | Store title, main keyword first, 30 characters at most |
| `name` | Short name used in cards and sentences |
| `tagline` | One sentence: what the app does and for whom (80 characters at most) |
| `project` | Folder name in `~/dev` the guide was written from |
| `package` | Android package id |
| `version` | App version the guide describes |
| `updated` | Date the guide was last written, `YYYY-MM-DD` |
| `privacy` | Address of the app's privacy policy; leave empty if none is hosted |

## Sections, in this order

1. `## What it does`: two or three sentences, then up to four bullets.
2. `## Get started`: first launch, permissions, first action.
3. One `##` per task, named as the task ("Scan a page"). Numbered steps, one action each. Button names in **bold**, written exactly as on screen.
4. `## Premium`: only if the app sells something. Say what it adds and how it is paid.
5. `## Questions`: three to five, each a bold question on its own line and the answer on the next.
6. `## Privacy`: one or two sentences and a link to the policy.

## Pictures

- `![What the picture shows](shots/NN-name.png)` on its own line after the steps it belongs to.
- Step pictures are real captures of the app, 720 px wide, PNG, with made-up sample content only.
- `shots/card.png` is the picture on the landing page card; `shots/icon.png` is the app icon (192 px).
- A step that still needs a picture keeps its `![…](shots/NN-name.png)` line even though the file is missing. The dashboard lists it as "needs screenshot" and the site leaves it out until the file exists.

## Rules

- Only say what the app really does in the version named in the front matter.
- No download links or store buttons: the site adds them, and only for apps that are live.
- No other companies' brand names except where the app itself shows them (for example "Google AdMob" in the privacy section).
- No email addresses, keys or personal data. The support address lives in `site.json`.
- Short sentences, plain words, second person ("Tap **Scan**").
