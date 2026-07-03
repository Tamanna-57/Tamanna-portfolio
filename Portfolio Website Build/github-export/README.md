# Tamanna Arora — Portfolio

Dark AI/robotics-themed portfolio. Single self-contained `index.html` — no build step, no dependencies. Open it in any browser or host it anywhere (GitHub Pages, Netlify, Vercel).

## Structure

- `index.html` — the whole site, bundled (fonts, styles, scripts inlined)
- `source/Portfolio v2.dc.html` — editable source file
- `source/support.js` — runtime the source file needs (keep next to it)

## Editing content (projects, links, experience)

Open `source/Portfolio v2.dc.html` and find the block marked:

```
// ─────────────────────────────
//  EDIT HERE — plug in real links / screenshots / updated details
// ─────────────────────────────
```

- `projects = [...]` — each project has `liveUrl` (paste your deployed URL → it embeds as a live frame), `repoUrl`, `tech`, `points`.
- `journey = [...]` — timeline entries; the internship entry has `ongoing: true`.
- `skills`, `honors`, `terminalLines` — same pattern.
- Social links (LinkedIn / GitHub / LeetCode) are in the contact section markup — search for `LinkedIn ↗`.

## Push to this repo

```bash
git clone https://github.com/Tamanna-57/Tamanna-portfolio.git
cd Tamanna-portfolio
# copy the contents of this folder in, then:
git add -A
git commit -m "Add portfolio site"
git push origin main
```

## Enable GitHub Pages

Repo → Settings → Pages → Source: `main` branch, `/ (root)` folder → Save.
Your site will be live at `https://tamanna-57.github.io/Tamanna-portfolio/`.
