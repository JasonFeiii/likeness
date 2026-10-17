# Likeness

A dark room that only shows your face where a scanning light passes. Face landmarks (468 points) are detected in the browser and lit by moving bands, a wandering lamp and raking light.
Everything runs locally with TensorFlow.js; photos and camera frames never leave the browser.

- `index.html` — the whole app
- `models/*.packed.json` — BlazeFace short-range detector and MediaPipe Face Mesh weights (Apache-2.0), packed as JSON

Serve over HTTPS (GitHub Pages works) so the camera can be used.
