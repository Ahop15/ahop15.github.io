# synapse-coherence.github.io

Project website for **Synapse** (MICRO 2026), served by GitHub Pages at <https://synapse-coherence.github.io>.
The code lives in [TUM-DSE/Synapse](https://github.com/TUM-DSE/Synapse).

Plain static HTML, no build step: `index.html` + `assets/site.css`. Fonts (IBM Plex, OFL) are self-hosted under `assets/fonts/`, so the page makes no third-party requests.
`.nojekyll` tells Pages to serve the files as they are.

Preview locally:

```
python3 -m http.server 8000
```

Open TODOs are marked `TODO` in `index.html` (paper PDF link, ACM BibTeX, generator example).
