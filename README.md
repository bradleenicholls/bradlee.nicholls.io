# bradlee.nicholls.io

Personal portfolio site for **Bradlee Nicholls — Data Analyst**. Dashboards, SQL, GA4, and marketing analytics that connect data to business decisions.

🔗 **Live site:** https://bradleenicholls.github.io/bradlee.nicholls.io/

## About

A single-page portfolio built as a self-contained static site — no build step, no framework, no dependencies to install. Everything renders from one `index.html`, with fonts loaded from Google Fonts and assets served from the `assets/` folder.

## Tech

- Plain HTML, CSS, and JavaScript (all inline in `index.html`)
- Google Fonts (Inter, Space Grotesk)
- Hosted on GitHub Pages

## Structure

```
.
├── index.html      # The entire site (markup, styles, and scripts)
├── assets/         # Images, icons, favicon
└── .nojekyll       # Tells GitHub Pages to serve files as-is (skip Jekyll)
```

## Running locally

No install needed. Either:

- Double-click `index.html` to open it in your browser, or
- Serve it locally for accurate paths:

  ```bash
  # Python 3
  python -m http.server 8000
  # then visit http://localhost:8000
  ```

## Deploying

This site auto-deploys via GitHub Pages. To publish a change:

1. Edit `index.html` (or files in `assets/`).
2. Commit to the `main` branch — directly on GitHub or by pushing.
3. GitHub Pages rebuilds and redeploys automatically within a minute or two.

Pages is configured under **Settings → Pages → Deploy from a branch → `main` / root**.

## Contact

Bradlee Nicholls · [LinkedIn](https://www.linkedin.com/) · nichollsb10@gmail.com
