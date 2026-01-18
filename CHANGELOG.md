# Changelog

## v4.0.2 OFFLINE-PORTABLE-REFACTOR
- **Fix:** removed duplicated Offline/Portable tools block that caused `LOCKDOWN_KEY` redeclaration errors.
- Version stamp updated.

## v4.0.1 OFFLINE-PORTABLE-REFACTOR
- Added in-app **System Tools**:
  - Offline Lockdown (blocks + logs external calls)
  - Offline Self‑Test (verifies offline integrity + storage)
  - Portable Mode export/import bundle (settings + session data)
- Added `AMP_Anomaly_Finder.html` (alternate filename entrypoint)

## v4.0.0 OFFLINE-REFACTOR
- Removed all external dependencies and saved-page artifacts.
- Cleaned up legacy/unused fragments and duplicate tags.
- Consolidated to a single `index.html` for easy GitHub ZIP distribution.
