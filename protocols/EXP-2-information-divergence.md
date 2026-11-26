# EXP-2. Information-Asymmetry Divergence
**Project:** EAV-MRCT-001
**Title:** Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time (TMRSCRT)
**Manuscript ID:** EAV-MRCT-001-M01
**Version:** 1.0 | Date: 24 October 2026
**Lead Author:** Angelica Pangan | Earth Angel Ventures
**Tests:** Postulate 1, Postulate 3, Postulate 5
**Hypotheses:** H1 (ζ0 = 0), H3 (ζ1 > 0), H4 (Φi predicts anticipation)
**Status:** Protocol Only. No data. Preregistration required.
**Verse:** 1 Corinthians 10:31 | Philippians 2:13

## 1. Claim — In Plain Language
Two observers in the same place have different realities because they have different information and different priors. Give them the same information and same training, and their realities should converge. No leftover mystery divergence should remain.

## 2. Formal Prediction
Eq.8: Ri(t) = ρi(Ω; Ci) = (Ii(t), Ki, Πi(t))
Eq.9: pi(e) = Pr[e in (t, t + H] | Ii(t), Ki], H = 2 s
Eq.10: Φi(t) = {e : pi(e) ≥ θ}, θ = 0.50
Eq.11: Dij = ½ DKL(pi ‖ m) + ½ DKL(pj ‖ m), m = (pi + pj) / 2, bits, 0-1
Eq.7: Λi(e) = τe − τ̂e,i
Eq.12: Dij = ζ0 + ζ1 ΔIij + ζ2 ΔKij + uij
Prediction: ζ0 = 0 within ±0.03 bits, ζ1 > 0.

## 3. Falsification Threshold — Decided In Advance
FALSIFIED if ζ0 is reliably > 0.03 bits (90% CI excludes 0 and bound) OR ζ1 ≤ 0.
If ζ0 > 0.03 bits reliably, unexplained experiential divergence is found. This triggers follow-up study. It does NOT support Physical Tier.
SUPPORTED if 90% CI for ζ0 inside ±0.03 bits AND ζ1 > 0 AND H4 supported.
Otherwise: NOT SUPPORTED.

## 4. Design
Experimental, paired observers.
N = 60 observers = 30 pairs.
Same location ≤ 2 m apart. Same physical event stream. Manipulated information.
Fixed N. No optional stopping.

## 5. Measures — Exact Definitions
- pi(e): Probability observer i assigns to event e in next H = 2 s. Sums to 1 over candidate set.
- Φi: Represented-future set, events with pi(e) ≥ 0.50.
- Dij: Jensen-Shannon divergence, bits, base 2, range 0-1. 0 = identical, 1 = maximum.
- ΔIij: Information difference. Number of task-relevant cues known to one observer of the pair and not to the other. Unit: cues.
- ΔKij: Prior difference. 0 if both had same training, 1 if different training.
- Λi(e): Anticipation lead. τe − τ̂e,i. Unit: ms. Positive = early anticipation.
- τe: True onset time of event e on physical clock. Unit: s.
- τ̂e,i: Onset time predicted by observer i. Unit: s.

## 6. Procedure — Step By Step
1. Consent. Explain tasks, probabilities, anticipation responses, withdrawal anytime.
2. Training. Pairs randomized to same training vs different training. ΔK recorded.
3. Pair seating. Pairs sit ≤ 2 m apart, view same event stream, same stimuli, same timing.
4. Information manipulation. One observer gets extra cue(s) per block. Cue levels: 0, 1, 2, 3 cues. Counterbalanced order.
5. Each block: Observers assign probabilities to upcoming events. Record pi(e) for each candidate event.
6. Each block: Observers respond / anticipate. Record τ̂e,i, Λi.
7. Repeat across blocks with counterbalanced cue levels.
8. Debrief. Explain hypothesis.

## 7. Sample Size + Power
Planned: 60 observers / 30 pairs.
Power for ζ0 equivalence ±0.03 bits and ζ1 > 0 at stated effect, α = 0.05, power = 0.90. See manuscript §12.2.
Fixed N. No optional stopping.

## 8. Blinding
Experimenter blind to pair assignment where possible.
Analyst blind to pair IDs until locked script runs.
Cue assignment recorded by separate log, not visible to analyst until analysis.

## 9. Frozen Analysis Plan — Locked Before Collection
Primary: Fit Eq.12: Dij = ζ0 + ζ1 ΔIij + ζ2 ΔKij + uij.
- H1: Test ζ0 equivalence to 0 within ±0.03 bits via 90% CI.
- H3: Test ζ1 > 0.
- H4: Test anticipation larger for events in Φi vs outside Φi, paired test.
Decision: If 90% CI for ζ0 inside ±0.03 AND ζ1 > 0 → SUPPORTED. If ζ0 CI excludes 0 and > 0.03 → UNEXPLAINED DIVERGENCE → Follow-up triggered, NOT Physical Tier support.
Secondary: Holm correction.
Missing: Complete-case primary, multiple imputation sensitivity.

## 10. Controls
Same location, same stimuli, same timing. Counterbalanced cue order. Training randomized. Pair as random effect in model.

## 11. Data Availability
Trial-level probabilities, cue logs, anticipation times in `data/EXP-2/` after collection.
No data yet. Folder empty in v1.0.
Codebook with every column, unit, missing code -999.

## 12. Ethics / Safety
Ethics approval REQUIRED. Status: NOT YET APPLIED.
Consent, withdrawal, pseudonymized. No deception about risks.
No physical risk. No deception beyond withholding hypothesis, disclosed at debrief.
