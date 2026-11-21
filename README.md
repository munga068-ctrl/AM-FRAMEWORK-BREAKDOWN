# AM Framework Heatmap

Weekday x month heatmap of high-probability days (AM FRAMEWORK logged in the Indices Log) plus the low-probability days card (FOMC / CPI / NFP + day before, PPI).

- `index.html` is the whole app (GitHub Pages serves it as-is).
- Live data is fetched from `https://munga068-ctrl.github.io/Playbook-/am-frameworks.json`, then `./am-frameworks.json`, then the embedded snapshot inside `index.html`.
- Optional `events` field in the JSON: `[["2026-06-10", ["FOMC"]], ...]` drives the low-probability card.
