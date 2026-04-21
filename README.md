# Pixel Roam

A single-file HTML demo of an autonomous pixel with simulated human-like intelligence — curiosity, memory, goals, moods, and the occasional change of heart. Fully responsive and reactive to device rotation (iPad / iPhone ready).

## What it does
- Pixel wanders a fullscreen canvas that reshapes to device size and orientation (portrait ↔ landscape).
- **Cognitive traits:**
  - Spatial memory (faint orange heatmap of visited areas)
  - Curiosity-driven goal selection (prefers unexplored space)
  - Mood cycle: curious → focused → satisfied → restless → bored → rebellious (color-coded)
  - Inner monologue shown in a floating thought bubble
  - ~0.15%/frame chance of abandoning its goal on a whim
- **Mobile-native:** retina-crisp rendering, safe-area insets, touch-action disabled, PWA meta tags.

## How to run
Open `index.html` in any modern browser. No build, no dependencies.

## Live demo
Served via GitHub Pages — see the repo's Pages URL.

## Files
- `index.html` — the entire app (markup, styles, canvas loop).
