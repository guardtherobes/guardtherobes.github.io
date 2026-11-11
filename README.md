# guardtherobes.github.io

The landing page for **GuardTheRobes**, a local-first digital wardrobe.
Live at <https://guardtherobes.github.io/>.

The app itself lives in [guardtherobes/guardtherobes](https://github.com/guardtherobes/guardtherobes).

## What's here

| File | What it is |
|------|------------|
| `index.html` | the whole page: one file, inline CSS, one Google Font (Archivo) |
| `closet.png`, `outfit-builder.png` | screenshots from the app's demo mode (garments drawn in code, no real clothes) |
| `sitemap.xml`, `robots.txt` | for search engines |
| `.nojekyll` | tells GitHub Pages to serve the files as they are |

## Run it locally

```bash
python3 -m http.server 8790 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8790>.

## Publish

This repo belongs to the `guardtherobes` GitHub organisation and is named
`guardtherobes.github.io`, so GitHub Pages serves it at the org's address.
Settings > Pages > Deploy from a branch > `main` / root.

MIT licensed.
