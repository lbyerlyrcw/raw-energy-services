# RCW Energy Services — Static Site

This repository contains the RCW Energy Services homepage (static HTML/CSS/JS).

## Live URL (after publishing)
https://lbyerlyrcw.github.io/rcw-energy-services/

## Quick start

**Option A — Drag & drop on GitHub**
1. Create a new repo on GitHub (public or private): `rcw-energy-services`.
2. Click **Add file → Upload files** and upload everything in this folder.
3. Go to **Settings → Pages** and under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main**, folder **/** (root). Click **Save**.

**Option B — Git CLI**
```bash
# From this folder
git init -b main
git add .
git commit -m "Initial commit: RCW Energy Services site"
git remote add origin https://github.com/lbyerlyrcw/rcw-energy-services.git
git push -u origin main
```
Then enable **Settings → Pages → Deploy from a branch** (main / root) or switch **Source = GitHub Actions**.

## Customize
- **Dispatch phone/email**: Edit `index.html` (search `903-999-9999` and `dispatch@rcwenergyservices.com`).
- **Form endpoints**: Replace the `action` attributes with your Formspree IDs or backend endpoints.
- **Logo font**: Place licensed `Serpentine-BoldOblique.woff2` (and `.woff`) into `assets/fonts/`.
- **Images**: Replace `assets/img/og-cover.png` and add your hero/service photos to `assets/img/`.

## Optional: GitHub Pages with Actions
If you prefer GitHub Actions, create the repo and push, then make sure `Settings → Pages → Source = GitHub Actions` and keep `.github/workflows/pages.yml` included here.

## License
Copyright © RCW Energy Services. All rights reserved.
