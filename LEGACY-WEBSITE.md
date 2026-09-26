# Legacy website

tilia now lives at https://tiliajs.dev.

This repo only serves the redirect from https://tiliajs.com to https://tiliajs.dev.
The redirect is the static site in `site/`, deployed to GitHub Pages by
`.github/workflows/deploy-pages.yml`. `404.html` forwards deep links to the same
path on tiliajs.dev, and `llms.txt` points agents to the new docs.

The rest of the tree is the frozen legacy monorepo. It is not built or deployed anymore.
