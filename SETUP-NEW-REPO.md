# How to Create the New Clean PT Ready Repo on GitHub

This folder contains a minimal, clean distribution-only repository.

## Recommended Repo Name
- `PT-Ready` (clean and simple)
- or keep `USAF-PT-Ready` if you prefer

## Steps

1. **Create the new repository on GitHub**
   - Go to https://github.com/new
   - Name: `PT-Ready` (recommended) or `USAF-PT-Ready`
   - **Important**: Make it **Private** (at least initially)
   - Do **NOT** initialize with README, .gitignore, or license (we're bringing our own)
   - Create the repo

2. **Initialize this folder as a new git repo**
   ```bash
   cd pt-ready-distribution
   git init
   git add .
   git commit -m "Initial commit - v2.5.0 Early Access distribution repo"
   ```

3. **Push to the new GitHub repo**
   ```bash
   git remote add origin https://github.com/SeanHSimpson/PT-Ready.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages** (for the tester landing page)
   - Go to the new repo → **Settings → Pages**
   - Source: `main`
   - Folder: `/docs`
   - Save

   Your landing page will be available at:
   `https://seanhsimpson.github.io/PT-Ready/test/`

5. **Create the first GitHub Release (v2.5.0)**
   - Go to Releases → Draft a new release
   - Tag: `v2.5.0`
   - Use the content from `docs/release/GITHUB-RELEASE-BODY-v2.5.0.txt`
   - Attach the signed APK
   - Publish

## What This Repo Contains

- Clean proprietary notices
- README
- CHANGELOG
- Tester landing page (via GitHub Pages at /test/)
- No application source code

This keeps the public footprint minimal and clearly proprietary.

## After Setup

- Update any tester communications to point to the new GitHub Pages URL.
- You can archive or delete the old `USAF-PT-Ready` repo once everything is moved.
