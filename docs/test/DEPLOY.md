# Deploying the PT Ready Tester Landing Page (GitHub Pages)

This page will be hosted at:
**https://seanhsimpson.github.io/USAF-PT-Ready/test/**

---

## Step-by-Step: Enable GitHub Pages (Fastest Option)

1. Go to your repository on GitHub:
   https://github.com/SeanHSimpson/USAF-PT-Ready

2. Click the **Settings** tab (top right).

3. In the left sidebar, scroll down and click **Pages**.

4. Under **"Build and deployment"**:
   - **Source**: Select **"Deploy from a branch"**
   - **Branch**: Select `main`
   - **Folder**: Select `/docs`

5. Click **Save**.

GitHub will take 30–90 seconds to deploy. You will see a green message with your site URL:

`https://seanhsimpson.github.io/USAF-PT-Ready/test/`

---

## What Gets Served

- `docs/test/index.html` → becomes the homepage at `/test/`
- Everything else in `docs/` is also publicly available if needed.

---

## Updating the Page Later

Just edit the files in `docs/test/`, commit, and push to `main`.  
GitHub Pages will automatically rebuild and update the site (usually within 1 minute).

---

## Current Recommended Flow for Testers

- Share the clean GitHub Pages link:  
  **https://seanhsimpson.github.io/USAF-PT-Ready/test/**

- Put the APK + `START_HERE.txt` in the Google Drive folder (the `START_HERE.txt` should now point to the GitHub Pages link above).

This gives testers a much better experience than trying to use HTML inside Google Drive.

---

Let me know when you've enabled Pages and I can help you test the link or make any last tweaks to the page.
