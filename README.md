# GTA VII România — 4D Edition

A mobile-friendly 3D open-world browser prototype built with HTML, Three.js and the Web Audio API. The fictional Romanian-inspired city includes driveable cars, police pursuits, a street race, a minimap, synthesized radio and mobile controls.

> **Unofficial fan prototype.** Not affiliated with or endorsed by Rockstar Games. “4D Edition” is a title; the game renders a 3D scene.

## Play

- Main prototype: open `index.html`.
- Atmosphere preview: open `immersion.html` for a cinematic accelerated day/night color grade and motion effects.
- Vehicle, police and street-race prototype: open `vehicles.html` for wanted stars, police pursuit, six timed checkpoints and a $2,500 race reward.
- Service Auto preview: open `service.html` to play the same vehicle/race prototype with a glowing blue garage marker. Driving into it costs $500, repairs the car and clears active wanted stars; it requires damage or an active wanted level.
- Synth radio edition: open `radio.html` for three original Web Audio stations: RADIO OFF, HORĂ MOLDOVENEASCĂ FM and TRAP ROMÂNIA FM. No external music files are used. Start playback with the radio button; browsers require a user gesture to enable audio.

Three.js is loaded from cdnjs, so an internet connection is needed. Serve the repository over HTTP (the previews use `fetch`), for example with `python -m http.server 8080`, then visit `http://localhost:8080/service.html`.

## Features

- Procedural Romanian-inspired city streets, apartment blocks and roundabout with tricolor flag
- Driveable sports sedan, ambient traffic, wanted stars and chasing police vehicles
- Timed street race with glowing checkpoints, directional arrow and cash reward
- Circular radar minimap with police and race checkpoint blips
- Service Auto marker with cash-gated repair and wanted-level clearing
- Mobile driving controls: steering, gas, brake, drift and horn
- Original synthesized radio melodies/rhythms via Web Audio API; no commercial music assets

The environment and music are fictional/original prototypes. Graphics, vehicle handling and AI are lightweight demos, not a production-scale AAA simulation.
