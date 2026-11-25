# Ascent to 180 (desktop)

An Electron wrapper around the game. Progress saves locally on the device (nothing is uploaded).

Run locally: `cd desktop && npm install && npm start`
Build installers: push a tag like `v1.0.0`, or run the "Build desktop apps" workflow by hand. Installers appear under Actions artifacts and Releases.

Builds are unsigned, so Windows shows an unknown publisher warning and macOS needs right-click, Open the first time.
