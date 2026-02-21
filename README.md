# Ephemeris

A 3D gravitational orbit simulator built in C++ with [Raylib](https://www.raylib.com/).

<p align="center">
  <img src="preview.jpg" alt="Ephemeris preview" width="800">
</p>

## Purpose

Ephemeris is a learning-driven project designed to strengthen engineering and physics thinking through hands-on practice with:

- **Low-level programming** — working directly with C++ and manual memory/data management
- **Vector math** — computing gravitational direction, distance and acceleration in 3D space
- **Numerical simulation** — implementing Newtonian gravity with frame-time integration
- **Real-time graphics** — rendering celestial bodies and camera controls with Raylib

The project trains problem solving, systems thinking and iterative learning through progressively more complex milestones, from simple orbital motion to cinematic rendering.

## Current Features

- 3D real-time rendering of celestial bodies (star and planet)
- Newtonian gravitational simulation using the standard gravitational parameter (μ = GM)
- Frame-time-based physics stepping
- Free camera controls
- Star and Planet classes with position, velocity, acceleration, mass and colour

## Tech Stack

| Component | Detail |
|-----------|--------|
| Language | C++14 |
| Graphics | Raylib 5.0 |
| Build | Makefile (supports Windows, Linux, macOS) |
| Editor | VS Code (workspace file included) |

## Getting Started

### Prerequisites

- A C++ compiler (g++ or clang++)
- [Raylib 5.0](https://github.com/raysan5/raylib/releases/tag/5.0) installed or available locally

### Build & Run

1. Open `main.code-workspace` in VS Code.
2. Navigate to `src/main.cpp`.
3. Press **F5** to compile and run.

Alternatively, build from the command line:

```bash
make
./game
```

## Project Structure

```
├── src/
│   └── main.cpp          # Entry point and simulation loop
├── lib/                   # Bundled runtime libraries
├── Makefile               # Build configuration
├── main.code-workspace    # VS Code workspace
└── preview.jpg            # Preview screenshot
```

## Roadmap

- [ ] Euler / Verlet numerical integration
- [ ] Multiple orbiting bodies and N-body interactions
- [ ] Orbital trail visualisation
- [ ] Realistic scale using real astronomical data
- [ ] Cinematic camera modes and post-processing effects
