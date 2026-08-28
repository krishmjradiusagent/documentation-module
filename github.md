repo: krishmjradiusagent/client-portal
branch: main

## Last sync
date: 2026-08-28T05:09:51Z

### Updated in this project
- Transaction sheet: dropped the sticky footer CTA; signed envelopes now show "View document" + download instead of "Track signatures".
- Fixed the stretched property thumbnail in the sheet header.
- Converted the whole client app to Phosphor regular — 168 glyphs, paths read from `phosphor-icons/core@main` `assets/regular/*.svg` (reference repo, not the primary source). Sign action uses `pen-nib`. Only the six social brand marks stay as-is.

## Sync history
### 2026-08-27T18:55:26Z
- Added a Documents tab to the client app bottom nav (icon read from `phosphor-icons/core@main`, `assets/regular/file-text.svg`).
- Added `Client Portal (web).dc.html` — the Search workspace recreated as HTML/CSS (dark floating sidebar, search header, results grid, map panel).
- Copied map and avatar assets from `public/`.

## Screen map
| Project screen | Repo files |
| --- | --- |
| Client Portal (web).dc.html | src/components/app-shell.tsx, src/components/app-sidebar.tsx, src/components/ClientPortal.tsx, src/components/SearchHeader.tsx, src/components/ResultsPanel.tsx, src/components/PropertyCard.tsx, src/components/MapPanel.tsx, src/components/ui/control-pill.tsx, src/components/mockData.ts, src/app/globals.css, tailwind.config.ts |
