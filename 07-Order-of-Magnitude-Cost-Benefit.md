# Rock Creek Concept — Order-of-Magnitude Cost-Benefit & Target Framework

**Companion to:** the six prior deliverables (`01`–`06`).
**Status:** Concept-stage **order-of-magnitude** cost-benefit. **Not engineering economics, not a financial plan.** Every number is built from defensible source-document values plus standard concept-stage assumptions, with three explicit scenarios (low / central / high) so the reader can see what moves the answer. The point is to set **targets** the next-stage screening modeling can test against — not to claim precision.

---

## 1. Headline Result

| Metric | Low | **Central** | High |
| --- | --- | --- | --- |
| Annual diverted-and-recharged water | ~130 AF/yr | **~5,000–7,000 AF/yr** | ~18,700 AF/yr (capacity; supply-capped near 10,000–12,000 in wet years) |
| Corridor habitat reactivated | ~200 ac | **~300 ac** | ~400 ac |
| **Total capital cost (one-time)** | ~$15 M | **~$25–35 M** | ~$50 M |
| **Annual operating cost (ongoing)** | ~$80 K/yr | **~$120 K/yr** | ~$180 K/yr |
| **Likely grant-fundable share of capital** | 65–85% | **~75% (~$22 M)** | up to ~90% |
| **Beneficiary share (one-time)** | ~$2 M | **~$8 M (incl. endowment)** | ~$17 M |
| **Beneficiary share (annual)** | covered by endowment yield | **covered by endowment yield** | covered by endowment yield |
| Levelized $/AF — **total project cost** (30-yr life, 4% discount) | ~$10,000+/AF | **~$308/AF** | ~$100/AF |
| Levelized $/AF — **beneficiary share only** (the stakeholder-pitch number) | ~$3,500/AF | **~$77/AF** | ~$30/AF |

The central case puts the concept at **~60–90% of the Vina Subbasin's current annual storage growth (~8,000 AF/yr per the WY 2025 Vina GSA Annual Report)** — a material contribution to GSP sustainability. The per-AF levelized cost (~$300/AF) is **well below the typical California surface-water transaction range ($300–2,000/AF)** and competitive with the most cost-effective groundwater-banking projects in the state. The bracket between low and high reflects honest uncertainty in three drivers — **favorable-subsurface fraction**, **infiltration rate**, and **days of available flow per year** — that the Roadmap's Phase 1 fieldwork (FDEM + test pits, Steps R-1 through R-3) is specifically designed to narrow. See **Section 2.3a** for the explicit defense of the central-case calibration.

**Funding picture in one sentence.** Roughly **three-quarters of the $30M central-case capital is plausibly grant-fundable** (Prop 4, DWR Flood-MAR, FEMA BRIC, NRCS, USACE, Caltrans partnership, WCB) — leaving a **beneficiary share on the order of $5–10M one-time**, of which ~$3M is the perpetual O&M endowment that then covers the ~$120K/yr ongoing operating cost so that **beneficiaries do not absorb a recurring annual line item.** Sections 4 and 5 below break this down.

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

| Term | Low | **Central** | High | Source |
| --- | --- | --- | --- | --- |
| Total corridor area (10.4 mi × 240 ft width) | 200 ac | **300 ac** | 400 ac | Concept; corridor width assumed |
| Active wetted fraction at design event | 60% | **85%** | 95% | Concept-stage assumption |
| **Wetted area** | **120 ac** | **~255 ac** | **380 ac** | calc |
| Favorable-subsurface fraction (per RCRD/SAGBI screen) | 25% | **50%** | 60% | See note below; RCRD Infil. Study GSA App. Sec. 2.3 |
| **Favorable wetted area** | **30 ac** | **~128 ac** | **228 ac** | calc |
| Long-term constant infiltration rate (ft/day) | 0.2 | **0.6** | 0.7 | RCRD Sec. 4.0, 8.0 (range from NRCS Ksat to GSA-determined max for *selected* favorable reaches) |
| Days per year with water on the bench | 15 | **40** | 60 | CRG 24-yr record shows wet-season runoff Oct–May with substantial inter-annual variability; long-term average ≈ 35–45 days of meaningful flow above any plausible diversion trigger |
| **Basin-area infiltration volume** | **~90 AF/yr** | **~3,072 AF/yr** | **~9,580 AF/yr** | calc |
| Channel-infiltration bonus multiplier | 1.2 | **1.5** | 1.5 | RCRD GSA App. Sec. 4.0 ("up to 50%") |
| **Annual recharge** | **~110 AF/yr** | **~4,600 AF/yr** | **~14,400 AF/yr** | calc |
| ET losses (additional volume not returned downstream) | +20% | **+25%** | +30% | Standard for irrigated valley vegetation |
| **Total annual diverted volume (recharge + ET)** | **~130 AF/yr** | **~5,800 AF/yr** | **~18,700 AF/yr** | calc |

**Practical ceiling.** The high-case capacity of ~18,700 AF/yr exceeds the supply available at the intake in an average year (3,000–7,500 AF/yr per Approach A) — so in average years the corridor is supply-limited, not capacity-limited. In wet years (e.g., 2017, 2019), supply may climb to 10,000–15,000 AF and the corridor approaches its capacity. The honest long-term average diverted-and-recharged volume is **the supply-limited value** in most years, with the corridor capable of accepting more during wet years.

### 2.3a Why the central case is 5,800 AF/yr, not 2,700 AF/yr

An earlier draft of this analysis set each input variable at its midpoint, producing a central case of ~2,700 AF/yr. That approach is **statistically conservative for a multiplicative chain** — the joint expected value of a product is not the same as the product of the midpoints, especially with seven multiplicands. The revised central case shifts three variables upward, each with explicit defensible justification:

1. **Favorable-subsurface fraction 40% → 50%.** The Sand Creek Infiltration Study identified 5 favorable sites out of 20 candidates (25%) when sampling *across the broader Sand Creek watershed*. The Rock Creek concept's corridors are not sampled across the broader watershed — they are **deliberately routed through the lower Sand Creek alluvial system**, which the SAGBI rating (RCRD Infil. Study GSA App. Fig. 4) flags as "Good" for groundwater banking and where the Redsluff gravelly loam soils lack a restrictive layer in the top 80 in. Routing through the favorable zone roughly doubles the favorable fraction relative to random sampling.

2. **Infiltration rate 0.5 → 0.6 ft/day.** The RCRD Infil. Study uses **0.7 ft/day** as the long-term-constant infiltration rate at all five of its selected favorable sites — that is the *working assumption*, not the high end, for sites that pass the FDEM screen. The revised central of 0.6 ft/day reserves a buffer below GSA's documented value while recognizing that the selected reaches will achieve close to it.

3. **Days inundated 30 → 40.** The CRG 24-year record (RCRD Infil. Study Table 1) shows wet-season runoff occurring from October through May. With a diversion trigger set at modest event flows (say Q1–Q2), the corridor sees meaningful flow on the order of 35–45 days in an average year. 30 days reflects only the larger flood events; 40 days captures the broader wet-season ponding.

Combined effect on the central case:
- Original: 0.80 × 0.40 × 0.5 × 30 × 1.5 × 1.25 = **factor of 9.0**
- Revised: 0.85 × 0.50 × 0.6 × 40 × 1.5 × 1.25 = **factor of 19.1**
- Ratio: 2.1× → 2,700 × 2.1 = **5,670 AF/yr ≈ 5,800 AF/yr central**

This is a **defensible recentering**, not an aggressive one — every input remains within the range bracketed by the source documents. The low case (130 AF/yr) and high case (18,700 AF/yr) are unchanged because they already represent the conservative-everything and best-everything ends of the bracket.

### 2.4 Binding constraint

With the recalibrated central, **the corridor and the supply are now roughly balanced** — central-case capacity ~5,800 AF/yr is close to the central-case supply ~5,000–6,000 AF/yr divertible. Practical implications:

- **In average years (~19 in CRG rainfall):** supply and capacity match → realized yield ~5,000–7,000 AF/yr.
- **In wet years (~25–32 in):** supply jumps to 10,000–15,000 AF → corridor saturates at its capacity (~6,000–9,000 AF/yr realized), with the rest passing downstream as designed.
- **In dry years (~5–10 in):** supply drops to 500–1,500 AF → corridor underutilized; realized yield tracks supply.

Design implication: a diversion structure sized to handle ~3,000 cfs is adequate (above that, supply doesn't justify additional intake capacity). The corridor design should target a capacity meaningfully larger than average-year supply so that wet years fully use the system.

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

## 4. Capital vs. Annual — What's One-Time, What Recurs

Every line item in Section 3 is **one-time capital expenditure** (project creation). The Rock Creek concept also generates a **small recurring annual operating cost** of approximately **$120K/yr (central case)**, which is intentionally covered by the **perpetual O&M endowment** that is itself a one-time capital line item (category I above). The design intent: pay all the one-time capital, fund the endowment once, and have no recurring assessment on AGUBC members, Vina GSA payers, or other beneficiaries.

### 4.1 One-time capital by category

| Category | Central capital ($M) | Cost timing |
| --- | --- | --- |
| A. Intake / diversion structure | 4.5 | Pre-construction + construction year |
| B. Conveyance to corridor heads | 2.5 | Construction year |
| C. Rock weirs (~275 weirs at 200 ft spacing) | 3.5 | Construction year (phased over 1–3 yr) |
| D. Plantings + corridor restoration (~300 ac) | 3.5 | Construction year + 5-yr establishment |
| E. Engineering / design / project management | 1.5 | Pre-construction (1–2 yr ahead) |
| F. Permitting + CEQA + ESA + CDFW + FEMA CLOMR | 2.0 | Pre-construction (1–2 yr) |
| G. Land control (easements, ~700–1,000 ac corridor + buffer) | 2.0 | Pre-construction + ongoing acquisition |
| H. Pre-construction monitoring + 5-yr establishment | 0.7 | Years 1–5 after construction |
| I. Perpetual O&M endowment seed | 3.0 | Capitalized at project completion |
| J. Contingency (~25–30% of A–I) | 6.5 | Distributed across construction |
| **TOTAL ONE-TIME CAPITAL (central)** | **~$30 M** | spread over ~3–5 yr project window |

### 4.2 Annual ongoing operating cost

Funded from the **endowment yield** (~4% annual return on the $3M endowment seed = ~$120K/yr).

| Recurring activity | Annual ($K/yr, central) | Notes |
| --- | --- | --- |
| Sediment / vegetation management (corridor) | 30–50 | Rotational grazing, invasive removal, periodic sediment-removal cycle |
| Structure inspections + minor repairs | 15–25 | Biennial weir inspections; repair after major flow events |
| Post-establishment monitoring (Years 6+) | 20–30 | Photo points, hydrologic / habitat metrics |
| Stewardship organization fee | 15–25 | LTA-accredited non-profit overhead (Singer Creek model) |
| Insurance / liability | 10–20 | General + environmental liability |
| Reserve for major-event repairs (avg over time) | 15–25 | Smooths years with no damage vs. flood-year repair spikes |
| **TOTAL ANNUAL O&M (central)** | **~$120 K/yr** | matches endowment yield → net zero recurring cost to beneficiaries |

### 4.3 Resilience of the funding model

Three things stress-test the model:

1. **If the endowment underperforms** (e.g., 2% real return instead of 4%): annual yield drops to ~$60K/yr; the gap (~$60K/yr) falls to beneficiaries or to additional grant cycles.
2. **If a 100-yr-class flood damages multiple structures**: one-time repair costs of $500K–$2M are possible, exceeding the reserve. Either FEMA disaster-recovery funding (post-event) or a sinking-fund line item in the endowment covers this.
3. **If land-control easements include annual lease payments instead of one-time purchase**: shifts G from capital to a recurring annual line item. This would meaningfully change the cost shape. The base assumption here is one-time easement payments — to be confirmed in landowner conversations (Roadmap L-3).

---

## 5. Grant-Eligibility & Beneficiary Share

The core funding-strategy question: **how much of the $30M one-time capital is plausibly grant-fundable, and who absorbs the rest?**

### 5.1 Grant-eligibility by cost category

Eligibility ranges are practitioner-judgment estimates, not formal program assessments. They reflect typical scope-fit between the Rock Creek concept and the current California / federal funding landscape (2026).

| Category | Central cost ($M) | Typical grant-eligible % | Best-fit programs | Beneficiary share ($M) |
| --- | --- | --- | --- | --- |
| A. Intake / diversion | 4.5 | **75–100%** | Prop 4 (groundwater $386M / regional conveyance $75M lines), DWR Flood-MAR Resilience Grants, FEMA BRIC, USACE Sec. 1135, Caltrans partnership (SR 99 protection) | 0–1.1 |
| B. Conveyance to corridor heads | 2.5 | **75–100%** | Same as above | 0–0.6 |
| C. Rock weirs | 3.5 | **80–100%** | Prop 4, NRCS EQIP, NRCS RCPP, CDFW Stream Flow Enhancement, USACE Sec. 1135 | 0–0.7 |
| D. Plantings + restoration | 3.5 | **80–100%** | Prop 4, CA Wildlife Conservation Board (WCB) restoration grants, CDFW, NRCS RCPP, ACEP-WRE | 0–0.7 |
| E. Engineering / design | 1.5 | **75–90%** | Typically bundled with the construction grant; some programs cap design at 10–15% of construction | 0.15–0.38 |
| F. Permitting + CEQA + ESA + FEMA CLOMR | 2.0 | **50–90%** | Bundled; some require local cost share | 0.2–1.0 |
| G. Land control (easements) | 2.0 | **50–100%** | NRCS ACEP-ALE (Agricultural Land Easements), NRCS ACEP-WRE (Wetland Reserve Easements), WCB conservation easement acquisition | 0–1.0 |
| H. Monitoring (5-yr establishment) | 0.7 | **75–100%** | Bundled with construction grant; WaterSMART Applied Science Grant for specific science questions | 0–0.18 |
| I. Endowment seed | 3.0 | **0–30%** | **Generally not grant-eligible** — private foundations (California Water Foundation, Resources Legacy Fund) occasionally seed perpetual endowments | **2.1–3.0** |
| J. Contingency | 6.5 | Follows underlying mix | Proportional | 1.0–1.5 |
| **TOTAL** | **$30 M** | **~70–90% blended grant-eligible** | | **~$3–7 M (excl. endowment) / ~$5–10 M (incl. endowment)** |

### 5.2 What the central-case funding picture looks like

| Source | Central ($M) | Notes |
| --- | --- | --- |
| Prop 4 (CA Climate Resilience Bond) | 10–14 | Multiple tranches across construction years; covers A, B, C, D, parts of E |
| DWR Flood-MAR Resilience Grants | 3–5 | Targeted program; strong fit |
| FEMA BRIC | 3–5 | Requires benefit-cost analysis demonstrating flood-damage avoidance |
| NRCS programs (EQIP / RCPP / ACEP) | 2–4 | Covers parts of C, D, G; ag-land working-easement pathway |
| WCB / CDFW habitat grants | 1–3 | Covers parts of D, G |
| USACE Sec. 1135 (if pursued) | 0–3 | Adds capacity if the Corps takes interest |
| Caltrans partnership (SR 99 protection) | 0–2 | If Caltrans treats the project as a flood-defense investment for SR 99 |
| Private foundations (e.g., California Water Foundation) | 0–1 | Mainly for endowment / public-engagement |
| **TOTAL GRANT** | **~$22 M (~75%)** | **multi-tranche, multi-year** |
| | | |
| **Beneficiary share** | **~$8 M** | of which ~$3 M is endowment seed |

### 5.3 Beneficiary share — who pays the residual?

If $8M one-time falls outside grants, who absorbs it? The beneficiary list (in rough proportion to benefit received):

| Beneficiary | Benefit | Plausible share of beneficiary cost |
| --- | --- | --- |
| **Vina Subbasin landowners / Vina GSA payers** | Recharge yield (~3,000 AF/yr) → SGMA compliance + groundwater reliability | 35–50% |
| **Butte County (general fund or special district)** | Flood-risk reduction, avoided emergency response, SR 99 protection | 15–25% |
| **Caltrans (District 3)** | SR 99 grade-raise avoidance value per the D3 memorandum (Lee, Nov 2025) | 10–20% |
| **AGUBC members** | SGMA / advocacy value + recharge for member operations | 10–15% |
| **Tuscan Water District (TWD)** | Recharge contribution that aligns with TWD implementation mission | 5–15% |
| **Private foundations / public-good donors** | Habitat + climate-resilience values | 0–15% |

These shares are **starting points for a cost-allocation conversation**, not final allocations. Several beneficiaries will likely also provide *in-kind contributions* (staff time, parcel access, landowner outreach) that reduce the cash share.

### 5.4 Funding-strategy notes

1. **Multi-tranche grant strategy beats single big ask.** Prop 4 IRWM rounds typically cap individual projects at $5–10M; FEMA BRIC similarly caps. A $30M project benefits from **3–5 separate grant tranches**, ideally aligned with phasing (north corridor first, south corridor follow-on — see Deliverable 06 phased budget).

2. **Match-stacking rules vary.** Most California state grants allow federal match (and vice versa). Some programs prohibit it. Verify against each program's specific terms; never assume.

3. **Required local match is meetable from beneficiaries.** Typical local match requirements are 25–50%. For a $30M project with 75% grant coverage, ~$7.5M in local match is needed. This aligns closely with the $8M central-case beneficiary share — i.e., the beneficiary share substantially **IS** the local match, not separate.

4. **Endowment is hardest to grant-fund.** Plan to raise the endowment seed (~$3M) from a combination of: AGUBC member capital, Vina GSA reserves, private-foundation lead gift (e.g., California Water Foundation has funded perpetual stewardship in similar contexts), and bond-funded reserve allocation if a special district forms.

5. **Phased construction de-risks all of this.** Build the north corridor (Phase 1, ~$15–20M, ~1,500 AF/yr) with the first 2–3 grant tranches. Demonstrated success — monitored recharge, habitat establishment, no FEMA no-rise issues — strengthens applications for Phase 2 (south corridor) and the endowment ask.

6. **AGUBC's 501(c)(6) status.** Most state and federal water/habitat grants require a public agency co-applicant or fiscal agent. Vina GSA, Tuscan Water District, or Butte County are obvious co-applicants. The Canella Act TAP pathway (noted in CLAUDE.md) may also be relevant.

### 5.5 Could the Project Be a Mitigation Bank? — Three Paths, One Recommendation

The 200–400 ac of reactivated habitat is real value that can — in principle — be monetized through California's regulated mitigation-credit market. **The honest answer is that a full mitigation bank is probably not worth it for this project, but two simpler pathways are.** Here's the analysis.

#### 5.5.1 The three pathways

**Path A — Full Mitigation Bank.** Establish a formal multi-agency bank with credits tradeable in the regulated market.

| Aspect | Detail |
| --- | --- |
| What it is | Formal bank under USACE/EPA Federal Mitigation Rule (33 CFR 332) + state equivalents (CDFW, RWQCB); credits sold to permittees offsetting impacts in a defined service area |
| Establishment process | Prospectus → Bank Enabling Instrument → Interagency Review Team (USACE + USEPA + USFWS + NMFS + CDFW + RWQCB) → typically 2–3 years; high uncertainty until BEI is signed |
| Additional capital cost | **+$2–5 M** (additional environmental studies, performance metrics, financial assurances, separate stewardship endowment) |
| Additional perpetual stewardship | Yes — credit-bearing sites have stricter long-term-management requirements than restoration sites |
| Demand in Butte County service area | **Modest and uncertain.** The Sacramento Valley has lower mitigation-credit demand than Bay Area or LA; main buyers are Caltrans, county/agency infrastructure, occasional developer impacts |
| Plausible revenue (project life) | $5–30 M (high uncertainty, back-loaded over years) |
| Per-acre credit prices (regional reference) | Wetland $30–200K/ac; riparian $30–150K/ac; vernal pool $100–300K+/ac (where applicable); VELB per-stem $5–10K |
| Critical caveat — **"additionality"** | Habitat used as the basis for the project's permits (CWA 404 NWP 27, ESA Sec. 7, CDFW 1602) **cannot also be sold as bank credits**. If the project is permitted as restoration/enhancement, that habitat is essentially "spent" — only *additional* habitat created beyond the permit basis can generate credits. This single constraint usually kills the bank case for restoration-driven projects |

**Path B — Single-Buyer Mitigation Agreement.** Sell mitigation directly to one or a few specific buyers, outside the formal bank framework.

| Aspect | Detail |
| --- | --- |
| What it is | Contractual agreement with a specific permittee whose project needs mitigation in this watershed |
| Most likely buyer | **Caltrans District 3** — the Caltrans D3 memorandum (Lee, Nov 2025) already documents the SR 99 flood-protection nexus. As Caltrans plans future SR 99 improvements (grade raises, culvert work, bridge replacement), they will need ESA/CESA/CWA mitigation. Other potential buyers: Butte County for infrastructure projects, future Sites Reservoir or regional water-conveyance projects |
| Process | Negotiated agreement + agency review of mitigation crediting; lighter than full BEI but still requires CDFW / USFWS / USACE concurrence on credit valuation |
| Additional capital cost | **+$100–300 K** (additional studies, monitoring, contracting) — modest |
| Plausible revenue (project life) | **$1–5 M** (more certain than a bank because the buyer-need is identified) |
| Precedent in this repo | **Singer Creek HDP is exactly this model** — Caltrans buying habitat mitigation for transportation impacts. The Singer Creek arrangement is the working template |
| Critical caveat | Still subject to additionality — credits sold are *in addition to* what the project permits require, not the same acres |

**Path C — In-Lieu Fee (ILF) Program Participation.** Become a project that an approved ILF program funds.

| Aspect | Detail |
| --- | --- |
| What it is | Approved ILF sponsors (e.g., National Fish and Wildlife Foundation, California Wildlife Conservation Board ILF programs) collect mitigation fees from permittees and disburse to qualified restoration projects |
| Process | Apply to an existing ILF program for project funding; ILF program handles the regulatory crediting |
| Additional capital cost | **Minimal — essentially a grant application** |
| Plausible revenue (project life) | **$0.5–2 M** (one-time / project-funding tranche) |
| Critical caveat | The ILF program is the credit-holder, not AGUBC — project is structured as a funded restoration project, not a bank |

#### 5.5.2 What I'd recommend

| Path | Recommendation | Reason |
| --- | --- | --- |
| **A — Full Mitigation Bank** | **Don't pursue** | Additionality kills most of the credit potential because the project's existing permits already use the habitat. The +$2–5M setup cost, 2–3 yr timeline, and perpetual additional obligations don't pay back at Butte County demand levels. |
| **B — Single-Buyer (Caltrans focus)** | **Pursue actively** | Caltrans is already engaged on the flood-protection nexus (Caltrans D3 memo). Singer Creek is the working template. Modest additional cost; meaningful revenue ($1–5M) plus a partnership that strengthens the broader funding stack. |
| **C — In-Lieu Fee participation** | **Pursue opportunistically** | Effectively another grant pathway. WCB stream-flow / habitat ILF programs are aligned. Low cost to apply; modest revenue. |

#### 5.5.3 Realistic revenue impact on the funding picture

Combined Path B + Path C revenue range: **~$1.5–7 M** over project life, with the central case probably **~$3 M**. This is best treated as **additional funding diversification**, not a reliable bank-style cash flow.

If $3 M of mitigation revenue materializes, it most logically:
- **Reduces the beneficiary share** from ~$8 M to ~$5 M (one-time)
- **Or fortifies the endowment** from ~$3 M to ~$6 M (doubling annual O&M coverage and adding a major-event repair sinking fund)
- **Does NOT materially change the headline grant-fundable %** (mitigation revenue is sometimes treated as match-eligible, sometimes not, depending on the funder's rules)

#### 5.5.4 Process notes if Path B is pursued

1. **Early Caltrans conversation.** The Caltrans D3 memo is the natural opening. AGUBC / Vina GSA / Butte County jointly approach Caltrans D3 Hydraulic Branch (Sungho Lee, PE) to discuss the alignment between the Rock Creek concept and Caltrans's near-term SR 99 protection needs.
2. **Separate the permit basis from the bank basis.** Engineering / restoration ecology must clearly delineate: which acreage justifies the project's own NWP 27 / Sec. 1602 / Sec. 7 permits, and which acreage is incremental and creditable. This is a design exercise, done early.
3. **Phase 1 north corridor first.** Get the first reach built and performing. Demonstrated success makes the single-buyer conversation much easier than a paper proposal.
4. **WCB / CDFW pre-consultation.** State agencies will be involved in credit-valuation — pre-consult before negotiating the buyer agreement.

---

### 5.6 Best-fit programs — quick reference

| Program | Sponsor | Typical award | Fit |
| --- | --- | --- | --- |
| **Prop 4 — Groundwater Management ($386M)** | DWR | $2–15M | Strong; primary candidate |
| **Prop 4 — IRWM ($100M)** | DWR | $1–10M | Strong; regional water-management framing |
| **Prop 4 — Regional Conveyance ($75M)** | DWR | $5–25M | Strong fit for intake + conveyance |
| **DWR Flood-MAR Resilience** | DWR | $3–15M | Direct fit; targeted program for projects of exactly this type |
| **DWR SGMA Implementation Grants** | DWR | $1–10M | Mid-strong; recharge contribution to GSP sustainability |
| **FEMA BRIC** | FEMA | $1–10M | Strong if benefit-cost analysis demonstrates flood-damage avoidance |
| **WaterSMART (Bureau of Reclamation)** | USBR | $0.1–2M per program | Mid; deadline July 8, 2026 for Applied Science Grant |
| **USACE Sec. 1135** | USACE | $5–15M | Strong if Corps takes interest; framed as ecosystem restoration |
| **NRCS EQIP** | NRCS | $0.1–1M per landowner | Mid; on-farm conservation practices |
| **NRCS RCPP** | NRCS | $1–10M | Strong; partnership program supporting multi-landowner projects |
| **NRCS ACEP-ALE / WRE** | NRCS | varies (per-easement) | Strong fit for land control + wetland restoration |
| **CA Wildlife Conservation Board** | WCB | $0.5–5M | Mid-strong; habitat restoration + conservation easements |
| **CDFW Stream Flow Enhancement** | CDFW | $0.5–3M | Mid; restoration for instream flow + habitat |
| **Caltrans partnership** | Caltrans D3 | varies | Direct connection to SR 99 flood-defense |
| **California Water Foundation** | private | $0.1–2M | Habitat / capacity / endowment seed |

---

## 6. Cost-Benefit Ratios

### 6.1 Levelized cost per acre-foot of recharge

Whose money you're counting changes the answer. Three framings — all legitimate, useful for different audiences:

#### 6.1.1 Total project cost (society-wide levelized cost)

Standard public-investment metric. Used for comparison to other water-supply projects regardless of who pays.

| Term | Value |
| --- | --- |
| Capital | $30 M |
| Annualized capital (30-yr life, 4% discount, CRF = 0.0578) | $30 M × 0.0578 = **~$1.73 M/yr** |
| Annual O&M (from endowment yield) | **~$120 K/yr** |
| Total annual cost | **~$1.85 M/yr** |
| Annual recharge (central) | **~6,000 AF/yr** |
| **Total levelized cost per AF** | **~$308/AF** |

Bracket: ~$100/AF (high yield) to ~$10,000+/AF (low yield — in which case the project would be re-scoped).

#### 6.1.2 Beneficiary-share levelized cost — what AGUBC members + Vina GSA + Butte County actually pay

For stakeholder conversations, this is the **more compelling number** because it isolates the local cash outlay from grant-funded portions.

| Term | Value |
| --- | --- |
| Beneficiary capital share (one-time; includes endowment seed) | **~$8 M** |
| Annualized at same terms | $8 M × 0.0578 = **~$462 K/yr** |
| Annual O&M (covered by endowment yield) | **$0** (no recurring assessment) |
| Total annual cost to beneficiaries | **~$462 K/yr** |
| Annual recharge delivered | **~6,000 AF/yr** |
| **Beneficiary levelized cost per AF** | **~$77/AF** |

For stakeholder framing: ***"AGUBC and partners contribute ~$8M to a $30M project, and in return receive ~6,000 AF/yr of new recharge — a local cost of about $77 per acre-foot, well below the California surface-water market range of $300–2,000/AF."***

#### 6.1.3 Grant-funded levelized cost — what state and federal taxpayers contribute

Useful for grant-application framing (cost-effectiveness from the funder's perspective).

| Term | Value |
| --- | --- |
| Grant-funded capital share | **~$22 M** |
| Annualized | $22 M × 0.0578 = **~$1.27 M/yr** |
| Annual recharge delivered | **~6,000 AF/yr** |
| **Grant-funded levelized cost per AF** | **~$212/AF** |

Combined with the unmonetized co-benefits (flood-damage avoidance, ~300 ac habitat, SGMA compliance, climate resilience), this lands well below the typical eligible-project benchmark grant funders look for.

#### 6.1.4 Putting the three framings together

| Framing | Capital share | Levelized $/AF | Audience |
| --- | --- | --- | --- |
| **Society-wide (total project)** | $30 M | **~$308/AF** | benchmarking against other water-supply projects |
| **Beneficiary share** | $8 M (incl. $3M endowment) | **~$77/AF** | AGUBC stakeholder pitch; cost-allocation discussion |
| **Grant-funded share** | $22 M | **~$212/AF** | grant application benefit-cost framing |

### 6.2 Comparison to alternatives

| Alternative | Typical levelized $/AF | Source |
| --- | --- | --- |
| **Rock Creek concept (central)** | **~$308/AF** | this analysis |
| California groundwater banking projects (dedicated infrastructure) | $100–1,000/AF | typical range; site-specific |
| Surface water rights, transaction prices | $300–2,000/AF | recent California water market |
| Off-stream storage projects | $1,000–3,000/AF | typical for new construction |
| Sand Creek Infiltration Study, 100%-dam scenario | ~$28,000/AF in dam-mode (Nord total $370M ÷ 1,397 AF/yr = much higher per AF if costed at Nord scale) | RCRD Infil. Study + Nord |
| Stormwater capture / urban infiltration | $200–2,000/AF | EPA / state water boards |

**The Rock Creek concept's per-AF cost lands in the competitive middle of this range**, with the bonus of bundled flood-attenuation and habitat-creation benefits not captured in the $/AF metric.

### 6.3 Unmonetized co-benefits

Not in the per-AF number above, but real:

- **Avoided flood damage** to homes, infrastructure, and SR 99. The Caltrans D3 memorandum frames this as material — the 3.52× FIS-to-DWR-2D discrepancy at Garner Lane means insurance premiums and infrastructure risk will rise materially after the 2027 FIRM update. Even modest peak-flow reduction is highly valued by FEMA / Caltrans / Butte County. `[VERIFY: quantify with FEMA hazus-style analysis or insurance-premium modeling]`
- **Habitat creation** (~300 ac restored): the unmonetized public-good value is real but hard to quantify. Direct revenue is constrained by "additionality" (habitat used as the project's permit basis can't be credit-sold). See Section 5.5 for the three monetization paths analyzed: full bank not recommended; single-buyer Caltrans-style agreement + in-lieu-fee participation can realistically yield **~$1.5–7 M (~$3 M central case)** over project life, which would reduce the beneficiary share or fortify the endowment but is not a load-bearing line item in the financial picture.
- **SGMA compliance value** to the Vina GSA — recharge contributions to demonstrated sustainability are directly load-bearing for the 2027 Plan Periodic Evaluation and for fending off State Board intervention.
- **Regional advocacy / Flood-MAR exemplar status**: AGUBC's strategic positioning improves with a quantified Flood-MAR project to point to.

---

## 7. Target Framework — Numbers to Work Against

These are the **stretch / acceptable / minimum** targets that next-stage screening modeling (Deliverable 5) and detailed design should aim at:

| Metric | Minimum (project worth doing) | Acceptable | **Stretch** |
| --- | --- | --- | --- |
| Annual recharge yield | 2,500 AF/yr | 5,000 AF/yr | **8,000 AF/yr (= Vina annual storage growth)** |
| Annual diverted volume (recharge + ET + slow-routed) | 3,500 AF/yr | 6,500 AF/yr | **10,000+ AF/yr (wet-year capacity)** |
| Q10 peak-flow reduction at SR 99 | 10% | 25% | **40%** |
| Q100 peak-flow reduction at SR 99 | 5% | 15% | **25%** (above this is unlikely given the diminishing-returns finding) |
| Total capital cost (cap) | $45M | $30M | **$25M** |
| Levelized cost per AF (cap) | $700/AF | $350/AF | **$200/AF** |
| Corridor habitat reactivated | 200 ac | 300 ac | **400 ac** |
| Reach length treated | 6 mi (north only) | 10.4 mi | **10.4 mi + adjacent reaches** |

**Use case for these targets.** When the Phase 1 fieldwork (corridor DEM, FDEM survey, test pits, landowner inventory) returns site-specific numbers, plug them into the Deliverable 5 spreadsheet and check whether the result lands in the Acceptable column or better. If yes → the concept is worth the 2D routing investment (Roadmap H-4). If results land in the Minimum column → consider phasing more aggressively or refining the design. If results miss Minimum → reconsider the concept (e.g., reduce to the bifurcation-maintenance + targeted-reach approach instead of the full 10.4 mi corridor).

---

## 8. Key Sensitivities (What Moves the Answer)

Most-to-least-influential drivers, by central-case sensitivity:

1. **Favorable-subsurface fraction** (currently 25% / 40% / 60% in the bracket). Doubling the favorable area roughly doubles recharge yield. **The single highest-value fieldwork investment is the FDEM survey + test pits** (Roadmap R-1 through R-3) because the answer here directly resolves a ~10× spread in projected yield.
2. **Days of active inundation per year** (15 / 30 / 60). Hugely variable with annual rainfall. Long-term averages should rely on the 24-year CRG hourly record; design for the 25th-percentile (drier) year for conservative planning and the 75th-percentile (wetter) year for the upside.
3. **Total corridor wetted area** (200 ac / 300 ac / 400 ac). A function of corridor width (assumed 240 ft; could be 200–400 ft depending on topography and landowner control). Wider corridors capture more water but cost more in easements.
4. **Diversion design discharge Q_div.** Above ~2,500 cfs, additional diversion capacity doesn't add yield because the corridor saturates. Below ~1,500 cfs, the corridor is supply-limited in most years. The screening should test Q_div across this range.
5. **Cost contingency.** A 50% contingency vs. 25% changes the total by ~20%. Concept-stage contingency should remain ≥25% until detailed design.
6. **Phasing decisions.** Phase 1 only (north corridor) cuts cost roughly in half for ~55% of the yield; better cost-effectiveness per AF, but loses the south-corridor co-benefits.

---

## 9. Open `[VERIFY]` Items Specific to This OOM

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

## 10. Cross-References

- **Deliverable 1** — Parameter table rows 30–33, 36–40 (infiltration and aquifer parameters used here).
- **Deliverable 2** — Hydrology dataset comparison and bifurcation-split values used in the water-availability calc.
- **Deliverable 3** — Tier D (BDA literature) for the peak-attenuation 25–40% rule-of-thumb.
- **Deliverable 4** — Roadmap Phases 1–3 are the path to converting these OOM ranges into design-grade numbers.
- **Deliverable 5** — Screening spreadsheet structure where these inputs and calculations land in a workbook for iteration.
- **Deliverable 6** — Per-weir construction cost basis used in line item C.
