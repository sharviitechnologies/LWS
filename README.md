# LWS Homepage — Static Build

A single-page static site. No build step or server required.

## Files
- `index.html` — the full homepage
- `assets/app.css` — compiled styles
- `assets/lws-logo.png` — logo
- `assets/favicon.png` — favicon

## Upload to GitHub Pages
1. Create a new repository on GitHub (e.g. `lws-site`).
2. Upload all files, keeping the `assets/` folder structure intact.
3. In the repo: **Settings → Pages → Source: Deploy from a branch**, pick `main` and `/ (root)`, save.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

Alternatively, with Git installed:
```
git init && git add . && git commit -m "LWS homepage"
git remote add origin https://github.com/<you>/lws-site.git
git push -u origin main
```

Fonts (Sora, Inter) load from Google Fonts, so an internet connection is needed for exact typography.
