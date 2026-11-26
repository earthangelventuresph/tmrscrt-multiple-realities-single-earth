# EXP-4. Physical Chronometer Test
**Project:** EAV-MRCT-001
**Title:** Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time (TMRSCRT)
**Manuscript ID:** EAV-MRCT-001-M01
**Version:** 1.0 | Date: 24 October 2026
**Lead Author:** Angelica Pangan | Earth Angel Ventures
**Tests:** Postulate 6 — Physical Tier
**Hypothesis:** H7 (γ ≠ 0)
**Status:** Protocol Only. No data. Preregistration required. A priori expectation is NULL.
**Verse:** 1 Corinthians 10:31 | Philippians 2:13

## 1. Claim — In Plain Language
Strongest reading: If consciousness frequency changes physical time, a calibrated clock sitting with an observer should run at a rate that depends on that observer's alpha frequency. Current physics predicts it will NOT. This experiment tests that strongest claim directly, so a null result can reject it decisively.

## 2. Formal Prediction
Eq.14: y = (ν − ν0) / ν0 = γ (F − Fref), Fref = 10 Hz.
y = Fractional frequency deviation, dimensionless.
γ = Physical coupling coefficient, Hz-1. Null γ = 0.
Reference scale ESTABLISHED Eq.R1: Δτ / τ ≈ −v² / (2c²) − ΔΦ / c².
Largest ordinary rate difference on Earth ~1.2×10-12 (rotation). 1 m height ~1.1×10-16. Hence test bound 1×10-12.

## 3. Falsification Threshold — Decided In Advance
FALSIFIED if 90% CI for γ lies inside bound equivalent to ±1×10-12.
SUPPORTED if 90% CI excludes 0 AND excludes bound. This would be a major finding, requires replication + reconciliation with physics. No such claim is made in this paper.
Otherwise: NOT SUPPORTED.
Limitation: Smaller effect < 1×10-12 would NOT be detected. Stated limitation.

## 4. Design
Blinded, co-located clock measurement.
N = 90 sessions.
Groups: 30 sessions low Fi (< 9 Hz), 30 sessions mid Fi (9-11 Hz), 30 sessions high Fi (> 11 Hz).
Control: Empty-room sessions, same duration, no observer.
No electronics carried into observer room.

## 5. Measures — Exact Definitions
- Fi: Resting EEG IAF, Hz, measured outside clock room / before session. Peak 7-14 Hz, O1, O2, Oz, PO3, PO4, POz.
- y: Fractional frequency deviation (ν − ν0) / ν0, dimensionless.
- Clock: Atomic / optical clock, UTC-traceable. Allan deviation σy(τ) reported.
- Environment: Temperature, pressure, vibration, magnetic field, logged per session.
- Clock drift: Recorded, included as covariate.

## 6. Procedure — Step By Step
1. Measure Fi for participant. Resting EEG, eyes-closed, 5 min, outside clock room.
2. Participant enters observer room with clock. Session duration predefined, e.g. 30 min, fixed in preregistration.
3. Clock frequency recorded continuously. Analyst blind to Fi.
4. Control sessions: No observer, empty room, same duration, same clock setup.
5. Repeat across Fi range: low, mid, high, 30 sessions each = 90 total.
6. Environmental logs recorded continuously: temperature, pressure, vibration, magnetic field.
7. Analyst blind to Fi until primary analysis locked.
8. Replication: Different clocks, different building, same protocol, same N.

## 7. Sample Size + Power
N = 90 sessions. Power to reject |γ| corresponding to |y| > 1×10-12 at α = 0.05, power = 0.90. Equivalence bound ±1×10-12.
Fixed N. No optional stopping.

## 8. Blinding
Clock operator blind to Fi. Participant told study tests clock stability, not told hypothesis that clock might respond to Fi (withheld, disclosed at debrief, approved by ethics). Analyst blind to Fi until locked script runs.

## 9. Frozen Analysis Plan — Locked Before Collection
Primary: Fit y = γ (F − Fref) + covariates (temperature, pressure, vibration, clock drift).
Report γ, 90% CI, 95% CI.
Decision: If 90% CI for γ inside ±1×10-12 → FALSIFIED / EQUIVALENCE SUPPORTED (no coupling above bound). If CI excludes 0 and bound → SUPPORTED (major finding, requires replication). Else NOT SUPPORTED.
Secondary: Empty-room vs observer comparison, Holm correction.
Missing: Complete-case primary, multiple imputation sensitivity.

## 10. Controls
Temperature, pressure, vibration, magnetic field logged. Empty-room controls. Different clocks/building for replication. No electronics in observer room. Clock drift corrected via covariates + control sessions.

## 11. Data Availability
Clock logs, Fi, environmental logs, locked script in `data/EXP-4/` after collection.
No data yet. Folder empty in v1.0.
Codebook with every column, unit, missing code -999.

## 12. Ethics / Safety
Ethics approval REQUIRED if human observers. Status: NOT YET APPLIED.
No invasive procedure. No claim participant can affect clock — participant told study tests clock stability.
Clock safety: Standard lab safety. No electronics in observer room.
Consent, voluntary withdrawal, pseudonymized.
