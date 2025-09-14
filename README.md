# bounation – GitHub Pages 3D Model

This is a minimal repo that hosts a GLB (`assets/model.glb`) on GitHub Pages using [`<model-viewer>`](https://modelviewer.dev).

## How to use

1. Replace `assets/model.glb` with your own GLB file (keep the same filename or update `index.html`).
2. Commit & push to GitHub.
3. In **Settings → Pages**, set Source to your branch (`main`) and folder `/ (root)`.
4. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

> Paths are relative (`./assets/model.glb`) so it works on project pages.

## Local preview (optional)

You can use a simple static server:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## Notes

- Export GLB (binary) from Blender or your DCC tool so textures are embedded.
- If your model appears black, check the Network tab (status 404 means wrong path) and Console for errors.
