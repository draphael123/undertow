# Undertow

A deep-sea drift racer. Pilot a submarine-on-wheels across a slick seabed — the rock is thin under the wheels, so you're **always sliding**. Steer into the slide, hold a drift to charge the meter, and release for a mini-turbo boost. Mind the abyssal chasm.

Single-file HTML + Three.js (no build step). Just open `index.html` or visit the live deploy.

## Controls
- **W / ↑** throttle, **S / ↓** reverse
- **A D / ← →** steer
- **Shift** dive-brake (break traction to drift)
- **R** reset

## Tech
- Three.js (r160, via CDN importmap), single `index.html`
- Velocity-preserving redirection drift model, drift→boost mini-turbo, coral-reef kelp walls, caustics/god-rays/marine-snow atmosphere, abyssal-chasm hazard with respawn.
