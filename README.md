# AR Tetris - Mobile AR Only

This build is intentionally scoped to mobile WebXR AR.

## Current fixes

- Prevents duplicate start/intro triggers from spawning an orphan Tetris piece at the top.
- Spawns the next piece only after line-clear animation finishes.
- Increases base drop speed from 1000ms to 500ms per row.
- Uses faster level progression scaling with a minimum 80ms drop interval.
- Removes Material Icons ligature text so users do not see raw icon text before the icon font loads.
- Keeps desktop/laptop keyboard and 3D fallback gameplay disabled by design.

## Supported path

- Android Chrome
- HTTPS hosting
- ARCore / Google Play Services for AR
- WebXR immersive-ar support

## Unsupported path

Unsupported devices show the disabled MOBILE AR ONLY button and explanatory status text.
