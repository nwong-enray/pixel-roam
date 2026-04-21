# Pixel Roam

A single-file HTML demo of an autonomous pixel performing a random walk on a flat canvas.

## What it does
- Yellow pixel wanders around a 1024×768 tablet-sized canvas (responsive — scales to viewport) using heading-drift random walk (tiny random nudge to angle each frame + momentum).
- Soft wall reflection keeps it inside the area.
- Fading blue trail shows the last ~180 steps.
- HUD displays live position + heading, with a `reset` button.

## How to run
Open `index.html` in any modern browser. No build, no dependencies.

## Live demo
Served via GitHub Pages — see the repo's Pages URL.

## Files
- `index.html` — the entire app (markup, styles, canvas loop).
