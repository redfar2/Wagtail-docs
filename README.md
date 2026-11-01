# Wagtail theme documentation

Static site for GitHub Pages: `index.html` is the whole site (no build step).

## Publish
1. On github.com, create a new **public** repository named `pawly-docs` (docs only — never the theme code).
2. Upload `index.html` (and this README) to the repository.
3. Repository → **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is live at `https://<your-github-username>.github.io/pawly-docs/`.

## Before publishing
- Replace `SUPPORT_FORM_URL` in `index.html` with your Google Forms / Tally link (questions in `SUPPORT-FORM.md`).
- Then put the docs URL and the support form URL into the theme's `config/settings_schema.json`
  (`theme_documentation_url`, `theme_support_url`).
