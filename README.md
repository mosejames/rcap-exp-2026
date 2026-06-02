# RCAP EXP Recap — Newsletter (production web version)

The "view online" version of the RCAP EXP recap newsletter, implemented from the
Claude Design handoff bundle. This is the beautiful, browser-faithful version —
the one to host so the Gmail send can link to it (Gmail will strip the fonts,
gradients, and layout from an inline email).

## Files
- `index.html` — the newsletter, self-contained (one HTML file + the `img/` folder)
- `img/` — 33 photos (~4.7 MB total), JPEG, already downscaled for web

## What changed from the design prototype
- Removed the design-tool scaffolding: the React/Babel **Tweaks** panel, the
  bundler thumbnail template, and the `data-screen-label` / `data-comment-anchor`
  prototype markers.
- Locked in the settings Mose approved: **Sunset** accent, **Soft** (16px) corners,
  captions **on**.
- Kept the click-to-zoom **lightbox** and the responsive mobile layout.
- Added `<meta>` description + Open Graph / Twitter tags so the hosted link shows a
  proper preview (hero photo + title) when shared.
- Masthead year corrected **2025 → 2026** (the event is "today," June 2026 — the
  prototype said 2025). Revert in `index.html` if that was intentional.

## How to host it (pick one)
- **Netlify Drop** — drag this whole folder onto https://app.netlify.com/drop →
  instant permanent URL. Easiest.
- **GitHub Pages** — push the folder to a repo, enable Pages.
- **RCA site** — upload `index.html` + `img/` to any subfolder.

Once you have the permanent URL, drop it into the Gmail email as the "View online"
link so the email always has a working "see it the pretty way" button.

## Live links already wired in
- Sign up → SignUpGenius (`...60B0949A4AB29A2F94-rcaexp2`)
- Gallery → Google Photos album
- Log hours → Track It Forward (Ron Clark Academy)
