# Changelog

## 1.1.0 — 2026-11-15

- New: accessibility on every screen — the “Aa” button (text size, high contrast, no animations, readable text, underlined links, read aloud), a “Back to top” arrow and “Skip to content”; the window always fits the screen; the magnifier zoom and “fit screen” controls now sit on the left edge (fff-kit 1.6.0).

## 1.0.2 — 2026-11-15

- Changed: shared interface kit refreshed — the button inside notifications gets a larger touch target (40 px). No change to the app's own logic or texts.

## 1.0.1 — 2026-11-15

- New: hyper-detailed fractal textures (fff-texturi 1.1.2) — the background and large surfaces (cards, panels, headers, buttons; tabs and dialogs that are hidden at load, once they open) get a locally generated material (WebGL2, no network, no images) that tiles seamlessly; the app keeps its own colours. Turn it off in the "Transparency" dialog or with `?notex=1`.

## 1.0.0 — 2026-11-06

- Adopt the fff-kit (transparency dialog, safe backup/restore), `#app-version`, application-version/last-updated metas, `app.json`.
- Replace native `alert`/`confirm` with accessible `FFF.dialog` dialogs.
- Add own test suite and axe-core verification (0 violations).
