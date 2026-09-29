# Hack Club Toolkit

Standalone source for the Toolkit website: landing page, submission guide, FAQ,
retro Notepad styling, and Glep window controls.

Extracted from `lolwutboi987/evanle.dev` at commit
`1b13df39dcd6df97c30349c48358a335a796d0c7`. The original website is unchanged.

## Edit

- `index.html`: landing page.
- `docs/index.html`: submission rules and FAQ.
- `toolkit.css`: shared Notepad theme.
- `docs/docs.css`: document layout and tables.
- `window.js` / `window.css`: minimize gag and homepage navigation.
- `glep.png` / `ASSETS.md`: image and source attribution.

## Preview

Run `python -m http.server 8000` from this directory, then open
`http://localhost:8000/`. There are no build dependencies.

## Hosting

Serve this directory as static files. Relative asset and navigation paths work
at a domain root or under a GitHub Pages project path.

Canonical and Open Graph URLs still reference the existing live site,
`https://www.evanle.dev/toolkit/`. Update both HTML files when moving to a
new public URL. This extraction does not enable hosting or move the domain.

The evanle.dev menu item and close button intentionally return to Evan's
personal website. Refresh restores a minimized Toolkit window.
