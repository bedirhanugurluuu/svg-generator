# Brush SVG Generator

A small generative art toy that paints a brush-textured city skyline, hills, and meadow as pure SVG. Same seed → same scene.

**Live demo:** open `index.html` locally, or after enabling GitHub Pages:

`https://<your-username>.github.io/<repo-name>/`

## Features

- Seeded, reproducible scenes
- Brush density, edge jitter, meadow density
- Palettes: Day, Dusk, Night, Fog, Autumn
- Portrait / landscape orientation
- Motion toggle (wind & clouds)
- Copy SVG, download SVG / PNG
- Shareable URL (settings sync to the query string)

## GitHub Pages

1. Push this repo to GitHub
2. **Settings → Pages → Deploy from branch**
3. Branch: `main` (or `master`), folder: `/` (root)
4. Wait a minute, then open the Pages URL

No build step — just static files.

## Local use

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## License

MIT
