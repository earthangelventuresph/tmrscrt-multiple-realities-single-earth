# EXP-3. Sham-Controlled Causal Modulation of Alpha Frequency
**Project:** EAV-MRCT-001
**Title:** Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time (TMRSCRT)
**Manuscript ID:** EAV-MRCT-001-M01
**Version:** 1.0 | Date: 24 October 2026
**Lead Author:** Angelica Pangan | Earth Angel Ventures
**Tests:** Postulate 4
**Hypothesis:** H6 (Increasing Fi causes narrower Bi)
**Status:** Protocol Only. No data. Begins ONLY after EXP-1 has met its decision rule. Preregistration required.
**Verse:** 1 Corinthians 10:31 | Philippians 2:13

## 1. Claim — In Plain Language
If we causally shift your alpha frequency up, your binding window should narrow. If we shift it down, your window should widen. If flicker does nothing to Bi beyond sham, the causal claim fails.

## 2. Formal Prediction
Eq.5: Ti = 1000 / Fi
Eq.6: Bi = b0 + κ Ti + λT Zi + εi
Contrast: Bi(+2 Hz) − Bi(−2 Hz) < 0. Contrast always negative — signed prediction of Postulate 4 (Figure 6b).
ΔFi = Change in Fi after flicker vs baseline, Hz.

## 3. Falsification Threshold — Decided In Advance
FALSIFIED if 90% CI for contrast lies inside equivalence bound (see manuscript §12.7).
SUPPORTED if contrast < 0 and 90% CI excludes 0.
Otherwise: NOT SUPPORTED.
P4 causal claim rejected if falsified.

## 4. Design
Sham-controlled, within-subjects crossover.
N = 130 analyzable participants. Recruit ~150 for attrition.
Conditions: +2 Hz flicker, −2 Hz flicker, sham flicker. Order randomized, washout between conditions.
Begins ONLY after EXP-1 meets decision rule (Figure 9).

## 5. Measures — Exact Definitions
- ΔFi: Change in Fi vs baseline, Hz, from resting EEG post-stimulation.
- Bi: TOJ JND, ms, pre/post each condition.
- δi: PSS, ms, pre/post each condition, secondary.
- Adverse events: Flicker discomfort, headache, dizziness, recorded per condition.

## 6. Procedure — Step By Step
1. Consent. Include flicker risk: discomfort, headache, photosensitivity screening. Exclude photosensitive epilepsy, migraine history.
2. Baseline. Resting EEG + TOJ. Record Fi baseline, Bi baseline, δi baseline.
3. Condition A. Flicker stimulation targeting +2 Hz shift. Duration predefined in preregistration. Post EEG + TOJ.
4. Washout. Predefined duration. Rest, no stimulation.
5. Condition B. Flicker stimulation targeting −2 Hz shift. Post EEG + TOJ.
6. Washout. Predefined duration.
7. Condition C. Sham flicker. Same visual flicker appearance, no entrainment frequency. Post EEG + TOJ.
8. Order randomized across participants. Counterbalanced.
9. Experimenter blind to condition order. Participant blind to hypothesis, told "visual stimulation".
10. Debrief. Explain hypothesis, conditions, results summary later.

## 7. Sample Size + Power
N = 130 analyzable. Power 0.90, α = 0.05, for paired dz at stated effect (see §12.3). Recruit ~150 for attrition.
Fixed N. No optional stopping.

## 8. Blinding
Experimenter blind to condition order. Participant blind to hypothesis. Analyst blind to condition labels until locked script runs.

## 9. Frozen Analysis Plan — Locked Before Collection
Primary: Paired contrast Bi(+2) − Bi(−2), controlling for ΔFi achieved. Report dz, 90% CI.
Decision chain (Figure 9): If contrast < 0 and CI excludes 0 → SUPPORTED. If 90% CI inside equivalence bound → FALSIFIED. Else NOT SUPPORTED.
Sensitivity: Per-protocol (only participants with |ΔFi| ≥ threshold) + intention-to-treat (all participants).
Secondary: δi change, adverse events, Holm correction.
Missing: Complete-case primary, multiple imputation sensitivity.

## 10. Confounds
Flicker discomfort, fatigue, order effects — counterbalanced, washout, sham control.
Time of day held constant per participant where possible.

## 11. Safety — Stop Rule
Exclude: Photosensitive epilepsy, migraine history, neurological condition, psychoactive medication.
Stop rule: If participant reports discomfort, dizziness, headache, visual disturbance, stop stimulation immediately, record adverse event, offer withdrawal, provide care.
Flicker safety screening mandatory before any stimulation.

## 12. Data Availability
EEG, TOJ, stimulation logs in `data/EXP-3/` after collection.
No data yet. Folder empty in v1.0.
Codebook with every column, unit, missing code -999.

## 13. Ethics / Safety
Ethics approval REQUIRED. Status: NOT YET APPLIED.
Consent includes flicker risk. Voluntary withdrawal. Pseudonymized.
