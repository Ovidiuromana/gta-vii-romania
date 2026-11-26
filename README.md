# GTA VII România — 4D Edition

A mobile-friendly 3D open-world browser prototype built with HTML, Three.js and the Web Audio API. The fictional Romanian-inspired city includes walkable streets, driveable cars, a minimap, mission markers, synthesized radio motifs and local saves.

> **Unofficial fan prototype.** Not affiliated with or endorsed by Rockstar Games. “4D Edition” is a title; the game renders a 3D scene.

## Play

- Main prototype: open `index.html` in a modern WebGL-enabled browser.
- Atmosphere preview: open `immersion.html` for a cinematic accelerated day/night color grade, night ambience, headlights overlay and motion effects. It embeds the main prototype.
- Vehicle and police prototype: open `vehicles.html` for a black sports sedan, synthesized engine and horn sounds, ambient classic-car traffic, a 1–5 star wanted system, speeding detection, and pursuing Romanian-style police cars with flashing sirens.
- Three.js is loaded from cdnjs, so an internet connection is required. You can run a local server with `python -m http.server 8000`, then visit `http://localhost:8000`.

## Prototype features

- Procedural city blocks, roads, central roundabout and Romanian tricolor landmark
- Third-person on-foot movement, sprint, jump and camera orbit in the main prototype
- Driveable parked cars and simple ambient traffic
- Timed destination missions with RON rewards
- Gas station, repair point, minimap and mobile touch controls
- Keyboard/mouse support, synthesized radio motifs and local `localStorage` saves
- Vehicle prototype with a sports sedan, lights, synthesized audio, traffic collisions, wanted stars and police pursuit
- Responsive HUD and WebGL fallback messaging

## Controls

| Action | Desktop | Mobile |
|---|---|---|
| Move / steer | WASD or arrow keys | Left virtual joystick (main prototype) |
| Enter / exit car | F or E | INTRĂ / IEȘI |
| Jump / nitro | Space | SALT / NITRO |
| Sprint | Shift | Hold action while on foot |
| Rotate camera | Q or drag | Drag the 3D scene |
| Radio / pause | R / Esc or M | HUD buttons |
| Vehicle prototype | WASD/arrows, Space horn, Shift drift | On-screen steering, gas, reverse and horn |

The city is fictional and inspired by Romanian settings; it is not a real-world map. Graphics, traffic, and effects are lightweight prototype features, not a production-scale AAA simulation.
