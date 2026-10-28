# Korean Food Culture

A responsive static site about Korean food culture, with bilingual content, themes, interactive menu filtering, and 3D food previews.

## Local preview

```bash
python -m http.server 5500
```

Open `http://localhost:5500/`.

## GitHub Pages deployment

1. Push this entire folder to a GitHub repository.
2. In **Settings > Pages**, select **GitHub Actions** as the source.
3. Push a commit to the `main` branch.
4. Wait for the **Deploy Korean food page to GitHub Pages** workflow to finish.

The site has no build dependencies or backend requirements. It only needs the external libraries loaded by the HTML page.
