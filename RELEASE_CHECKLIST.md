# Release checklist (offline single-file)

## Before tagging

- [ ] Open `index.html` from **file://** in Chrome/Edge
- [ ] Import at least one real AMP CSV and confirm:
  - [ ] row counts match expectation
  - [ ] filters/search work
  - [ ] anomaly explanations render
- [ ] Run **System Tools → Offline Self‑Test** (should report clean)
- [ ] Toggle **Offline Lockdown** ON (default) and confirm no blocks occur during normal use
- [ ] Export CSV and re-open the export to sanity-check columns
- [ ] Export a Portable Bundle and import it back in (Replace + Merge)

## Repo hygiene

- [ ] Confirm no `_files/` folder references or CDN usage
- [ ] Confirm icons/assets are embedded (data: URIs)
- [ ] Confirm `LICENSE` is present
- [ ] Update `CHANGELOG.md` and bump `BUILD_TAG` (in `index.html`)

## GitHub release

- [ ] Tag the release (e.g., `v4.0.2`)
- [ ] Attach the repo ZIP (or let GitHub generate it)
- [ ] Add screenshots (optional) in `docs/`
- [ ] Paste highlights from `CHANGELOG.md` into the release notes
