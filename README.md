# Bunco Score Tracker

Free, static, no-account running-score calculator for Bunco game night. Single page,
reuses the same generic `tracker.js` engine first built for `card-game-scorer-network`
(editable player count/names, per-round point entry, running history, localStorage
persistence) with zero code changes.

## Files
- `index.html` — the tracker + a short "How Bunco Scoring Works" reference
- `tracker.js` — shared generic engine (copied unchanged)
- `styles.css` — shared theme (copied unchanged)

## Local development
No build step. Serve the directory with any static server, e.g.:
```
python3 -m http.server 8000
```

## Deploy
Push to a GitHub repo with Pages enabled on the root of `main` (or push `site/` as the
repo root).
