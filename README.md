# Sketch Tracer

This HTML page allows you to trace a sketch overlay (`evolve.jpg`) over an original painting (`original.jpg`) by controlling the opacity of the overlay interactively.

## Features

- Absolute stacking of two images of the same size.
- Fade the top image (`evolve.jpg`) at different speeds.
- Keyboard controls for opacity and fade speed:
  - `1` → Fully transparent (opacity 0)
  - `2` → Fully opaque (opacity 1)
  - `3` → Fast fade
  - `4` → Medium fade
  - `5` → Slow fade
  - `6` → Very slow fade
- Zoom in/out using the browser’s `+` and `-` keys.
- Scroll to different parts of the image with standard scrollbars.

## Setup

1. Place `original.jpg` and `evolve.jpg` in the same folder as `index.html`.
2. Open `index.html` in a modern browser.
3. Use the keyboard controls to adjust opacity or fading speed while tracing.

## Notes

- Both images **must have exactly the same dimensions**.
- Fade speed is adjustable in real-time via keys `3-6`.
- Zooming is done via browser zoom; no custom zoom logic is implemented.
