# Taiwan Ride Sim

Zwift-inspired indoor cycling simulator focused on Taiwan routes.

## Goal (MVP)
- Import GPX routes
- Generate elevation & grade profiles (via DEM or GPX elevation)
- Use power/cadence to drive virtual speed
- Ride a route continuously for 5–10 minutes

## Tech Stack
- Unity
- GPX parsing + DEM elevation
- BLE (read-only, later phase)

## Roadmap
- Phase 0: Basic ride loop (fake power → speed → distance)
- Phase 1: GPX route loading & progress along route
- Phase 2: Elevation/grade-aware speed model
- Phase 3: BLE sensor input
- Phase 4: Stylized 3D world (OSM/DEM)
- Phase 5 (optional): Real view (user video sync) / Ghost replay
