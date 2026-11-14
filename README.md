# Peter Nilsson — personal CV

A responsive, dependency-free personal CV website hosted on GitHub Pages.

## Content

The content is based on Peter's supplied LinkedIn PDF export, dated November
2026, and his supplied portrait. It includes the profile summary, top skills,
all 15 listed roles with dates and condensed descriptions, and all three
education entries. Overlapping role dates are preserved as supplied.

The original PDF and personal email address are not published. The website
links to [Peter's LinkedIn profile](https://www.linkedin.com/in/peteranilsson/)
for further details.

## Preview and edit

Open `site/index.html` in a browser, or serve the `site/` directory with any
static HTTP server. Edit `site/index.html` for content and `site/styles.css`
for styling. No build step, external fonts, scripts, or tracking are used.
`site/portrait.jpg` is an optimized copy of the supplied photo. When updating
styles, increment the stylesheet version in `site/index.html` so returning
visitors do not retain a cached older design.
The visual direction takes inspiration from [rigner.se](https://rigner.se/):
bold typography, italic accents, generous spacing, and contrasting sections.
No text, photographs, or source code from that site are reused.

## Deployment

GitHub Pages must be configured to use **GitHub Actions** in the repository's
Settings → Pages. `.github/workflows/pages.yml` publishes only the `site/`
directory on pushes to `main`, or when manually dispatched.

Public site: https://pnilss50.github.io/peteranilsson-cv/
