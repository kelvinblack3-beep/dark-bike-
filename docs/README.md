# PROJECT ZAMANI — Documentation Foundation

Purpose
- Create and maintain the engineering documentation foundation for ZAMANI-P (Plasma Electromagnetic Engine) and the broader PROJECT ZAMANI research program.
- This branch holds research- and feasibility-phase documentation only. No hardware designs, dimensions, or construction procedures are included.

Scope
- Requirements, assumptions, candidate architectures, analyses, simulation and validation requirements, risk register, ADR system, and decision gates.
- All concepts are recorded without selecting a final architecture.

How to use
- Add new Architecture Decision Records (ADRs) in docs/arh/ using the ADR template (docs/ADR_TEMPLATE.md).
- Update sections with references and evidence as analysis proceeds.
- All changes targeting experimental design or tests must be reviewed and pass the Decision Gate described in docs/17_decision_gates.md.

First engineering gate
- "Does a physically credible plasma architecture exist that could plausibly scale to useful power?"
  - This gate must be answered before any experimental hardware design or prototyping is allowed.

Conventions
- Filenames prefixed with two-digit numbers map to the canonical engineering areas.
- Use the ADR template for each proposed concept. Assign unique IDs using the scheme: ZP-ADR-YYYYMMDD-NN or ZP-CONCEPT-XXXX.
