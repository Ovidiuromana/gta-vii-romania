# GTA VII România — 4D Edition

A browser-based, mobile-friendly **3D open-world game prototype** built with HTML, Three.js and the Web Audio API. The project creates a fictional Romanian-inspired city with walkable streets, driveable cars, a minimap, mission markers, a procedural radio soundtrack and local save data.

> **Fan prototype:** This is an unofficial independent project and is not affiliated with, endorsed by, or connected to Rockstar Games. “4D Edition” is a title only; the prototype renders a 3D scene.

## Play

Open `index.html` in a modern browser with WebGL enabled and an internet connection (Three.js is loaded from CDN). For a quick local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- Procedural 3D city blocks, roads, a central roundabout and Romanian tricolor landmark
- Third-person on-foot movement, sprinting, jumping and camera orbit
- Driveable parked cars and simple ambient traffic
- Missions with destinations, countdowns and RON rewards
- Gas station, vehicle repair point and minimap
- Mobile virtual joystick and touch controls; keyboard and mouse controls on desktop
- Original synthesized radio motifs via Web Audio API (no commercial music assets)
- Local progress saving with `localStorage`
- Responsive HUD and WebGL fallback messaging

## Controls

| Action | Desktop | Mobile |
|---|---|---|
| Move / steer | WASD or arrow keys | Left virtual joystick |
| Enter / exit a car | F or E | INTRĂ / IEȘI button |
| Jump / nitro | Space | SALT / NITRO button |
| Sprint | Shift | Hold the action button while walking |
| Rotate camera | Q or drag | Drag the 3D scene |
| Radio | R | RADIO button |
| Pause | Esc or M | Pause button |
| Accelerate / reverse | W / S | GAZ / ÎNAPOI buttons |

## Notes

- The city and its locations are fictional and inspired by Romanian settings; this is not a real-world map.
- Browser storage is device-local and can be cleared by browser settings.
- Graphics and traffic are intentionally lightweight so the prototype can run on mobile hardware. It is not a production-scale AAA game.
- External dependency: Three.js r128 from cdnjs.
