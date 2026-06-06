# Mise website

Static site for App Store Connect (support, privacy, terms) and marketing.

## Edit content

Update the Markdown files — not HTML:

- `index.md` — homepage
- `support.md` — support page
- `privacy.md` — privacy policy
- `terms.md` — terms of service

Layout and styling live in `_layouts/default.html` and `assets/css/styles.css`.

## Publish

Push to GitHub; Pages rebuilds automatically:

```bash
cd website
git add .
git commit -m "Update site"
git push
```

Live at https://gregstarr7.github.io/mise/
