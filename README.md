# Dr. Ghias Attar — Static HTML/CSS Site

Pure HTML + CSS, no JavaScript framework. SEO-optimized with server-rendered content, JSON-LD structured data, hreflang, sitemap, and robots.

## Files
- `index.html` — Arabic (root, default)
- `en/index.html` — English
- `styles.css` — All styles
- `assets/` — Images (doctor, before/after, clinic)
- `favicon.png` — Tooth icon
- `robots.txt`, `sitemap.xml` — SEO

## Hosting
Drop the entire folder into any static host:
- **Netlify / Vercel**: drag-and-drop the folder
- **Cloudflare Pages / GitHub Pages**: push as repo
- **Hostinger / cPanel**: upload via FTP to `public_html`

No build step. No server. Crawlers see the full content immediately.

## Edit content
Open `index.html` (Arabic) or `en/index.html` (English) in any text editor.
- Phone number: search-replace `966572718649` and `+966 57 271 8649`
- Address / hours: in the `#location` section
- Reviews: in the `#testimonials` section
- Before/after images: replace files in `assets/before-after-N.jpg`

## Domain setup
Update the canonical/sitemap URLs in:
- `index.html` and `en/index.html` — `<link rel="canonical">`, og:url, hreflang
- `sitemap.xml` and `robots.txt` — replace the domain
