# SolarVerse

An interactive solar system built with Three.js. Drag to orbit, right-drag (or two-finger drag) to pan, and scroll or pinch to zoom. Select a planet to focus and learn about it. Use the lower controls to pause, change speed, show or hide paths and labels, and travel through time. Compare worlds and take the quiz from the top navigation.

## Run locally

Serve this folder with any static server, for example `python3 -m http.server 8000`, then visit http://localhost:8000. The Three.js ES modules and optional Google fonts are loaded from public CDNs, so an internet connection is required. WebGL is required.

## GitHub Pages

Push these files to the repository, then enable Pages in repository Settings → Pages, select “Deploy from a branch”, and choose the main branch and root folder. No build or base-path configuration is needed.

## Scientific notes

Planet sizes and orbital distances are adjusted for visibility. Circular orbits, initial phases, and animation are educational approximations, not ephemerides. The simulated date starts at January 1, 2026; it does not predict actual positions. Planet textures are procedurally generated artistic approximations. Moon counts change as discoveries are confirmed; plus signs indicate approximate lower bounds rather than a live catalog. Temperatures and other facts are approximate.
