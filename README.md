# Flavorly website

Static marketing + legal site for the Flavorly app (cooking recipes).

- `index.html` - landing page
- `privacy.html` - privacy policy (App Store Privacy Policy URL: `/privacy`)
- `terms.html` - terms of use (`/terms`)
- `support.html` - support + FAQ (App Store Support URL: `/support`)
- `vercel.json` - enables clean URLs (`/privacy` instead of `/privacy.html`)
- `assets/` - real app brand art (favicon, apple-touch-icon, hero webp), resized from the app repo's `app/assets/images/icon.png`

Deployed on Vercel as a static site: no build step, framework preset "Other", output directory = repo root. Same setup as the Tourly site.
