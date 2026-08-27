# ZAM-P1 Claim Verification Register

This register tracks major numerical claims made in the P1 plasma campaign and specifies the evidence required to verify each.

Columns: Claim ID | Claim | Current Status | Evidence Required | Source | Verification Method | Notes

P1-C001 | PAC can improve efficiency by 2–10% | UNVERIFIED | Primary-source experimental data or replication; engine model with plasma input | P1 report (secondary) | Reproduce on-engine or validated simulation + independent measurement | Keep claim UNVERIFIED until source located

P1-C002 | 6% BSFC improvement demonstrated on a production 2.5 L Atkinson engine | UNVERIFIED | Primary test report / dataset with test protocols and baseline | P1 report (secondary) | Independent review of test data and reproduction if feasible | Flag for literature search

P1-C003 | PAC plasma electrical consumption is <1 kW | UNVERIFIED | Measurement logs or hardware datasheets | P1 report (secondary) | Electrical power monitoring during representative engine operation | Check instrumentation accuracy

P1-C004 | PAC subsystem mass can be 10–25 kg | ENGINEERING ESTIMATE / UNVERIFIED | Detailed BOM and subsystem layout or measured prototype mass | P1 report (secondary) | Parts-level estimate and prototype measurement | Mass must include power electronics, cooling, mounting

P1-C005 | LMMHD can achieve quoted power density | SOURCE-DEPENDENT / UNVERIFIED FOR VEHICLE SYSTEM LEVEL | Primary literature showing complete system-level density, including magnets, pumps, heat exchangers | P1 report (secondary) | Independent mass/energy closure that includes auxiliaries | Often power-density claims omit system mass

P1-C006 | Continuous 250–350 kW plasma-primary vehicle power system exists | NO EVIDENCE IDENTIFIED | Peer-reviewed demonstrations at system level or validated technical path with closed energy balance | n/a | Not applicable | Classify as unsupported until evidence is produced


Notes
- For every claim: add a cross-link to the primary source when found and change status appropriately (SUPPORTED / VERIFIED). Until then, status remains UNVERIFIED or SOURCE-DEPENDENT.
