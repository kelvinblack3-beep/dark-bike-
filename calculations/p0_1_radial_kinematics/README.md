This directory contains the calculation framework and working files for P0.1 — Five-cylinder radial geometry and kinematic foundation.

Purpose
- Host analytical derivations, parameter tables, and Python modules that implement the radial kinematics model.

Important
- DO NOT compute or freeze final engineering dimensions in this directory during initialization.
- All parameters that appear here must be explicitly labelled with their status (UNKNOWN / ASSUMPTION / PROVISIONAL / CALCULATED / REQUIRES VALIDATION).

What belongs here
- parameters.py (parameter table)
- geometry.py (geometric helpers)
- kinematics.py (kinematic functions)
- validation.py (consistency checks)
- run_model.py (script to run the model)

At this initialization step no code or numerical values are included — this README is a placeholder to establish the workspace.