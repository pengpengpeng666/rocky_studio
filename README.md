# Rocky's Studio — Introduction & Discussion

This repository hosts the GitHub Pages site that serves as the introduction and discussion hub for **Rocky's Studio**: <https://rocky-studio.pages.dev/#/>

The published Pages site lives at: <https://pengpengpeng666.github.io/rocky_studio/>

## What is Rocky's Studio?

Rocky's Studio is a collection of small, focused, in-browser web tools for developers and power users — JSON formatter, regex tester, HTTP client, X.509 certificate viewer, packet analyzer, and many more. Everything runs in your browser; nothing is uploaded to a server.

## Where to discuss

All discussion happens via **GitHub Issues** (which is always enabled and works without extra setup):

- **Start a new discussion:** <https://github.com/pengpengpeng666/rocky_studio/issues/new?template=discussion.md&title=Discussion%3A+>
- **Browse existing discussions:** <https://github.com/pengpengpeng666/rocky_studio/issues>

The discussion page also embeds an [utterances](https://utteranc.es/) widget so you can read and post directly from the site.

## Local preview

This is a plain static site. Open `index.html` directly in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is automatically published to GitHub Pages via the workflow in
`.github/workflows/pages.yml` on every push to `main`. The workflow uses the
`enablement: true` flag so Pages is automatically configured — no manual
Settings change is required.

To trigger a deploy:

1. Push to `main`, or
2. Go to the **Actions** tab, select **Deploy to GitHub Pages**, and click **Run workflow**.

## File layout

- `index.html` — the landing page
- `assets/css/style.css` — stylesheet
- `assets/js/main.js` — small interactive helpers
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow
- `.github/ISSUE_TEMPLATE/discussion.md` — issue template for new discussions
