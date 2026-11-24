# Ascent to 180

An LSAT practice game. Practice score is altitude on a live 3D mountain.

Adaptive practice, blind review and trap-coded explanations, in a single installable web app (HTML, CSS and JavaScript, with WebGL for the mountain). In development.

Designed, written and tested by Jay Leggette.

## Run it

No build step. Serve this folder with any static server, or open `index.html` in a browser:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Contents

- `index.html`: the whole app
- `sw.js`, `manifest.webmanifest`, `icons/`: offline support and install metadata
- `fonts/`: self-hosted fonts
