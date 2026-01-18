# AMP Anomaly Finder (Offline)

[![Offline](https://img.shields.io/badge/offline-100%25-brightgreen)](./index.html)
[![Single File](https://img.shields.io/badge/single--file-yes-blue)](./index.html)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-success)](./index.html)

A **single-file, fully offline** HTML tool to review **AMP “Press” CSV exports** and flag potential anomalies with **explainable causes**.

## Quick start

1. Download this repo as a ZIP (or clone it).
2. Open **`index.html`** (or **`AMP_Anomaly_Finder.html`**) directly in a browser.
3. Drag-and-drop one or more AMP CSV files.

## Files

- `index.html` — the full application (preferred entry)
- `AMP_Anomaly_Finder.html` — same app, alternate filename for workflows
- `CHANGELOG.md` — release notes
- `RELEASE_CHECKLIST.md` — quick ship checklist

## Offline + privacy guarantees

- **No network calls** (optional “Offline Lockdown” blocks and logs any attempted external calls).
- Nothing is uploaded anywhere.
- Settings are stored locally in your browser (`localStorage`).

## Utilities

Open the in-app **System Tools** to access:

- **Offline Self‑Test** — verifies:
  - no external references (http/https/ws/wss/chrome-extension)
  - storage availability
  - File APIs availability
  - whether lockdown is enabled
  - whether any blocked network attempts occurred

- **Portable Mode**
  - **Export bundle**: session data + settings (`localStorage`) into a JSON file
  - **Import bundle**: Replace or Merge, optionally applying imported settings

## Exports

- Export the currently filtered rows as CSV
- Export/Import a portable JSON bundle (sessions + settings)

## Browser notes

- **Chrome / Edge** recommended.
- Some browsers restrict drag‑and‑drop or file access when running from `file://`. If you run into issues, try Chrome/Edge or open the folder via a simple local web server.

## Screenshots

Drop screenshots into `docs/screenshots/` for GitHub releases:

- `docs/screenshots/screenshot-01.png` — main view
- `docs/screenshots/screenshot-02.png` — anomalies view
- `docs/screenshots/screenshot-03.png` — System Tools

See `docs/README.md` for the suggested layout.

(These assets are optional; the app remains single-file and fully offline.)

