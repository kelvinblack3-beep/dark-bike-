# PROJECT ZAMANI — MASTER STATE

## 1. Project Mission
PROJECT ZAMANI is an experimental extreme-lightweight futuristic single-seat performance vehicle research program. The current research emphasis is to evaluate advanced power systems including plasma-related and hybrid architectures to determine feasibility for a vehicle target power envelope.

## 2. Current Date
2026-08-27

## 3. Current Phase
ZAM-P0.2 — CROSS-DIVISION RESEARCH & ADVERSARIAL CLOSURE (research / feasibility)

## 4. Architecture Status
UNFROZEN — the previous 3-cylinder radial-engine direction is archived and no longer active. The project is actively exploring plasma/advanced power systems combined with extreme lightweight vehicle architectures.

## 5. Current Vehicle Targets (provisional)
- Peak power (provisional): 250–350 kW
- Vehicle mass (provisional): 500–700 kg (dry/curb to be clearly defined per mass-closure rule)
- Single-seat, track-focused machine

## 6. Division I Status (Plasma Power System Research)
Mission: Determine whether plasma physics can provide a physically defensible and useful energy/power function for Zamani.
Current focus: plasma-assisted hybrid concepts, plasma-assisted combustion, plasma-enhanced conversion, and hybrid MHD recovery concepts.
Accepted provisional direction: plasma-assisted combustion (provisionally accepted). Several other pure-plasma generation concepts remain rejected or archived; see docs/18_rejected_concepts.md.

## 7. Division II Status (Futuristic Vehicle Architecture)
Mission: Develop vehicle layouts consistent with whichever power system is selected.
Current provisional baseline: dual-motor electric AWD as a comparison architecture. This baseline must be adversarially closed per ZAM-P0.2 priorities.

## 8. Division III Status (Adversarial Independent Verification)
Mission: Independently try to refute claims from Divisions I & II. Maintain a preserved failure database. Recent findings emphasize that thermal closure, realistic materials, and complete vehicle-level energy/mass accounting are critical.

## 9. Accepted Results
- Plasma-assisted combustion is provisionally accepted as a research direction.
- Helium recuperated Brayton thermodynamic calculations (previous work) were internally consistent under their assumptions.

## 10. Rejected Results
See docs/18_rejected_concepts.md for full archive. Notable rejections include microwave air plasma thruster, plasma-heated Brayton cycle (low priority), direct plasma-to-electricity converters for current vehicle scale.

## 11. Failure Database
- All failed hypotheses must be preserved under calculations/ and failure-log/; do not delete or obscure past attempts.
- Create and maintain a running failure-log entry for each archived concept.

## 12. Open Hypotheses
- Can a plasma-assisted hybrid architecture (e.g., plasma-assisted combustion with waste-heat MHD recovery) close energy/mass/thermal budgets for 250–350 kW vehicle application?
- Can thermal rejection be achieved within the vehicle mass envelope for high-temperature hybrid schemes?
- Which material systems are compatible with any candidate high-temperature plasma interfaces?

## 13. Breakthrough Candidates
- Plasma-assisted combustion + liquid-metal MHD waste-heat recovery (requires mass/thermal research).
- Any new plasma-hybrid candidate which demonstrably closes first-principles energy accounting and mass/thermal budgets.

## 14. Current Mass Budget
- Project-level mass budgets are provisional. Division II must produce a full vehicle mass-closure including all items per the Critical Mass-Closure Rule before any final mass claim.

## 15. Current Power Budget
- Baseline comparison: electric AWD architecture (to be independently closed). Plasma candidates must provide full energy-in/energy-out accounting and auxiliary power estimates.

## 16. Current Thermal Budget
- Thermal rejection is a leading risk. Each candidate must include an order-of-magnitude thermal rejection estimate before Gate 1.

## 17. Current Aerodynamic Targets
- To be established alongside concept studies (Concepts A/B/C). Aerodynamic closure required for performance claims.

## 18. Current Vehicle Concept Direction
- Proceed with three concept studies: CONCEPT A (PREDATOR), CONCEPT B (PHANTOM), CONCEPT C (PLASMA). Each is exploratory and must be documented under vehicle-concepts/.

## 19. Research Rules
- Do not freeze architectures prematurely. Preserve failure records. Apply adversarial iterative research loop (hypothesis → model → independent check → evidence search → adversarial attack → archive if failed).

## 20. Known Errors / Corrections
- Previous Division II document contained at least one power-to-weight arithmetic inconsistency; Division III should list and correct in calculations/.

## 21. Next Required Research
Priority 1: Independently close the Electric AWD baseline (battery pack, motors, cooling, thermal, vehicle mass).
Priority 2: Independently evaluate plasma-assisted hybrid architecture.
Priority 3: Continue searching for superior plasma-related power architectures.
Priority 4: Begin preliminary futuristic vehicle concept studies (A/B/C).

## 22. Session History
- ZAM-P0.2 initialized 2026-08-27. This master state file created/updated by the project agent. All future agents should read this file first.

## 23. Decision Log
- 2026-08-27: Architecture marked UNFROZEN. 3-cylinder radial engine archived. Plasma-assisted combustion provisionally accepted. ZAM-P0.2 defined as the next active research phase.


### What was written to the repository in this session
- Added documentation foundation files under docs/ (README, ADR template, templates for 01–18, ADR index, ADR folder README).
- Created docs/zamani/PROJECT_ZAMANI_MASTER_STATE.md capturing the current master-state snapshot.

### Current status
- Research phase active; architecture UNFROZEN. Awaiting Division II mass/power closure and Division I deeper feasibility studies.

### Recommended next steps
- Division III: begin adversarial closure of Electric AWD baseline (Priority 1).
- Division I: produce detailed energy-accounting examples for plasma-assisted combustion and candidate hybrid schemes.
- Create calculation notebooks in calculations/ and record failures in failure-log/.
