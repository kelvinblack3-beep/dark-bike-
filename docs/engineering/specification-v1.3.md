# Specification — Engineering Baseline V1.3

1. Confirmed Architectural Principles
------------------------------------
- The primary vehicle architecture (engine → clutch → gearbox → final drive → rear wheel) is the baseline control hierarchy for propulsion and must function independently of experimental systems.
- Experimental systems (X1..X4) are modular augmentation systems and must not be required for fundamental vehicle operation.

2. Provisional Parameters
-------------------------
- 5-cylinder radial engine — PROVISIONAL (conceptual)
- Approximately 750 cc target displacement — PROVISIONAL
- Four-stroke cycle — PROVISIONAL
- Forced-air cooling — PROVISIONAL

3. Open Engineering Parameters
-----------------------------
The following parameters remain open and MUST be derived in future sessions or work packages:
- bore
- stroke
- exact displacement
- cylinder spacing
- crank geometry
- master-rod geometry
- articulating-rod geometry
- connecting-rod lengths
- crankpin diameter
- main-bearing arrangement
- crankshaft dimensions
- firing order
- cam indexing
- compression ratio
- valve diameter
- valve train geometry
- cam timing
- maximum RPM
- torque curve
- power curve
- cooling airflow
- fan diameter
- fan RPM
- fan pressure rise
- fan electrical power
- gearbox
- primary ratio
- final-drive ratio
- chassis dimensions
- CG position
- suspension geometry
- braking system
- aerodynamic dimensions
- thermal limits
- composite material system

4. Engineering Corrections
--------------------------
- Do not assume master-rod/articulating-rod dimensions or crankpin geometry; these must be mathematically derived.
- Cylinder angular spacing is geometrically 72° for five cylinders, but firing order must be derived from crank and cam indexing.
- Vibration characteristics, torque/power relationships, cooling requirements, engine packaging, and temperature limits require calculation and testing before being described as verified.

5. Development Sequence
-----------------------
P0.0 — Repository engineering foundation
P0.1 — Radial geometry and kinematics
P0.2 — Thermodynamic model
P0.3 — Dynamic / balance model
P0.4 — Crankshaft design
P0.5 — Cooling / fan sizing
P0.6 — Powertrain / transmission
P0.7 — Vehicle dynamics
P0.8 — Aerodynamics
P0.9 — Structural design
P1 — Parametric CAD / engine mockup
P2 — Rolling chassis
P3 — Engine bench testing
P4 — Thermal validation
P5 — Enclosed vehicle
P6 — Controlled vehicle testing

6. Validation Requirements
--------------------------
- All provisional parameters require documented calculations, simulations, or experimental validation before promotion to VERIFIED or VALIDATED status.
- Any change of status (e.g., PROVISIONAL → VERIFIED) must cite the session ID, date, supporting evidence, and approval record.
