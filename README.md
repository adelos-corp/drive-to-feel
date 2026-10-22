# DRIVE TO FEEL

A browser-based interactive Formula-style steering-wheel prototype focused on paddle shifting, simulated drivetrain response, dashboard controls, and synthesized engine audio.

## Run locally

Keep these files together in the same directory:

- `index.html`
- `drive_to_feel_wheel.png`

Open `index.html` in a modern browser. Click **IGNITION**, then **ENABLE AUDIO** (browsers require a user gesture before audio playback). Use the throttle slider and paddle hitboxes or the **UP SHIFT** / **DOWN SHIFT** controls.

## Controls

- **Ignition:** start or stop the simulated engine.
- **Throttle:** increase simulated engine load and RPM.
- **Paddle shifters:** shift through neutral and eight forward gears.
- **DRS:** activates above 100 km/h; the simulation reduces drag and permits a higher speed ceiling. DRS closes automatically below the threshold.
- **Pit limiter / pit procedure:** simulate pit-lane speed management and selecting neutral.
- **Rotaries and buttons:** change simulated race map, energy phase, brake bias, differential, and engine-braking settings.
- **Keyboard:** Arrow Up / W shifts up, Arrow Down / S shifts down, Space toggles ignition, M toggles audio.

## Current limits

This is an educational interaction prototype, not an official F1 simulator or a validated 2005 car powertrain model. The rev ceiling is set to 15,000 RPM and the top-speed model is a simplified approximation. Engine sound is synthesized by the Web Audio API; authentic period V10 recordings are not yet included. Some wheel control mappings and vehicle responses are illustrative.

## Deploy

The project is a static site: deploy the repository using GitHub Pages or any static hosting provider. Ensure `index.html` and `drive_to_feel_wheel.png` remain in the same directory.

DRIVE TO FEEL is an independent fan-made concept and is not affiliated with or endorsed by Formula 1 or Ferrari.
