# The Voyage · Beat The Globe

## Put it online with GitHub Pages

1. Create a new **public** repository, for example `the-voyage`.
2. Upload `index.html` and `og-image.png` to it (Add file → Upload files → Commit).
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/the-voyage/`.
5. For a picture in the WhatsApp link preview: open `index.html`, replace `YOUR-SITE-URL` with that address (no trailing slash), and commit.

## Good to know

- This version has no backend, so it runs in preview mode: registrations, boarding passes and photos work on each person's own screen but are not saved or shared.
- For the live demo with saving, use the claude.ai artifact link.
- To collect real registrations publicly, connect a backend (Firebase or Supabase both have free tiers).
