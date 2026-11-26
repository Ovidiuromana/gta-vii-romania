# GTA VII România — 4D Edition

A mobile-friendly 3D open-world browser prototype built with HTML, Three.js and the Web Audio API. The fictional Romanian-inspired city includes walkable streets, driveable cars, a minimap, mission markers, synthesized radio motifs and local saves.

> **Unofficial fan prototype.** Not affiliated with or endorsed by Rockstar Games. “4D Edition” is a title; the game renders a 3D scene.

## Play

- Main prototype: open `index.html` in a modern WebGL-enabled browser.
- Atmosphere preview: open `immersion.html` for a cinematic accelerated day/night color grade, night ambience, headlights overlay and motion effects. It embeds the main prototype.
- Three.js is loaded from cdnjs, so an internet connection is required. You can run a local server with `python -m http.server 8000`, then visit `http://localhost:8000`.

## Prototype features

- Procedural city blocks, roads, central roundabout and Romanian tricolor landmark
- Third-person on-foot movement, sprint, jump and camera orbit
- Driveable parked cars and simple ambient traffic
- Timed destination missions with RON rewards
- Gas station, repair point, minimap and mobile touch controls
- Keyboard/mouse support, synthesized radio motifs and local `localStorage` saves
- Responsive HUD and WebGL fallback messaging

## Immersion preview

`immersion.html` adds an accelerated cinematic day/night cycle, sunset/night color grading, simulated street-lamp glow and headlight bloom, plus lightweight camera movement and speed-line effects while acceleration controls are held. These are presentation-layer effects over the prototype, not physically simulated lighting or vehicle telemetry. Respect for reduced-motion preferences disables the motion effects.

## Controls

| Action | Desktop | Mobile |
|---|---|---|
| Move / steer | WASD or arrow keys | Left virtual joystick |
| Enter / exit car | F or E | INTRĂ / IEȘI |
| Jump / nitro | Space | SALT / NITRO |
| Sprint | Shift | Hold action while on foot |
| Rotate camera | Q or drag | Drag the 3D scene |
| Radio / pause | R / Esc or M | HUD buttons |
| Accelerate / reverse | W / S | GAZ / ÎNAPOI |

The city is fictional and inspired by Romanian settings; it is not a real-world map. Graphics, traffic, and effects are lightweight prototype features, not a production-scale AAA simulation.
