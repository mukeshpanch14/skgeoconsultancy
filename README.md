# SK Geo Consultancy website

Static one-page site, no build step. The deployable site lives in `docs/`.

## Deploy on GitHub Pages
1. Push this repo to GitHub.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, Folder = `/docs`.
3. Site goes live at `https://<user>.github.io/<repo>/`.

Custom domain: add a `docs/CNAME` file containing the domain (e.g. `www.skgeoconsultancy.com`) and set it under Settings → Pages.

## Local preview
    cd docs && python3 -m http.server 8000

## Structure
- `docs/index.html`: the whole page (inline styles; Google Fonts)
- `docs/images/`: logo and photos (Unsplash License)
- `docs/404.html`, `docs/robots.txt`, `docs/.nojekyll`
