# Morphwave

Audio-reactive visualizer that warps photos, video and your live camera to music. Three.js, web-first.

## Run it

Open `index.html` from any HTTPS host (GitHub Pages works) or localhost. Camera and mic only work on HTTPS or localhost.

## Controls

- **Sources:** demo beat, audio file, mic, image/video, camera (tap again to flip)
- **Modes (keys 0–9):** none, smear, droste, shatter, prism, infinite, halftone, solar, melt, ripple
- **Sliders:** React, Chaos, Trails, Heat, Symmetry, Twist, Bright (double-click to reset)
- **Keys:** X shuffle, H hide controls, Space demo beat on/off. Tap the canvas to hide/show controls.

## Roadmap

- Split into a Vite + TypeScript project: shaders, renderer, media, audio, ui, loop
- MP4 recording with audio
- More modes (terrain, pixel sort, mosh, corridor)
- Palette system, presets, output window
