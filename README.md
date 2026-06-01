# sridharsabarish.github.io

Personal portfolio site — static HTML/CSS, hosted on Cloudflare Pages.

## Deploy to Cloudflare Pages (recommended)

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/) → **Create a project** → **Connect to Git**
2. Select this repo (`sridharsabarish/sridharsabarish.github.io`)
3. Set:
   - **Build command**: *(leave empty)*
   - **Build output directory**: `/` (root)
4. Click **Save and Deploy**

Cloudflare will serve `index.html` from the repo root. Every push to `main` redeploys automatically.

To use a custom domain, add it under **Custom Domains** in the Cloudflare Pages dashboard.

## Deploy via Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler pages deploy . --project-name sabarish-portfolio
```

## Local preview

Open `index.html` directly in a browser — no build step or server needed.

## Repo structure

```
index.html      ← portfolio page
style.css       ← dark theme styles
wrangler.toml   ← Cloudflare Pages config
.nojekyll       ← disables Jekyll on GitHub Pages
```
