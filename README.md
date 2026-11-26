# GTA VII România — 4D Edition

A mobile-friendly 3D open-world browser prototype built with HTML, Three.js and the Web Audio API. The fictional Romanian-inspired setting includes driveable cars, police pursuits, missions and mobile controls.

> **Unofficial fan prototype.** Not affiliated with or endorsed by Rockstar Games. “4D Edition” is a title; the game renders a 3D scene.

## Play

- Main game: `index.html`.
- Multi-country expansion: `countries.html` extends the main Three.js world eastward with three fictionalized regions, connecting bridges, border checkpoints, direction signs and distinct scenery. Drive east from the Romanian city along the extended highway to cross into Bulgaria, then continue to Hungary / Central Europe.
- Race + radio edition: `race-radio.html` adds the timed street race and synthesized radio.
- Vehicle / police demo: `vehicles.html`; cinematic effects: `immersion.html`; radio wrapper: `radio.html`; service demo: `service.html`.

Run from the repository directory using `python -m http.server 8080`, then open `http://localhost:8080/countries.html`. The multi-country page fetches `index.html`; use a local HTTP server rather than opening the page directly. Three.js is loaded from cdnjs.

The country environments are original, simplified prototypes—not real-world maps or exact replicas of existing cities.
