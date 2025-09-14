# 3D Viewer – GitHub Pages Starter

This is a minimal static site that displays a GLB/GLTF model using the `<model-viewer>` web component.

## Quick Start
1. Create a **public** GitHub repo (e.g., `3d-viewer`).
2. Upload all files in this folder to the repo (keep the structure).
3. Enable **GitHub Pages**: **Settings → Pages → Deploy from a branch**. Choose `main` and `/ (root)`.
4. Open your site at `https://<your-user>.github.io/<repo>/`.

## Add your model
- Put your file at `assets/model.glb` (GitHub hard limit is ~100 MB per file; try to keep it smaller).
- Edit `index.html` and set `<model-viewer src="/assets/model.glb">` (or click the “Use /assets/model.glb” button).

### Tips
- For large models, compress with [gltfpack](https://github.com/zeux/meshoptimizer/tree/master/gltf#gltfpack) or export Draco-compressed GLB from Blender.
- Use **relative paths** so it works both locally and on Pages.
- Project sites are served from a subpath: `https://<user>.github.io/<repo>/`.

## QR
The page includes a simple QR generator. Paste your final site URL and download the QR PNG for printing.
