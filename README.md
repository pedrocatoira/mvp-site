# MVP for Jira — website

Public site for MVP for Jira by Catoira Consulting Inc, served with GitHub Pages.

- `index.html` is written by hand.
- Inner pages (docs, privacy, terms, security, support) are built from `_src/pages/*.html`:
  `python3 _src/build.py _src .` (run from the repo root), then commit the generated `.html` files.
- `assets/` holds the stylesheet, the self-hosted Archivo font (SIL Open Font License, see `assets/fonts/OFL.txt`) and icons.

Before launch: replace the `MARKETPLACE_URL` placeholder
in `index.html` and `_src/build.py` with the real listing URL.
