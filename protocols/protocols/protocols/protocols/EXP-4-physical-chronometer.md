# EXP-4. Physical Chronometer Test
**Project:** EAV-MRCT-001
**Tests:** P6 Physical Tier | Hypothesis: H7 (γ ≠ 0)
**Status:** Protocol Only. No data. Preregistration required. A priori expectation is NULL.

## 1. Claim
If consciousness frequency changes physical time, co-located atomic clock rate y = γ(F - Fref), Fref=10 Hz, should depend on observer Fi. Current physics predicts γ=0.

## 2. Design
Blinded, co-located clock measurement, N=90 sessions. Observer with known Fi sits in room with calibrated clock. No electronics carried into observer room.

## 3. Measures
- Fi: Resting EEG IAF, Hz, measured outside clock room / before session.
- y: Fractional frequency deviation (ν-ν0)/ν0, dimensionless.
- Clock: Atomic / optical clock, UTC-traceable, Allan deviation σy(τ) reported.
- Reference scale: Rotation-induced difference ~1.2×10-12, 1m height ~1.1×10-16 (Eq.R1).

## 4. Procedure
1. Measure Fi for participant (resting EEG).
2. Participant enters observer room with clock. Session duration predefined (e.g. 30 min).
3. Clock frequency recorded continuously, blinded to Fi.
4. Control sessions: No observer, empty room, same duration.
5. Repeat across Fi range: low Fi (<9 Hz), mid (9-11 Hz), high (>11 Hz), 30 sessions each = 90 total.
6. Analyst blind to Fi until primary analysis locked.

## 5. Sample Size
90 sessions. Power to reject |γ| corresponding to |y| >1×10-12 at α=0.05, power 0.90. Equivalence bound ±1×10-12.

## 6. Analysis - Frozen
Primary: Fit y = γ(F - Fref) + covariates (temperature, pressure, vibration, clock drift).
Decision: If 90% CI for γ lies inside bound equivalent to ±1×10-12 → Falsified / Equivalence supported (no coupling above bound). If CI excludes 0 and bound → Supported (major finding, requires replication + reconciliation with physics). Else Not supported.

## 7. Falsification
FALSIFIED if 90% CI inside ±1×10-12. P6 rejected at stated sensitivity. Smaller effect <1×10-12 would NOT be detected — stated limitation.

## 8. Controls
Temperature, pressure, vibration, magnetic field logged. Empty-room controls. Different clocks/building for replication. No electronics in observer room.

## 9. Data
Clock logs, Fi, environmental logs, locked script in data/EXP-4/. No data yet.

## 10. Ethics / Safety
Ethics approval REQUIRED if human observers. No invasive procedure. Clock safety: standard lab safety. No claim that participant can affect clock — participant told study tests clock stability.
