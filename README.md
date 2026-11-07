# NS Labs static website

No build step, JavaScript, cookies, analytics, CDNs or remote fonts. Deploy the contents of this folder as the publishing root. Works at a domain root or repository subpath.

Local preview: `python3 -m http.server 8080 --directory /workspace/nslabs-site`

## Hosting
- GitHub Pages: publish this directory from your chosen branch/root; `.nojekyll` is included.
- Netlify or Cloudflare Pages: no build command; use this folder as the publish directory.

## Before launch / Play submission
- The app is not published: retain the coming-soon label until an approved real Play URL is available.
- Privacy policy is explicitly a pre-launch draft: obtain publisher approval, a real public privacy/support contact and an effective date. Do not present it as submission-ready yet.
- Replace support placeholders in home and policy together. Never invent contact details.
- Once the public URL is known, convert each `og:image` value to an absolute public URL for social crawlers (relative values intentionally preserve portable subpath hosting). Add canonical and og:url tags only after the URL is known.
- Host-level 404 handling varies. Relative links in 404.html resolve correctly at the publish root; for arbitrary nested missing URLs configure the host’s 404 route or replace them with the actual deployment base when known.
- Hosting providers may keep connection/access logs; inspect their settings and privacy practices.

## Sources
Brand art/fonts: NS Labs brand kit. App copy, images and policy: DocScanner-branding publication drafts. Font license notices are preserved under assets/fonts. App description and substantive policy text retained; policy placeholders are labeled in plain English. No release artifacts, keys, credentials or personal documents are included.
