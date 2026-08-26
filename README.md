# TPS System Map

A self-contained, interactive system map of the Tax Planning experience — a pannable/zoomable diagram covering the traditional TPS-native spine, decision points, Ester-assisted entry modes (estimated baseline, partial return, raw document synthesis, direct IRS pull), and where the product converges with shared/Estate-side surfaces (Vault, Balance Sheet, Scenarios, Actions, Reports, Overview).

Open `tps_system_map.html` directly in a browser — no build step, no dependencies. Everything (including demo videos) is embedded inline.

## Features

- Click any card, decision diamond, or the Ester hub for detail
- **Highlight a flow** — filter to a specific entry mode (Full Return, Estimated, Partial Return, Raw Document Synthesis, Direct IRS Pull)
- **Explore a "what if"** — Vault as router (swaps Vault/Overview ordering), Tax Breakdown (TPS-native) (reverts the Overview convergence)
- Deep-linking: `#<nodeId>` in the URL opens straight to that card (e.g. `#hub` for Ester)
- Drag to pan, scroll to zoom, drag the drawer's left edge to resize it

## History

Recovered/reconstructed on 2026-08-26 after the original hosted artifact stopped rendering, by replaying the full edit history from the local session logs. Committed here going forward so it isn't dependent on any one hosting platform.
