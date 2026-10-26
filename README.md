# ABRAM — Portfolio | بورتفوليو ابرام

Personal portfolio of **Abram (ابرام)** — Web & App Designer (مصمم مواقع ويب وتطبيقات).
Bilingual Arabic / English with a live language toggle, immersive icy 3D visuals, and a WhatsApp contact (+20 122 787 0493).

## Files | الملفات

- `index.html` — the whole site in one self-contained file (markup, styles, scripts and translations are all inside it; fonts and Three.js load from public CDNs).
- `.nojekyll` — tells GitHub Pages to serve the files as-is, without Jekyll processing.

## Host on GitHub Pages | النشر على GitHub Pages

1. Create a new repository on GitHub (for example `abram-portfolio`).
   - Tip: if you name it `<your-username>.github.io`, the site becomes your main GitHub site.
2. Upload `index.html` and `.nojekyll` to the root of the repository (Add file → Upload files).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Source: Deploy from a branch**, then select branch `main` and folder `/ (root)`, and Save.
5. Wait about a minute — your site will be live at `https://<your-username>.github.io/<repo-name>/` (or `https://<your-username>.github.io/` for the special repo name above).

## Update the site | تحديث الموقع

Replace `index.html` with a newer export and commit — GitHub Pages republishes automatically.
