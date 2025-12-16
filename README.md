# SubSavvy Landing

Static landing page for the SubSavvy app, designed to mirror the in-app palette (mint gradients, teal primary, soft glass panels).

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages

1. Commit and push to `main`.
2. In the repository settings, open **Pages**.
3. Under **Source**, choose `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save—your site will be available at `https://<your-username>.github.io/subsavvy-landing/`.

## Structure

- `index.html` — all markup, styles, and minimal JS (smooth scroll + dynamic year).
