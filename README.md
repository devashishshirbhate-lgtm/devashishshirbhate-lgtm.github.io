# Devashish Shirbhate – Portfolio

Static portfolio site (HTML, CSS, vanilla JS). No build tools, no dependencies.

## Before you publish – replace these placeholders
1. **Photo:** add `assets/profile.jpg`, then in `index.html` change the hero image `src` from `assets/profile-placeholder.svg` to `assets/profile.jpg`.
2. **Resume:** copy your PDF to `assets/Devashish_Shirbhate_Resume.pdf` (the Download buttons point to this exact name).
3. **Social preview image:** add a 1200x630 `assets/og-image.png`.
4. **Project links:** CONTEXTA and CodeFix currently link to your GitHub profile. Replace with the repository URLs and add live demo links when they exist.
5. **Site URL:** the files assume `https://devashishshirbhate-lgtm.github.io/` (a GitHub Pages user site). If yours differs, update it in `index.html` (canonical, `og:url`, `og:image`, JSON-LD `url`), `robots.txt` and `sitemap.xml`.
6. **Phone number:** intentionally not published. Add it to the Contact section only if you want it public.

## 1. Preview locally
Open `index.html` in a browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## 2. Upload to a public GitHub repository
Create a repository named `devashishshirbhate-lgtm.github.io` (public) and upload all files, keeping `assets/` as a folder.

## 3. Enable GitHub Pages
Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`, then Save. The site goes live in a few minutes.

## 4. Submit to Google Search Console
Go to https://search.google.com/search-console, add your live URL as a property, verify ownership, then submit `sitemap.xml`. Indexing takes time and no ranking is guaranteed.
