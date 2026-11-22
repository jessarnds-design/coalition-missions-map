# Publish — Coalition Missions Impact map

Live: **https://jessarnds-design.github.io/coalition-missions-map/**  
Repo: **https://github.com/jessarnds-design/coalition-missions-map** (Pages from the `main` branch root)

## What to publish

| Local path | Repo role |
|---|---|
| `index.html` | GitHub Pages entry |
| `data.js` / `data.json` | Public-safe map data (no initials or sensitive names) |
| `assets/` | Seal and favicon |
| `embed.html` | iframe snippets |
| `README.md` | Method and security notes |

Rebuild data with `python3 /workspace/coalition-missions/build_data.py`, then commit and `git push origin main` as `jessarnds-design`. Enable GitHub Pages: Settings → Pages → Deploy from branch `main` / `/ (root)`.

## Do not

- Put initials, classified names, or city-level field coordinates on the public map.
- Use tile providers that require an API key. Keep OpenStreetMap.
