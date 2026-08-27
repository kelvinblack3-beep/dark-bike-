# ZAM-P1 — Plasma Architecture Matrix

This document records the set of plasma-related architectures investigated during the Project Zamani P1 research campaign. Each entry captures primary energy source, the plasma role, current status, and key concerns. This matrix is the canonical record: do not re-open an entry without explaining what new evidence or boundary conditions differ.

A1 — Plasma-Assisted Combustion / Nanosecond Pulsed Plasma Ignition (PAC)
Primary source: Chemical fuel
Plasma role: Ignition enhancement; combustion chemistry modification; lean-burn assistance
Status: PROVISIONALLY SUPPORTED — ASSIST TECHNOLOGY ONLY
Notes: This is NOT a plasma primary power core. Numerical claims in P1 remain PROVISIONAL and UNVERIFIED unless traced to primary sources. See ZAM-P1_PAC_BASELINE.md and the Claim Verification Register.

A2 — Open-Cycle MHD
Primary source: Chemical combustion products
Plasma role: Electrical extraction from a conducting hot gas stream
Status: CONDITIONALLY POSSIBLE / ENGINEERINGALLY UNATTRACTIVE
Known concerns: magnet mass, channel size, thermal rejection, electrode erosion, seed management, continuous vehicle-scale operation challenges.

A3 — Closed-Cycle MHD
Primary source: External heat source (required)
Plasma role: Electrical conversion within a closed working fluid
Status: UNATTRACTIVE / UNVERIFIED FOR VEHICLE SCALE
Key problem: external heat source mass/thermal system must be included in energy/mass closure.

A4 — Non-Equilibrium Plasma Fuel Reforming
Primary source: Chemical fuel + electrical input
Plasma role: Reforming fuel (chemical processing)
Status: REJECTED AS PRIMARY POWER GENERATOR
Reason: Prior examined configurations were net-energy-consuming or unattractive once full accounting is applied.

A5 — Pulsed Plasma Generator / Inductive Plasma Systems
Primary source: Stored electrical energy (capacitors/batteries)
Plasma role: Energy redistribution and short-duration high-power pulses
Status: REJECTED AS CONTINUOUS VEHICLE POWER SOURCE
Reason: Converts stored energy; not an independent continuous energy source.

A6 — Plasma + Turbine / Reciprocating Hybrid
Primary source: Chemical fuel / conventional prime mover
Plasma role: Assist or preheat; reduces to conventional powertrain + plasma assist
Status: REDUCES TO CONVENTIONAL POWERTRAIN + PLASMA ASSIST

A7 — Electrostatic / Magnetized Plasma Direct Converter
Primary source: Requires high-energy plasma input (external)
Plasma role: Direct conversion of particle/field energy to electric power
Status: UNVERIFIED / NOT VEHICLE-READY
Problems: needs genuine high-energy plasma source, space-charge limits, conversion efficiency, thermal management, source mass.

A8 — Pure Plasma Core With No Primary Energy Source
Primary source: None
Plasma role: Proposed sole power source
Status: FUNDAMENTALLY REJECTED
Reason: Energy conservation — plasma is not itself an energy source.


Document history
- Created: 2026-08-27 (ZAM-P1 archival)
- Author: Project Zamani repository steward (memory record)
