# Peter Nilsson — personal CV

A responsive, dependency-free personal CV website hosted on GitHub Pages.

## Content

The page uses only the supplied publicly visible information from
[Peter Nilsson's LinkedIn profile](https://www.linkedin.com/in/peteranilsson/):
name, location, current company, education and years, and a public summary
excerpt. It intentionally omits role titles, employment dates, skills, contact
details, achievements, and recommendations not publicly available.

## Preview and edit

Open `site/index.html` in a browser, or serve the `site/` directory with any
static HTTP server. Edit `site/index.html` for content and `site/styles.css`
for styling. No build step, external fonts, scripts, or tracking are used.
The visual direction takes inspiration from [rigner.se](https://rigner.se/):
bold typography, italic accents, generous spacing, and contrasting sections.
No text, photographs, or source code from that site are reused.

## Deployment

GitHub Pages must be configured to use **GitHub Actions** in the repository's
Settings → Pages. `.github/workflows/pages.yml` publishes only the `site/`
directory on pushes to `main`, or when manually dispatched.

Public site: https://pnilss50.github.io/peteranilsson-cv/
