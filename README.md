# AMP Anomaly Finder (Offline)

A single-file, fully offline HTML tool to review **AMP “Press” CSV exports** and flag potential anomalies with **explainable causes**.

## What’s in this repo

- `index.html` — the entire application (no external dependencies)

## Run it

1. Download this repo as a ZIP (or clone it).
2. Open `index.html` directly in a browser (Chrome / Edge recommended).
3. Drag-and-drop one or more AMP CSV files.

## Offline / privacy

- No network calls.
- Nothing is uploaded anywhere.
- Settings are stored locally in your browser (`localStorage`).

## Exports

- Export the currently filtered rows as CSV
- Export/Import a `.json` package (sessions + settings)

## Notes

This is a cleanup/refactor build intended to be **distribution-ready** as a GitHub repository ZIP.
