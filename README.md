# 7-Seg Art

A tiny browser tool for turning images, videos, and GIFs into a wall of seven-segment displays.

Open `index.html` locally. Media is processed in the browser and is never uploaded. Animated GIF support loads `gifuct-js` from jsDelivr when a GIF is opened.

## Exports

- PNG: current rendered frame.
- JSON: segment bitmasks in row-major order for each exported frame.
