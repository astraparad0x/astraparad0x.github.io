# Research portfolio — Chetan Singh

A static, single-page research portfolio. No build step, no JavaScript, no tracking.

## Privacy

This site is **unlisted**, not access-controlled:

- Every page carries `noindex, nofollow, noarchive, nosnippet` meta tags.
- `robots.txt` allows crawling so engines can read the `noindex` directive. A
  `Disallow: /` rule would paradoxically let engines index the URL without
  reading the tag.
- `_headers` sets `X-Robots-Tag: noindex` on hosts that support custom headers
  (Netlify, Cloudflare Pages). GitHub Pages ignores it.
- The page contains no email address, phone number, or CV PDF.

Anyone with the URL can view the page. If true access control is required, use
a host with password protection or an identity-aware proxy.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

```
index.html          Single-page site
assets/styles.css   All styling
assets/favicon.svg  Favicon
assets/og.png       Social preview card (1200×630)
robots.txt          Crawl policy
_headers            Noindex headers for Netlify/Cloudflare
```

## Content

Selected threat research published at Cyble (2021), the HHS HC3 citation,
certifications, and a career summary.
