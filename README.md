# DID Brain Visualization

Interactive 3D brain visualization for a 66-alter DID system. Built with Three.js.

## Features

- **3D Brain Model** — Auto-loads STL brain shell from GitHub Releases with adaptive scaling
- **66 Alter Database** — Complete neural mapping with strength/clinical profiles
- **Directed Neural Pathways** — Pathways aim toward anatomically-correct target ROIs
- **Per-Alter Style Variation** — Executive, emotional, motor, and dissociative pathway types
- **Relationship Lines** — Ally bonds (cyan) and rival tensions (red) between active alters
- **Brightness Sliders** — Real-time control of shell and point cloud opacity
- **Drag & Drop STL** — Fallback for local brain model loading

## Setup

1. Open `index.html` in a browser (GitHub Pages or local)
2. The STL brain model auto-loads from the configured URL
3. Search and inject alters to visualize their neural networks

## GitHub Pages Deployment

1. Create a new repository and push this directory
2. Create a Release (v1.0) and upload `brain_final.stl` as a release asset
3. Update `STL_URL` in `index.html` with the release asset URL
4. Enable GitHub Pages from Settings → Pages → Deploy from branch (main)

## Configuration

Edit the `STL_URL` variable near the top of `index.html`:

```js
var STL_URL = 'https://github.com/YOUR_USER/YOUR_REPO/releases/download/v1.0/brain_final.stl';
```
