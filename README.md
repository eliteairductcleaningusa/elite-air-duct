# Elite Air Duct Cleaning USA - Website

Files: index.html (main page), privacy.html, assets/ (images), netlify.toml.

## Before launch: edit 3 things in index.html (search for "SETTINGS")
- FB_URL   = your PUBLIC Facebook page link (shows Facebook buttons when filled)
- PIXEL_ID = your Meta Pixel ID (turns on ad tracking when filled)
- FORM_KEY = free access key from web3forms.com (bookings are emailed to you; needed on GitHub Pages)

## Deploy on Netlify (recommended - forms work)
1. Put these files in a GitHub repo (index.html at the repo root).
2. Netlify > Add new site > Import from Git > pick the repo > Deploy.
3. Site settings > Forms > Notifications > add your email so bookings reach you.
4. Add your custom domain under Domain management (free HTTPS).

## GitHub Pages (free)
Repo > Settings > Pages > Deploy from branch > main / root. Add FORM_KEY so bookings arrive by email. Without it, the form opens WhatsApp with the customer's details.
