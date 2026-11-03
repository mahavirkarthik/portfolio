# Mahavir Karthik — Portfolio

A responsive static portfolio built with HTML, CSS and JavaScript. It is ready for GitHub Pages and requires no build step or backend.

## Preview locally
Run from this directory:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Publish / update on GitHub Pages
Copy all files in this folder into the root of your `portfolio` repository, then run:

```bash
git add .
git commit -m "Refresh portfolio design and add profile photo"
git push origin main
```

In GitHub, check **Settings → Pages** and ensure the source is `Deploy from a branch`, branch `main`, folder `/ (root)`.

For a repository named `portfolio` under `mahavirkarthik`, the site URL is:
`https://mahavirkarthik.github.io/portfolio/`

## Included files
- `index.html` — content and structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation
- `mahavir-profile.webp` — optimized profile image

## Notes
- Technology marks are loaded from the Devicon CDN; the page remains readable if the icon CDN is unavailable.
- Verify contact details and project claims before sharing with recruiters.
- The Qwen / RAG work is labelled as a personal proof of concept, not a production deployment.


## Version 3 updates
- Dark technical theme with magenta / orange light accents inspired by Splunk's expressive gradient and Pump's direct, trust-building FAQ approach. This is an independent design, not a copy of either brand.
- Added an interactive "Why I chose it" section with expandable engineering trade-off answers.
- Added an explicit AI-assisted development disclosure: AI is used heavily as an accelerator, while architecture, infrastructure, integration, deployment, testing, troubleshooting and validation remain engineer-owned.


## Version 4 updates
- Increased paragraph, project description, experience bullet, AI disclosure and expandable Q&A font sizes for easier reading on desktop and mobile.
