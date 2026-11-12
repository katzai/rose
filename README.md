# Crimson Rose — Procedural 3D Web Scene

A real-time, browser-rendered rose scene built with HTML, CSS, JavaScript and Three.js. No flower photograph or pre-rendered video is used.

## Run locally
Open a terminal in this folder and run `python -m http.server 8000`, then visit `http://localhost:8000`. Three.js loads from jsDelivr, so an internet connection is required.

## Controls
- Move the pointer to subtly rotate the rose/camera.
- Scroll to shift the scene vertically.

The petals, leaves, stem, droplets, particles, spiral trails and water rings are generated at runtime. This is a procedural interpretation of the supplied reference; exact pixel matching requires the original 3D asset, material maps and lighting setup.
