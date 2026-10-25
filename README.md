# Everyday Strength

Website for Everyday Strength, nutrition and health coaching for women 40+.

It is a static site with no build step, so Vercel serves the files as they are.

- `index.html` is the home page
- `privacy.html` and `disclaimer.html` are the legal pages
- `styles.css` holds the home page styles
- `images/certificates/` holds the certificate images shown in the About section

## Preview locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Import this repository in Vercel with the "Other" framework preset and no build command. Every push to `main` deploys the live site, and every pull request gets a preview link.
