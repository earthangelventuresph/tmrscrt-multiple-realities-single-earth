# EXP-2. Information-Asymmetry Divergence
**Project:** EAV-MRCT-001
**Tests:** P1, P3, P5 | Hypotheses: H1 (ζ0=0), H3 (ζ1>0), H4 (Φi predicts anticipation)
**Status:** Protocol Only. No data. Preregistration required.

## 1. Claim
Dij fully explained by ΔI + ΔK. No residual when information + priors matched. Φi predicts anticipation Λi.

## 2. Design
Experimental, paired observers, N=60 observers (30 pairs). Same location ≤2m, same physical event stream, manipulated information.

## 3. Measures
- pi(e): Probability assigned to each candidate event in next H=2s, sums to 1.
- Φi: {e: pi(e) ≥0.50}
- Dij: Jensen-Shannon divergence, bits, 0-1, base 2.
- ΔIij: # task-relevant cues known to one, not other.
- ΔKij: 0 same training, 1 different training.
- Λi(e): τe - τ̂e,i, ms. Positive = early anticipation.
- τe: True onset on physical clock.

## 4. Procedure
1. Consent, training (same vs different training per pair, randomized).
2. Pairs sit ≤2m apart, view same event stream.
3. Information manipulation: One observer gets extra cue(s) per block (0, 1, 2, 3 cues).
4. Each block: Observers assign probabilities to upcoming events, then respond / anticipate.
5. Repeat across blocks with counterbalanced cue levels.

## 5. Sample Size
Planned 60 observers / 30 pairs. Power for ζ0 equivalence ±0.03 bits and ζ1>0 at stated effect, α=0.05, power 0.90 (see manuscript §12.2). Fixed N, no optional stopping.

## 6. Analysis - Frozen
Primary: Fit Eq.12: Dij = ζ0 + ζ1 ΔIij + ζ2 ΔKij + uij.
- H1: Test ζ0 equivalence to 0 within ±0.03 bits via 90% CI.
- H3: Test ζ1 >0.
- H4: Test anticipation larger for events in Φi vs outside, paired test.
Decision: If 90% CI for ζ0 inside ±0.03 AND ζ1>0 → Supported. If ζ0 CI excludes 0 and >0.03 → Unexplained divergence found → Follow-up study triggered, does NOT support Physical Tier.

## 7. Falsification
FALSIFIED if ζ0 reliably >0.03 bits (CI excludes 0 and bound) OR ζ1 ≤0. P5 rejected as stated.

## 8. Controls
Same location, same stimuli, same timing. Counterbalanced cue order. Experimenter blind to pair assignment.

## 9. Data
Trial-level probabilities, cue logs, anticipation times in data/EXP-2/. No data yet.

## 10. Ethics
Ethics approval REQUIRED. Consent, withdrawal, pseudonymized. No deception about risks.
