# MEC002 · Production & Pipeline Compressor 3D Digital Twin

Interactive 3D & Baker Hughes MKVIe iHMI Digital Twin Simulator for **Vietnam Block B Gas Project (VBGP) EPCI #1 (CPPT)**:
- **Units**: `CPPT-PK-1101` (Right Dismantling) & `CPPT-PK-2101` (Left Dismantling)
- **Train Architecture**: `GE LM2500+G4 SAC` (17-stage CCW GG + 6-stage Free Power Turbine @ 3,600 rpm + WHRU Diverter Damper) → `Lufkin NF2219E` (1:2.594, ΔZ = 558.8 mm lateral offset, CCW→CW reversal) → `Baker Hughes 2BCL456/A` (Back-to-back 2×3 impellers, slide-out 7,237 kg rotor bundle, Tandem `GASPAC-L-55` Dry Gas Seal).
- **Simulations**:
  - Real-time multi-shaft speed/thermo/antisurge physics across Design Cases 1–5 (`E07-00001`).
  - Live Dual Antisurge Maps `(Pd/Ps)` vs `√(hs/Ps)` showing SLL, SCL, and dynamic working point.
  - Full 426-row searchable Cause & Effect Matrix (`SOM896292590 Rev 6`) + 15 SIF `SIL 2` + `SIL 3` PNOZ-S4 hardware trips (`ES`, `ESN`, `ESN_VENT`, `SD`).
  - 10 Guided Operating & Fault Scenarios (`OP1–OP4`, `CH1–CH6`) with 3D Halo & Bezier Cause→Effect pulse links.

## Live Demo
Open `index.html` directly in any modern WebGL browser (offline iHMI/C&E works without internet; 3D WebGL uses Three.js `r128` via CDN fallback).
