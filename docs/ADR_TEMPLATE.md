# Architecture Decision Record (ADR) — Template

ID: ZP-ADR-YYYYMMDD-NN
Title: Short descriptive name
Date: YYYY-MM-DD
Status: proposed | under review | accepted | rejected | superseded
Authors: Name(s)
Related ADRs: (IDs)

Summary
- One-paragraph summary of the concept.

Physical principle
- e.g., magnetohydrodynamic acceleration; electromagnetic plasma confinement; inductive acceleration; Hall-effect-like plasma jets; RF-driven plasma/ponderomotive force, etc.

Energy source
- Primary source(s) of energy (chemical, stored electrical, capacitive discharge, inductive transfer, nuclear — note any restrictions).

Energy conversion mechanism
- How input energy is converted into mechanical/kinetic/electric output (e.g., Poynting-flux acceleration, plasma jet momentum exchange, electromagnetic field coupling).

Predicted output
- Scalar description: expected form of output (thrust, power, torque), estimated magnitude (order-of-magnitude only), scaling relationships.

Efficiency estimate
- Best estimate for conversion efficiency with confidence band; rationale and dominant loss mechanisms.

Losses
- List and describe expected loss channels (radiative, collisional, resistive, conduction, incomplete ionization, circuitry losses).

Thermal rejection requirement
- Estimated thermal load and approximate rejection approach (radiative/conductive/coolant) — order-of-magnitude only, no hardware details.

Major assumptions
- Explicit list of assumptions (plasma density, magnetization level, mean free path regimes, confinement times, boundary conditions).

Evidence level
- Categorize evidence: literature-theory | small-scale experiment | simulation | analogous technology
- Attach references in docs/04_literature_sources.md

Unresolved questions
- Clear, testable questions remaining.

Validation method
- Proposed validation pathway (analytical scaling, non-harmful simulation, low-energy surrogate tests — subject to safety review).

Decision history
- Notes about reviews and decisions.

Notes
- Other remarks and links to supporting files, simulations, notebooks.
