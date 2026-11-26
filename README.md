# RECLAIM

Interactive maps and tools from the project.

Live site: https://chiaquino.github.io/reclaim/

## Contents

| Folder | What it is |
|---|---|
| `/` | Landing page (`index.html`) |
| `energy-vulnerability/` | Padova energy vulnerability map. One self-contained page, built by `build_padova_webmap.py` |

## Update the map

1. Re-run `build_padova_webmap.py` (it writes `energy-vulnerability/index.html`).
2. Commit and push. The site refreshes after a minute or two.

## Data and credits

- ISTAT census data; IRPEF income by postcode (MEF) allocated to urban units.
- Building footprints: EUBUCCO and OpenStreetMap contributors.
- Energy values are modelled estimates, not measured consumption.
