# Figure 4 — Operator Pipeline
**File:** Figure-04-Operator-Pipeline.png
**Title:** Frequency gate → t̂i, Bi, Λi, pi
**Project:** EAV-MRCT-001 | TMRSCRT v1.0

## Flow — left to right, accurate
1. Inputs: Environmental information X(t) + Observer state Ci(t)
2. Frequency gate: Fi → Ti = 1000 / Fi → Bi
3. Temporal estimator → 3 outputs:
      - Estimated present: t̂i = t + δi
      - Resolution: Bi
      - Future quantities: Λi and pi
4. Dashed path: Confound vector Zi always enters estimator
      - Zi = [Pi, Mi, Ai, Si, Qi, agei], k = 6

## Caption
Figure 4. Operator pipeline for one observer. Environmental information X(t) and the observer state Ci(t) enter the frequency gate, which converts alpha frequency Fi into the alpha period Ti and the binding window Bi. The temporal estimator then produces three outputs: the estimated present t̂i = t + δi, the resolution Bi, and the future quantities Λi and pi. The confound vector Zi enters by the dashed path and is always included in the statistical models, so it cannot be mistaken for an effect of frequency.
