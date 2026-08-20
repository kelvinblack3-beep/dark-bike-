# PROJECT DARKBIKE

Project DARKBIKE — Experimental single-rider motorcycle engineering program.

Project purpose
---------------
To develop an engineering baseline and controlled research program for an experimental single-rider motorcycle powered by a radial engine and augmented by modular airflow and exhaust systems. This repository holds the engineering-control infrastructure, documentation, and traceability records for the program.

Current project status
----------------------
PROJECT DARKBIKE IS CURRENTLY AN ENGINEERING-CONCEPT DEVELOPMENT PROGRAM AND HAS NOT YET REACHED FABRICATION.

Current architecture (conceptual)
---------------------------------
- 5-cylinder radial engine (conceptual)
- ~750 cc target displacement (PROVISIONAL)
- Four-stroke cycle (PROVISIONAL)
- Forced-air cooling (PROVISIONAL)
- Mechanical rear-wheel propulsion
- Clutch
- Motorcycle gearbox
- Final-drive system
- Mechanical steering
- Retractable low-speed stabilizers
- Enclosed/streamlined vehicle body
- Modular experimental front fan / air-management system (X1)
- Modular experimental rear exhaust augmentation system (X2)
- Future experimental active aerodynamic system (X3)
- Future advanced exhaust research program (X4)

Engineering philosophy
----------------------
- The primary vehicle must function independently of all experimental systems.
- Experimental systems are AUGMENTATION only and must not be required for propulsion, steering, braking, or fundamental stability.
- Major engineering decisions are proposed, reviewed, challenged, calculated or researched, resolved, recorded, approved, and versioned.

Development phases
------------------
- P0 — Engineering definition
- P0.1 — Radial geometry and kinematics
- P0.2 — Thermodynamic model
- P0.3 — Dynamic / balance model
- P0.4 — Crankshaft design
- P0.5 — Cooling / fan sizing
- P0.6 — Powertrain / transmission
- P0.7 — Vehicle dynamics
- P0.8 — Aerodynamics
- P0.9 — Structural design
- P1 — Parametric CAD / engine mockup
- P2 — Rolling chassis
- P3 — Engine bench testing
- P4 — Thermal validation
- P5 — Enclosed vehicle
- P6 — Controlled vehicle testing

Multi-AI engineering workflow
-----------------------------
- Lead systems engineering and decisions: ChatGPT (Lead Systems Engineer).
- Research, verification, adversarial review and analysis: multi-AI team (Perplexity, Grok, DeepSeek) as defined in AI_ENGINEERING_PROTOCOL.md.
- Implementation and repository changes: GitHub Copilot (repository implementation and documentation engineer).
- Human project owner retains final authority and approval for manufacturing decisions.

GitHub / Copilot role
---------------------
GitHub Copilot is the repository implementation and documentation assistant; it implements files, documentation, and traceability controls as directed by the lead engineering AI and the human project owner.

Engineering traceability philosophy
-----------------------------------
- Every major decision, assumption, calculation, and version change must be recorded with session ID and timestamp.
- Unknown items must be explicitly labeled "UNKNOWN".
- Assumptions must be labeled "ASSUMPTION / PROVISIONAL".
- Calculations must be labeled "CALCULATED".
- Physically tested results must be labeled "VALIDATED".

Safety philosophy
-----------------
- The repository contains engineering definitions only; no hardware is to be fabricated from documents here without formal validation, review, and approval.
- Experimental systems shall not be treated as required for safe operation of the core vehicle.

Current phase
-------------
P0 — ENGINEERING DEFINITION

Current session
---------------
DB-P0.0-S001 (2026-08-20)

Current next milestone
----------------------
Repository Engineering Infrastructure (complete for this session). Next engineering task: DB-P0.1-S001 — Five-cylinder radial geometry and kinematic model (P0.1).
