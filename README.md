# spin-ittt
3D Spin the Wheel — single-file demo using Three.js served from `index.html`.

## Local preview

Start a local static server and open your browser:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## GitHub Pages

This repo is a single-page static demo. To publish on GitHub Pages from the `main` branch:

1. Commit and push `index.html` to `main`.
2. In the repository Settings → Pages, set the source to the `main` branch and `/ (root)`.
3. The demo will be available at `https://<your-username>.github.io/<repo-name>/` within a minute.

Notes

- Click or tap once on the page to enable audio (required by browser autoplay policies).
- No build steps or external files required — everything is in `index.html` and uses CDN-hosted Three.js.
