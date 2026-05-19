# Rock Creek Concept — Flood-Routing Screening Spreadsheet Structure

**Companion to:** `Rock-Creek-Floodplain-Reactivation-Concept-DRAFT.md`, `01-Refined-Concept-and-Parameter-Table.md`, `02-Discharge-Dataset-Comparison.md`, `03-Benchmarking-Matrix.md`, `04-Feasibility-and-Next-Steps-Roadmap.md`
**Status:** Concept-stage screening structure, not an engineered analysis. Pre-fills source-document values with citations; flags placeholders as `[VERIFY]` where genuinely absent. This document defines the spreadsheet logic; the actual workbook can be built by exporting these tables to .xlsx.

---

## 1. What This Tool Is and Isn't

**This is** a deliberately simple screening framework that:

1. Inventories the hydrology inputs from the four discharge datasets (Deliverable 2);
2. Defines the diversion / corridor / weir parameters as variables that can be swept across plausible ranges;
3. Produces *order-of-magnitude* estimates of peak reduction, attenuated hydrograph duration, and corridor recharge volume;
4. Reports results in dataset-of-record terms so that the headline benefit claims can be honestly tied to the design hydrology.

**This is NOT** a substitute for a HEC-RAS 2D routing in the DWR / Wood Rodgers model (that's Roadmap Step H-4). It is the **screening that precedes** the 2D routing and that lets stakeholders see whether the concept is large enough to be worth the 2D work.

---

## 2. Spreadsheet Architecture

Five sheets, in this order:

1. **`README`** — version, source documents, decision rules, units, disclaimers.
2. **`Inputs_Hydrology`** — the four discharge datasets and the bifurcation flow split at all events of interest. Pre-filled from source documents with citations.
3. **`Inputs_Design`** — diversion, corridor, weir, and infiltration parameters. Plausibility ranges with `[VERIFY]` flags.
4. **`Calc_Peak_Reduction`** — peak reduction at Rock Creek and Keefer Slough downstream points for each design event.
5. **`Calc_Recharge_Volume`** — annual and per-event recharge volume estimate.
6. **`Output_Summary`** — single-page summary table, dataset-of-record-aware.

A future workbook can be set up with the same sheet names; this document lays out the columns and the calculation logic.

---

## 3. `README` Sheet

```
Title                : Rock Creek Concept — Flood-Routing & Recharge Screening
Version              : 0.1 (concept stage)
Prepared by          : Per project instructions, May 2026
Source documents     : See README block below
Units                : English (cfs, ft, ac, ac-ft, mi, sq mi, in)
Design decision rules:
  - Track A (Nord HEC-HMS Current Study) governs upstream hydrology
  - Track B (DWR HEC-RAS 2D) governs downstream / Keefer Slough impact + FEMA no-rise
  - 2011 FIS values shown for regulatory-context comparison, not as design basis
  - StreamStats values shown as cross-check
Disclaimers          : Concept-stage; not engineering, legal, or water-rights advice.
                       All [VERIFY] cells are concept-stage placeholders.
```

### Source documents

| ID | Document (path relative to repo) |
| --- | --- |
| `NORD_A` | Nord_Feasibility_Study_Part_A.md |
| `NORD_B1` | Nord_PartB_1_Geotechnical_Memo.md |
| `NORD_B2` | Nord_PartB_2_Geomorphic_Assessment.md |
| `NORD_B3` | Nord_PartB_3_Environmental_Constraints.md |
| `NORD_B5` | Nord_PartB_5_Appendices_8-11.md |
| `RCRD_INF` | RockCreek_Reclamation_District-Infiltration_Feasibility_Study_Oct2023.md |
| `SINGER` | Singer_Creek_HDP_Vol_1.md |
| `CT_D3` | Flooding_Issues_Along_Hwy99_Mud_Creek_to_Rock_Creek.md |
| `CONCEPT` | Rock-Creek-Floodplain-Reactivation-Concept-DRAFT.md |

---

## 4. `Inputs_Hydrology` Sheet

### 4.1 Discharge at Rock Creek ~0.91 mi upstream of bifurcation (~25 sq mi drainage area)

| AEP (%) | Recurrence (yr) | 2011 FIS Effective (cfs) | Nord Current Study (cfs) | USGS StreamStats (cfs) | DWR HEC-RAS 2D (cfs) | Citation |
| --- | --- | --- | --- | --- | --- | --- |
| 50 | 2 | `[VERIFY: not in NORD_A Table 12]` | `[VERIFY: not in NORD_A Table 10]` | `[VERIFY: not in NORD_A Table 11]` | `[VERIFY: extract from DWR 2D]` | — |
| 10 | 10 | 2,300 | 5,185 | 3,580 | `[VERIFY]` | NORD_A Tables 10, 11, 12 |
| 4 | 25 | `[VERIFY: not in FIS]` | 6,215 | 4,870 | `[VERIFY]` | NORD_A Tables 10, 11 |
| 2 | 50 | 4,400 | 7,115 | 6,000 | `[VERIFY]` | NORD_A Tables 10, 11, 12 |
| 1 | 100 | **5,600** | **8,020** | **7,170** | `[VERIFY]` | NORD_A Tables 10, 11, 12 |
| 1-plus | — | — | 9,785 | 17,100 (outlier — see Deliverable 2) | — | NORD_A Tables 10, 11 |
| 0.2 | 500 | 7,800 | 10,220 | 10,000 | `[VERIFY]` | NORD_A Tables 10, 11, 12 |

### 4.2 Bifurcation flow split

| Split version | % to Rock Creek | % to Keefer Slough | When applicable | Citation |
| --- | --- | --- | --- | --- |
| 2011 FIS | 56% | 44% | Currently effective FEMA; pre-2025 condition | NORD_A Sec. VII.B; CT_D3 Sec. 1 |
| DWR HEC-RAS 2D (current condition) | 39% | 61% | Post-sediment accumulation; awaiting FEMA approval (anticipated 2027) | CT_D3 Sec. 1 |
| Post-bifurcation maintenance (hypothetical) | ~56% | ~44% | If bifurcation cleanup MOU implemented and maintained (Caltrans memo recommendation) | CT_D3 Sec. "Regular Maintenance" |

### 4.3 Specific Keefer Slough cross-section values

| Cross-section | Drainage area (sq mi) | 2011 FIS Q100 (cfs) | DWR 2D Q100 (cfs) | Ratio (2D / FIS) | Citation |
| --- | --- | --- | --- | --- | --- |
| 1,125 ft d/s of Hicks Lane | 0.3 | 560 | `[VERIFY]` | — | NORD_A Table 12 |
| 500 ft u/s of Garner Lane (FIS) / 1,099 ft u/s of Garner Lane (DWR 2D) | 2.9 (FIS) | 680 | 2,390.90 | 3.52× | NORD_A Table 12; CT_D3 Sec. 1 |
| At State Highway 99 (channel cap. 525 cfs) | 4.4 | 525 (with 155 cfs sheet flow) | `[VERIFY]` | — | NORD_A Table 12 |

### 4.4 Combined Rock Creek + Keefer Slough at the bifurcation (DWR 2D)

| AEP (%) | Combined RC+KS upstream (cfs) | Rock Creek share (cfs / %) | Keefer Slough share (cfs / %) | Citation |
| --- | --- | --- | --- | --- |
| 1 | 6,413 | 2,483 / 39% | 3,867 / 61% | CT_D3 Sec. 1 |
| 10 | `[VERIFY]` | — | — | — |
| 2 | `[VERIFY]` | — | — | — |
| 0.2 | `[VERIFY]` | — | — | — |

### 4.5 Precipitation basis

| Item | Value | Citation |
| --- | --- | --- |
| Watershed mean annual precipitation | 38 in | NORD_B2 Physiographic Setting |
| Long-term hourly record (recharge calcs) | CRG gauge, Feb 2000 – Aug 2023 | RCRD_INF Sec. 5.1 |
| CRG average annual rainfall | 19.33 in (range 5.13 – 32.22 in) | RCRD_INF Table 1 |
| Wet years (>25 in) | 2001, 2003, 2005, 2010, 2016, 2019 | RCRD_INF Table 1 |
| Dry years (<10 in) | 2007, 2013, 2015, 2020, 2022 | RCRD_INF Table 1 |
| Design-storm framework (Nord) | NOAA Atlas 14, 24-hr, areally reduced by HMR59 DARF | NORD_A Sec. 6.1.1 |

---

## 5. `Inputs_Design` Sheet

### 5.1 Diversion structure

| Parameter | Concept value | Low end (screen) | High end (screen) | Citation / Status |
| --- | --- | --- | --- | --- |
| Intake location (mi u/s of bifurcation) | 1.1 | 0.6 | 1.4 | CONCEPT; Nord precedent envelope NORD_A Sec. 9.2.1, 9.2.2 |
| Drainage area at intake (sq mi) | 25 (interpolated) | 22 | 27 | NORD_A Table 10 |
| Diversion design discharge (cfs) | `[VERIFY: DATA MISSING]` | 1,000 | 5,000 | — |
| Diversion trigger threshold (cfs) | `[VERIFY: DATA MISSING]` | 500 | 2,000 | — |
| Diversion structure type | `[VERIFY: DATA MISSING]` | side-channel weir + bypass | gated structure | — |
| Diversion structure length (ft) | `[VERIFY: DATA MISSING]` | 100 | 300 | Nord envelope NORD_A Tables 6, 7 |
| Diversion structure height (ft) | `[VERIFY: DATA MISSING]` | 5 | 20 | Nord envelope NORD_A Tables 6, 7 |

### 5.2 Conveyance + corridors

| Parameter | Concept value | Low end | High end | Citation / Status |
| --- | --- | --- | --- | --- |
| Conveyance channel length to corridor heads (ft) | `[VERIFY: DATA MISSING]` | 1,000 | 7,500 | Nord envelope NORD_A Tables 6, 7 |
| Conveyance channel excavation (cy) | `[VERIFY: DATA MISSING]` | 50,000 | 800,000 | Nord envelope NORD_A Tables 6, 7 |
| North corridor length (mi) | 6.0 | 5.5 | 6.5 | CONCEPT |
| South corridor length (mi) | 4.4 | 4.0 | 4.8 | CONCEPT |
| Combined corridor length (mi) | 10.4 | 9.5 | 11.3 | CONCEPT |
| North corridor average width (ft) | `[VERIFY: DATA MISSING]` | 200 | 800 | — |
| South corridor average width (ft) | `[VERIFY: DATA MISSING]` | 200 | 800 | — |
| North corridor reactivated area (ac) | `[VERIFY: DATA MISSING — computed from length × width]` | 145 | 575 | — |
| South corridor reactivated area (ac) | `[VERIFY: DATA MISSING — computed from length × width]` | 105 | 425 | — |
| Combined reactivated area (ac) | `[VERIFY — computed]` | 250 | 1,000 | — |

### 5.3 Distributed rock weirs

| Parameter | Concept value | Low end | High end | Citation / Status |
| --- | --- | --- | --- | --- |
| Weir nominal height (ft) | 2.5 | 2.0 | 3.0 | CONCEPT |
| Weir spacing (ft) | `[VERIFY: DATA MISSING — function of slope; typical PBR practice = crest of one ≈ toe of next]` | 100 | 400 | — |
| Total weir count (computed) | `[VERIFY — = 5,280 × corridor mi / weir spacing]` | ~140 (10.4 mi at 400 ft spacing) | ~550 (10.4 mi at 100 ft spacing) | — |
| Per-weir backwater length at design Q (ft) | `[VERIFY: DATA MISSING]` | 50 | 200 | — |
| Per-weir effective ponded area at design Q (ac) | `[VERIFY: DATA MISSING]` | 0.05 | 0.5 | — |
| Total effective ponded area (computed) | `[VERIFY — = weir count × per-weir ponded area]` | 7 | 275 | — |

### 5.4 Surface infiltration

| Parameter | Concept value | Low end | High end | Citation |
| --- | --- | --- | --- | --- |
| Surface infiltration rate — favorable reaches (ft/day) | 0.7 | 0.5 | 0.7 | RCRD_INF Sec. 4.0, 8.0 (GSA report) |
| Surface infiltration rate — unfavorable reaches (ft/day) | 0.2 | 0.1 | 0.3 | RCRD_INF GSA App. Sec. 2.3 |
| Channel-infiltration bonus (multiplier on basin-area infiltration) | 1.5 (i.e., +50%) | 1.2 | 1.5 | RCRD_INF GSA App. Sec. 4.0 |
| Fraction of corridor expected to have favorable subsurface | `[VERIFY: DATA MISSING — set after R-1 / R-2 in Deliverable 4]` | 0.20 | 0.60 | — |
| Days per year with surface water available | 30 | 15 | 60 | RCRD_INF Table 1 (CRG record); set 60 days in wet years, 15 days in dry, 30 days central case |

### 5.5 Subsurface / vadose zone

| Parameter | Concept value | Citation |
| --- | --- | --- |
| Depth to groundwater (ft bgs) | 60–110 | RCRD_INF Sec. 7.0, GSA App. Sec. 2.4 |
| Permeable material extent (ft bgs) | 300–350 | RCRD_INF Sec. 7.0 |
| Tuscan aquifer specific yield (-) | 0.059 – 0.071 | RCRD_INF GSA App. Sec. 2.4 |
| Tuscan aquifer transmissivity (sq ft/day) | 2,322 – 23,650 | RCRD_INF GSA App. Sec. 2.4 |
| Tuscan aquifer horizontal Ksat (ft/day) | 66 – 5,712 | RCRD_INF GSA App. Sec. 2.4 |

---

## 6. `Calc_Peak_Reduction` Sheet — Logic

### 6.1 Inputs

For each design event (Q10, Q25, Q50, Q100, Q500), pull:

- Upstream design discharge `Q_upstream` from `Inputs_Hydrology` (per dataset: FIS / Nord / StreamStats / DWR 2D).
- Diversion design discharge `Q_div` and trigger `Q_trig` from `Inputs_Design`.

### 6.2 Calculation

```
Diversion captured (cfs)        = MIN( MAX(Q_upstream - Q_trig, 0), Q_div )
Residual Rock Creek peak (cfs)  = Q_upstream - Diversion captured
Bifurcation split applied to Residual:
    Rock Creek d/s of bifurcation (cfs) = Residual × Rock Creek share
    Keefer Slough d/s of bifurcation (cfs) = Residual × Keefer share
Corridor attenuation factor (-) = [VERIFY: DATA MISSING — function of weir count,
                                   spacing, corridor roughness, event size; expected
                                   range 0.6 – 0.95, with lower values (more attenuation)
                                   at smaller events and approaching 1.0 (no attenuation)
                                   at extreme events]
Corridor return flow peak (cfs) = Diversion captured × Corridor attenuation factor

Corridor return joins Rock Creek near SR 99 (N corridor) or main channel (S corridor).
At the SR 99 confluence point:
    Combined Q (cfs) = Rock Creek d/s of bifurcation peak (lagged) + Corridor return peak (lagged)
```

The peak-superposition is a screening simplification. Real routing would account for hydrograph lag — a key benefit of the concept is that the corridor *delays* the return-flow peak so that the unmitigated peak passes downstream before the diverted volume rejoins. The screening should report **both** an "in-phase" (conservative) and a "fully-lagged" (optimistic) bound on the downstream combined peak.

### 6.3 Sensitivity sweeps

Run the calculation across:

- 4 hydrology datasets × 5 design events × 3 corridor-attenuation assumptions = 60 cases.

Output: peak-reduction percentage at the downstream confluence vs. baseline (no-project) Q.

### 6.4 Report format

| Hydrology dataset | Event | Q_upstream (cfs) | Q_div used (cfs) | Residual Rock Cr. peak (cfs) | Corridor return peak (cfs) | Combined d/s peak (in-phase) (cfs) | Combined d/s peak (lagged) (cfs) | % reduction vs. no-project (in-phase) | % reduction vs. no-project (lagged) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Nord HEC-HMS | Q10 | 5,185 | `[VERIFY]` | `[calc]` | `[calc]` | `[calc]` | `[calc]` | `[calc]` | `[calc]` |
| ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |

---

## 7. `Calc_Recharge_Volume` Sheet — Logic

### 7.1 Inputs

- Corridor reactivated area (ac) — favorable fraction × total corridor area.
- Surface infiltration rate (ft/day) — favorable reaches.
- Channel-infiltration bonus multiplier.
- Days per year with surface water available.

### 7.2 Calculation

```
Favorable corridor area (ac)            = total reactivated area × favorable fraction
Annual basin-area recharge (ac-ft)      = Favorable area × Infiltration rate × Days available
Channel-infiltration bonus (ac-ft)      = Annual basin-area recharge × (Channel-bonus multiplier − 1)
Total annual corridor recharge (ac-ft)  = Annual basin-area recharge + Channel-infiltration bonus
```

### 7.3 Sensitivity sweeps

| Scenario | Favorable fraction | Infiltration rate (ft/day) | Days/yr | Total recharge (ac-ft/yr) |
| --- | --- | --- | --- | --- |
| Conservative | 0.20 | 0.2 | 15 | `[calc]` |
| Central | 0.40 | 0.5 | 30 | `[calc]` |
| Optimistic | 0.60 | 0.7 | 60 | `[calc]` |

**Worked example for a 500-ac corridor central case:**
- Favorable area = 500 × 0.40 = 200 ac
- Basin-area recharge = 200 ac × 0.5 ft/day × 30 days = 3,000 ac-ft
- Channel bonus = 3,000 × 0.5 = 1,500 ac-ft
- Total ≈ 4,500 ac-ft/yr

For comparison, the Sand Creek Infiltration Study's five-basin **100%-dam-height** scenario yielded 1,397 ac-ft/yr average across all five basins combined (*RCRD_INF*, Sec. 8.0). The rock-weir corridor benefit scales with corridor area and surface contact time; the favorable-fraction assumption is the dominant lever. **All numbers above are illustrative and depend on the placeholder inputs.**

### 7.4 Cross-check against Vina Subbasin recharge needs

Per AGUBC project context (CLAUDE.md), Vina Subbasin storage is growing ~8,000 AF/yr at current conditions. A central-case 4,500 ac-ft/yr recharge addition would be **~56% of current annual storage growth** — a meaningful contribution to GSP sustainability metrics, *if* the central-case assumptions are validated.

---

## 8. `Output_Summary` Sheet — Single-Page Summary

### 8.1 Headline screening result template

```
ROCK CREEK CONCEPT — SCREENING RESULT (concept stage)
Hydrology Track A (Nord HEC-HMS Current Study):
    Q100 upstream:                 8,020 cfs
    Q100 diverted:                 [calc]
    Q100 Rock Cr. d/s reduction:   [calc] %
    Q100 Keefer Sl. d/s reduction: [calc] %
    Q10/Q25/Q50 peak reductions:   [calc] %, [calc] %, [calc] %

Hydrology Track B (DWR HEC-RAS 2D):
    Q100 combined upstream:        6,413 cfs
    Q100 Keefer Sl. at Garner Ln (no-project): 2,391 cfs
    Q100 Keefer Sl. at Garner Ln (with concept): [calc] cfs
    Reduction at Garner Ln:        [calc] %

Recharge (Central case):
    Annual recharge:               [calc] ac-ft/yr
    % of current Vina Subbasin annual storage growth (8,000 AF/yr): [calc] %

Honest caveats:
    - Track A vs Track B difference at Q100 reflects unresolved hydrology disagreement
    - Corridor attenuation factor is a [VERIFY] placeholder — replace with HEC-RAS 2D
      result before quoting headline numbers
    - Diminishing-attenuation finding applies: Q100 / Q500 reductions are at the
      least-attenuated end of the event range
    - [VERIFY] placeholders mean the headline cannot be quoted yet
```

### 8.2 What this gives stakeholders

A single page that shows, before any 2D routing is done:

- Whether the concept's peak reduction looks like **5–15%, 25–40%, or 50%+** at frequent events;
- Whether the Keefer Slough benefit at Garner Lane looks meaningful when measured against the DWR 2D baseline;
- Whether the annual recharge benefit is a **fraction**, a **major portion**, or a **multiple** of the current Vina Subbasin storage growth;
- Where the largest uncertainty is — and what closing that uncertainty would change.

The screening result is not the design number. It is the **go / no-go input to a 2D routing decision**.

---

## 9. Translation to an .xlsx Workbook

When this structure is exported to .xlsx (Tovey's `anthropic-skills:xlsx` skill is the right tool):

- Each section above becomes a named range or a sheet.
- `Inputs_Hydrology` and `Inputs_Design` are the only sheets with user-editable cells; all other sheets are computed.
- All `[VERIFY]` cells should be conditional-formatted in a distinct color so the reader can see at a glance which numbers are placeholders.
- Source-cited cells should carry a note (Excel cell comment) with the source ID and section.
- A `Versioning` block in the README sheet should track when inputs were updated, by whom, and against which source revision.

---

## 10. Limits of This Screening

This screening **deliberately does not**:

- Route an actual hydrograph (no time-series; peak-flow only).
- Apply attenuation as a function of corridor geometry (uses a flat per-event attenuation factor as a `[VERIFY]` input).
- Account for tailwater conditions at the SR 99 / corridor return point.
- Resolve hydrograph lag rigorously (uses in-phase and fully-lagged bounds).
- Address backwater effects, sediment routing, water-quality routing.
- Substitute for FEMA no-rise demonstration (that requires the full DWR / Wood Rodgers 2D model).

The screening is for **deciding whether the concept is worth 2D routing**. The 2D routing is for **deciding whether the concept is worth designing**. Designing is for **deciding whether the concept is worth building**.
