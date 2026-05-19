# Rock Creek / Keefer Slough — Discharge Dataset Comparison

**Companion to:** `Rock-Creek-Floodplain-Reactivation-Concept-DRAFT.md` and `01-Refined-Concept-and-Parameter-Table.md`
**Status:** Concept-stage technical analysis. Cited values are taken directly from the source documents in this repository. Datasets disagree materially; this document structures the comparison and recommends a governing dataset for the concept's screening flood-routing analysis.

---

## 1. The Problem

Three repository documents present three (in practice four) different peak-flow estimates for the same locations on Rock Creek and Keefer Slough, with material disagreement that matters most at frequent-to-moderate events — exactly the range in which a distributed rock-weir / floodplain-reactivation concept is expected to show its strongest attenuation benefit.

The datasets:

1. **Nord HEC-HMS "Current Study"** — Wood Rodgers / DWR hydrologic analysis prepared for the FEMA flood study update; rainfall-runoff (no streamflow gauge calibration on Rock Creek). *Nord_Feasibility_Study_Part_A.md, Appendix 1, Table 10.*
2. **USGS StreamStats** — regional regression equations (drainage-area-based) — included by the Nord study as a cross-check. *Nord_Feasibility_Study_Part_A.md, Table 11.*
3. **2011 Butte County FIS Effective Flows (FEMA)** — currently effective FEMA discharges; on Rock Creek, the FIS adopted Little Chico Creek peak discharges as a proxy because the watersheds are "very similar in respect to size, orientation, topography, and ground cover." *Nord_Feasibility_Study_Part_A.md, Table 12, citing FEMA 2011 FIS.*
4. **(Bonus, from Caltrans memo) DWR / Wood Rodgers HEC-RAS 2D model** — the *hydraulic* 2D model built on the Nord HEC-HMS hydrology; reports flow at specific cross-sections rather than at watershed-outlet analysis points. Not yet FEMA-approved (review anticipated 2027). *Flooding_Issues_Along_Hwy99_Mud_Creek_to_Rock_Creek.md, Sec. 1 and Sec. "Butte County, DWR and FEMA".*

The concept draft already flagged the three-way disagreement; the Caltrans memo introduces the fourth value at a downstream cross-section and is included here for completeness.

---

## 2. Side-by-Side Comparison — Rock Creek ~0.91 mi Upstream of the Bifurcation

This is the analysis point closest to the concept's proposed intake (~1.1 mi upstream). All three documents tabulate peak discharge here; the drainage area at this point is ~25 sq mi.

| Annual Exceedance Probability | Recurrence (yr) | Nord HEC-HMS "Current Study" (cfs) | USGS StreamStats (cfs) | 2011 FIS Effective (cfs) | Δ FIS vs. Current Study | Δ StreamStats vs. Current Study |
| --- | --- | --- | --- | --- | --- | --- |
| 50% | 2 | — | — | — | — | — |
| 10% | 10 | 5,185 | 3,580 | 2,300 | **−56%** | −31% |
| 4% | 25 | 6,215 | 4,870 | — | — | −22% |
| 2% | 50 | 7,115 | 6,000 | 4,400 | **−38%** | −16% |
| 1% | 100 | **8,020** | **7,170** | **5,600** | **−30%** | −11% |
| 1%-Plus | — | 9,785 | 17,100 | — | — | +75% (StreamStats anomaly) |
| 0.2% | 500 | 10,220 | 10,000 | 7,800 | **−24%** | −2% |

*Drainage area: Nord 25.1 sq mi; StreamStats 25.8 sq mi. Source: Nord Feasibility Study Part A, Tables 10–12. Δ percentages calculated against Nord "Current Study" as the reference.*

**Key observations:**

- **The three datasets agree best at the rarest events** (Q500: within 24% range), and **disagree most at frequent events** (Q10: 56% spread). The 100-yr (Q100) range is **5,600–8,020 cfs**, a ~43% relative spread.
- **2011 FIS Effective is the lowest** of the three at every event. The Nord report notes the FIS values are "less than the current study on the order of 35 percent" and attributes the difference to method (FIS used a gauge analysis from adjacent Little Chico Creek; Current Study used rainfall-runoff modeling on Rock Creek itself).
- **StreamStats 1%-Plus value of 17,100 cfs is an outlier** — likely reflecting an upper confidence bound or regression-equation tail behavior rather than a physical estimate. Treat as an artifact, not a usable design number.

---

## 3. Side-by-Side Comparison — Keefer Slough (Multiple Locations)

The disagreement compounds for Keefer Slough because Keefer's flow is dominated by the bifurcation diversion from Rock Creek, not by its own local watershed.

### 3.1 Keefer Slough at Hicks Lane Bridge (1.3–1.4 sq mi local drainage)

| AEP | Nord HEC-HMS (cfs) | USGS StreamStats (cfs) |
| --- | --- | --- |
| 10% | 280 | 225 |
| 4% | 350 | 295 |
| 2% | 400 | 345 |
| 1% | 450 | 390 |
| 1%-Plus | 550 | 980 |
| 0.2% | 575 | 475 |

*Source: Nord Tables 10 and 11.*

### 3.2 Keefer Slough at FEMA FIS Reference Points (2011 FIS)

| Location | Drainage area (sq mi) | Q10 (cfs) | Q50 (cfs) | Q100 (cfs) | Q500 (cfs) |
| --- | --- | --- | --- | --- | --- |
| Approx. 1,125 ft downstream of Hicks Lane | 0.3 | 130 | 400 | **560** | 750 |
| Approx. 500 ft upstream of Garner Lane | 2.9 | 275 | 500 | **680** | 850 |
| At State Highway 99 (channel capacity = 525 cfs) | 4.4 | 415 | 525 | **525** | 525 |
| Total at SR 99 including sheetflow | — | — | 760 | 840 | 1,200 |

*Source: Nord Table 12, reproducing 2011 FIS Table 3.*

### 3.3 Same Locations, DWR 2D Model (per Caltrans 2025)

> "Based on the proposed DWR 2D model result, the 100-yr flow discharge at the same location of the upstream boundary of the Caltrans 2D model is **2,390.90 cfs** at 1,099 feet upstream of the Garner Lane bridge. This value is **3.52 times** larger than the 100-yr flow discharge (680 cfs) of the original FEMA FIS report."
> — *Flooding_Issues_Along_Hwy99_Mud_Creek_to_Rock_Creek.md, Sec. 1.*

So at the **same Keefer Slough cross-section** (500 ft / 1,099 ft upstream of Garner Lane), the values are:

- FEMA 2011 FIS Q100: **680 cfs**
- DWR HEC-RAS 2D Q100: **2,390.90 cfs**
- Ratio: 3.52×

This is by far the largest disagreement in any of the datasets, and it directly affects every downstream concept on Keefer Slough (including this concept's stated benefit of reducing volume reaching Keefer Slough).

### 3.4 Bifurcation Flow Split — Then and Now

> "[The 2011 FIS] result of this rating is that approximately 44 percent of the 1-percent-annual-chance total Rock Creek discharge is diverted into Keefer Slough."
> — *Nord_Feasibility_Study_Part_A.md, Sec. VII.B, quoting FEMA 2011 FIS.*

> "The 100-yr flood discharge of Rock Creek from the upper watershed is **6,413 cfs**, which is divided at the Keefer Slough / Rock Creek bifurcation. The diverged flow discharge is: Rock Creek: 2,483 cfs (39%); Keefer Slough: 3,867 cfs (61%) — previous study by the Corps showed 44%.
>
> The channel conveyance capacity of Rock Creek decreased from 56% to 39% due to sediment deposit and growing vegetation at Rock Creek."
> — *Flooding_Issues_Along_Hwy99_Mud_Creek_to_Rock_Creek.md, Sec. 1.*

**The split itself has shifted by ~17 percentage points** in favor of Keefer Slough over the period of record because of sediment deposition and vegetation at the bifurcation. This is independently confirmed in the Nord geomorphic assessment, which classifies the bifurcation reach (Site 1-3) as having sediment-supply-index > 3 (highest in the study) and 6–10 ft of vertical knickpoint instability (*Nord_PartB_2_Geomorphic_Assessment.md*, Table 1).

---

## 4. Why the Datasets Disagree — Per the Nord Study's Own Discussion

The Nord hydrology report (*Nord_Feasibility_Study_Part_A.md*, Sec. VII.D, "Discussion of Results") gives the most authoritative same-document reconciliation:

1. **2011 FIS adopted a different watershed.** "The effective discharge on Rock Creek above the bifurcation is from a gage analysis of an adjacent watershed (Little Chico Creek) where the current study method is rainfall-runoff with no available gage data." The FIS imports the Little Chico Creek peak discharges and assumes Rock Creek behaves the same. Whether that adoption is conservative or under-estimating depends on watershed-specific differences in runoff response that the FIS did not test against Rock Creek itself.
2. **No streamflow gauge data exists for Rock Creek or its tributaries.** Both the Current Study and StreamStats are uncalibrated regional methods. The Current Study reports rainfall-runoff HEC-HMS values; StreamStats reports regional-regression values. They are within each other's confidence intervals at most events.
3. **The 2013 CVHS values are lower again** because CVHS calibrated against the adjacent gauged Mud Creek and used a 22-hour basin lag (vs. ~5-hour as calculated for Rock Creek) — significantly attenuating the design hydrograph.

**The Nord study concludes:** "The current study discharges are within the error of the regression estimates from StreamStats." It does **not** conclude that the FIS is wrong or that the Current Study is the correct dataset — only that the Current Study and StreamStats are consistent with each other, while the FIS is lower because of method.

---

## 5. Which Dataset Should Govern Routing Analysis for This Concept?

**Recommendation:** Use a **two-track approach** rather than picking one dataset:

### Track A — Nord HEC-HMS "Current Study" for **upstream-of-bifurcation hydrology**

Use the Nord HEC-HMS Current Study as the **primary design hydrology** for the diversion intake and the upstream reaches of the two corridors. Reasons:

- It is the **most recent rainfall-runoff analysis** specifically built for Rock Creek (rather than adopted from Little Chico Creek).
- It is **internally consistent with the Nord HEC-RAS 2D model**, which is the most current and most relevant 2D model in the region.
- The Sand Creek Infiltration Study used the **same Nord HEC-HMS model** (modified for Sand Creek subbasins) — so adopting Nord's hydrology keeps the concept consistent with the recharge-feasibility source. *RockCreek_Reclamation_District-Infiltration_Feasibility_Study_Oct2023.md, Sec. 2.2.*
- StreamStats is within Nord's confidence bounds and is acceptable as a cross-check.

### Track B — DWR HEC-RAS 2D model for **downstream impact / Keefer Slough flooding / FEMA no-rise**

Use the DWR 2D model (the same Wood Rodgers 2D model referenced by Caltrans) as the **authoritative downstream impact dataset**. Reasons:

- It is the model FEMA is reviewing for the next FIRM update (anticipated 2027).
- It already incorporates the **updated bifurcation flow split** (39/61 RC/KS) reflecting current sediment / vegetation conditions, which is materially different from the 2011 FIS 44/56 split.
- Any FEMA CLOMR / LOMR submittal for the concept will be reviewed against this 2D model, so screening against the same model now reduces downstream redesign risk later.
- The Caltrans memo confirms a 3.52× disagreement with the 2011 FIS at Garner Lane (Keefer Slough); routing against the FIS would understate the downstream condition the concept must change.

### Why **not** the 2011 FIS Effective Flows as the design basis

- They are 35% lower than the Current Study at most events and were derived from an adjacent-watershed proxy.
- They will be **superseded by the DWR/FEMA update** (review anticipated 2027).
- Using them as the design basis risks under-designing the diversion and over-claiming attenuation benefit (since the "baseline" peak would be artificially low).

The 2011 FIS values **remain relevant** as the *currently effective FEMA-published flows* for any regulatory floodplain / no-rise comparison made today (since the DWR update is not yet adopted). They should appear in the screening table for regulatory-context reference but not be used as the design peak.

### Why **not** USGS StreamStats as the design basis

- It is uncalibrated regional regression. The Nord Current Study supplies a rainfall-runoff model built specifically for Rock Creek with topography, soils, and land cover.
- The 1%-Plus StreamStats value of 17,100 cfs (vs. 9,785 cfs Current Study) is a regression-tail artifact and would mislead any design that uses StreamStats uncritically.
- StreamStats is appropriate as a **cross-check** of the Current Study, which is how Nord itself uses it.

---

## 6. Recommended Comparison Table for the Routing Screen

For Deliverable 5 (Screening Spreadsheet Structure), the routing screen should display **all four datasets in parallel** rather than collapsing to one, with the governing dataset highlighted by track. Use this structure:

| Location | AEP | 2011 FIS Effective (cfs) | Nord HEC-HMS Current Study (cfs) | USGS StreamStats (cfs) | DWR HEC-RAS 2D (cfs) | Governing for this concept |
| --- | --- | --- | --- | --- | --- | --- |
| Rock Creek ~0.91 mi upstream of bifurcation | 10% | 2,300 | 5,185 | 3,580 | `[VERIFY: extract from DWR 2D at concept intake]` | **Nord Current Study** (Track A) |
| Rock Creek ~0.91 mi upstream of bifurcation | 1% | 5,600 | 8,020 | 7,170 | `[VERIFY: extract from DWR 2D at concept intake]` | **Nord Current Study** (Track A) |
| Rock Creek + Keefer Slough at bifurcation (combined) | 1% | `[derive from FIS]` | `[derive from Nord HMS routing]` | — | 6,413 | **DWR 2D** (Track B) |
| Rock Creek share at bifurcation (post-split) | 1% | 56% × upstream | per Nord routing | — | 2,483 (39%) | **DWR 2D** (Track B) |
| Keefer Slough share at bifurcation (post-split) | 1% | 44% × upstream | per Nord routing | — | 3,867 (61%) | **DWR 2D** (Track B) |
| Keefer Slough at Garner Lane | 1% | 680 | — | — | 2,390.90 | **DWR 2D** (Track B) |
| Keefer Slough at SR 99 (channel cap. 525 cfs) | 1% | 525 (capped, with 155 cfs overflow per FIS) | — | — | `[VERIFY: extract from DWR 2D]` | **DWR 2D** (Track B) |

`[VERIFY]` cells will be filled when the DWR 2D model output is obtained (most likely via DWR Northern Region Office or via Wood Rodgers if the Nord HEC-RAS 2D model files are released with the Nord study).

---

## 7. Implications for the Concept's Headline Claims

The concept draft has two headline benefit claims that depend directly on which dataset is adopted. The dataset choice should be acknowledged in any stakeholder communication.

### 7.1 "Reduce Rock Creek peak flow downstream of the diversion"

Magnitude of the claim is dataset-sensitive:
- Against **2011 FIS Q100 (5,600 cfs on Rock Creek above the bifurcation)**: a diversion of, say, 3,000 cfs would be a 54% peak reduction.
- Against **Nord Current Study Q100 (8,020 cfs)**: the same 3,000 cfs is a 37% peak reduction.
- Against **DWR 2D Q100 share to Rock Creek post-bifurcation (2,483 cfs)**: the same diversion would exceed the bifurcation-only flow — which is the point of removing flow *before* the bifurcation, but it also makes clear that diversion-capacity sizing has to be done against the *upstream-of-bifurcation* hydrology (Track A), not the post-split hydrology.

### 7.2 "Reduce flow reaching Keefer Slough"

Magnitude is even more dataset-sensitive:
- Against **2011 FIS Q100 at Garner Lane (680 cfs)** the entire Keefer flooding problem looks small.
- Against **DWR 2D Q100 at Garner Lane (2,391 cfs)** Keefer Slough is the dominant flood-risk corridor, and reducing the source flow at the upstream Rock Creek intake is a very high-leverage intervention.

The DWR 2D framing is the one Caltrans is acting on (and the one FEMA will move to). The concept's downstream benefit story should be framed against the DWR 2D values, not the FIS.

---

## 8. Open Questions for Subsequent Phases

These are questions the concept-stage analysis cannot resolve from the documents in this repository:

1. **Can the Wood Rodgers / DWR HEC-RAS 2D model files be obtained?** Either via DWR Northern Region Office or under the Nord contract. Without the 2D model, downstream-impact verification has to rely on cross-section spot values from the Caltrans memo and the Nord HEC-RAS 2D figures rather than a full re-routing.
2. **How will the FIRM update be scoped?** If DWR's 2D model and updated FIRM map are adopted by FEMA in 2027 as the Caltrans memo anticipates, the concept's regulatory pathway (CLOMR / LOMR) will be against the new map, not the current FIS. Pre-2027 design work should anticipate AE-zone designation in the corridor.
3. **Is there a planned re-rating of the bifurcation split as part of the FIRM update?** The current 39/61 split is itself the product of sediment/vegetation accumulation that someone may choose to address through bifurcation maintenance (the Caltrans memo's "Regular Maintenance Activity at the Bifurcation Area"). If that happens, the split shifts back toward 56/44 and the design hydrology for *this concept's diversion* changes again.
4. **Should the concept design against the existing split, the historical (FIS) split, or a future-maintained split?** Conservatively, design against the existing (DWR 2D) split for downstream Keefer Slough benefit claims, and design against the future-maintained (FIS-like 56/44) split for an upper-bound on the volume the concept would intercept upstream.
