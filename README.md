# Ballantyne.online holding page

A responsive, static site with no build process, framework, analytics, or external assets.

## GitHub Pages deployment

1. Create a public GitHub repository, for example `ballantyne-online`.
2. Upload `index.html`, `styles.css`, `topography.svg`, `favicon.svg` and `CNAME` to the repository root.
3. Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**.
4. In **Settings → Pages**, confirm the custom domain is `ballantyne.online`.
5. At your DNS provider, configure A records for `@` to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a CNAME for `www` to `<your-github-username>.github.io`.
6. Once DNS and certificate provisioning complete, enable **Enforce HTTPS**.

Do not delete email-related DNS records (MX, SPF, DKIM, DMARC).

## Before publishing

- Verify that the current domain DNS has no conflicting old A/AAAA records.
- Keep a backup of your old WordPress content before shutting down the server.

## Files

- `index.html`: semantic markup and page copy
- `styles.css`: responsive layout and colours
- `topography.svg`: locally hosted vector background
- `favicon.svg`: locally hosted icon
- `CNAME`: GitHub Pages custom domain

## Visual revision
Adds a subtle technical drafting background and a 25+ years technical experience signature. The illustration is a self-contained SVG and requires no external resources. No contact button is present.
