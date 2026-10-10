# Rana Muhammad Mazhar Khan — Portfolio

3D personal portfolio site. Single self-contained `index.html` (all assets inlined) — ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a new public repo on GitHub (e.g. `ranamazhar145.github.io` or `portfolio`).
2. Upload `index.html` to the repo root (drag-and-drop on github.com works).
3. Go to **Settings → Pages** → under *Build and deployment*, set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Use your .me domain

1. At your domain registrar, point the domain to GitHub Pages:
   - For an apex domain (`you.me`): add four `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - For `www.you.me`: add a `CNAME` record → `<username>.github.io`
2. In the repo: **Settings → Pages** → *Custom domain* → enter your domain → Save. GitHub creates the `CNAME` file for you.
3. Tick **Enforce HTTPS** once the certificate is issued (takes up to ~24h).

## Notes

- The contact form sends via FormSubmit to ranamazhar1450@gmail.com. It needs a one-time activation: submit the form once from the live site, then click the activation link in the email FormSubmit sends.
- The 3D hero loads Three.js from a CDN, so the page needs internet access to show the full 3D effect (a static fallback shows otherwise).
