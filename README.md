# Typed Particle Laboratory

A dependency-free visual baseline for teaching TypeScript message protocols, worker lifecycles, transferable buffers, and rendering fallbacks. The catalog version uses a small main-thread simulation so it works without a bundler or optional browser APIs.

## Run locally

Open `index.html` or serve the folder with `python3 -m http.server 4173`.

## Study path

Start with the state object and deterministic seed. Then map the controls to the future TypeScript protocol: `init`, `resize`, `setParameters`, `frame`, and `error`. A full source-study version can add a Web Worker and OffscreenCanvas behind feature detection.

## Inclusive behavior

The visual field is supplemental. Controls, a text readout, keyboard focus, pause, reset, low-power mode, and reduced-motion handling provide the complete task path.

## Performance boundary

This demo does not claim that a worker or OffscreenCanvas is always faster. Workload size, startup, transfer, browser, and device conditions must be measured separately.

## License

MIT. See `LICENSE`.
