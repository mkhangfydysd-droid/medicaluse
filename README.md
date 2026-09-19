# Medical Student Portfolio

A single-page, self-contained HTML portfolio site — bio/hero, clinical rotation
timeline, "conditions & wellness" write-ups, and an office-hours booking section.

All content (name, rotations, articles, contact info) is placeholder text.
Open `index.html` and edit directly — everything (HTML, CSS, JS) lives in that
one file, so there's nothing else to wire up.

## Run it locally

No build step is required — you can just open `index.html` in a browser.

If you'd rather serve it locally (e.g. to test relative paths):

```bash
npm start
```

This runs a local static server via `npx serve .`.

## Deploy with GitHub Pages

This repo includes a GitHub Actions workflow (`.github/workflows/deploy.yml`)
that publishes the site to GitHub Pages automatically on every push to `main`.

To enable it:

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Push to `main` (or re-run the workflow from the **Actions** tab).

Your site will be published at:
`https://<your-username>.github.io/<repo-name>/`

## Notes

- The booking form on the page is front-end only — submitting it just shows a
  confirmation message in the browser. To make it functional, connect it to
  a form backend (e.g. Formspree, Netlify Forms) or your own API.
