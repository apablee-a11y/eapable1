# Edgar Apable — Portfolio (Static HTML)

Single-file static site. Deploy to Vercel, Netlify, GitHub Pages, or any static host.

## Files
- `index.html` — the entire site
- `portfolio/` — images referenced by the page
- `vercel.json` — minimal Vercel config

## Deploy to Vercel
1. Push this folder to a GitHub repo.
2. Import it in vercel.com → "New Project" → select the repo.
3. Framework Preset: **Other** (static). Output directory: `/` (root).
4. Click Deploy.

## Deploy to GitHub Pages
1. Push to a repo.
2. Repo Settings → Pages → Source: `main` branch, `/ (root)`.
3. Site goes live at `https://<user>.github.io/<repo>/`.

## Local preview
Just open `index.html` in a browser. (Loom embed requires being served over http(s) — use `npx serve .` for full fidelity.)
