# NEON APEX — 3D Street Racing

A small, playable 3D arcade driving game built with Three.js. It runs in a modern browser and can be hosted on GitHub Pages.

## Play locally
Because this uses JavaScript modules, run it from a local web server rather than opening `index.html` as a `file://` URL.

If you have Python installed:
```bash
python -m http.server 8000
```
Then open http://localhost:8000

## Controls
- W / ↑: accelerate
- S / ↓: brake
- A / ← and D / →: steer
- R: reset
- Touch controls appear on smaller/touch devices.

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `neon-apex-racing`.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment. Your public URL will look like `https://YOUR-USERNAME.github.io/neon-apex-racing/`.

## Notes
- Three.js is loaded from jsDelivr, so players need an internet connection.
- This is a prototype: it uses simple procedural 3D shapes rather than licensed car models or sound assets.
- For a commercial release, add a license, test on target devices, and review third-party asset and library licenses.
