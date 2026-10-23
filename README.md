# Cyberabad / Hyderabad Open World

A standalone browser-based 3D driving prototype focused on a fictionalized, game-scale slice inspired by HITEC City, Cyber Towers and Madhapur in Hyderabad, Telangana.

## Play

Once the GitHub Pages deployment finishes, open:

https://bharath20865.github.io/ride_in_hyd/

## Controls

- **W / Up Arrow**: accelerate
- **S / Down Arrow**: brake or reverse
- **A / D / Left / Right Arrow**: steer
- **Space**: handbrake
- **C**: cycle follow / cockpit / high camera
- **M**: map overlay
- **N**: switch day/night
- **P / Escape**: pause/resume

Mobile touch controls appear on smaller screens.

## Data and scope

This is a first district prototype, not a complete, surveyed or verified inch-by-inch reconstruction of Hyderabad. The navigation map attempts to load real OpenStreetMap road geometry and building footprints for a bounded area around Cyber Towers / HITEC City / Madhapur. If the public Overpass endpoint is unavailable, the game uses its handcrafted local map fallback. The 3D streetscape itself is a custom approximation with original storefronts, signs, barriers, flyover and metro structures, street furniture, flyers and props. These do not claim to copy every real-world advertisement, pillar, barrier or sign. The driving layout is not navigation-grade.

## Data and image credits

- OpenStreetMap contributors, Open Database License (ODbL): https://www.openstreetmap.org/copyright
- Intro reference photograph: “Buildings in HiTech city from Raidurg Metro station” by iMahesh, Creative Commons Attribution-ShareAlike 4.0. The image is displayed as a dimmed/blended intro background. Source: https://commons.wikimedia.org/wiki/File:Buildings_in_HiTech_city_from_Raidurg_Metro_station.jpg. License: https://creativecommons.org/licenses/by-sa/4.0/

## Technology

One static HTML page using Three.js and procedurally generated 3D assets with optional public OpenStreetMap data. No paid map API key, paid Lovable tier, login or backend is required. A network connection is needed for the Three.js library, intro reference image and optional map data.
