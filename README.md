# flight-widget

Data and image assets for the Scriptable flight countdown widgets (CX 434 trip and beyond).

- `flight-data.json` — flights + asset index (same data as the flight page).
- `assets/**.b64` — images stored as base64 text so they can be maintained through the GitHub connector; the widgets fetch and decode them at runtime.
