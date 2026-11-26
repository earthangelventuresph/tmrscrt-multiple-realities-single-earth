# EXP-1. Alpha Frequency and Temporal Resolution
**Project:** EAV-MRCT-001
**Tests:** P2, P4 | Hypotheses: H2 (stable δi), H5 (κ > 0)
**Status:** Protocol Only. No data. Preregistration required. Analysis code locked + hashed before collection.

## 1. Claim
Higher Fi = narrower binding window Bi = b0 + κTi, Ti=1000/Fi. δi is stable trait.

## 2. Design
Observational, cross-sectional, N=280 analyzable participants. One session EEG + TOJ tasks.

## 3. Measures
- Fi: Peak 7-14 Hz, resting eyes-closed EEG, occipito-parietal O1, O2, Oz, PO3, PO4, POz, Hz.
- Bi: JND (SD of fitted cumulative Gaussian) of audiovisual TOJ, ms.
- δi: PSS of audiovisual TOJ, ms.
- Confounds Zi: Pi (visual acuity + auditory threshold z), Mi (digit span), Ai (PVT mean reciprocal RT), Si (PSQI), Qi (PSS-10), age. k=6.
- Secondary: Duration reproduction, test-retest δi (subset, 2nd session), group shared present S3.

## 4. Procedure
1. Consent, screening, Karolinska sleepiness — exclude if ≥8.
2. Resting EEG eyes-closed 5 min.
3. Audiovisual TOJ: flash + beep at varied SOA, report order. Fit cumulative Gaussian → PSS + JND.
4. Duration reproduction task.
5. Questionnaires: PSQI, PSS-10.
6. Test-retest subset returns within 7 days, same time of day.

## 5. Sample Size
Eq.16 Fisher z, k=6, α=0.05, power 0.90. Association r=0.20 needs 265. Equivalence bound 0.20 needs 273. Planned 280 analyzable (power 0.92 / 0.91). Recruit ~320 for attrition / EEG quality.

## 6. Analysis - Frozen
Primary: Partial correlation Fi vs Bi controlling Zi. Report r, 90% CI, 95% CI.
Decision chain (Figure 9):
- If CI excludes 0 and κ>0 → Supported for H5.
- If 90% CI inside ±0.20 → Falsified / Equivalence supported (no effect ≥0.20).
- Else → Not supported / Uninformative.
Secondary H2: ICC (two-way mixed, absolute agreement) for δi test-retest. Holm correction.
S3: Precision-weighted mean δi closer to 0 than unweighted in ≥50% bootstrap resamples of groups of 6.

## 7. Falsification
FALSIFIED if 90% CI for partial r lies inside ±0.20. H5 rejected.

## 8. Confounds / Exclusions
Sleepiness ≥8, neurological condition, psychoactive medication, hearing/vision impairment uncorrected, EEG quality < threshold (predefined). Sensitivity: multiple imputation.

## 9. Blinding
Analyst blind to participant IDs. EEG preprocessing blind to TOJ scores until locked script runs.

## 10. Data
Raw EEG, TOJ trials, questionnaires, locked script in data/EXP-1/ after collection. No data yet.

## 11. Ethics / Safety
Ethics approval REQUIRED before recruitment. Informed consent, voluntary withdrawal, pseudonymized. EEG non-invasive. No deception beyond withholding hypothesis, disclosed at debrief.
