# Gimmie Right — Static Landing Page

This repository contains a single-file static landing page `index.html` and an `assets/` folder with images used by the page.

Goal: publish this site publicly (GitHub Pages, Netlify, Vercel, etc.) so social shares show the correct thumbnail.

Quick steps to publish via GitHub Pages (recommended):

1. Create a new PUBLIC repository on GitHub (for example: `gimmie-right`).
2. From your machine, add the remote and push:

```bash
cd '/Users/golfsavedmylife/Downloads/Gimmie Right'
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

If you prefer HTTPS:

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

3. In the GitHub repository, go to Settings → Pages and enable Pages from the `main` branch (root). GitHub will publish to a URL like `https://YOUR_USERNAME.github.io/YOUR_REPO/` within a minute or two.

4. Once you have the public site URL, update the open-graph metadata in `index.html` to use the full public URL for `og:image` and `twitter:image` (example below):

```html
<meta property="og:image" content="https://YOUR_USERNAME.github.io/YOUR_REPO/assets/craft-shoe.png">
<meta name="twitter:image" content="https://YOUR_USERNAME.github.io/YOUR_REPO/assets/craft-shoe.png">
```

5. Use the Facebook/Twitter preview/debugger tools to refresh cached previews.

If you want, paste the GitHub repository URL here and I will add the remote and push from this machine (you may need to authenticate if using HTTPS or have SSH keys configured).

---

Files of interest:

- `index.html` — main page
- `assets/` — images (thumbnail is `assets/craft-shoe.png`)

Questions? I can push to a repo for you if you provide the target repo URL, or I can walk you through the steps.
