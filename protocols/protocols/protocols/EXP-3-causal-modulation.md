# EXP-3. Sham-Controlled Causal Modulation of Alpha Frequency
**Project:** EAV-MRCT-001
**Tests:** P4 | Hypothesis: H6 (Increasing Fi causes narrower Bi)
**Status:** Protocol Only. No data. Begins ONLY after EXP-1 meets decision rule. Preregistration required.

## 1. Claim
Causal: Manipulating Fi shifts Bi. +2 Hz shift → Bi decreases. -2 Hz → Bi increases. Contrast always negative (Figure 6b).

## 2. Design
Sham-controlled, within-subjects crossover, N=130 analyzable. Conditions: +2 Hz flicker, -2 Hz flicker, sham flicker. Order randomized, washout.

## 3. Measures
- ΔFi: Change in Fi vs baseline, Hz, from resting EEG post-stimulation.
- Bi: TOJ JND, ms, pre/post each condition.
- δi: PSS secondary.

## 4. Procedure
1. Baseline EEG + TOJ.
2. Condition A: Flicker stimulation targeting +2 Hz shift. Post EEG + TOJ.
3. Washout (predefined duration).
4. Condition B: -2 Hz flicker. Post EEG + TOJ.
5. Condition C: Sham flicker (same visual flicker, no entrainment frequency). Post EEG + TOJ.
6. Experimenter blind to condition order. Participant blind to hypothesis (told "visual stimulation").

## 5. Sample Size
130 analyzable. Power 0.90, α=0.05, for paired dz at stated effect (see §12.3). Recruit ~150 for attrition.

## 6. Analysis - Frozen
Primary: Paired contrast Bi(+2) - Bi(-2), controlling for ΔFi achieved. Report dz, 90% CI.
Decision chain (Figure 9): If contrast <0 and CI excludes 0 → Supported. If 90% CI inside equivalence bound → Falsified. Else Not supported.
Sensitivity: Per-protocol (only participants with |ΔFi| ≥ threshold) + intention-to-treat.

## 7. Falsification
FALSIFIED if 90% CI for contrast lies inside equivalence bound (see manuscript §12.7). P4 causal claim rejected.

## 8. Confounds
Flicker discomfort, fatigue, order effects — counterbalanced, washout, sham control. Exclude if flicker induces adverse symptoms.

## 9. Data
EEG, TOJ, stimulation logs in data/EXP-3/. No data yet.

## 10. Ethics / Safety
Ethics approval REQUIRED. Flicker safety: Exclude photosensitive epilepsy, migraine history. Stop rule for discomfort. Consent includes flicker risk.
