# Likeness

In-browser face landmark detection (468 points) drawn into a flowing WebGL field.
Everything runs locally with TensorFlow.js; photos and camera frames never leave the browser.

- `index.html` — the whole app
- `models/*.packed.json` — BlazeFace short-range detector and MediaPipe Face Mesh weights (Apache-2.0), packed as JSON

Serve over HTTPS (GitHub Pages works) so the camera can be used.
