![Version](https://img.shields.io/badge/version-1.0-blue)
![Status](https://img.shields.io/badge/status-hypothesis%20%2B%20protocol-orange)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-green)
![Project](https://img.shields.io/badge/project-EAV--MRCT--001-purple)
![No Data](https://img.shields.io/badge/data-none%20collected-red)

# Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time (TMRSCRT)

### One Earth, One Physical World, One Clock Time. Many Experienced Reality States.

**Earth Angel Ventures Theoretical Research Paper**

| Field | Entry |
| :--- | :--- |
| **Full Title** | Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time |
| **Short Title** | Multiple Realities on a Single Earth (TMRSCRT) |
| **Project ID** | EAV-MRCT-001 |
| **Manuscript ID** | EAV-MRCT-001-M01 |
| **Lead Author** | Angelica Pangan |
| **Research Owner** | Earth Angel Ventures |
| **Version** | 1.0 |
| **Date** | 24 October 2026 |
| **Status** | Hypothesis and Experimental Protocol Document |
| **Classification** | Research and Development - Theoretical Model with Experimental Protocols |

> **Position:** Two people can stand in the same place, witness the same event, and still perceive, remember, and anticipate it differently. Those differences are measurable as different observer reality states. They do not require different Earths. They do not require different physical worlds.

> **Consciousness frequency is defined, not vague:** It is Individual Alpha Frequency Fi in Hz, measured from resting EEG. The word "vibration" is not used as a scientific term in this paper.

> **Verse:** 1 Corinthians 10:31 | Philippians 2:13

---

## ABSTRACT

**Background.** Two people can stand in the same place, witness the same event, and still perceive, remember, and anticipate it differently. The working manuscript proposed that such differences may amount to multiple distinguishable realities on a single Earth, that what one observer experiences as the present another may experience as the future, and that an observer's consciousness frequency may govern this difference. Established science supports experienced time varying between people, but offers no evidence for a physical change in the present.

**Objective.** To convert the proposal into a complete, testable theory by (a) defining every term in measurable units, (b) writing a closed mathematical model, (c) specifying experiments with fixed sample sizes and quantitative decision rules, and (d) separating an experiential tier from a physical tier.

**Methods.** Six postulates. Consciousness frequency = Individual Alpha Frequency Fi (Hz) from resting EEG. Reality state = triple (Ii, Ki, Πi) = accessible information, prior model, predictive distribution. Difference between realities = Jensen-Shannon divergence Dij in bits. Frequency gate: Bi = b0 + κTi, where Ti = 1000/Fi ms. Four experiments: EXP-1 (280 analyzable), EXP-2 (60 observers), EXP-3 (130 analyzable), EXP-4 (90 sessions, equivalence bound ±1×10-12).

**Results.** None. No empirical data have been collected. All numerical values in figures are computed from stated equations and labelled as model-implied.

**Interpretation.** Experiential Tier (Postulates 1-5) predicts differences in present and future are fully explained by information, priors, and frequency-dependent resolution. Physical Tier (Postulate 6) asserts a clock-rate coupling to alpha frequency that current physics does not predict; it is stated so a null result can reject it decisively.

**Conclusion.** The theory is complete as a formal, preregistrable programme. Whether it is true is an empirical matter only the specified experiments can settle.

**Keywords:** multiple realities; single Earth; consciousness frequency; individual alpha frequency; temporal perception; subjective time; observer dependence; reality divergence; Jensen-Shannon divergence; temporal binding window; equivalence testing; falsification.

---

## RESEARCH SIGNIFICANCE

People who share a place and an event often hold different accounts of what is happening now and what will happen next. Cognitive science explains parts through attention, memory, prediction. Physics explains simultaneity differences between fast-moving frames. No existing framework puts these into one quantitative model linking a measurable neural rhythm, temporal resolution, and divergence between predictions.

Three gaps: (1) Evidence that alpha frequency determines temporal resolution is mixed, and no study ties it to anticipation or between-observer divergence. (2) No agreed metric for how different two observers' "realities" are while sharing one situation. (3) Claims that consciousness changes physical time have never been tested against a calibrated physical clock under blinded, preregistered, equivalence-based conditions.

If the experiential tier is supported, it supplies a measurable explanation for why observers in the same situation experience different presents and futures, with applications in communication, safety-critical teamwork, and education. If falsified, it removes an untested claim with a quantitative equivalence result. If the physical tier is rejected, as current physics predicts, the rejection is itself a rigorous null result.

---

## RESEARCH HIGHLIGHTS

1. **One Earth, One World, One Clock.** No additional Earths required. Multiple realities = multiple observer reality states Ri from same Ω.
2. **Consciousness Frequency Defined:** Fi = Individual Alpha Frequency in Hz, from resting eyes-closed EEG over O1, O2, Oz, PO3, PO4, POz.
3. **Present Is Operational:** Estimated present = t + δi, where δi = point of subjective simultaneity in timed judgment task.
4. **Frequency Gate:** Bi = b0 + κ·1000/Fi ms. Higher alpha = finer temporal resolution.
5. **Divergence Measured:** Dij = Jensen-Shannon divergence between predictions, in bits. 0 = identical, 1 = maximum.
6. **Information-Sufficiency Test:** Decides if divergence is fully explained by information + priors, or leaves unexplained remainder.
7. **Physical Claim Isolated:** Postulate 6 tested with co-located atomic clock against equivalence bound ±1×10-12.
8. **Every Outcome Classified:** Every experiment has fixed N, quantitative falsification rule, and classification for every possible outcome as supported, falsified, or not supported.

---

## EVIDENCE-STATUS LEGEND

Every claim carries one label:
- **ESTABLISHED:** Published, widely accepted, independently replicated. Background only.
- **CONTESTED:** Published with mixed/conflicting replication. Motivation only, re-tested here.
- **HYPOTHESIS:** Proposed here, not yet tested. Stated with quantitative falsification rule.
- **METHOD:** Definition / convention / procedure to make a hypothesis testable. Not a claim about nature.

---

## FORMAL MODEL - 6 POSTULATES

### P1. One Physical World, Many Reality States
One physical world Ω(x,t) on one Earth. Each observer holds reality state Ri(t) = ρi(Ω; Ci) = (Ii(t), Ki, Πi(t)). "Multiple realities" = different triples, not different worlds. **Test:** EXP-2.

### P2. Time As Experienced Construct
Estimated present differs from clock time by measurable, stable offset. Eq.1: t̂i(t) = t + δi(t). Eq.2: Ci(t) = [Pi, Mi, Ai, Fi]T. Eq.3: t̂i(t) = f(t, Ci(t), X(t)) + εi(t). δi = point of subjective simultaneity (PSS), ms. **Test:** EXP-1, H2.

### P3. Observer-Relative Present and Future
Event is possibility for one observer, already likely for another, due to information / priors. Eq.9: pi(e) = Pr[e in (t, t+H] | Ii, Ki], H=2s. Eq.10: Φi(t) = {e: pi(e) ≥ θ}, θ=0.50. Eq.11: Dij = ½ DKL(pi‖m) + ½ DKL(pj‖m), m=(pi+pj)/2, bits. Eq.7: Λi(e) = τe - τ̂e,i. **Test:** EXP-2, H3, H4.

### P4. Frequency-Gated Temporal Resolution
Binding window increases with alpha period, so higher Fi = finer resolution. Eq.5: Ti = 1000/Fi. Eq.6 (primary): Bi = b0 + κTi + λT Zi + εi. Eq.4 (secondary): δi = β0 + β1 Fi + βZ T Zi + εi. Zi = [Pi, Mi, Ai, Si, Qi, agei], k=6. Worked example: At 8 Hz, Ti=125ms, events at 10ms and 110ms fall in same window and bind. At 12 Hz, Ti=83.3ms, same events fall in different windows and resolve as separate. **Test:** EXP-1 H5, EXP-3 H6.

### P5. Shared Location Does Not Guarantee Identical Experience
All divergence explained by information + priors; none remains once matched. Eq.12: Dij = ζ0 + ζ1 ΔIij + ζ2 ΔKij + uij, prediction ζ0=0 (±0.03 bits) and ζ1>0. ΔI = cues one observer has that other lacks. ΔK = 1 if different training, 0 otherwise. **Test:** EXP-2 H1, H3.

### P6. Physical Coupling (Physical Tier)
Strongest reading: consciousness frequency changes physical present. If so, calibrated clock with observer should run at rate depending on Fi. Eq.14: y = (ν-ν0)/ν0 = γ(F - Fref), Fref=10 Hz. Null γ=0. Reference scale ESTABLISHED Eq.R1: Δτ/τ ≈ -v²/(2c²) - ΔΦ/c². Largest ordinary rate difference on Earth ~1.2×10-12 (rotation). Hence test bound 1×10-12. **Test:** EXP-4 H7. A priori expectation is null.

### Extended Mechanisms
**11.1 Group Shared Present:** t̂G = Σ wi t̂i / Σ wi, wi=1/σi². More consistent observers count more. Hypothesis, no weight in primary decisions.
**11.2 Information-Sufficiency Decomposition:** Eq.12 isolates residual ζ0. If ζ0 >0.03 bits reliably, unexplained experiential divergence found — triggers follow-up, does NOT support Physical Tier.
**11.3 State Modulators:** Arousal, emotion, fatigue enter only via Zi (Si sleep, Qi stress, Ai attention) and exclusion (Karolinska sleepiness ≥8). No separate mechanism.
**11.4 Boundary:** Model does NOT assert: (a) more than one Earth exists; (b) physical time does not exist; (c) consciousness = alpha frequency; (d) other vibration has role; (e) observers can perceive events before they happen.

---

## VISUAL BLUEPRINTS

1. **Figure 1 - Emblem:** One Earth, One Clock Time, Many Experienced Reality States. Central sphere = single Earth Ω. Outer clock = one physical time t. Six nodes R1-R6 = reality states, joined by ρi.
2. **Figure 2 - Formula Basis Chart:** All equations Eq.1-16 + R1 in one panel.
3. **Figure 3 - Core Structure:** Ω → Ci → ρi → Ri. Dij computed only from Ri.
4. **Figure 4 - Operator Pipeline:** X(t) + Ci(t) → frequency gate → Bi, t̂i, Λi, pi. Confound Zi via dashed path.
5. **Figure 5 - Frequency Gate:** Two events 100ms apart at 8 Hz vs 12 Hz. Model illustration, not recording.
6. **Figure 6 - Model Response Curves:** B vs F, and EXP-3 contrast (+2 Hz vs -2 Hz). Computed from Eq.6, b0=0. No data.
7. **Figure 7 - Experimental System Architecture:** EXP-1 to EXP-4. One sync hub, photodiode + audio loopback. EXP-4 arm independent, no electronics in observer room.
8. **Figure 8 - Power Blueprint:** EXP-1 needs 265 for association r=0.20, power 0.90; 273 for equivalence. Planned 280 satisfies both (0.92, 0.91).
9. **Figure 9 - Decision Logic:** EXP-1, EXP-3, EXP-4 chains. Every result ends as supported / falsified / uninformative / not supported.
10. **Figure 10 - Programme Schedule:** 26 months. EXP-3 begins only after EXP-1 meets decision rule. Replication follows every supported result.

---

## EXPERIMENTS AND FALSIFICATION

| ID | Test | N | Primary Decision |
| :--- | :--- | :--- | :--- |
| **EXP-1** Alpha & Temporal Resolution | P2, P4 | 280 analyzable | Association + Equivalence, α=0.05, power 0.90 |
| **EXP-2** Information-Asymmetry Divergence | P1, P3, P5 | 60 observers | Information-sufficiency ζ0 = 0 ±0.03 bits |
| **EXP-3** Sham-Controlled Causal Modulation | P4 | 130 analyzable | Causal shift in Bi, sham-controlled |
| **EXP-4** Physical Chronometer Test | P6 | 90 sessions | Equivalence bound ±1×10-12 on γ |

All experiments: preregistered, analysis code locked + hashed, Holm correction for secondary tests, complete-case primary + multiple imputation sensitivity, open data except identifying info.

**Independent Replication:** Every supported H1-H7 replicated by independent lab, different EEG amplifiers, different pool, different clocks/building for EXP-4. If replication fails, original reported as not replicated.

---

## DIFFERENCES FROM EXISTING FRAMEWORKS

| Factor | Standard Models | TMRSCRT Position |
| :--- | :--- | :--- |
| **Worlds** | One world, one experience assumed, or many worlds | One world Ω, many reality states Ri |
| **Time** | Clock time = felt time | Clock t ≠ felt t̂i = t + δi |
| **Consciousness frequency** | Vague / metaphorical | Defined: Fi = IAF, Hz, EEG |
| **Reality difference** | Qualitative | Quantitative: Dij in bits, 0-1 |
| **Physical time claim** | Not tested / asserted | Isolated as P6, tested vs atomic clock |
| **Falsifiability** | Often interpretive | Fixed N, decision logic for every outcome |

**Novelty claim:** To be verified by literature search in Section 13.3. Claimed combination: (a) measured alpha, (b) quantitative binding window, (c) information-theoretic divergence, (d) equivalence-tested physical clock in one model. Not asserted as established until search is recorded.

---

## RESULTS

No data have been collected. No experiment started. No ethics approval obtained. No statistic reported comes from observations. Numbers in figures are computed from equations and design assumptions.

---

## TRANSPARENCY

References [1]-[3] carried from original manuscript. All other references marked "Recalled; to be verified" — must be checked against publisher/database before submission. References cited for background/method only; none verifies postulates.

## HOW TO CITE

> Pangan, A. (2026). Theory of Multiple Realities on a Single Earth and Consciousness-Relative Time. Earth Angel Ventures. EAV-MRCT-001-M01. v1.0.

## FINAL DECLARATION

Project ID: EAV-MRCT-001. Principal Investigator: Angelica Pangan. Organization: Earth Angel Ventures. Version 1.0.

This manuscript is a theoretical proposal. No data, results, or approvals are claimed that do not exist. Experiential Tier and Physical Tier are separate. No evidence for Physical Tier exists. Paper does not claim more than one Earth exists, physical time does not exist, or any person can perceive events before they occur.

**Earth Angel Ventures Research Standard:** The standard is not how extraordinary a claim sounds, but how reliably the evidence supports it and how well others can examine, challenge, reproduce, and build upon the work.

## More Files
- [COMPANY.md](COMPANY.md) | [RESEARCHER.md](RESEARCHER.md) | [LEGAL-ETHICS.md](LEGAL-ETHICS.md) | [CONTACT.md](CONTACT.md)
- [CONTRIBUTING.md](CONTRIBUTING.md) | [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | [SECURITY.md](SECURITY.md)
- [FUNDING.md](FUNDING.md) | [ROADMAP.md](ROADMAP.md) | [FAQ.md](FAQ.md) | [GLOSSARY.md](GLOSSARY.md) | [PRESS-KIT.md](PRESS-KIT.md)
- [CITATION.cff](CITATION.cff) | [CHANGELOG.md](CHANGELOG.md)
- [Protocols](protocols/) | [Figures](paper/figures/README.md) | [Data](data/README.md) | [Analysis](analysis/README.md)

## Protocols
- [EXP-1 Alpha & Temporal Resolution](protocols/EXP-1-alpha-temporal-resolution.md) — N=280
- [EXP-2 Information Divergence](protocols/EXP-2-information-divergence.md) — N=60
- [EXP-3 Causal Modulation](protocols/EXP-3-causal-modulation.md) — N=130
- [EXP-4 Physical Chronometer](protocols/EXP-4-physical-chronometer.md) — N=90 sessions, ±1×10-12

## Figures
- [Figure-01 Emblem](paper/figures/Figure-01-Emblem.md) | [Figure-02 Formula Basis](paper/figures/Figure-02-Formula-Basis.md) | [Figure-03 Core Structure](paper/figures/Figure-03-Core-Structure.md) | [Figure-04 Operator Pipeline](paper/figures/Figure-04-Operator-Pipeline.md) | [Figure-05 Frequency Gate](paper/figures/Figure-05-Frequency-Gate.md)
- [Figure-06 Model Curves](paper/figures/Figure-06-Model-Curves.md) | [Figure-07 System Architecture](paper/figures/Figure-07-System-Architecture.md) | [Figure-08 Power Blueprint](paper/figures/Figure-08-Power-Blueprint.md) | [Figure-09 Decision Logic](paper/figures/Figure-09-Decision-Logic.md) | [Figure-10 Schedule](paper/figures/Figure-10-Schedule.md)
