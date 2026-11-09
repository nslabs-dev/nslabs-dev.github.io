# NS Labs static website

No build step, JavaScript, cookies, analytics, CDNs or remote fonts. Deploy the contents of this folder as the publishing root. Works at a domain root or repository subpath.

Local preview: `python3 -m http.server 8080 --directory /workspace/nslabs-site`

## Hosting
- GitHub Pages: publish this directory from your chosen branch/root; `.nojekyll` is included.
- Netlify or Cloudflare Pages: no build command; use this folder as the publish directory.

## Before launch / Play submission
- The app is not published: retain the coming-soon label until an approved real Play URL is available.
- NS Scan privacy policy is published and final as of November 9, 2026: `/privacy/ns-scan.html`. Contact path is the public GitHub issues tracker; a dedicated support email is not published yet and may still be needed for Play Console fields.
- Never invent contact details.
- `og:image` values already use the absolute GitHub Pages URL. Add canonical and og:url tags only if the public URL changes.
- Host-level 404 handling varies. Relative links in 404.html resolve correctly at the publish root; for arbitrary nested missing URLs configure the host’s 404 route or replace them with the actual deployment base when known.
- Hosting providers may keep connection/access logs; inspect their settings and privacy practices.

## Sources
Brand art/fonts: NS Labs brand kit. App copy, images and policy: DocScanner-branding publication drafts. Font license notices are preserved under assets/fonts. App description and substantive policy text retained. No release artifacts, keys, credentials or personal documents are included.
