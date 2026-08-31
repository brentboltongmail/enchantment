# Enchantment of the Seas - 3D Ocean Showcase

An interactive 3D WebGL / Three.js ocean and cruise ship showcase featuring realistic water shaders, dynamic lighting, weather controls, interactive deck exploration, fireworks, route mapping with Leaflet, and a 3D model of *Enchantment of the Seas*.

## Features

- **Realistic Ocean Simulation**: Custom vertex & fragment shaders simulating ocean swell, choppy surface waves, foam, specular highlights, and subsurface scattering.
- **Interactive 3D Ship Model**: 3D GLB model with day/night lighting, spot lights, deck markers, and interior views.
- **Environmental Controls**: Dynamic time of day (day, golden hour, sunset, night), storm/rain conditions, fog, wave height, and wind settings.
- **Route & Cruise Map**: Integrated interactive Leaflet map tracing the ship's itinerary and coordinates.
- **Deck & Camera Modes**: Orbit mode, first-person deck walkthrough, bridge view, and cinematic aerial fly-arounds.
- **Interactive Fireworks & Audio**: Custom particle system for fireworks displays with lighting reflections on water.

## Getting Started

To run locally, serve the directory using any static web server:

```bash
# Python 3
python3 -m http.server 8000

# or Node.js (npx)
npx serve .
```

Then open `http://localhost:8000` in your web browser.

## Requirements

- Web browser with WebGL 2.0 support
- [Git LFS](https://git-lfs.com/) for cloning/pulling the 3D model (`enchantment.glb`)
