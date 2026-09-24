# Orbital Foundry

**Orbital Foundry** is a browser-based 3D rocket and spaceflight sandbox built largely inside a single HTML file.

<img width="1170" height="2074" alt="image" src="https://github.com/user-attachments/assets/7ad36a3a-164a-4a91-91fb-5f927f9c3713" />


## Features

* **3D rocket builder** — a large procedural/PBR part catalog, attachment nodes, symmetry, layers, rotation, undo/redo, section-based staging, saved rockets, blueprints, and `.glb` export.
* **Vehicle engineering** — per-stage Δv/TWR, mass and thrust analysis, center of mass / pressure / thrust, stability checks, landing stance, power, parachute, and structural checks.
* **Rigid-body flight physics** — Rapier3D rigid bodies, per-part colliders and joints, fixed-step simulation, floating-origin physics, aerodynamics, heating, collision damage, and a built-in 6-DOF fallback physics system.
* **Orbital mechanics** — 3D patched conics, universal-variable propagation, SOI transitions, orbital elements, encounter prediction, Lambert transfers, maneuver nodes, and on-rails time warp.
* **Spaceflight systems** — SAS, RCS, fly-by-wire control, navball, docking, action groups, parachutes, fairings, landing gear, solar power, multiple vessels, crew, EVA, recovery, and science.
* **Flight Director / Auto Navigation** — numerical guidance and control for launch, orbit, transfers, flybys, and landing.
* **Optional Gemini tools** — an AI Rocket Designer and AI Mechanic integrated with the actual in-game vehicle and part systems.
* **Exploration** — planetary systems, custom worlds, deterministic procedural stars and planets, rare multiple-star systems, and dynamic asteroids.
* **Persistence and tools** — save slots, autosaves, `.ofsave` import/export, blueprints, graphics and control settings, desktop/mobile interfaces, developer tools, and regression tests.

## Running

Download the HTML file and open it in a modern browser. There is no build step.

Some libraries are loaded at runtime, so an internet connection may be required if they are not already cached. Gemini-powered features are optional and require your own API key.

## Origins & Credits

Orbital Foundry started as a fork of [CatPrinceHQ2](https://github.com/CatPrinceHQ2)'s [SpaceflightSimulatorInHTML](https://github.com/CatPrinceHQ2/SpaceflightSimulatorInHTML).

What began as a smaller single-file spaceflight project kept growing: the renderer became fully 3D, and much of the simulation and game logic was expanded, replaced, or rewritten along the way.

Many thanks to **CatPrinceHQ2** for the original project and for providing the starting point.

* [Original repository](https://github.com/CatPrinceHQ2/SpaceflightSimulatorInHTML)
* [Original Reddit post](https://www.reddit.com/r/SpaceflightSimulator/comments/1vjevli/i_made_spaceflight_simulator_in_a_single_html/)

## Status

Orbital Foundry is a work in progress. Expect bugs, unfinished systems, questionable balancing decisions, and things to change.
