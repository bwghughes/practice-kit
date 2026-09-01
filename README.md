# PracticeKit — Marketing Website

Static marketing site for PracticeKit, published via GitHub Pages.

## Files

- `index.html` — main landing page (early-access signup)
- `privacy.html` — privacy policy, data practices, accessibility, disclaimer
- Product/SEO pages under feature folders (`secure-counselling-notes/`, etc.)
- `about/` and `authors/helen-hughes/` — company and founder pages
- `assets/style.css` — shared stylesheet
- `sitemap.xml` / `robots.txt` — crawl guidance

## Publishing on GitHub Pages

1. Push to the `main` branch
2. Settings → Pages → Deploy from branch `main`, folder `/ (root)`
3. Custom domain: `CNAME` is set to `practice-kit.app`

## SEO / campaign notes

- Homepage title and meta description prioritise early-access signup
- FAQ section with `FAQPage` schema for rich results
- `SoftwareApplication` schema with pre-order / early-access offer
- Breadcrumb schema on product and about pages
- Open Graph + Twitter large-image cards sitewide

## TODO before launch

- [ ] Add App Store link once available
- [ ] Add real screenshots of the app
- [ ] Confirm Formspree / email capture destination for campaign traffic
