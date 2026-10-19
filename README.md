# ORBITAL ATLAS

### The Living System · An interactive 3D field study

A small, cinematic orrery built to make a star system feel close enough to explore. Follow the planets around Sol, select a world to read its field notes, or take the controls and find your own view.

**[Open the live atlas →](https://bhavyajindal494.github.io/orbital-atlas/)**

## Explore

- **Five atlas entries** — Sol, Mercury, Terra, Mars, and Saturn, each with its own color, surface, and field notes.
- **A living orrery** — moving worlds, hand-built orbital paths, Terra's moon, and Saturn's rings.
- **Find your angle** — drag to orbit, scroll to move closer, and use the reset control to return to the wide view.
- **Set the pace** — pause the system or tune its motion with the time slider.
- **Made to travel** — responsive layout, keyboard-ready controls, reduced-motion support, and procedural textures generated in the browser.

## Controls

| Action | How |
| --- | --- |
| Select a world | Use the atlas buttons, or click a planet |
| Rotate the view | Click or touch and drag |
| Zoom | Scroll or pinch |
| Pause / resume | Use the footer control |
| Change orbital speed | Move the Time slider |
| Return to the wide view | Select Reset View |

## Run locally

This is a single-page project with no build step. Open index.html in a modern browser while connected to the internet. Three.js and OrbitControls load from the unpkg CDN.

If your browser blocks module imports from a local file, start a small static server in this folder instead:

~~~sh
python3 -m http.server 8000
~~~

Then visit http://localhost:8000.

## Built with

Three.js · WebGL · HTML · CSS · JavaScript

---

*A quiet corner of the cosmos, held in balance by gravity.*
