# VENOM OS — Cockpit Simulator

Browser-first prototype of the proposed car infotainment / vehicle-control system.

## Run

Open `index.html` in a modern browser. No build step or server is required.

For the best cockpit-like preview, use fullscreen mode and a wide screen.

## Included prototype systems

- Main vehicle cockpit / HUD
- Fuel gauge with configurable reserve threshold
- Range calculation
- Interactive vehicle status
- Climate control, fan, airflow, A/C and recirculation
- Panoramic sunroof + sunshade controls
- Media / volume / EQ
- 360° camera concept screen
- TPMS, engine, electrical and body diagnostics
- Display brightness
- Drive modes
- Custom vehicle simulator sliders for speed, fuel, engine temperature and outside temperature
- App/function grid
- Responsive layout for desktop and mobile

## Next engineering stage

The browser state model is deliberately kept simple so it can later be mapped to Flutter/Dart state and, eventually, a vehicle gateway/CAN-bus layer. The simulator values are not connected to real vehicle hardware.
