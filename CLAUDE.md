# Golden Years Senior Care website

## Rules for every session
- Source files (logo, photos, content.md) are in _source/. content.md is the ONLY source for text. Never invent services, staff titles, prices, testimonials, or claims. Never mention med passers or licensed assistants by title. Use "assisted living."
- Plain HTML5 and CSS only. No JavaScript, frameworks, npm, CDNs, or third-party requests.
- No inline styles, scripts, or event handlers (strict CSP).
- Self-hosted woff2 fonts. Inline SVG icons only.
- All images: EXIF/GPS metadata stripped, resized, WebP with srcset, width and height set.
- External links use rel="noopener noreferrer".
- Semantic HTML, one h1 per page, WCAG 2.2 AA, 18px minimum body text.
- CSS custom properties, organized and commented, no !important.
- Palette: #2E4E1C green, #E0960F gold (accents only), #F2C744 yellow (tiny highlights), #FAFAF7 background, #222222 text.
- Hosting: Cloudflare Pages. Security headers live in _headers.
- Tristen secures only the code, the GitHub repo, and her Cloudflare account. The owner's domain, DNS, and email are out of scope.
- Never claim something is secure or passing without evidence.
- Always give complete files.