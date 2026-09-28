# Speed Test By Rahul — Production Website

This package is a static website built from the supplied Speed Test HTML.

## Included
- `index.html` — main speed-test app
- `about.html` — About page
- `privacy.html` — Privacy page
- `favicon.svg` — favicon
- `site.webmanifest` — install/app metadata
- `robots.txt` and `sitemap.xml` — basic SEO/crawler files
- `CNAME` — custom-domain configuration for `speedtestbyrahul.com`

## Important
The speed test itself uses Cloudflare's public speed-test endpoints. Hosting this site does not create your own speed-test server.

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload all files in this folder to the repository root.
3. Enable GitHub Pages from the repository's Pages settings and deploy from the main branch/root.
4. In your domain registrar, point `speedtestbyrahul.com` to the GitHub Pages address recommended by GitHub.
5. Keep the `CNAME` file in the repository.
6. Enable HTTPS after the DNS record has propagated.

## Deploy with Cloudflare Pages
Upload this folder as a static site/project. Then add `speedtestbyrahul.com` under Custom Domains in Cloudflare Pages and follow the DNS instructions shown by Cloudflare.

## Before launch
- Replace `speedtestbyrahul.com` everywhere if you choose another domain.
- Verify the final domain in Google Search Console.
- Submit `/sitemap.xml`.
- Test the site on mobile and desktop.
- Check that About and Privacy links work.
- Recheck the third-party speed-test/privacy wording if the measurement provider changes.
