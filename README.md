# vinayknetha.github.io

Portfolio — UI/UX engineering.

Single self-contained `index.html`: no framework, no build step, no external requests.
Hand-written CSS with a token-level light/dark theme, a monospace display face paired
with a humanist sans for body, and a live WCAG 2.1 contrast meter that computes its
own ratios in the browser.

## Running it locally

    python -m http.server 8000

Then open http://localhost:8000.

## Deploying

GitHub Pages serves `main` from the repository root. Pushing to `main` publishes to
https://vinayknetha.github.io.
