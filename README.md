# Hyderabad Open World

A free browser-based 3D driving prototype inspired by HITEC City and Madhapur, Hyderabad.

## Play

Once GitHub Pages is enabled and the deployment finishes, visit:

https://bharath20865.github.io/ride_in_hyd/

## Controls

- **W / Up Arrow**: accelerate
- **S / Down Arrow**: brake or reverse
- **A/D / Left/Right Arrow**: steer
- **Space**: handbrake
- **C**: cycle camera
- **M**: open the local map
- **N**: toggle night/day
- **P / Esc**: pause/resume

Mobile touch controls are shown on smaller screens.

## Data and scope

This is a first playable prototype, not a full, verified inch-by-inch reconstruction of Hyderabad. It creates custom 3D city props and tries to retrieve road and building geometry from public OpenStreetMap data for a bounded region. If that public service is unreachable, a handcrafted procedural city is shown instead.

Street signs, flyers, barriers, utility poles and many building details are original game props or approximations. They do not claim to reproduce every real-world sign, flyer, pillar or barrier. OpenStreetMap coverage is incomplete and is not navigation-grade here.

When OpenStreetMap data is used, attribution is shown in-game: © OpenStreetMap contributors. Data is available under the Open Database License (ODbL): https://www.openstreetmap.org/copyright

## Technology

A static HTML page using Three.js from a public CDN, with a procedural city fallback and optional OpenStreetMap-derived geometry. No paid map API key or backend is required. An internet connection is required to load the Three.js library and attempt to fetch fresh map data.
