# Rock Creek Concept — Feasibility and Next-Steps Roadmap

**Companion to:** `Rock-Creek-Floodplain-Reactivation-Concept-DRAFT.md`, `01-Refined-Concept-and-Parameter-Table.md`, `02-Discharge-Dataset-Comparison.md`, `03-Benchmarking-Matrix.md`
**Status:** Concept-stage roadmap. Identifies what would have to be true for the concept to work, what the source documents already answer, what remains open, the rough sequence of next steps, and likely responsible parties.

---

## How to Read This Roadmap

Six feasibility domains, each with the same structure:

1. **What would have to be true.** The substantive feasibility condition.
2. **What the source documents already answer.** Cited.
3. **What remains open.** Specific data or analysis gaps.
4. **Next step.** The concrete action that closes the gap.
5. **Sequence.** Where this sits in the order of work.
6. **Likely responsible party.** Best-positioned organization or role.

Where a step depends on another, that dependency is named.

---

## 1. Hydraulics / Flood Routing

### 1.1 What would have to be true

A defined diversion at the concept intake (~1.1 mi upstream of the bifurcation), routed through ~10.4 mi of corridors with hundreds of distributed 2–3 ft rock weirs, must produce:

- A measurable Rock Creek peak-flow reduction downstream of the diversion, especially at frequent-to-moderate events (Q10, Q25, Q50).
- A measurable reduction in flow volume reaching Keefer Slough.
- An honestly characterized — not assumed — attenuation result at Q100 and Q500, where the diminishing-returns finding from the BDA / Sand Creek-dam literature applies.
- No increase in flood elevation anywhere in the regulated floodplain (FEMA "no-rise" requirement; *Flooding_Issues_Along_Hwy99_Mud_Creek_to_Rock_Creek.md*, Sec. "FEMA CLOMR/LOMR").

### 1.2 What the source documents already answer

- **Watershed hydrology and design discharges** at ~0.91 mi upstream of bifurcation (very close to concept intake) are available across four datasets — see Deliverable 2 (*Nord_Feasibility_Study_Part_A.md*, Tables 10–12; *Flooding_Issues_Along_Hwy99...*, Sec. 1).
- **The HEC-RAS 2D model platform exists** (Wood Rodgers / DWR) and is the most appropriate routing tool. The Sand Creek Infiltration Study used a truncated subset for site-specific routing (*RockCreek_Reclamation_District-Infiltration_Feasibility_Study_Oct2023.md*, Sec. 6.1.2).
- **Bifurcation flow split is documented under two regimes:** 2011 FIS (44% to Keefer) and DWR 2D (61% to Keefer); the difference is driven by sediment / vegetation accumulation (*Flooding_Issues_Along_Hwy99...*, Sec. 1).
- **Channel bottlenecks identified:** Nord's geomorphic assessment identified a 2,277-ft constriction on Rock Creek downstream of the bifurcation that the Nord alternatives proposed to enlarge as part of any diversion concept (*Nord_Feasibility_Study_Part_A.md*, Table 5).
- **Keefer Slough channel capacity at SR 99 is 525 cfs** (per FIS); anything above this overtops or sheet-flows across SR 99 (*Nord*, Table 12, footnote 2; *Flooding_Issues_Along_Hwy99...*, Fig. 10).

### 1.3 What remains open

- **Diversion design discharge, trigger threshold, and structure type.** No source document sets these for a 2–3 ft rock-weir downstream system; Nord sets them only for dam-based downstream systems.
- **Per-weir hydraulic-loss characterization.** Manning's n equivalent or per-structure ΔH at design discharge needs to be assigned for screening-level routing.
- **Weir spacing.** Function of corridor longitudinal slope and design hydraulic regime; cannot be set from source documents alone.
- **Quantified peak-flow attenuation at each event from Q10 through Q500.** Must come from a screening flood-routing analysis (Deliverable 5) and then a full 2D routing in the DWR / Wood Rodgers model.
- **Quantified reduction in Keefer Slough peak / volume** at the same event range.
- **FEMA "no-rise" demonstration.** Concept must not raise flood elevations anywhere in the regulated floodplain at Q100. This is a binding constraint.

### 1.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| H-1 | Obtain the DWR / Wood Rodgers HEC-RAS 2D model files (and Nord's modifications). | Model handoff via DWR Northern Region Office and/or Wood Rodgers under the Nord scope. |
| H-2 | Build a corridor topographic surface (DEM, ~1-m resolution) for the two corridors. USGS 1-m DEM available (already used by Sand Creek Infiltration Study, *Sand Creek Infiltration Study*, Sec. 5.2). | Corridor DEMs (north / south). |
| H-3 | Screen the diversion design with a simple spreadsheet (Deliverable 5) — vary diversion capacity, trigger threshold, corridor roughness across plausible ranges; report Q100 attenuation envelope. | Screening table. |
| H-4 | Refine the screening result into a full HEC-RAS 2D scenario in the DWR / Wood Rodgers model, with the diversion and corridors represented (2D lateral structure or terrain modification). | 2D routing report. |
| H-5 | Test sensitivity across the four discharge datasets (Deliverable 2) at Q10, Q25, Q50, Q100, Q500. | Sensitivity report. |
| H-6 | Demonstrate FEMA no-rise (or quantify the rise + identify mitigation) for Q100 across all flood-control-relevant cross-sections in the regulated floodplain. | No-rise / mitigation memorandum. |

### 1.5 Sequence

H-1 first (it gates H-3 / H-4 / H-5 / H-6). H-2 in parallel. H-3 before H-4. H-4 / H-5 / H-6 sequential.

### 1.6 Likely responsible party

- **H-1:** Tovey Giezentanner (AGUBC project manager) requests via DWR Northern Region Office and/or Butte County WRC (Christina Buck).
- **H-2:** AGUBC, Vina GSA, or Butte County WRC; surface preparation likely outsourced to a GIS / civil-engineering consultant.
- **H-3:** AGUBC + qualified water-resources engineer (concept-stage screening; could be Wood Rodgers, given continuity with Nord, or another firm).
- **H-4 / H-5 / H-6:** Specialized hydraulic-engineering firm with HEC-RAS 2D experience and FEMA review history; Wood Rodgers is the obvious continuity choice but not the only one.

---

## 2. Recharge Feasibility (Lead with Sand Creek Infiltration Study and the Shallow-Clay-Layer Check)

### 2.1 What would have to be true

Across the ~10.4 mi of corridor, enough reaches must have favorable subsurface conditions — adequate surface infiltration rates, no laterally continuous shallow restrictive layer, and adequate vadose-zone storage above groundwater — that the concept produces a meaningful net recharge to the Tuscan aquifer system over time.

### 2.2 What the source documents already answer

- **Long-term constant infiltration rate at favorable Sand Creek sites is 0.7 ft/day (0.35 in/hr).** This is the same-area maximum applicable to favorable reaches of the corridor (*Sand Creek Infiltration Study*, Sec. 4.0, Sec. 8.0).
- **NRCS Ksat estimates** for the broader study area: most areas <0.2 ft/day; favorable channel-corridor zones up to 0.6 ft/day; values reduced 10× from raw NRCS Ksat per GSA practice (*Sand Creek Infiltration Study*, GSA App. Sec. 2.3, Fig. 4).
- **Channel-infiltration bonus of up to ~50%** above basin-area infiltration is GSA's experience-based finding (*Sand Creek Infiltration Study*, GSA App. Sec. 4.0).
- **Shallow-clay-layer reconciliation:** Hardpan / restrictive layers as shallow as 2 ft bgs in some Sand Creek wells; Tuscan loams have duripan at 18–22 in (*Singer Creek HDP*, Sec. 2.5); spatial variability is the key finding — downstream Sand Creek (Redsluff gravelly loam) lacks restrictive layer in top 80 in; upstream / northern areas are poor (*Sand Creek Infiltration Study*, GSA App. Sec. 2.3, Figs. 3–4).
- **SAGBI rating** across the Sand Creek footprint: Good (downstream channel) to Very Poor (upper / northern areas) (*Sand Creek Infiltration Study*, GSA App. Sec. 2.3, Fig. 4).
- **Vadose-zone storage:** Depth to groundwater 60–110 ft bgs; permeable material to 300–350 ft bgs; Tuscan aquifer specific yield 5.9–7.1%, transmissivity 2,322–23,650 sq ft/day (*Sand Creek Infiltration Study*, Sec. 7.0, GSA App. Sec. 2.4).
- **NRCS conservation easements cover most candidate Sand Creek sites** — extensive coordination required (*Sand Creek Infiltration Study*, Sec. 8.0).

### 2.3 What remains open

- **Corridor-specific subsurface characterization.** Sand Creek Infiltration Study covered five candidate sites; the concept's ~10.4 mi corridor needs reach-by-reach characterization, not basin-by-basin.
- **Reach-by-reach SAGBI / NRCS-Ksat / FDEM screen.** Same screening sequence Sand Creek used (SAGBI → FDEM → test pitting / borehole) applied to the corridor footprint.
- **Quantified annual recharge expected.** A reach-area × infiltration rate × inundation-duration estimate, calibrated to the same long-term historical hourly record (CRG gauge, 2000–2023) the Sand Creek Infiltration Study used.
- **Net effect on Vina Subbasin water budget.** Translation of corridor-recharge estimate into Vina GSP-relevant metrics (consistent with the Vina GSP and AGUBC's existing positions on recharge).

### 2.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| R-1 | Run a SAGBI / NRCS Web Soil Survey screen on the two corridors. | Reach-by-reach favorability map. |
| R-2 | Procure a corridor-scale FDEM survey using Collier Geophysics or equivalent (Sand Creek used Collier for the GSA report). | Apparent-conductivity maps at 5–7, 9–14, 15–22 ft bgs. |
| R-3 | Reach-specific test-pitting / borehole investigation at the most-favorable subset of corridor reaches. | Confirmed infiltration rates, restrictive-layer characterization. |
| R-4 | Build a reach-by-reach infiltration model (corridor area × event-driven inundation × reach-specific infiltration rate), using the CRG gauge long-term record. | Annual recharge estimate envelope. |
| R-5 | Confirm aquifer's ability to accept the recharge (mounding analysis using transmissivity and specific yield from *Sand Creek Infiltration Study*, GSA App. Sec. 2.4). | Mounding screening report. |
| R-6 | Translate into Vina Subbasin water-budget terms and reconcile with Vina GSP and AGUBC's existing AGUBC ISW / demand-reduction work. | Concept-stage water-budget memo. |

### 2.5 Sequence

R-1 first; R-2 second; R-3 only at the most-favorable subset identified by R-1/R-2; R-4 in parallel once R-3 is underway; R-5 / R-6 after R-4.

### 2.6 Likely responsible party

- **R-1:** Tovey or contracted GIS analyst; SAGBI + NRCS Web Soil Survey are public-data lookups.
- **R-2:** GeoSystems Analysis (GSA) + Collier Geophysics, continuing the Sand Creek precedent team.
- **R-3:** Same team plus a drilling subconsultant.
- **R-4 / R-5:** Water-resources engineering / hydrogeology consultant (Wood Rodgers continuity is again a natural choice).
- **R-6:** AGUBC + Vina GSA jointly; outputs feed both organizations' SGMA work.

---

## 3. Land / Site Control

### 3.1 What would have to be true

The two corridors must traverse parcels under landowner agreement — willing-landowner easement, conservation easement, fee acquisition, or a working-lands instrument — sufficient to allow rock-weir construction, periodic maintenance, and any seasonal flooding that would result from operation. Multiple existing instruments (NRCS conservation easements, mitigation easements, family-trust ownership patterns) must be navigated rather than overridden.

### 3.2 What the source documents already answer

- **Nord identified a pattern of multiple family ownerships across the corridor area** (per concept draft and Nord environmental constraints; *Nord_PartB_3_Environmental_Constraints.md*).
- **Most Sand Creek candidate sites are within NRCS conservation easements** — "will require extensive coordination with this agency and the property owner to ensure compliance with the intent of the easement or agreement that benefits will outweigh impacts" (*Sand Creek Infiltration Study*, Sec. 8.0).
- **Singer Creek demonstrates a perpetual-protection model** that combines fee acquisition + conservation easement held by an LTA-accredited non-profit + endowment fund (*Singer Creek HDP*, Sec. 1.2, Sec. 8.0).

### 3.3 What remains open

- **Landowner inventory along both corridors** — names, parcel APNs, ownership type (fee / trust / easement), current land use.
- **Willingness assessment** — which landowners are open to easements; which have existing NRCS or other conservation easements that already cover compatible uses; which are not feasible.
- **Easement instrument and compensation structure** — what compensates a landowner for accepting a flood-flow easement plus rock-weir maintenance access; whether the working-lands grazing pattern continues; one-time payment vs. annual.
- **NRCS coordination** for parcels already in conservation easements — whether rock-weir flooding is compatible with the existing easement purpose (in most cases meadowfoam / vernal pool protection — habitat enhancement *may* be compatible).
- **Long-term stewardship entity.** If easements are perpetual, the steward should be an LTA-accredited non-profit on the Singer Creek model.

### 3.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| L-1 | Build a parcel inventory along both corridors using Butte County Assessor data. | Inventory spreadsheet with APN, owner, area, current use, existing easements. |
| L-2 | Confirm the existing NRCS conservation easements that overlap the corridors. | NRCS easement footprint map. |
| L-3 | Begin discreet, low-formality conversations with the largest / most-pivotal landowners (relationship-led, no signed instruments). | Landowner-willingness assessment. |
| L-4 | Engage NRCS regional office about compatibility of seasonal flooding for habitat enhancement within existing meadowfoam-protection easements. | NRCS coordination memo. |
| L-5 | Identify an LTA-accredited non-profit candidate to hold any new conservation easements (Wildlife Heritage Foundation held Singer Creek Phase 1A and is the local incumbent). | Stewardship-entity letter of interest. |
| L-6 | Draft an easement framework (compensation, access, weir maintenance, seasonal flooding, term). | Standard-form easement draft. |

### 3.5 Sequence

L-1 / L-2 in parallel. L-3 after L-1 / L-2 are in hand (so the conversations are well-informed). L-4 in parallel with L-3 (different counterparty). L-5 / L-6 after L-3 / L-4 progress, before any project-level commitments.

### 3.6 Likely responsible party

- **L-1 / L-2:** Tovey / AGUBC; Butte County WRC support possible.
- **L-3:** Tovey, AGUBC leadership (Rich McGowan, Darren Rice, Todd Turley, Steve Koehnen) — leveraging existing relationships with corridor landowners.
- **L-4:** Tovey via NRCS State Conservationist's office; AGUBC has standing as an agricultural-stakeholder organization.
- **L-5 / L-6:** Tovey + a land-use attorney with conservation-easement experience.

---

## 4. Water Rights, CEQA, and Permitting Pathway

### 4.1 What would have to be true

The diversion of high flows from Rock Creek for spreading / recharge must obtain (or be lawfully exempt under) the SWRCB water-rights process. CEQA review (or NEPA equivalent if federal-nexus) must be completed. CWA 404, CWA 401, ESA Sec. 7 (federal) / Sec. 10 (non-federal) consultations, CESA Sec. 2081(b), CDFW Sec. 1602, and FEMA CLOMR / LOMR must all be cleared. Federal permits trigger NEPA; in-channel work triggers CDFW; floodway work triggers FEMA.

### 4.2 What the source documents already answer

- **SWRCB recharge permit explicitly required** for diverting surface water for groundwater recharge: "The State Water Resources Control Board and its regional arm will require a permit to allow recharging groundwater from surface water sources related to the State's adjudication of water rights" (*Sand Creek Infiltration Study*, Sec. 8.0).
- **CVFPB jurisdiction does NOT extend to the Sand Creek system** (*Sand Creek Infiltration Study*, Sec. 8.0). Confirm location-specific for the rock-weir corridors.
- **CDFW Streambed Alteration Agreement (Fish & Game Code §1602) required** for any work in any stream (ephemeral or perennial) (*Sand Creek Infiltration Study*, Sec. 8.0).
- **Sensitive-species exposure documented for the corridor:** Butte County meadowfoam (FE / SE), vernal pool fairy shrimp (FT), vernal pool tadpole shrimp (FE), Central Valley spring-run Chinook (FT / ST), Central Valley steelhead (FT), foothill yellow-legged frog (SE), VELB (FT), Swainson's hawk (ST), tricolored blackbird (ST) (*Nord_PartB_3_Environmental_Constraints.md*, Tables 2–3).
- **Migratory Bird Treaty Act protections** apply Feb 1 – Aug 31; pre-construction surveys required (*Singer Creek HDP*, Sec. 1.3).
- **FEMA Zone A → AE transition expected post-DWR FIRM update** (~2027); CLOMR before construction, LOMR after (*Flooding_Issues_Along_Hwy99...*, Sec. "FEMA CLOMR/LOMR").
- **No-rise requirement** — proposed actions in the floodway must not increase Q100 flood heights (*Flooding_Issues_Along_Hwy99...*, Sec. "FEMA CLOMR/LOMR").
- **NWP 27 is the right CWA 404 target** for a restoration / enhancement intent (per Singer Creek precedent; *Singer Creek HDP*, Sec. 1.3).

### 4.3 What remains open

- **Water-rights theory of the case.** Is this an application for a new appropriative right? A change petition to existing rights? A reliance on the SGMA-enabled recharge framework? The right pathway is fact-specific to the season, source, volume, and downstream impact.
- **CEQA lead agency.** Likely AGUBC or Vina GSA, depending on grant structure; could also be Butte County if the County is the project sponsor.
- **ESA Sec. 7 vs. Sec. 10.** Federal nexus (e.g., NRCS easement coordination, USACE 404 permit, federal funding) triggers Sec. 7. Without federal nexus, Sec. 10 ITP route required.
- **FEMA CLOMR scope.** Whether the concept is submitted as a single CLOMR or phased by reach.
- **Bifurcation maintenance agreement.** The Caltrans memo notes "no responsible agency or authority" currently maintains the bifurcation and suggests an MOU between Butte County, the private landowner(s), and other related agencies (*Flooding_Issues_Along_Hwy99...*, Sec. "Regular Maintenance Activity"). This is parallel to but reinforcing of the diversion concept and should be addressed in the same regulatory framework.

### 4.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| P-1 | Identify SWRCB recharge-permit pathway with water-rights counsel (potential precedents: SGMA-enabled recharge, Flood-MAR pathway, conjunctive-use change petition). | Water-rights theory memo. |
| P-2 | Identify CEQA lead agency and prepare an initial CEQA scoping plan. | CEQA scoping plan. |
| P-3 | Confirm CVFPB jurisdictional status at the corridor locations. | CVFPB jurisdiction memo. |
| P-4 | Begin informal ESA Sec. 7 pre-consultation with USFWS and NMFS (vernal pool species + Chinook/steelhead). | Pre-consultation feedback. |
| P-5 | Begin informal CDFW pre-consultation for the Sec. 1602 SAA. | Pre-consultation feedback. |
| P-6 | Plan a single CLOMR application sequencing through the post-2027 DWR FIRM update; identify whether to file CLOMR before or after the FIRM update (likely after — to use the updated regulatory baseline). | CLOMR sequencing memo. |
| P-7 | Bifurcation maintenance MOU concept — propose AGUBC / Vina GSA / Butte County / landowner(s) as parties; structure to reinforce the diversion concept. | MOU concept draft. |

### 4.5 Sequence

P-1 / P-2 first (frames everything). P-3 in parallel (cheap and bounded). P-4 / P-5 informal pre-consultation begins after concept stabilizes (after Deliverable 5 routing screen). P-6 after DWR FIRM update visibility improves. P-7 in parallel — independent of the concept timeline but should advance together.

### 4.6 Likely responsible party

- **P-1:** Tovey + water-rights attorney; coordinate with Vina GSA legal counsel and SWRCB Northern Region staff.
- **P-2:** AGUBC + CEQA consultant.
- **P-3:** Tovey direct query to CVFPB staff.
- **P-4 / P-5:** Environmental consultant (likely the same firm that prepared the Nord environmental-constraints assessment, Sec. 4.4 of *Nord_PartB_3*).
- **P-6:** Hydraulic engineer + FEMA-compliance consultant.
- **P-7:** Tovey + Butte County (the County has stated in the Caltrans memo it lacks jurisdiction at the bifurcation — i.e., a maintenance MOU has a willing partner to organize).

---

## 5. Sediment and Maintenance

### 5.1 What would have to be true

The corridor must accept the sediment load delivered by the diverted floods without progressive aggradation that compromises weir function or downstream water-quality. Maintenance — sediment-management cycles, weir-stone replacement, vegetation management, structure inspections — must be funded perpetually and assigned to a steward.

### 5.2 What the source documents already answer

- **Nord's geomorphic assessment characterizes sediment supply and grain size** for Rock Creek and tributaries: D50 13–118 mm across 15 field sites; six sites have sediment-supply index > 1; highest at confluences (bifurcation SSI > 3); 50–100 year incision history at some sites (*Nord_PartB_2_Geomorphic_Assessment.md*, Tables 1–2, Sec. "Channel Instability").
- **Sand Creek Infiltration Study finding on dam-induced sediment:** "The main impacts to geomorphic stream conditions that are created by impounding water are from trapping sediment upstream of dams and thereby starving the downstream reaches of sediment that would have otherwise migrated. Removing upstream sediment will require some degree of routine maintenance" (*Sand Creek Infiltration Study*, Sec. 4.0). This is dam-specific in magnitude; the rock-weir version is distributed sediment retention with much smaller per-structure accumulation, but the principle applies.
- **Singer Creek's grazing-and-monitoring maintenance model** is a working precedent for distributed-structure sites: rotational grazing, invasive species control, 5-year establishment monitoring per phase, perpetual stewardship by an LTA non-profit (*Singer Creek HDP*, Secs. 8.3–8.4, Sec. 7.0).
- **Bifurcation sediment dynamics** documented: sediment + vegetation accumulation has shifted the bifurcation split from 56/44 toward 39/61 over the period of record (*Flooding_Issues_Along_Hwy99...*, Sec. 1); this is the same sediment-supply problem operating without management.

### 5.3 What remains open

- **Expected sediment yield from the diverted Rock Creek hydrograph** at each design event.
- **Per-weir sediment accumulation rate** as a function of weir spacing, weir height, and reach slope.
- **Maintenance frequency** — weir-stone replacement, sediment-pulse management, vegetation management.
- **Funded maintenance program** — who pays, on what schedule, from what endowment / annual revenue.
- **Downstream sediment-starvation risk.** Distributed weirs retain less per-structure sediment than dams but, in aggregate, could still produce some downstream sediment deficit; this needs an honest assessment.

### 5.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| S-1 | Estimate sediment load delivered by the diverted hydrograph (function of design discharge and Rock Creek sediment-rating relationship). | Sediment-load estimate. |
| S-2 | Adopt a maintenance design philosophy — e.g., "design for sediment pass-through at extreme events; allow accumulation at frequent events; remove on N-year cycle." | Maintenance design memo. |
| S-3 | Test a single pilot reach (perhaps the lower north corridor, where subsurface is most favorable) and monitor for 3–5 yr to calibrate the maintenance assumptions. | Pilot-reach monitoring report. |
| S-4 | Build the long-term operations & maintenance plan on the Singer Creek model (rotational grazing, invasive species control, structure inspections, sediment-removal cycle). | Long-term O&M plan. |
| S-5 | Establish a perpetual endowment for the O&M plan, funded by a combination of grant principal, landowner / agency partnership, and ongoing revenue (grazing leases, ag-stewardship payments). | Endowment structure memo. |

### 5.5 Sequence

S-1 after H-3 (screening hydraulic results). S-2 in parallel. S-3 starts after first construction phase (i.e., late in the overall sequence). S-4 / S-5 in parallel with project advancement.

### 5.6 Likely responsible party

- **S-1 / S-2:** Geomorphologist + hydraulic engineer (the Nord Part B geomorphic assessment team, or equivalent).
- **S-3:** Pilot-reach landowner partnership + AGUBC + Vina GSA + monitoring consultant.
- **S-4 / S-5:** AGUBC + the chosen LTA-accredited non-profit steward + Vina GSA.

---

## 6. Cost and Funding

### 6.1 What would have to be true

The concept must have a cost envelope that matches at least one identifiable funding pathway, with realistic combinations of state, federal, and private sources. The 80%+ of project cost that Nord assigned to dams + reservoir mitigation does not apply here; the concept's cost is dominated by conveyance + distributed weir construction + landowner agreements + monitoring.

### 6.2 What the source documents already answer

- **Nord channel and intake line-item unit costs (2023 basis)** are directly transferable:
  - Diversion channel excavation: $6 / cy
  - Diversion structure (in-creek concrete): $40 / cy
  - In-creek foundation prep: $250,000 lump sum
  - *Source: Nord_PartB_5_Appendices_8-11.md, Appendix 9.*
- **Nord's total alternative costs ($222M – $370M)** are dominated by dam fill, outlet works, environmental mitigation, and land acquisition — these are NOT transferable line items.
- **Singer Creek explicitly funded via Caltrans transportation-project mitigation;** not directly applicable here unless a transportation-mitigation tie exists (not obvious for the concept).
- **The project-instructions context names the right candidate funding programs:** Prop 4 ($386M groundwater management + $100M IRWM + $75M regional conveyance), federal WaterSMART (Applied Science Grant deadline July 8, 2026), Canella Act (AGUBC TAP eligibility), NRCS EQIP / RCPP, SGMA implementation grants. *Source: CLAUDE.md project context.*

### 6.3 What remains open

- **Concept-stage order-of-magnitude cost.** Need to combine: diversion + intake (Nord transferable); conveyance to corridor heads (Nord transferable per cy); distributed weir construction (no direct precedent — RDS / BDA per-structure costs from external sources); landowner-agreement compensation; permits / CEQA / environmental documentation; monitoring; perpetual O&M endowment.
- **Funding-pathway mapping.** Which programs are the most likely fit — and which require federal nexus, which require state-only, which favor agricultural land use, which favor habitat-mitigation use.
- **Phasing-funding strategy.** Singer Creek's phase-by-phase funding model fits the concept well — north corridor first, south corridor follow-on; each phase has its own grant tranche.

### 6.4 Next steps

| Step | Action | Output |
| --- | --- | --- |
| C-1 | Build a concept-stage order-of-magnitude cost using Nord transferable unit costs for diversion + conveyance, RDS / BDA-derived per-weir costs (external source) for the corridor weirs, and Singer Creek-derived monitoring / O&M endowment estimates. | OOM cost envelope. |
| C-2 | Map the cost envelope to candidate funding programs (Prop 4 lines, WaterSMART, Canella Act TAP, NRCS EQIP / RCPP, SGMA implementation). | Funding-fit matrix. |
| C-3 | Identify the lead funding pathway for the first phase (likely Prop 4 + Flood-MAR pilot funding through DWR). | Phase-1 funding strategy. |
| C-4 | Coordinate with Butte Farm Bureau (existing SWEEP grant partner) and Butte County WRC on co-applicant / co-sponsor opportunities. | Partnership map. |
| C-5 | Confirm AGUBC's eligibility as a TAP under the Canella Act for 501(c)(6) status. | TAP-eligibility memo. |

### 6.5 Sequence

C-1 after R-4 (recharge volume estimate) and H-3 (peak attenuation estimate) — those scope the benefit side. C-2 / C-3 / C-4 / C-5 in parallel as background research; the live opportunities (WaterSMART July 8, 2026 deadline; Prop 4 application windows) drive timing.

### 6.6 Likely responsible party

- **C-1:** AGUBC + cost-estimating consultant; Wood Rodgers continuity is again natural for the diversion / conveyance line items.
- **C-2 / C-3:** Tovey + grants-administration support (Butte County WRC has experience; Butte Farm Bureau partnership active).
- **C-4 / C-5:** AGUBC leadership; the Canella Act TAP question is already on AGUBC's agenda per project context.

---

## 7. Master Sequence

| Phase | Months | Primary Activities | Major Outputs |
| --- | --- | --- | --- |
| **0 — Concept Synthesis (current)** | 0–3 | Deliverables 1–5; stakeholder discussion | Concept documents + 4-dataset screen |
| **1 — Foundational Data & Relationships** | 3–9 | H-1, H-2, R-1, R-2, L-1, L-2, P-3, C-1, P-7 (bifurcation MOU) | Corridor DEMs; SAGBI / NRCS / FDEM screen; landowner inventory; CVFPB confirmation; OOM cost; bifurcation MOU concept |
| **2 — Hydraulic Screening + Subsurface Confirmation** | 6–18 | H-3, H-4 (in parallel), R-3, R-4, S-1, L-3 (landowner conversations) | Screening + 2D routing results; reach-by-reach recharge model; pilot-reach selection; willingness assessment |
| **3 — Regulatory Pathway + Detailed Design (phased)** | 12–30 | H-5, H-6, R-5, R-6, P-1, P-2, P-4, P-5, P-6, L-4, L-5, L-6, S-2, C-2, C-3 | No-rise demonstration; mounding analysis; water-rights theory; CEQA scoping; ESA / CDFW pre-consultation; CLOMR sequencing; easement framework; sediment-management philosophy; funding-fit matrix |
| **4 — Phase-1 Construction (likely north corridor pilot reach)** | 30–48 | S-3 pilot reach + first construction; companion monitoring | Built reach + monitoring data |
| **5 — Long-term Stewardship** | 48 + perpetuity | S-4, S-5; phased expansion to south corridor | Singer-Creek-style perpetual stewardship plan + endowment |

---

## 8. Honest Caveats and Concept-Stage Disclaimers

1. **This concept is not engineering, not legal, and not water-rights advice.** Every step in this roadmap is gated by analysis or counsel that has not yet been retained.
2. **The discharge-dataset disagreement is unresolved.** See Deliverable 2 — the screening must run against both Track A (Nord HEC-HMS) and Track B (DWR HEC-RAS 2D) hydrology and report results in both terms.
3. **The diminishing-attenuation finding at extreme events is real.** See Deliverable 3, Tier D. The headline flood-safety claim should be qualified accordingly — "meaningful peak reduction at frequent-to-moderate events; modeled (not assumed) result at Q100 / Q500."
4. **The bifurcation problem is partly separate.** Sediment / vegetation maintenance at the bifurcation alone (the Caltrans memo's MOU recommendation) materially reduces Keefer Slough flooding. The concept can advance and benefit from a parallel bifurcation MOU; it does not solve the bifurcation problem on its own.
5. **NRCS conservation easements are a major constraint.** Most candidate Sand Creek sites are within existing easements; the concept's corridor likely intersects more easements that the source documents have not enumerated. Early NRCS engagement is non-optional.
6. **Singer Creek is not a flood precedent.** It is a habitat / land-control / stewardship precedent. Cite it for those purposes; do not cite it for flood-attenuation precedent.
7. **A bifurcation cleanup happened in February 2025.** The 39/61 split presumably reflects post-cleanup conditions or recent post-cleanup conditions (*Flooding_Issues_Along_Hwy99...*, "Butte County, DWR and FEMA"). If subsequent cleanups occur on a schedule, the design baseline will shift again.
