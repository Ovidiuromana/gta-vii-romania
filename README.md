# GTA VII România — 4D Edition

A mobile-friendly 3D open-world browser prototype built with HTML, Three.js and the Web Audio API. The fictional Romanian-inspired city includes walkable streets, driveable cars, police pursuits, missions and mobile controls.

> **Unofficial fan prototype.** Not affiliated with or endorsed by Rockstar Games. “4D Edition” is a title; the game renders a 3D scene.

## Play

- Main game: `index.html`.
- Race + radio edition: `race-radio.html` layers the timed 6-checkpoint street race and three synthesized radio stations over the main game without replacing its existing visuals, simulation or touch controls. Start the race by driving into the glowing green marker near the starting cars. Finish in 45 seconds for **+2,500 RON**.
- Other demos: `vehicles.html`, `immersion.html`, `radio.html` and `service.html`.

Run from the repository directory with `python -m http.server 8080`, then open `http://localhost:8080/race-radio.html`. The race edition fetches `index.html`, so use a local web server rather than opening the file directly. Three.js is loaded from cdnjs and needs an internet connection.

## Features

- Original Three.js city scene, third-person gameplay and mobile controls
- Glowing race-start marker; 45-second race with six sequential 3D checkpoints and a floating direction arrow
- +2,500 RON reward, HUD countdown and celebratory success banner/sound
- Radio cycle: RADIO OFF, HORĂ MOLDOVENEASCĂ FM, TRAP ROMÂNIA FM
- Synthesized Web Audio folk-inspired melody and trap-style bass rhythm; no MP3 assets

All locations and music are fictional prototypes. This is not a production-scale AAA game.
