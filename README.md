# VG-GUI-TASKER.github.io

Project page for **VG-GUI-Bench**, served via GitHub Pages at
<https://vg-gui-tasker.github.io>.

This is a static site (plain HTML + CSS, no build step). GitHub Pages serves
`index.html` from the root of the `main` branch.

## Local preview

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Editing

- `index.html` — page content (authors, links, abstract, leaderboard, BibTeX)
- `style.css` — styling
- `.nojekyll` — disables Jekyll so all files are served as-is

Update the placeholder author names, affiliations, paper/arXiv links, and
leaderboard numbers before publishing.

## Deploy

Any push to the `main` branch automatically redeploys the site (usually within
a minute). Configure under **Settings → Pages** if needed.
