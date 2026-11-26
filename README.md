# True Auth

An Entrext venture. We're exploring one question: **how do you know who you're really communicating with, at the moment it matters?**

This repo is a single-page site about the problem statement. It is a hypothesis, not a product.

## Files

- `index.html` is the whole site (HTML, CSS and JS in one file, no build step).
- `assets/linkedin-banner.png` is the LinkedIn banner (2256x382).
- `.nojekyll` tells GitHub Pages to serve the files as they are.

## Run it locally

Open `index.html` in a browser. That's it.

## Put it live with GitHub Pages

1. Create a new repository on GitHub (for example `trueauth`).
2. Upload everything in this folder to the repository root, keeping `index.html` at the top level.
3. Go to **Settings, then Pages**.
4. Under **Build and deployment**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Use your own domain

In **Settings, then Pages, then Custom domain**, enter your domain and add the DNS records GitHub shows you. Tick **Enforce HTTPS** once it's available.

## Notes

- Fonts load from Google Fonts, so the site falls back to system fonts when offline.
- The site respects light and dark mode and reduced-motion settings.
