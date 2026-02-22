# PracticeKit — Marketing Website

Static marketing site for PracticeKit, published via GitHub Pages.

## Files

- `index.html` — main marketing page
- `privacy.html` — privacy policy, data practices, accessibility statement, and disclaimer
- `assets/style.css` — shared stylesheet

## Publishing on GitHub Pages

1. Create a new GitHub repo (e.g. `practicekit-website`)
2. Push this folder to the `main` branch
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`
5. Your site will be live at `https://yourusername.github.io/practicekit-website`

To use a custom domain (e.g. `practicekit.app`):
1. Add a `CNAME` file containing just your domain name
2. Configure your DNS with your registrar
3. Set the custom domain in GitHub Pages settings

## TODO before launch

- [ ] Replace `hello@practicekit.app` with real contact email in `privacy.html`
- [ ] Add App Store link once available
- [ ] Add real screenshots of the app
- [ ] Wire up the email capture form (e.g. Mailchimp, ConvertKit, or Formspree)
- [ ] Add CNAME file for custom domain
- [ ] Add Open Graph / social preview meta tags
- [ ] Add favicon
