# Rock Creek Floodplain Reactivation Concept

Concept-stage technical synthesis for a flood-diversion, groundwater-recharge, and floodplain-reactivation project on Rock Creek, Butte County, California — prepared for AGUBC (Agricultural Groundwater Users of Butte County) stakeholder discussion, May 2026.

**Live dashboard:** https://agubc-vina.github.io/rock-creek-floodplain/

The dashboard renders this repository's six markdown deliverables as a single tabbed page with the project vicinity map and key figures from the Caltrans D3 memorandum embedded for context.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | Single-page tabbed dashboard (6 tabs). Loads the deliverable markdown files client-side via `marked.js`. |
| `00-README-Deliverables.md` | Overview tab content — headline findings and source index. |
| `01-Refined-Concept-and-Parameter-Table.md` | Refined technical description + 50-row parameter table with source citations. |
| `02-Discharge-Dataset-Comparison.md` | Four-way discharge dataset comparison (2011 FIS / Nord HEC-HMS / USGS StreamStats / DWR 2D) + governing-dataset recommendation. |
| `03-Benchmarking-Matrix.md` | Concept benchmarked against Nord, Sand Creek Infiltration Study, Singer Creek, Flood-MAR, USGS RDS pilots, BDA literature. |
| `04-Feasibility-and-Next-Steps-Roadmap.md` | Six feasibility domains; what would have to be true; what's open; sequence and responsible parties. |
| `05-Flood-Routing-Screening-Spreadsheet-Structure.md` | Five-sheet spreadsheet logic with cited inputs and calculation rules. |
| `06-Typical-Reach-Design-Concept.md` | Concept-stage best-guess illustration of one 600-ft reach (plan view + two cross sections + planting palette + species notes). |
| `07-Order-of-Magnitude-Cost-Benefit.md` | OOM cost-benefit bracket: ~2,500–3,000 AF/yr recharge at ~$25–35 M capital, ~$650/AF levelized. Target framework for screening modeling. |
| `Rock-Creek-Floodplain-Reactivation-Concept-DRAFT.md` | Original stakeholder-facing concept draft (predecessor to the deliverables). |
| `assets/` | Project vicinity map and figures extracted from the Caltrans D3 memorandum. |

## Source documents

The deliverables cite five source documents that live in iCloud rather than this repo (they are large PDFs / scanned reports):

- **Nord Feasibility Study (Part A + 5 Part B appendices)** — Wood Rodgers for Butte County / DWR, Aug 2023
- **Rock Creek Reclamation District Infiltration Feasibility Study** — Wood Rodgers / GeoSystems Analysis, Oct 2023
- **Singer Creek Preserve Habitat Development Plan, Vol. 1** — Restoration Resources for BCAG, 2008–2009
- **Caltrans D3 Hydraulic Branch memorandum** — *Studying the Flooding Issues Along Hwy 99 from Mud Creek to Rock Creek*, Sungho Lee PE, Nov 2025
- **Rock Creek Floodplain Reactivation Concept DRAFT** — original stakeholder-facing draft (included in this repo)

## Local preview

To preview the dashboard locally:

```bash
cd rock-creek-floodplain
python3 -m http.server 8080
# then open http://localhost:8080/ in a browser
```

The dashboard fetches the `.md` files via `fetch()`, which requires HTTP (not `file://`).

## Status

Concept-stage. Not engineering, legal, or water-rights advice. All quantitative values flagged `[VERIFY]` require technical confirmation before external use.
