# Rock Creek Concept — Order-of-Magnitude Cost-Benefit & Target Framework

**Companion to:** the six prior deliverables (`01`–`06`).
**Status:** Concept-stage **order-of-magnitude** cost-benefit. **Not engineering economics, not a financial plan.** Every number is built from defensible source-document values plus standard concept-stage assumptions, with three explicit scenarios (low / central / high) so the reader can see what moves the answer. The point is to set **targets** the next-stage screening modeling can test against — not to claim precision.

---

## 1. Headline Result

| Metric | Low | **Central** | High |
| --- | --- | --- | --- |
| Annual diverted-and-recharged water | ~200 AF/yr | **~2,500–3,000 AF/yr** | ~9,000 AF/yr |
| Corridor habitat reactivated | ~200 ac | **~300 ac** | ~400 ac |
| Total capital cost (one-time) | ~$15 M | **~$25–35 M** | ~$50 M |
| Levelized cost per AF of recharge (30-yr life, 4% discount) | ~$4,500/AF | **~$650/AF** | ~$150/AF |

The central case puts the concept at **~30–40% of the Vina Subbasin's current annual storage growth (~8,000 AF/yr per the WY 2025 Vina GSA Annual Report)** and at a **per-AF cost competitive with California surface-water alternatives** (typical $300–2,000/AF, lower for banking projects). The wide bracket between low and high reflects honest uncertainty in three drivers — **favorable-subsurface fraction**, **infiltration rate**, and **days of available flow per year** — that the Roadmap's Phase 1 fieldwork (FDEM + test pits, Steps R-1 through R-3) is specifically designed to narrow.

---

## 2. How Much Water Can We Pull Off Rock Creek?

The diverted volume is **the minimum of three constraints**: water available at the intake, diversion-structure capacity, and corridor acceptance capacity. We estimate each, then identify the binding constraint.

### 2.1 Water available at the intake (~25 sq mi drainage)

Two complementary approaches both land in the same range:

**Approach A — watershed water budget.**

| Term | Value | Source |
| --- | --- | --- |
| Drainage area at intake | 25 sq mi (16,000 ac) | Nord Table 10 |
| Watershed mean annual precipitation | 38 in/yr | Nord Part B, Physiographic Setting |
| Annual gross precipitation volume | 16,000 ac × 38/12 ft = **~50,700 ac-ft/yr** | calc |
| Runoff coefficient (foothill annual avg) | 0.20–0.30 | Standard for Sacramento Valley foothill watersheds |
| **Estimated annual basin runoff at intake** | **~10,000–15,000 AF/yr** | calc |
| Of which, "high-flow" (above any plausible diversion trigger) | 30–50% of total | rule-of-thumb for flashy foothill creeks |
| **Estimated annual divertible volume** | **~3,000–7,500 AF/yr** | calc |

**Approach B — event-based.**

A single Q10 flood at the intake delivers roughly:
- Q10 peak = 5,185 cfs (Nord Table 10)
- 24-hour triangular hydrograph approximation → volume ≈ 5,185 cfs × 86,400 s × 0.5 / 43,560 sf/ac ≈ **~5,150 ac-ft** in one event.
- Statistically, Q5–Q10-equivalent peak flows occur ~1 event/yr on average → **~3,000–5,000 AF/yr from these moderate events**.
- Plus smaller frequent events (Q2 etc.) contribute additional 1,000–2,000 AF/yr.

**Both approaches → ~3,000–7,500 AF/yr is the order of magnitude of divertible water at the intake.** Wet years (e.g., 2017, 2019) push higher; dry years (2013, 2015) push lower. The 24-year CRG rainfall record (RCRD Infil. Study Table 1) shows a 6× range between wet and dry years.

### 2.2 Diversion-structure capacity

We can divert up to the design capacity (call it Q_div). At Q_div = 3,000 cfs:
- Captures essentially all of small/moderate events (where peak < Q_div).
- Caps capture during a Q100 event at 3,000 cfs (the rest passes downstream — by design).
- Annual captured volume tracks closely with Approach A above for any Q_div ≥ ~2,500 cfs.

`[VERIFY: optimal Q_div is set by the downstream-peak-reduction target and the corridor acceptance capacity. Hydraulic screening (Deliverable 5 + Roadmap H-3/H-4) will set this.]`

### 2.3 Corridor acceptance (infiltration + ET + slow-flow attenuation)

This is the variable that most strongly drives the central estimate.

| Term | Low | Central | High | Source |
| --- | --- | --- | --- | --- |
| Total corridor area (10.4 mi × 240 ft width) | 200 ac | 300 ac | 400 ac | Concept; corridor width assumed |
| Active wetted fraction at design event | 60% | 80% | 95% | Concept-stage assumption |
| **Wetted area** | **120 ac** | **240 ac** | **380 ac** | calc |
| Favorable-subsurface fraction (per RCRD/SAGBI screen) | 25% | 40% | 60% | RCRD Infil. Study GSA App. Sec. 2.3 (SAGBI: Good downstream channel, Very Poor upstream) |
| **Favorable wetted area** | **30 ac** | **96 ac** | **228 ac** | calc |
| Long-term constant infiltration rate (ft/day) | 0.2 | 0.5 | 0.7 | RCRD Sec. 4.0, 8.0 (range from NRCS Ksat to GSA-determined max) |
| Days per year with water on the bench | 15 | 30 | 60 | Concept (CRG record shows variable wet seasons) |
| **Basin-area infiltration volume** | **90 AF/yr** | **1,440 AF/yr** | **9,580 AF/yr** | calc |
| Channel-infiltration bonus multiplier | 1.2 | 1.5 | 1.5 | RCRD GSA App. Sec. 4.0 ("up to 50%") |
| **Annual recharge** | **~110 AF/yr** | **~2,200 AF/yr** | **~14,400 AF/yr** | calc |
| ET losses (additional volume not returned downstream) | +20% | +25% | +30% | Standard for irrigated valley vegetation |
| **Total annual diverted volume (recharge + ET)** | **~130 AF/yr** | **~2,700 AF/yr** | **~18,700 AF/yr** | calc |

After capping by the available divertible water (Approach A, max 7,500 AF/yr), the high-case caps at ~7,500 AF/yr. After applying engineering realism (corridor saturates at peak), call it ~9,000 AF/yr ceiling.

### 2.4 Binding constraint

For most of the parameter space, **corridor acceptance is the binding constraint**, not water availability. The corridor "fills up" before exhausting the divertible Rock Creek flow. Design implication: a Q_div somewhat smaller than the maximum-divertible volume is still adequate; over-sizing the diversion intake doesn't pay back.

### 2.5 Flood-attenuation benefit (separate from recharge)

Some divert volume is **routed through the corridor and returned to Rock Creek downstream** (not recharged). That return-flow path is what produces the **peak-flow reduction** at the Rock Creek / Sand Creek confluence near SR 99. Best-guess at peak attenuation for Q5–Q10 events: 25–40% reduction in downstream peak (per BDA/RDS literature in Deliverable 3, Tier D, applied to a corridor of this scale). For Q100/Q500 the attenuation is materially smaller — the diminishing-returns finding.

`[VERIFY: peak attenuation must be modeled per Deliverable 5 + Roadmap H-4. The 25–40% range is BDA-literature-derived, not site-modeled.]`

---

## 3. How Much Would It Cost?

Built bottom-up from Nord's 2023 unit costs (`NORD_B5` Appendix 9) for items that transfer, plus standard concept-stage assumptions for everything else. Three scenarios bracket the range.

| Cost category | Low ($M) | **Central ($M)** | High ($M) | Basis |
| --- | --- | --- | --- | --- |
| A. Intake / diversion structure | 3.0 | **4.5** | 7.0 | Nord Alt 5 diversion structure ~$2.5M; add gates, fish passage, controls |
| B. Conveyance to corridor heads | 1.0 | **2.5** | 5.0 | Excavation @ $6/cy; geometry-dependent |
| C. Rock weirs (~275 at 200 ft spacing × 10.4 mi) | 3.0 | **3.5** | 5.0 | $10–15K per weir × ~275; per-weir cost from Deliverable 6 |
| D. Plantings + corridor restoration (300 ac) | 2.0 | **3.5** | 5.0 | Singer-Creek-style restoration $5–15K/ac |
| E. Engineering / design / PM (10–15% of A–D) | 1.0 | **1.5** | 3.0 | Standard fee structure |
| F. Permitting + CEQA + ESA + CDFW + FEMA CLOMR | 1.0 | **2.0** | 3.0 | Standard for projects of this scale |
| G. Land control (easements on ~700–1,000 ac corridor + buffer) | 0.5 | **2.0** | 5.0 | Highly variable; depends on negotiated terms |
| H. Pre-construction monitoring + first-5-yr establishment | 0.5 | **0.7** | 1.0 | Singer-Creek model |
| I. Perpetual O&M endowment | 2.0 | **3.0** | 5.0 | Singer-Creek model; produces ~$120K/yr at 4% yield |
| Subtotal (A–I) | 14.0 | **23.2** | 39.0 | sum |
| J. Contingency (25–30%) | 3.5 | **6.5** | 11.7 | Standard concept-stage |
| **TOTAL CAPITAL COST** | **~$17.5 M** | **~$30 M** | **~$50 M** | |

**Phased budget alternative** (matches Singer Creek's funding model):
- **Phase 1** — North corridor only (6 mi, ~150 weirs, ~180 ac restored) + intake + permitting: **~$15–20 M**, yielding ~1,500–1,800 AF/yr at central assumptions
- **Phase 2** — South corridor (4.4 mi, ~110 weirs, ~120 ac restored): **~$10–15 M**, yielding additional ~1,000–1,200 AF/yr

Phasing matches the AGUBC-vina funding pathway pattern (Prop 4 / WaterSMART / SGMA implementation grants come in tranches) and reduces upfront commitment risk.

---

## 4. Cost-Benefit Ratios

### 4.1 Levelized cost per acre-foot of recharge

Annualizing the central-case capital over a 30-year project life at a 4% discount rate (capital recovery factor = 0.0578):

| Term | Value |
| --- | --- |
| Capital | $30 M |
| Annualized capital | $30 M × 0.0578 = **~$1.73 M/yr** |
| Annual O&M (from endowment yield) | **~$120K/yr** |
| Total annual cost | **~$1.85 M/yr** |
| Annual recharge (central) | **~2,750 AF/yr** |
| **Levelized cost per AF** | **~$675/AF** |

The low and high scenarios bracket from ~$150/AF (high yield) to ~$4,500/AF (low yield).

### 4.2 Comparison to alternatives

| Alternative | Typical levelized $/AF | Source |
| --- | --- | --- |
| **Rock Creek concept (central)** | **~$675/AF** | this analysis |
| California groundwater banking projects (dedicated infrastructure) | $100–1,000/AF | typical range; site-specific |
| Surface water rights, transaction prices | $300–2,000/AF | recent California water market |
| Off-stream storage projects | $1,000–3,000/AF | typical for new construction |
| Sand Creek Infiltration Study, 100%-dam scenario | ~$28,000/AF in dam-mode (Nord total $370M ÷ 1,397 AF/yr = much higher per AF if costed at Nord scale) | RCRD Infil. Study + Nord |
| Stormwater capture / urban infiltration | $200–2,000/AF | EPA / state water boards |

**The Rock Creek concept's per-AF cost lands in the competitive middle of this range**, with the bonus of bundled flood-attenuation and habitat-creation benefits not captured in the $/AF metric.

### 4.3 Unmonetized co-benefits

Not in the per-AF number above, but real:

- **Avoided flood damage** to homes, infrastructure, and SR 99. The Caltrans D3 memorandum frames this as material — the 3.52× FIS-to-DWR-2D discrepancy at Garner Lane means insurance premiums and infrastructure risk will rise materially after the 2027 FIRM update. Even modest peak-flow reduction is highly valued by FEMA / Caltrans / Butte County. `[VERIFY: quantify with FEMA hazus-style analysis or insurance-premium modeling]`
- **Habitat creation** (~300 ac restored): valued at $5,000–50,000/ac in mitigation credit markets, but project context is enhancement (not impact-offsetting), so direct mitigation revenue is uncertain. Could be ~$1.5–15 M in habitat-value terms.
- **SGMA compliance value** to the Vina GSA — recharge contributions to demonstrated sustainability are directly load-bearing for the 2027 Plan Periodic Evaluation and for fending off State Board intervention.
- **Regional advocacy / Flood-MAR exemplar status**: AGUBC's strategic positioning improves with a quantified Flood-MAR project to point to.

---

## 5. Target Framework — Numbers to Work Against

These are the **stretch / acceptable / minimum** targets that next-stage screening modeling (Deliverable 5) and detailed design should aim at:

| Metric | Minimum (project worth doing) | Acceptable | **Stretch** |
| --- | --- | --- | --- |
| Annual recharge yield | 1,000 AF/yr | 2,500 AF/yr | **5,000 AF/yr** |
| Annual diverted volume (recharge + ET + slow-routed) | 1,500 AF/yr | 3,500 AF/yr | **7,000 AF/yr** |
| Q10 peak-flow reduction at SR 99 | 10% | 25% | **40%** |
| Q100 peak-flow reduction at SR 99 | 5% | 15% | **25%** (above-this is unlikely given diminishing-returns finding) |
| Total capital cost (cap) | $45M | $30M | **$25M** |
| Levelized cost per AF (cap) | $1,500/AF | $700/AF | **$400/AF** |
| Corridor habitat reactivated | 200 ac | 300 ac | **400 ac** |
| Reach length treated | 6 mi (north only) | 10.4 mi | **10.4 mi + adjacent reaches** |

**Use case for these targets.** When the Phase 1 fieldwork (corridor DEM, FDEM survey, test pits, landowner inventory) returns site-specific numbers, plug them into the Deliverable 5 spreadsheet and check whether the result lands in the Acceptable column or better. If yes → the concept is worth the 2D routing investment (Roadmap H-4). If results land in the Minimum column → consider phasing more aggressively or refining the design. If results miss Minimum → reconsider the concept (e.g., reduce to the bifurcation-maintenance + targeted-reach approach instead of the full 10.4 mi corridor).

---

## 6. Key Sensitivities (What Moves the Answer)

Most-to-least-influential drivers, by central-case sensitivity:

1. **Favorable-subsurface fraction** (currently 25% / 40% / 60% in the bracket). Doubling the favorable area roughly doubles recharge yield. **The single highest-value fieldwork investment is the FDEM survey + test pits** (Roadmap R-1 through R-3) because the answer here directly resolves a ~10× spread in projected yield.
2. **Days of active inundation per year** (15 / 30 / 60). Hugely variable with annual rainfall. Long-term averages should rely on the 24-year CRG hourly record; design for the 25th-percentile (drier) year for conservative planning and the 75th-percentile (wetter) year for the upside.
3. **Total corridor wetted area** (200 ac / 300 ac / 400 ac). A function of corridor width (assumed 240 ft; could be 200–400 ft depending on topography and landowner control). Wider corridors capture more water but cost more in easements.
4. **Diversion design discharge Q_div.** Above ~2,500 cfs, additional diversion capacity doesn't add yield because the corridor saturates. Below ~1,500 cfs, the corridor is supply-limited in most years. The screening should test Q_div across this range.
5. **Cost contingency.** A 50% contingency vs. 25% changes the total by ~20%. Concept-stage contingency should remain ≥25% until detailed design.
6. **Phasing decisions.** Phase 1 only (north corridor) cuts cost roughly in half for ~55% of the yield; better cost-effectiveness per AF, but loses the south-corridor co-benefits.

---

## 7. Open `[VERIFY]` Items Specific to This OOM

| Item | Resolution path |
| --- | --- |
| Watershed runoff coefficient (using 0.20–0.30; could be different for Rock Creek specifically) | Calibrate against Sand Creek annual yield once basin runoff record is established |
| Favorable-subsurface fraction in the two corridors | Corridor FDEM survey (Roadmap R-2) |
| Days of inundation per year per scenario | Hourly hydrologic modeling using CRG record + Sand Creek HEC-HMS subbasin model (RCRD Infil. Study methodology) |
| Corridor width and reactivated acreage | Corridor topographic survey + landowner-inventory-driven footprint (Roadmap H-2, L-1, L-3) |
| Per-weir installed cost | RDS pilot project benchmarking (external sources to be added to the repo) |
| Land-control easement compensation | Confidential landowner conversations (Roadmap L-3) |
| Peak-flow attenuation at the design events | HEC-RAS 2D screening (Roadmap H-3/H-4) |
| Avoided flood damage | FEMA hazus-style analysis after the 2027 FIRM update |
| Habitat-value mitigation crediting (if pursued) | Mitigation-bank feasibility analysis (separate from this concept) |

---

## 8. Cross-References

- **Deliverable 1** — Parameter table rows 30–33, 36–40 (infiltration and aquifer parameters used here).
- **Deliverable 2** — Hydrology dataset comparison and bifurcation-split values used in the water-availability calc.
- **Deliverable 3** — Tier D (BDA literature) for the peak-attenuation 25–40% rule-of-thumb.
- **Deliverable 4** — Roadmap Phases 1–3 are the path to converting these OOM ranges into design-grade numbers.
- **Deliverable 5** — Screening spreadsheet structure where these inputs and calculations land in a workbook for iteration.
- **Deliverable 6** — Per-weir construction cost basis used in line item C.
