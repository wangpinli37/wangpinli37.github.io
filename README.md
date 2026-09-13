# Pinli Wang — academic homepage

Public URL: https://wangpinli37.github.io/

A responsive, dependency-free academic homepage hosted on GitHub Pages.

## Edit

- `index.html`: biography, research, education, and contact details.
- `style.css`: colors, typography, layout, mobile, and print styles.
- `landau-invariant-learning.bib`: downloadable preprint citation.
- `favicon.svg`: browser icon.

The biography and background were prepared from `Pinli_Wang_CV.pdf`. The preprint title, author order, date, and link were verified against https://arxiv.org/abs/2608.09396. Research appointments and education dates reflect the supplied CV. The original CV and its telephone number are not included in this public repository.

## Preview

Open `index.html` directly, or run `python -m http.server 8765 --bind 127.0.0.1` in this directory and visit http://127.0.0.1:8765.

## Publish updates

GitHub Pages serves the root of the `main` branch. Commit changes and push to `origin main`; GitHub will rebuild the site. Update the footer date when revising the content. No package installation or build step is needed.
