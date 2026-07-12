# Oğuzhan Satılmış — iOS Developer Website

Static website for showcasing iOS apps, meant to be published with GitHub Pages.
Provides the URLs required by App Store Connect (Privacy Policy, Support).

## Structure

- `index.html` — Apps list (also the site's landing page)
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `support.html` — Support / FAQ
- `contact.html` — Contact
- `css/style.css` — Shared styles

## Before publishing

- Replace the placeholder app names, icons, descriptions, and App Store links in `index.html`
- Review `privacy.html` and `terms.html` to make sure they match what your apps actually do

## Publishing with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then save.
5. The site will be available at `https://<username>.github.io/<repo-name>/`
   (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

Use the published Privacy Policy and Support URLs in App Store Connect, e.g.:

- Privacy Policy URL: `https://<username>.github.io/<repo-name>/privacy.html`
- Support URL: `https://<username>.github.io/<repo-name>/support.html`
