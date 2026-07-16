# FixLoop

FixLoop is a repair-before-recycle marketplace that connects customers with trusted local repair shops.

Live site: <https://sidm13.github.io/FixLoop/>

## Deployment

The site is deployed automatically to GitHub Pages whenever `main` is updated. The workflow publishes the repository as a static site and includes a `404.html` fallback for client-side routes.

## Local preview

From the repository root:

```bash
python3 -m http.server 4173
```

Then open <http://localhost:4173/>.
