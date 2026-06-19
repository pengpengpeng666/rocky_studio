# Rocky's Studio — Introduction & Discussion

This repository hosts the GitHub Pages site that serves as the introduction and discussion hub for **Rocky's Studio**: <https://rocky-studio.pages.dev/#/>

## What is Rocky's Studio?

Rocky's Studio is a collection of small, focused, in-browser web tools for developers and power users — JSON formatter, regex tester, HTTP client, X.509 certificate viewer, packet analyzer, and many more. Everything runs in your browser; nothing is uploaded to a server.

## Where to discuss

- **Ideas & questions:** [GitHub Discussions](https://github.com/pengpengpeng666/rocky_studio/discussions)
- **Bug reports:** [GitHub Issues](https://github.com/pengpengpeng666/rocky_studio/issues)

## Local preview

This is a plain static site. Open `index.html` directly in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is automatically published to GitHub Pages via the workflow in
`.github/workflows/pages.yml` on every push to `main`.

To enable it:

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Trigger the workflow by pushing to `main` (or run it manually from the Actions tab).

## File layout

- `index.html` — the landing page
- `assets/css/style.css` — stylesheet
- `assets/js/main.js` — small interactive helpers
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow
