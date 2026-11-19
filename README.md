# CAR CUSTOMZ

A responsive, browser-based original 3D garage and driving prototype.

## Current build

- Procedural 3D vehicle bodies and a 3D presentation garage
- Eight original fictional vehicle presets across hypercar, supercar, JDM, muscle, luxury, off-road SUV, classic and track-racer styles
- Paint colour, finish, wheel package, rim size, spoiler / wide-body selection and ride-height controls
- Performance tuning controls and automatic / manual transmission setting
- A drivable procedural circuit with chase, cockpit and cinematic camera modes
- Keyboard controls (WASD / arrow keys) and touch controls
- Local-device save data
- Responsive desktop and mobile layouts
- PWA manifest and service-worker app-shell caching

## Run

This is a static web app. Serve the repository root with any static web server, or deploy it to Vercel. The 3D renderer uses Three.js from jsDelivr, so the first load requires an internet connection. The app shell is cached after the service worker installs; the 3D engine itself is not bundled offline in this prototype.

## Controls

- Drive: hold W / Up Arrow or the GO button
- Brake: hold S / Down Arrow or BRAKE
- Steer: A / D, arrow keys, or on-screen steering controls
- Manual gearbox: Shift to upshift, Ctrl to downshift
- Touch: use the on-screen buttons

## Scope

This is an early playable foundation, not a finished commercial racing simulator. Vehicle geometry, handling, sound, art assets, multiplayer, online accounts, cloud saves, licensed real-world vehicle models, damage simulation, and a downloadable Windows executable remain future development work.
