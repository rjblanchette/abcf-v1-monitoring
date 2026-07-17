# ABCF-v1 Corpus Layer 1 — Research Positioning Report

```
[RJ-WE v1.0]
AGENT         : Recognizer (Rocketman partially active)
LAYER         : Recognition
MODE          : Work
DOCUMENT ID   : 2026-07-17_Layer1_Run3_SCOPE-ALL
LIFECYCLE     : Stage 01 — InterpretationArtifact
OUTPUT CLASS  : Classification / Structural Evaluation
AUTHORITY     : NOT_AUTHORIZED
RUN DATE      : 2026-07-17
PROMPT        : ABCF-v1_Corpus_Layer1_v1.1
RUN SCOPE     : ALL
```

---

## 0. Method note

Corpus verified by fresh tarball pull from `main` immediately prior to this run. Executed over the full `briefs/` directory: **ten briefs, Run 1–Run 10** (2026-06-15 to 2026-07-17).

**Corpus integrity flag:** `2026-07-17_Brief_Run10.md` is present and committed on `main`. This run was not reflected as committed in prior session state — it exists on the repo as of this pull and is included in scope. Noting this once, factually, per the corpus-integrity precondition; no further action implied.

Three prompt-version boundaries fall inside this scope:
- Runs 1–2: Tier 1 v1.2–v1.3(unconf.)
- Run 3: v1.4
- Run 4: v1.5
- Runs 5–10: v2.0 (MAJOR — structural output-format change; per-run "suggested searches" retired in favor of this section, §8)

This is a mature nine-week longitudinal window (not a single test session, as Layer 1 Run 2 was), so trajectory claims here carry more weight than in the prior report — but are still inferences over a live-search corpus, not a peer-reviewed literature review.

---

## Section 1 — Corpus inventory

| Brief | Run date | Prompt | Items | Proximity signals | Competitive signals | Classification distribution (Aligned / Incomplete / Problem / Background / Not relevant) |
|---|---|---|---:|---:|---:|---|
| `2026-06-15_Brief_Run1.md` | 2026-06-15 | v1.2 | 8 | 5 | 0 | 2 / 4 / 1 / 1 / 0 |
| `2026-06-15_Brief_Run2.md` | 2026-06-15 | v1.3 (unconf.) | 9 | 7 | 0 | 1 / 6 / 2 / 0 / 0 |
| `2026-06-16_Brief_Run3.md` | 2026-06-16 | v1.4 | 11 | 9 | 0 | 3 / 3 / 3 / 2 / 0 |
| `2026-06-16_Brief_Run4.md` | 2026-06-16 | v1.5 | 9 | 8 | 0 | 3 / 0 / 4 / 2 / 0 |
| `2026-06-17_Brief_Run5.md` | 2026-06-17 | v2.0 | 7 | 3 | 1 | 3 / 2 / 2 / 0 / 0 |
| `2026-06-22_Brief_Run6.md` | 2026-06-22 | v2.0 | 6 | 4 | 1 (watch-marker) | 0 / 2 / 2 / 2 / 0 |
| `2026-06-24_Brief_Run7.md` | 2026-06-24 | v2.0 | 5 | 4 | 0 | 0 / 3 / 0 / 0 / 0 |
| `2026-07-01_Brief_Run8.md` | 2026-07-01 | v2.0 | 7 | 5 | 0 | 1 / 3 / 3 / 0 / 0 |
| `2026-07-13_Brief_Run9.md` | 2026-07-13 | v2.0 | 7 | 5 | 0 | 2 / 3 / 2 / 0 / 0 |
| `2026-07-17_Brief_Run10.md` | 2026-07-17 | v2.0 | 5 | 2 | 0 | 0 / 2 / 0 / 1 / 2 |

**Corpus totals:** 74 items · 52 PROXIMITY SIGNAL flags · 2 COMPETITIVE SIGNAL (JEPA-class watch-marker) flags · **zero DIRECT CITATION flags across all ten runs.**

**Cross-run continuity note:** several items are carried across multiple runs rather than independently re-selected (Accountability Horizon / Tibebu AIT: Run 1, 6, 7, 8, 9; NIST AI Agent Standards Initiative: Run 3/5, 7, 8, 9; AgentGov-SC: Run 3, 5, 7, 8; GSDC named-human-owner: Run 8, 9; Munich/Google AI Overviews: Run 3, 4, 10). Item counts above are per-brief as published; Section 2 counts distinct concept-cluster appearances, which is the more meaningful figure for convergence assessment.

---

## Section 2 — Concept cluster map

| Cluster (RJB terminology) | P-ref | Appearances | Source diversity | Trajectory | Gap assessment |
|---|---|---:|---:|---|---|
| Structural attribution limit / accountability incompleteness | P1 / P5 | ~14 | ~11 independent | **increasing, most stable cluster in corpus** | Field converges on attribution *difficulty* (formal, legal, judicial, empirical, policy, and now safety-verification registers); RJB retains the ontological rank-deficiency characterization (SLT/SI) no source reaches |
| Execution-gate / rooted-authorization operationalization | P1 / P2 / P3 | ~16 | ~10 independent | **accelerating — fastest-moving cluster in corpus** | Standards (NIST), protocol (IETF: DRP/DAAP/AIP → EMILIA/PEDIGREE → WIMSE), and practitioner (GSDC) layers all converging on authorization-before-execution; identifiability precondition still absent everywhere |
| Epistemic-authority / sycophancy (CVG) | P1 / P2 | ~9 | ~7 independent | increasing, fastest-accumulating behaviorally | Field treats sycophancy as UX/RLHF defect; one Run 9 item edges toward commitment-gating architecture, narrowing but not closing the authority-boundary reframing gap |
| Agent authority-chain / delegation topology | P3 (TR-SA-1.1) | ~6 | ~5 independent | stable–increasing | Nominal delegation/credential infrastructure; substantive-authority + fail-closed condition still unaddressed |
| Creative authorship | P6 | ~3 | ~2 (one case line) | stable | Courts anchor authorship at the human level; do not reach structural indeterminacy upstream of output |
| Provenance / interpretive-continuity (new, Run 10) | P1 | 1 | 1 | **too early to call** | Institutional-legibility literature independently arriving at "authority must remain reconstructible/continuous" from a different direction than protocol engineering; watch for convergence with cluster 2 |
| JEPA-class governance-sufficiency bet | P3 | 2 (watch-marker only) | — | **flat — no accumulation in 5 runs (Run 6–10)** | No source has yet made an explicit world-model-as-governance-sufficiency claim; flag held at lowest confidence throughout |
| Standards / provenance (lineage tracking) | P2 | ~3 | ~3 | stable | Documentation/lineage requirements; not formal identifiability conditions |

**Cold domains (zero dedicated signal, five consecutive runs — Run 6 through Run 10):** P4 (economic surplus), P7 (Swiss / recognition neutrality), P8 (REA / Civic Legibility Packet). Confirmed as genuine uncolonized conceptual territory by explicit re-scan and §9 do-not-trigger discipline each run, not as a search-vector artifact.

**Top three by source diversity — prose:**

**(1) Structural attribution limit / accountability incompleteness (P1/P5).** The corpus's deepest and most stable cluster, now spanning formal theory (Tibebu AIT — carried five times, unchanged, the corpus's single most persistent external anchor), peer-reviewed legal scholarship (Oxford MLR liability-sink line, the Answerability Fuse), judicial rulings (Munich/Google, the ChatGPT product-liability MDL), empirical/behavioral work (Human Attribution of Causality), policy commentary (PAI, TechPolicy.Press), and — new as of Run 9 — safety-claim-verification methodology (Behavioural Assurance Cannot Verify, Lexsi Labs), which independently restates an Audit-Illusion-class result from a second research community entirely. Every converging source treats the failure as evidentiary, institutional, or measurement-level; none reaches RJB's ontological rank-deficiency characterization. That gap is stable across nine weeks and is the cluster's clearest defensible edge.

**(2) Execution-gate / rooted-authorization operationalization (P1/P2/P3).** This cluster shows the clearest acceleration pattern in the corpus: Run 7 found a single standards-body node (NIST); Run 8 found three simultaneous layers (standards, protocol via IETF, and practitioner via GSDC); Run 9 found the protocol layer itself splitting into two sub-layers (delegation-chain evidence vs. named-human-authorization root) with terminology ("human authority, not organizational policy") close enough to ABCF's own vocabulary that it was flagged as the strongest convergence found across all nine runs to that point; Run 10 shows the composition logic between those two sub-layers now being formalized. This is the cluster Layer 1 Run 2 named as most at-risk of independent convergence within 1–3 months — that window has passed, and the convergence materialized largely on schedule, still without the identifiability precondition ABCF's P3 supplies.

**(3) Epistemic-authority / sycophancy (P1/P2).** Accumulating fastest at the behavioral-research level (AEDI, Silicon Mirror, sycophancy taxonomy, Cognitive Agency Surrender, three independent streams converging in Run 3 alone). The field frames this as a UX/RLHF/model-quality problem; Run 9 logged the first item proposing an actual commitment-gating architecture (Premise Governance / Sensemaking), which is a genuine narrowing of the reframing gap even though it grounds the gate in decision-theoretic value-of-information rather than rooted causal authority.

---

## Section 3 — Field convergence assessment (clusters, source diversity ≥ 2)

**Structural attribution limit / accountability incompleteness (P1/P5)**
- Convergence type: **independent parallel** — Tibebu explicitly named in P5 as an independently derived result; no converging source cites RJB or, visibly, each other.
- Depth: **Formal** for Tibebu AIT and Behavioural Assurance (impossibility/insufficiency-theorem object class); **Structural** for the legal, judicial, and policy sources.
- RJB priority: P1 (2026-03-04) and P5 Zenodo timestamps appear to predate the April–July converging preprints and rulings. *Apparent by timestamp only — Layer 2 / counsel matter, not established here.*
- Remaining gap: the ontological rank-deficiency characterization of attribution failure. Nine weeks of re-scan have not surfaced a source that reaches it.

**Execution-gate / rooted-authorization operationalization (P1/P2/P3)**
- Convergence type: **independent parallel**, now shading toward **sequential elaboration** within the IETF thread itself (DRP/DAAP/AIP → EMILIA/PEDIGREE → WIMSE delegation-mapping is one continuous protocol lineage advancing draft-over-draft, not independent restarts).
- Depth: **Structural**, and as of Run 9 the closest **terminological** proximity in the corpus (named-human-authorization root framed explicitly as distinct from organizational policy).
- RJB priority: P1/P2/P3 timestamps appear to predate the IETF draft lineage and the NIST/GSDC nodes. *Apparent only.*
- Remaining gap: the identifiability-state precondition on the gate — present in every layer's architecture as an unfilled slot, not as a competing solution.

**Epistemic-authority / sycophancy (P1/P2)**
- Convergence type: **independent parallel**.
- Depth: **Structural** — converging on epistemic drift as a governance-relevant (not merely UX) failure; the Run 9 commitment-gating item edges toward **Structural-to-Formal** but does not cross.
- RJB priority: P1 timestamp appears to predate the cluster. *Apparent only.*
- Remaining gap: authority-boundary (CVG) framing; the field's causal grounding for the gate remains epistemic/decision-theoretic, not rooted-authority-based.

**Agent authority-chain / delegation topology (P3)**
- Convergence type: **independent parallel / sequential** (IETF and NIST/GSDC threads both elaborate across runs).
- Depth: **Structural**.
- Remaining gap: nominal-vs-substantive authority distinction and the fail-closed condition.

---

## Section 4 — Citation and framing opportunities

| Item | Publication / source | Use type | Notes |
|---|---|---|---|
| Tibebu AIT (arXiv 2604.07778) | arXiv | Citation support | Independent formal parallel to SLT, named in P5; stable anchor across five runs — the corpus's strongest "field recognizes structural impossibility" citation |
| Behavioural Assurance Cannot Verify (Seth & Sankarapu, Lexsi Labs) | Industry/academic | Citation support | Second independent research community (safety-claim verification) restating an Audit-Illusion-class result; strengthens the "not domain-specific" claim for the Audit Illusion |
| IETF EMILIA/PEDIGREE evidence-layer cluster | IETF | Framing anchor | Closest terminological proximity in the corpus to ABCF's chain/root separation; frame as "field arriving at the vocabulary, not yet the precondition" |
| IETF WIMSE delegation-mapping (Rampalli) | IETF | Framing anchor | Continuation of the above; useful for a "convergence timeline" figure showing draft-over-draft advance without the identifiability gate |
| Human Attribution of Causality (arXiv 2603.13236) | arXiv | Framing anchor | Empirical entry to the P1 problem; frame as "field finds the difficulty, treats it as evidentiary" |
| Munich / Google AI Overviews (LG München I) | Court | Positioning contrast | Judicial authorship-via-control; contrast with the structural identifiability condition ABCF requires |
| The Answerability Fuse | Legal scholarship | Positioning contrast | Names the liability-sink phenomenon directly; contrast "statutory reconstructability" against "structural non-identifiability" |
| GSDC named-human-owner pattern | Practitioner guide | Framing anchor | First practitioner-level node rooting accountability in a named human principal — useful as a "field is already building toward this" example |
| Causal AI Decision Intelligence (theCUBE) | Industry | Positioning contrast | Names causality as the "missing layer" from a commercial angle; contrast capability-addition framing against ABCF's formal precondition framing |

---

## Section 5 — Domain coverage assessment

| Domain | P-ref | Items in corpus | Concept hits | Gap |
|---|---|---:|---|---|
| Core causal governance / SLT | P1 | high (~14 direct + present in most other clusters) | attribution limit, execution gate, sycophancy, JEPA-watch | Best-covered domain; strongest and most stable external contact |
| Causal Non-Interference / CNI | P2 | medium–high | audit illusion, execution gate, lineage tracking | Covered via infra + standards; identifiability-gating gap persists |
| Latent-space extensions (L-SLT, RI, SA) | P3 | medium | agent authority chain, IETF protocol layer, JEPA-class watch | Covered via delegation topology; JEPA-class governance-sufficiency claim never materialized (5 runs flat) |
| Economic domain | P4 | **zero direct (five consecutive runs)** | tangential PAI value-chain mention only (Run 3) | **Confirmed vector gap** — re-scanned five times (Run 6–10) with explicit distribution/measurement literature found but none grounding ungovernability in structural attribution indeterminacy |
| Legal attribution | P5 | high | Munich, liability sinks, Oxford MLR, Answerability Fuse | Well-covered; judicial and legal-scholarship registers both active |
| Creative authorship | P6 | low | Thaler / Andersen case line only | Single case line across ten runs; needs a dedicated creative-domain vector |
| Swiss / recognition neutrality | P7 | **zero direct (five consecutive runs)** | none — only conventional-sense "neutrality" and Swiss AI-regulation mechanics, explicitly non-convergent per §9 | **Confirmed vector gap** |
| REA / Civic Legibility Packet | P8 | **zero direct (five consecutive runs)** | none — civic-legibility, deliberative-democracy literature found but lacks the recognition→explanation→authorization sequencing | **Confirmed vector gap** |

P4/P7/P8 zero-coverage is now a five-consecutive-run finding with explicit re-scan and do-not-trigger documentation each time — this reads as genuine field absence in these three domains, not a search-vector defect. Recommended search terms for all three are carried into Section 8.

---

## Section 6 — Weak signal watch list

| Signal | Status across runs | Proximity flagged? | Promote? |
|---|---|---|---|
| Rampalli SCITT Agent Action Capsule work | New at Run 9; not yet independently retrieved as a full item | No | Watch — potential PEL analogue at protocol level; candidate for promotion if it reaches full-item status |
| Khipu Problem companion manuscripts ("Fail-and-report," "From can to would") | New at Run 10, unpublished/unlocated | No | Watch closely — titles suggest closer P1/P2 proximity than the located Khipu paper itself |
| AMI Labs / JEPA-class governance-sufficiency claim | Flagged Run 5 (COMPETITIVE, watch-marker), Causal-JEPA Run 6 (watch-marker), zero accumulation Run 6–10 | Watch-marker only, never asserted | Hold at watch-marker — five runs with no governance-sufficiency claim is itself a data point worth noting in Section 7 |
| Attribution-by-contribution machinery (SCM/Shapley methods, arXiv 2411.03275 / 2603.13236) | Carried Run 8–9, no movement | No (§9 do-not-trigger — assumes attribution is resolvable) | Watch — standing tension with P1; would be significant if a source crosses into non-identifiability framing |
| ISO/IEC 42006 conformity-criteria maturation | Flagged Run 3–4 as highest-value standards watch item; published Run 5 | No — audit criteria still policy/documentation-level, not causal-identifiability-level | Watch — re-check conformity language each Layer 1 pass |
| Frankfurt Google ruling (second German AI-Overviews line) | Flagged Run 4, never independently retrieved | No | Retrieve — would strengthen or complicate the Munich line |
| Andersen v. Stability AI trial (September 2026) | Flagged Run 1–5, calendar-anchored | P6 | Watch — real date; outcome will move the P6 cluster |
| Practitioner governance-brief cluster (identity propagation, behavioral-authorization gap) | New Run 10, near-miss (IAM/engineering-hygiene framing, not structural identifiability) | No (§9 do-not-trigger) | Watch — adjacent to cluster 2; would matter if reframed toward identifiability |

---

## Section 7 — Research positioning summary

Across ten runs and nine weeks, the corpus shows a field that has moved from *building isolated pieces* of AI governance infrastructure to *actively assembling the operational layer* ABCF-v1 sits above — while the specific structural precondition ABCF supplies remains, run after run, the one piece nobody else has reached.

**1. Where the field is moving relative to ABCF.** Two things are true simultaneously. First, the diagnosis is converging fast and from an increasingly diverse set of registers: formal theory, peer-reviewed legal scholarship, judicial rulings, standards bodies, protocol engineering, and now safety-claim-verification methodology (Behavioural Assurance, Run 9) all independently locate an attribution or accountability gap with a "structural, not fixable-by-more-transparency" shape. Second, the *build* — not just the diagnosis — is accelerating specifically in the execution-gate cluster: standards, protocol, and practitioner layers are now all constructing authorization-before-execution gates simultaneously, and the IETF protocol lineage in particular is advancing draft-over-draft rather than restarting from independent groups. Neither movement has yet reached the identifiability precondition ABCF supplies; both are converging on the shape of the problem ABCF was built to solve.

**2. Concepts most at risk of independent convergence in the next 1–3 months.** The execution-gate / rooted-authorization cluster remains the pressure point — the terminological proximity reached at Run 9 (EMILIA/PEDIGREE's "human authority, not organizational policy") is closer to ABCF's own vocabulary than anything the corpus has previously surfaced, and Run 10 shows the sub-layers being actively composed. If any single actor in that IETF thread adds an identifiability-state check to the existing chain/root architecture, that would materially close the P3 gap without RJB involvement. *This is a convergence-risk observation, not an IP/prior-art finding — that determination belongs to Layer 2.*

**3. Concepts structurally ahead with no visible convergence.** The ontological rank-deficiency characterization of structural indeterminacy remains untouched after ten runs and eleven independent sources approaching the attribution-limit problem from every other angle. The substantive-vs-nominal authority distinction with fail-closed gating is similarly untouched at the technical level, though the field is now building the infrastructure that distinction would attach to. P4, P7, and P8 remain completely uncolonized after five consecutive explicit re-scans — the strongest and most repeatable null result in the corpus.

**4. Highest-priority research actions visible from the corpus.**
   (a) The execution-gate convergence window flagged in Layer 1 Run 2 has now materialized largely as predicted — this is the moment to fix RJB's positioning relative to the IETF/NIST/GSDC operational layer before any of those threads adds the missing precondition independently.
   (b) The Audit-Illusion-class result now has two independent research communities behind it (accountability theory and safety-claim-verification methodology) — this cross-domain replication is citation-support-grade and worth incorporating into any near-term P1/P2 framing work.
   (c) P4/P7/P8 remain the cleanest priority/defensive-publication territory in the corpus after five consecutive confirmed-null runs; this is now a stronger claim than it was at Layer 1 Run 2, where only four runs (~2-day window) supported it.

**This is a Stage 01 InterpretationArtifact. No action should be taken on these assessments without RJ's explicit review and AuthorizationAct.**

---

## Section 8 — Recommended search vectors for next Tier 1 run

1. `IETF WIMSE PEDIGREE EMILIA delegation mapping identifiability 2026` — *refinement* (P1/P2/P3, track whether the sub-layer composition logic gains an identifiability check)
2. `SCITT agent action capsule provenance binding Rampalli 2026` — *new* (P1/P2, promote the Run 9 weak signal to a tracked vector)
3. `Khipu Problem Tallam fail-and-report authorization primitive agentic AI` — *new* (P1/P2, chase the unpublished companion manuscripts flagged Run 10)
4. `Behavioural Assurance safety claims verification governance 2026` — *refinement* (P1/P5, track whether the safety-verification community produces further Audit-Illusion-class results)
5. `economic surplus attribution AI governance ungovernability structural 2026` — *new* (P4, sixth consecutive re-scan attempt with tightened structural-indeterminacy framing)
6. `recognition restraint contested causal explanation AI governance` — *new* (P7/P8, tightened framing away from conventional "neutrality" terms that keep returning false negatives)
7. `Frankfurt Landgericht Google AI Overviews liability ruling 2026` — *refinement* (P5, retrieve the still-unconfirmed second German ruling)
8. `Andersen v Stability AI trial September 2026 proceedings outcome` — *refinement* (P6, calendar-anchored)
9. `ISO IEC 42006 conformity criteria causal traceability audit 2026` — *refinement* (P1/P2, re-check whether published conformity language has moved past documentation-level)
10. `AMI Labs world model governance sufficiency claim 2026` — *refinement* (P3 COMPETITIVE-signal watch, sixth attempt to confirm or close the JEPA-class flag)
11. `premise governance commitment gating rooted authority 2026` — *refinement* (P1/P2, follow the Run 9 near-miss that edged toward structural reframing)
12. `IEEE P2863 organizational AI governance draft status 2026` — *refinement* (standards vector, flat since Run 4; check for movement)

New vectors: 2, 3, 5, 6. Refinements: 1, 4, 7, 8, 9, 10, 11, 12.

**Cadence note:** Per §8 architecture (v1.1), these vectors are the sole authoritative source of next-Tier-1 guidance until the next Layer 1 pass. At current cadence (Layer 1 roughly every 5 Tier 1 runs), refresh Layer 1 again after Tier 1 Run 15, or sooner if the execution-gate cluster's identifiability gap closes at any layer.

---

*All outputs are InterpretationArtifacts at Stage 01.*
*Layer 1 outputs are research-positioning artifacts — not legal opinions, patent opinions, prior-art findings, filing instructions, or authorization acts.*
*Proximity signals indicate architectural convergence only; they are not citations or IP claims.*
*No action authorized without RJ's explicit AuthorizationAct.*
*Save to: Reports/2026-07-17_Layer1_Run3_SCOPE-ALL.md*
