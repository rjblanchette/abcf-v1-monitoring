# ABCF-v1 Corpus Layer 1 — Research Positioning Report

```
[RJ-WE v1.0]
AGENT         : Rocketman (Structure layer)
LAYER         : Recognition / Structure
MODE          : Work
DOCUMENT ID   : 2026-10-05_Layer1_Run5_SCOPE-ALL
LIFECYCLE     : Stage 01 — InterpretationArtifact
OUTPUT CLASS  : Classification / Structural Evaluation
AUTHORITY     : NOT_AUTHORIZED
RUN DATE      : 2026-10-05
PROMPT        : ABCF-v1_Corpus_Layer1_v1.1
RUN SCOPE     : ALL
```

---

## 0. Method note and corrections to the record

Corpus: `briefs/` of `rjblanchette/abcf-v1-monitoring`, shallow clone of `main` on 2026-10-05. **Sixteen briefs, Run 1–Run 16** (2026-06-15 to 2026-10-05). Layer 1 Run 4 (2026-08-21) covered Runs 1–14; this run adds **Run 15 (2026-09-24) and Run 16 (2026-10-05)** and re-derives all corpus-wide sections. Counts for items, flag rows and P-tags were computed by script from the briefs; cluster coding is mine and is listed in Appendix A.

**Trigger:** Run 15 and Run 16 both record that the Layer 1 Run 4 early-refresh condition was met (the authorization/identifiability "join" was named from outside, in Run 15 Item 7).

**Limits that apply to everything below.** Run 15–16 characterizations of arXiv/IETF items rest largely on summary-level extraction (stated in Run 16 §6). "No citation of RJB/Tibebu found" means *not found in the extraction*, which is weak evidence of absence. Search is vector-driven and built from RJB vocabulary, so what the corpus can show is biased toward RJB-shaped material (see Section 7).

**Corrections to Layer 1 Run 4 and to the briefs.** These change claims that earlier reports relied on.

1. **Prompt versions.** The Run 4 inventory lists Run 2 as v1.3 and Run 5 as v2.0. The headers say Run 2 = v1.2 and Run 5 = v1.5; Run 6 is the first v2.0 brief (Run 6 says so itself).
2. **P4 and P8 were not "zero" or "first hit at Run 14" on flag rows.** P8 is tagged in Run 1 (Premise Governance), Run 4 (EU Omnibus; CETS 225) and Run 14 (Reg. 2026/1755). P4 is tagged in Run 3 (PAI) and Run 15 (Justice). Runs 1, 3 and 4 predate the v2.0 do-not-trigger rules and the earlier tags may not survive them, but the statement "zero across all runs" is true only for **P7**. Run 15 also calls its P4 tag the series' first; Run 3 predates it.
3. **P2 date.** The project registry gives P2 as "March–April 2026". The Publication Control Record and Layer 2 Run 2 record the Zenodo date as **4 May 2026** (P3 26 Apr; P5/P6 3 May; P4 25 May; P7 8 Jun; P8 9 Jun). This report uses the Zenodo dates. The registry in the project instructions has not been corrected.
4. **"RJB predates every converging source" does not hold on the briefs' own dates** for the execution-gate cluster (Section 3). The "~3-month field lag" inference in Run 4 is unsupported: it was computed from the *latest* items, not the earliest.
5. **Repeat appearances inflate counts.** At least 16 of 76 proximity rows (≈21%) are repeat appearances of an already-flagged source: 9 are explicitly "carried" (Runs 7–10) and 7 are unmarked (Run 4 Munich; Run 6 Accountability Horizon, which is the same paper as Run 1 Item 1 [arXiv:2604.07778]; Run 6 Cognitive Agency Surrender; Run 7 AgentGov-SC and NIST; Run 12 Tallam, which includes arXiv:2605.05440 already flagged in Run 1 Item 6; Run 16 ACP, already in Run 11 Item 1). Run 14 §5 and Run 16 Item 7 call ACP "not previously recorded"; Run 11 Item 1 names it.
6. **Run 16 Item 5** is flagged PROXIMITY SIGNAL (self-described borderline) but classified Background only. If downgraded, Run 16 has 5 rows and the corpus 75.
7. Minor: Run 3's trend note refers to "Runs 4 and 5" (session-numbering drift; Runs 3 and 4 share a date).

---

## Section 1 — Corpus inventory

Classification order: Aligned / Incomplete / Problem / Background / Not relevant. "Items" counts headed items, including carried and backfill entries.

| Brief | Run date | Prompt | Items | Proximity signals | Competitive | Classification |
|---|---|---|---:|---:|---:|---|
| `2026-06-15_Brief_Run1.md` | 2026-06-15 | v1.2 | 8 | 5 | 0 | 2 / 4 / 1 / 1 / 0 |
| `2026-06-15_Brief_Run2.md` | 2026-06-15 | v1.2 | 9 | 7 | 0 | 1 / 6 / 2 / 0 / 0 |
| `2026-06-16_Brief_Run3.md` | 2026-06-16 | v1.4 | 11 | 9 | 0 | 3 / 3 / 3 / 2 / 0 |
| `2026-06-16_Brief_Run4.md` | 2026-06-16 | v1.5 | 9 | 8 | 0 | 3 / 0 / 4 / 2 / 0 |
| `2026-06-17_Brief_Run5.md` | 2026-06-17 | v1.5 | 7 | 3 | 1 | 3 / 2 / 2 / 0 / 0 |
| `2026-06-22_Brief_Run6.md` | 2026-06-22 | v2.0 | 6 | 4 | 1 (watch-marker) | 0 / 2 / 2 / 2 / 0 |
| `2026-06-24_Brief_Run7.md` | 2026-06-24 | v2.0 | 5 | 4 | 0 | 0 / 3 / 0 / 0 / 0 (+2 unclassified)¹ |
| `2026-07-01_Brief_Run8.md` | 2026-07-01 | v2.0 | 7 | 5 | 0 | 1 / 3 / 3 / 0 / 0 |
| `2026-07-13_Brief_Run9.md` | 2026-07-13 | v2.0 | 7 | 5 | 0 | 2 / 3 / 2 / 0 / 0 |
| `2026-07-17_Brief_Run10.md` | 2026-07-17 | v2.0 | 5 | 2 | 0 | 0 / 2 / 0 / 1 / 2 |
| `2026-07-31_Brief_Run11.md` | 2026-07-31 | v2.0 | 5 | 2 | 0 | 1 / 3 / 0 / 1 / 0 |
| `2026-08-11_Brief_Run12.md` | 2026-08-11 | v2.0 | 6 | 4 | 0 | 2 / 3 / 0 / 1 / 0 |
| `2026-08-15_Brief_Run13.md` | 2026-08-15 | v2.0 | 4 | 3 | 0 | 1 / 3 / 0 / 0 / 0 |
| `2026-08-21_Brief_Run14.md` | 2026-08-21 | v2.0 | 6 | 5 | 0 | 2 / 3 / 1 / 0 / 0 |
| `2026-09-24_Brief_Run15.md` | 2026-09-24 | v2.0 | 7 | 4 | 0 | 0 / 4 / 1 / 2 / 0 |
| `2026-10-05_Brief_Run16.md` | 2026-10-05 | v2.0 | 9 | 6 | 0 | 0 / 6 / 0 / 3 / 0 |

¹ Run 7 Item 4 is a carried Accountability Horizon entry ("Coherent problem signal (carried)", excluded to avoid double counting); Item 5 is "no new node".

**Totals:** 111 items · 76 PROXIMITY SIGNAL rows · 2 COMPETITIVE SIGNAL rows (Runs 5–6, both JEPA-class; none since) · **0 DIRECT CITATION** · Classification: Aligned 21, Incomplete 50, Problem 21, Background 15, Not relevant 2, unclassified 2.

**Run 15–16 changes in pattern:**
- **No item has been classified "Coherent and aligned" in Runs 15 or 16.** Last: Run 14 (two). The authority-side material is arriving as "incomplete" because every instance is attribution-empty.
- Flag rows per item: Runs 1–4 0.78; Runs 5–10 0.68; Runs 11–14 0.67; Runs 15–16 0.63. Runs 1–4 were a backlog sweep, so the early rate is not comparable.
- **Discovery date ≠ publication date.** Of Run 15–16's 10 flag rows, 5 are backfill dated before Aug 21 (McCann Apr–May; Justice PDF 28 Jul; Governed Individuation 6 Jul; Wu et al. 19 Aug; ACP Mar) and 5 are new in the window. Read the apparent acceleration with this in mind.

---

## Section 2 — Concept cluster map

Rows = proximity/competitive rows coded to the cluster (rows can sit in more than one). "Distinct sources" dedupes repeats and treats one author program as one source. All trajectory statements are inferences.

| Cluster (RJB terminology) | P-ref | Rows | Distinct sources | Trajectory (rows by window: R1–4 / R5–10 / R11–14 / R15–16) | Gap assessment |
|---|---|---:|---:|---|---|
| Execution-gate / rooted-authorization operationalization | P1/P2/P3 | 32 | ~22 author groups | 6 / 11 / 7 / 8. New groups per run ≈ 1.5 / 1.2 / 1.5 / 4.0, but 5 of the 8 latest rows are backfill | Sixteen runs and no instance attaches an identifiability condition. The one formal bound in the cluster (Governed Individuation, Run 16) rests on verifier soundness, which is the identifiability-adjacent question |
| Structural attribution limit / accountability incompleteness | P1/P5 | 24 | 17 | 8 / 10 / 3 / 3. New sources per window: 8 / 4 / 2 / 3 | Steady, not accelerating. Field reaches "structural, not epistemic" from formal, legal, qualitative and computability directions. None reaches rank deficiency of the admissible intervention map or a restoration route |
| Legal attribution / liability allocation | P5 | 11 | 10 | 6 / 2 / 2 / 1 | Courts attribute by observable proxy: München I (operator synthesis), Berlin II (operator influence over sources), Ninth Circuit (user direction). No court engages causal contribution |
| Epistemic authority / sycophancy (CVG) | P1/P2 | 7 | 6 | 6 / 1 / 0 / 0 | No flag since Run 6; the vector has returned nothing at item level for five runs (Run 16 §8). Content is being absorbed into the authorization-standing question |
| World-model / latent-space identifiability | P3 (TR-LSPD-1.0) | 5 (2 competitive watch-markers, 3 proximity) | ~3 programs | 0 / 2 / 3 / 0 flagged; 2 unflagged Background items in Runs 15–16 | Corroborates predictive ≢ interventional identifiability. No governance claim anywhere. Fifth–seventh consecutive run of §3b activity |
| Institutional compliance regimes (EU AI Act, ISO 42006, CETS 225, NIST RMF profile) | P1/P8 | 5 | 5 | 5 / 0 / 0 / 0 | Not flagged since Run 4; remains in briefs as Background or as context for the legal cluster |
| Creative authorship | P6 | 2 | 1 line | 2 / 0 / 0 / 0 | Andersen trial reported moved to 5 Apr 2027 (single secondary source). Nearest calendar test lost for six months |
| REA / recognition sequencing | P8 | 4 (tags) | 3 sources | 3 / 0 / 1 / 0 | See Section 5. Unconfirmed |

*(Legal-attribution rows by window, as coded in Appendix A: R1–4 6, R5–10 2, R11–14 2, R15–16 1; total 11.)*

**Top three by source diversity, in prose.**

**1. Execution-gate / rooted authorization (~22 groups).** The cluster now contains a standards-track WG document (draft-ietf-wimse-aims-00, 15 Sep), two further IETF individual or independent drafts (das, 23 Sep; kroehl, 6 Sep), a model-checked admission protocol (ACP), a mechanized effect gate (McCann), a signed-act authority architecture with a proved bound (Governable Individuals / Governed Individuation), and an industry architecture with disclosed US provisional filings (Justice EACL). Their shared move: authority is a rooted, signed, narrowing grant, and apparent consent or behaviour is denied authority standing. Their shared absence: no causal-identifiability condition. This is the cluster where independent convergence is most advanced; it is also the cluster where Run 15 Item 7 and Run 16 Item 3 now sit closest to the RJB position.

**2. Structural attribution limit (17 sources).** Growth has flattened since Run 10 but breadth has widened to a qualitative-empirical route (Nguyen et al., AIES 12–14 Oct) and a computability route (McCann). Run 15 Item 7 is the first governance architecture built on Tibebu's limit; it treats the limit as terminal. Run 16 §6 notes a 122-study accountability review (LAAF) that, per extraction, mentions neither Tibebu nor SLT, which suggests the impossibility results have travelled less far than the cluster map implies (inference, extraction-level evidence).

**3. Legal attribution (10 sources).** The Ninth Circuit decision (4 Aug 2026, recorded in Run 16) adds a third proxy beside the two German rulings. This is the clearest sequence in the corpus in which the same question is answered three ways by three observable features.

---

## Section 3 — Field convergence assessment

Epistemic rule applied: convergence is asserted only where ≥2 sources reach structurally similar claims without citing each other or RJB, *on the evidence retrieved*. Sources that build on one another are marked sequential.

### 3.1 Execution-gate / rooted-authorization (P1/P2/P3)
- **Convergence type:** Independent parallel across at least six starting points (identity/IAM standards; formal transition systems; embodied-agent robotics; mechanized program semantics; protocol-boundary engineering; patent-disclosed industry architecture). Sequential elaboration inside the WIMSE line (cross-org delegation → layered mapping → adoption call → WG document) and inside Governable Individuals → Governed Individuation.
- **Depth:** Structural throughout; Formal in the cases with proofs or model checking (ACP TLA+; McCann Rocq; Governed Individuation Theorem 1). Convergence on *gate placement and rooted signed authority* is structural; convergence on *identifiability* is absent.
- **RJB priority position (dates only; see table below):** RJB P1 (4 Mar) predates most sources, but **P2 (4 May) and P3 (26 Apr) do not predate** HDP, ACP, Fernandez ADB, Tibebu or McCann, and Premise Governance (2 Feb) and Audit Trails (28 Jan) predate P1. Whether any source anticipates a given P-ref claim is a Layer 2 / counsel question and is not assessed here.
- **Remaining gap:** identifiability precondition on the gate; restoration route; the "faithfulness of the effect abstraction" question (Governed Individuation).

| Source | Date in briefs | vs P1 (4 Mar) | vs P3 (26 Apr) | vs P2 (4 May) |
|---|---|---|---|---|
| Audit Trails for LLMs (2601.20727) | 28 Jan 2026 | before | before | before |
| Premise Governance (2602.02378) | 2 Feb 2026 (v1) | before | before | before |
| ACP (2603.18829) | Mar 2026 by ID; first-submission day unresolved | same month | before | before |
| HDP | IETF draft Mar 2026; arXiv 6 Apr | ≈ / after | before | before |
| Tibebu AIT (2604.07778) | 10 Apr 2026 | after | before | before |
| Fernandez ADB (2604.17511) | Apr 2026 | after | before or ≈ | before |
| McCann (2604.27292 et al.) | Apr–May 2026, days not retrieved | after | ≈ | ≈ / before |
| DTF (2605.15228) / Tallam 2605.05440 | 13 May / 6 May 2026 | after | after | after |
| Governed Individuation, Governable Individuals | Jul 2026 | after | after | after |
| draft-ietf-wimse-aims-00, das-01, kroehl-02 | Sep 2026 | after | after | after |
| Justice EACL | PDF 28 Jul 2026; claims design predates Apr 2026 (company claim, unverified) | after | after | after |

### 3.2 Structural attribution limit (P1/P5)
- **Type:** Independent parallel (Tibebu formal; McCann computability; Nguyen et al. qualitative; Behavioural Assurance safety-verification; Oxford MLR and liability-sink scholarship legal; AgentGov-SC regulatory). Sequential: Tibebu → Solozobov (DEMM, DEMM-Bench) → Justice.
- **Depth:** Structural; Formal for Tibebu and McCann; Surface for Nguyen et al. and the policy commentary.
- **Priority:** P1 (4 Mar) predates Tibebu (10 Apr) by ~5 weeks and the Run 6–16 sources. Oxford MLR (18 Mar) and Human Attribution of Causality (Mar 2026) postdate P1 by 2 weeks or less. The liability-sink cluster is dated "2025–2026" in Run 2 and includes material before P1. P1 was modified 26 May (content change unconfirmed per the Control Record).
- **Gap:** rank-deficiency characterization of the admissible intervention map; computable extent below the threshold; restoration by governed probe expansion. Justice and Tibebu treat the limit as terminal.

### 3.3 World-model identifiability (P3)
- **Type:** Independent parallel within one sub-field (LeJEPA conditions; controlled-dynamics conditions; certificate-gated blind region; Kori & Russo taxonomy; InfluenceField). Sequential inside the sub-field.
- **Depth:** Structural, Formal in Run 14's certificate-gated result. Authors scope claims as operational and objective-relative and make no governance claim.
- **Priority:** P3 (26 Apr). LeJEPA and later papers postdate it by weeks to months; earlier causal-representation-learning identifiability work (Run 4 weak signal, arXiv:2411.03275, a different problem) predates.
- **Gap:** no link from identifiability to authorization or accountability; narrower than P3's ontological claim.

### 3.4 Legal attribution (P5)
- **Type:** Independent parallel (judgments, scholarship, legislation). **Depth:** Surface to Structural; the PLD and Reg. 2026/1755 are Formal in the sense of binding mechanisms that presuppose the attribution-difficulty premise.
- **Priority:** P5 (3 May). Oxford MLR (18 Mar), Thaler cert. denial (2 Mar) and the PLD analyses precede it. München I and Berlin II (1 Jun) postdate it.
- **Gap:** none of the courts or instruments names the indeterminacy formally; each allocates by a chosen proxy.

### 3.5 Epistemic authority (P1/P2) and creative authorship (P6)
Epistemic authority: independent parallel, Surface-to-Structural (diagnosis converges, remedy is measurement or mitigation). Creative authorship: sequential case line, Surface; no convergence assertion warranted.

---

## Section 4 — Citation and framing opportunities

Selection rule: items with a citable primary source and a clear use type. The corpus has 71 "Aligned" or "Incomplete" items; the earlier Run 4 table is carried where unchanged and items from Runs 15–16 are added. Run 15–16 sources need a full-text check before citing (extraction was summary-level). Sources that disclose patent filings or compete in claim territory route through Layer 2 first.

| Item | Publication / source | Use type | Notes |
|---|---|---|---|
| Justice, EACL (Run 15 Item 7) | SSRN 7202899 | Positioning contrast | Closest authority-side overlap; accepts Tibebu "without reservation"; attribution conceded as terminal; §8.3 names an "epistemic layer" as open. **Layer 2 first:** author discloses US provisional applications 64/021,779 and 64/062,705 |
| Governed Individuation (Run 16 Item 3) | arXiv:2607.04613 | Framing anchor / positioning contrast | Formal bound conditional on verifier soundness, which the authors call "the hard systems problem" and call undefined for open action spaces. Strong support for "the guarantee is only as good as the faithfulness of the abstraction" |
| Governable Individuals (Run 14) | arXiv:2607.05463 | Citation support | Companion now located; see reclassification note below |
| draft-ietf-wimse-aims-00 (Run 15 Item 1) | IETF Datatracker | Positioning contrast | WG-owned text denying authority standing to local UI confirmation; no identifiability condition. Highest standing of any flagged text |
| McCann cluster (Run 15 Item 2) | arXiv:2604.27292, 2604.27289; `mashin-live/governance-proofs` | Framing anchor | Third independent impossibility route (Rice). Governs effects, silent on authority origin. April dating relative to P2: Layer 2 |
| "No One to Blame" (Run 16 Item 4) | arXiv:2608.12104 (AIES 2026) | Citation support | Venue standing for "unachievable, not merely obstructed"; qualitative, no formal threshold |
| München I / Berlin II / Ninth Circuit | LG München I; LG Berlin II 52 O 62/26; *Amazon v. Perplexity* (9th Cir., 4 Aug 2026) | Framing anchor | Three proxies, three rulings; judgment texts not all retrieved (Berlin, Ninth Circuit via commentary) |
| Revised PLD; Reg. (EU) 2026/1755 (Run 14) | EU legislative texts | Framing anchor | Reallocation of causation burden without resolving it |
| Certificate-gated identifiability map (Run 14) | arXiv:2607.27017 | Citation support | Demonstrated blind region; intervention-side restoration |
| Controlled world-model identifiability (Run 13) | arXiv:2607.22430 | Framing anchor | Policy-side analogue of rank deficiency |
| Kori & Russo (Run 15 Item 6) | arXiv:2608.13456 | Framing anchor | Survey-level statement that predictive ≠ interventional identifiability |
| Fernandez ADB (Run 11) / ACP | arXiv:2604.17511 / 2603.18829 | Framing anchor | Formal admissibility-at-execution result; **dated before P2 and P3 (Section 3.1)** |
| Tibebu AIT; DEMM-Bench | arXiv:2604.07778; arXiv:2606.20634 | Citation support | Field recognition of accountability incompleteness |
| Bertino et al. (Run 13) | arXiv:2608.01558 | Positioning contrast | Trajectory-level assurance with accountability left open |
| Draft das / kroehl (Run 16) | IETF I-Ds | Positioning contrast (low weight) | Independent or individual submissions; das requires no named human accountable party |

**Reclassification question (RJ's decision).** Run 14 stated that if the Governable Individuals companion carried a formal containment result, Item 4 might need revisiting from "Coherent and aligned". The companion exists and does carry one. On the Run 16 evidence, "Coherent but incomplete" fits the pair better, because the load-bearing assumption is where the RJB position places its unresolved question. This is an assessment; no reclassification has been made.

---

## Section 5 — Domain coverage assessment

"Rows" = proximity/competitive rows carrying the P-tag in the brief (script count; rows can carry several tags). "Substantive hits" = my read of whether the matched concept is the RJB concept or an adjacent one.

| Domain | P-ref | Rows | Substantive hits | Gap |
|---|---|---:|---|---|
| Core causal governance / SLT | P1 | 52 | High; the structural attribution limit across ~17 sources | Rank-deficiency characterization unreached |
| Causal Non-Interference / CNI | P2 | 21 | Moderate; gate and refusal analogues, mostly via execution-gate cluster | Identifiability-state gating absent everywhere; **P2 is dated 4 May (not Mar–Apr)** |
| Latent-space (L-SLT, RI, SA) | P3 | 28 | High; both halves (authorization and identifiability) developing apart | Join unoccupied (Section 7) |
| Economic | P4 | 2 | Run 3 (PAI) was policy-level; Run 15 (Justice) matched the DOG/implementation concept, not Surplus Governability or Non-Conversion | Core economic concepts: no match in 16 runs |
| Legal attribution | P5 | 24 | High and broadening | Proxy-allocation documented; no formal treatment |
| Creative authorship | P6 | 2 | Low; one case line | Trial moved to Apr 2027 (unconfirmed) |
| Swiss neutrality | P7 | 0 | None | See below |
| REA / CLP | P8 | 4 | Run 1 and Run 4 tags are loose; Run 14 is a reading of Reg. 2026/1755 through RJB's lens, and the source makes no such claim. Gattupalli (Run 15, essay) is Surface only; Abiri (Run 16) does not trigger | Unconfirmed; leaning null |

**P4/P7/P8 interpretation.** The earlier reports read these nulls as "confirmed genuine field absence". That reading is stronger than the evidence. The vectors use RJB-specific phrasing (Surplus Governability, recognition restraint, four functions of neutrality), and the do-not-trigger rules exclude anything not grounded in structural attribution indeterminacy, so the vectors are built to return nothing even where adjacent literature is active (Run 6–9 re-scans found substantial AI-surplus, deliberative-democracy and civic-legibility work, all excluded). What the nulls show is *no external text uses this framing*. Two implications: this is useful for priority-and-vocabulary purposes, and it also means there is no external audience vocabulary to anchor a citation strategy. Layer 2 Run 2 additionally records P7 and P8 as outside the ABCF-v1 governance-IP scope, so the "gap" is partly a scope boundary. Repeating the same query is not independent confirmation; Run 15 and Run 16 already show this (query reruns with tightened wording returned nothing new).

---

## Section 6 — Weak signal watch list

| Signal | Status across runs | Proximity flagged? | Promote? |
|---|---|---|---|
| Andersen v. Stability AI trial | Moved from 8 Sep 2026 to 5 Apr 2027 on one secondary source; docket unconfirmed (Runs 15–16) | P6, Runs 1 and 3 | Weakened as a near-term signal. Re-anchor; confirm on docket |
| Governable Individuals companion | Located Run 16 (Governed Individuation) | Yes (Run 16) | Resolved; reclassification is RJ's decision |
| Justice / Alethera companion paper | Announced in the paper (proofs and evaluation deferred). Neighbours named: Bhardwaj 2026, Kaptein et al. 2026, Cihon et al. 2025 | Yes (Run 15) | Watch closely; Layer 2 input |
| McCann companions (2605.01030, 01032, 01037) | New Run 15 | In cluster | Check for authorization semantics at the governed boundary |
| Intent-Driven Computing (Rice) | Run 13–14; Run 15 located the McCann line | No | Folded into the McCann item; retire standalone |
| ACP (2603.18829) | Run 11 (bundled), Run 14 (weak signal), Run 16 (item) | Yes (Runs 11, 16) | Resolved |
| VC Confidence Method (W3C) | Working Draft 10 Sep; the "September Recommendation" target not met | No | Hold; low priority |
| Reg. 2026/1755 expert chain | Nothing located in Runs 15–16; Scientific Panel appointed 1 Jun 2026, link unverified | No | Held |
| Frankfurt ruling | Twelve unconfirmed attempts; Run 15 suggests misattribution of the Munich ruling | No | **Retire** |
| AMI Labs / JEPA-class governance-sufficiency bet | No governance claim in 10 consecutive runs (last competitive row Run 6); Run 16 Item 8 (as reported) runs against self-governance | No | Retire as standalone |
| Epistemic-sovereignty / sycophancy vector | Five consecutive absences at item level | No | Decide: re-specify once or retire (Section 8) |
| Gattupalli, "causal inversion" (P8, essay) | Run 15 weak signal; Run 16 unchanged | No | Hold. Surface only |
| Abiri, "Regulating for AI Legitimacy" | Run 16; does not trigger P8 | No | Do not promote |
| Holland, "Authority Inversion" (Zenodo, 11 Jan 2026) | Run 16; dated before P1; Surface depth; no RJB citation found | No | Watch; dating is a Layer 2 input |
| LAAF (arXiv:2608.27102) | Run 16; 122-study review that per extraction omits Tibebu/SLT | No | Watch as an indicator of diffusion of the impossibility results |
| Automated AI R&D oversight call | Run 16 Item 8, secondary report only; primary paper not retrieved; includes an Anthropic co-founder per the report | No | Retrieve primary |
| Ninth Circuit remand / further review | New Run 16 | Run 3 flag stands | Watch |
| J. Postgrad. Med. "algorithmic sycophancy … institutional governance" | Run 15; abstract not retrieved | No | Retrieve abstract |
| Nguyen et al. at AIES (12–14 Oct) | Run 16 | Yes (Run 16) | Presentation falls in the next run interval |
| Stanford "phantom agent" / Startari | Surfaced Run 16, unassessed | No | Triage |
| OECD agentic AI report (15 Sep) | Run 15 Item 3; PDF blocked | No | Retrieve PDF; no flag by rule |
| IEEE P2863 "D2 Mar 2026" | Retail listing only (Run 16), unverified | No | Verify at IEEE |
| NIST CAISI | Fifth consecutive run without a primary-source check | Yes (Runs 5–9, 12) | Change retrieval method (Section 8) |
| ISO/IEC 42006 accreditation | Not re-verified for content since Run 12 | Yes (Run 4) | Low |
| Layered mutability (Tallam 2604.14717) | Not touched Runs 15–16 | No | Hold |

---

## Section 7 — Research positioning summary

**1. Where the field is moving.** The authorization half of ABCF-v1 is being built in public, and the build is now escalating in standing as well as number. An IETF working group adopted the agent-authorization draft on 15 September; two further IETF texts, a model-checked admission protocol, a mechanized effect gate, and a signed-act architecture with a proved bound all place authority at a rooted, narrowing, fail-closed gate. Not one attaches a causal-identifiability condition. Independently, the world-model community continues to produce identifiability results with no governance framing.

**2. At risk of convergence in one to three months.** The execution-gate cluster, and now more sharply the join itself. Justice's paper names an "epistemic layer … whether the knowledge on which an authorization rests is itself warranted" as open work, and Governed Individuation rests its theorem on verifier soundness. Both describe the identifiability question from the authority side. If either author group attaches a faithfulness or identifiability requirement, the join closes without RJB involvement. This is a convergence-risk observation, not a prior-art finding. The risk is asymmetric: the authority-side groups have the standing and the deployment pathway, while the identifiability side has the formal result but no governance audience.

**3. Structurally ahead with no visible convergence.** The rank-deficiency characterization and the restoration route (identifiability recovered by governed probe expansion). The only external demonstration of intervention-side restoration is in a restricted, objective-relative regime (Run 14). P4, P7 and P8 show no matches, but that is a statement about vocabulary, not about the field (Section 5).

**4. Two cautions the corpus itself supports.** First, the "RJB predates the cluster" framing needs revision for P2 and P3: several execution-gate and admissibility sources are dated before or within weeks of 26 April and 4 May. Second, the system has a selection problem: 68% of items are flagged, the vectors derive from RJB vocabulary, and the trigger rules exclude contribution-based attribution work, which is the main body of work arguing attribution is *resolvable*. The corpus therefore contains almost no disconfirming evidence, and positioning claims are only as strong as that gap allows.

**5. Highest-priority actions.** (a) Resolve the dating table in Section 3.1 with counsel before any priority claim is made in a paper. (b) Occupy the join in a short framing piece, using Governed Individuation's soundness assumption as the anchor, after Layer 2 clears the Justice disclosures. (c) Add a disconfirmation vector (Section 8).

**This is a Stage 01 InterpretationArtifact. No action should be taken on these assessments without RJ's explicit review and AuthorizationAct.**

---

## Section 8 — Recommended search vectors for next Tier 1 run

Run 4 vector yield: productive — 2 (companion located), 6 (McCann), 7 (WIMSE adopted), 8 (ACP); partially — 1 (trial moved); no yield — 3, 4, 5, 9, 10, 11, 12.

| # | Query | New / refinement | Target |
|---|---|---|---|
| 1 | `draft-ietf-wimse-aims working group last call list discussion attribution OR identifiability` | Refinement (Run 4 vector 7) | P1/P3 |
| 2 | `Alethera "Execution Authority Control Layer" companion evaluation` and `Bhardwaj "Agent Behavioral Contracts" 2026`, `Kaptein runtime compliance agent execution paths 2026` | New | P1/P3; Justice neighbours |
| 3 | `agent verifier effect abstraction soundness faithful causal effects open action space` | New | The join; verifier-soundness question |
| 4 | `"epistemic layer" OR "semantic governance" authorization warranted knowledge agentic` | New | The join; Justice §8.3 |
| 5 | `"accountability horizon" OR "accountability incompleteness" citing follow-up 2026` | Refinement (Tibebu cluster) | P1/P5 |
| 6 | `AIES 2026 accountability agents proceedings` (time-sensitive: 12–14 Oct) | New | P1/P5 |
| 7 | `AI output liability court ruling Germany OR EU Landgericht OLG 2026` (replaces Run 4 vector 9) and `Amazon v. Perplexity Ninth Circuit remand OR en banc` | Refinement + new | P5 |
| 8 | `draft-das-accountable-autonomous-effectuation OR draft-kroehl-agentic-trust-aae adoption working group` | New | P3 standings |
| 9 | `attribution recoverable multi-agent AI Shapley OR mechanistic interpretability OR causal tracing responsibility` | **New — disconfirmation vector** | P1; counter-evidence the current rules exclude |
| 10 | `sycophancy structural authority boundary governance architecture 2026` once; retire the vector if it is still null in two runs | Refinement | P1/P2 epistemic cluster |
| 11 | `marginal product of AI attribution value capture who is entitled causal contribution measurement` | New vocabulary for P4 (economic-literature terms in place of RJB coinages) | P4 |
| 12 | Fetch nist.gov AI agent standards and NCCoE agent identity pages directly instead of searching | Refinement (Run 4 vector 12; five unverified runs) | §3a |

Retire: Run 4 vector 9 as written (Frankfurt), vector 5 in current form (P7: repeated null), the current P8 query form (low yield; a P8 retry is better placed in neighbouring-discipline vocabulary such as administrative-law "interim measures before explanation" if wanted). Re-anchor vector 1 (Andersen, 5 Apr 2027, docket check).

**Cadence note.** Vectors 1–12 stay authoritative until the next Layer 1 pass. Refresh sooner if the Justice companion paper appears, the WIMSE draft changes §10.1 or §10.7, or the join shows movement.

---

## Appendix A — Coding of flag rows to clusters (auditable)

A attribution limit · B execution gate · C epistemic authority · D legal attribution · E world-model · F institutional regimes · G creative authorship · H P8-tagged.

- R1: AIT [A]; HDP [B]; Premise Governance [C,H]; Thaler [G]; Multi-agent authorization survey 2605.05440 [B]
- R2: DTF [B]; Silicon Mirror [C]; AEDI [C]; Medical Negligence Oxford [A,D]; Human Oversight in Practice [A]; Liability sinks [A,D]; Overlaying Governance [B]
- R3: Munich [D]; Amazon v. Perplexity [B,D]; Human Attribution of Causality [A]; EU AI Act Aug 2026 [F]; NIST RMF profile [F]; Sycophancy three streams [C]; Thaler/Andersen [G]; Causal AI decision intelligence [A]; PAI [A,D]
- R4: Munich [D]; EU Omnibus [F,H]; CETS 225 [F,H]; IETF DRP/DAAP/AIP [B]; Sycophancy taxonomy [C]; TechPolicy.Press [A]; ISO 42006 [F]; Cognitive Agency Surrender [C]
- R5: JCCP 5431 [D]; NIST CAISI [B]; AgentGov-SC [A]; AMI Labs [E, competitive]
- R6: Accountability Horizon [A]; AARM [B]; Embodied runtime [B]; Cognitive Agency Surrender [C]; Causal-JEPA [E, competitive]
- R7: NIST [B]; Answerability Fuse [A,D]; AgentGov-SC [A]; Accountability Horizon [A]
- R8: NIST [B]; IETF delegation drafts [B]; GSDC [B]; Accountability Horizon [A]; AgentGov-SC [A]
- R9: EMILIA/PEDIGREE [B]; NIST [B]; GSDC [B]; Accountability Horizon [A]; Behavioural Assurance [A]
- R10: WIMSE delegation mapping [B]; Khipu Problem [A]
- R11: Atomic Decision Boundaries [B]; DEMM [A]
- R12: WIMSE layered mapping [B]; Tallam series [B]; DEMM-Bench [A]; world-model identifiability [E]
- R13: WIMSE adoption call [B]; controlled world-model identifiability [E]; trajectory assurance [B]
- R14: draft-klrc-03 [B]; Reg. 2026/1755 [D,H]; certificate-gated identifiability [E]; Governable Individuals [B]; revised PLD [A,D]
- R15: draft-ietf-wimse-aims-00 [B]; McCann [A,B]; LG Berlin II [D]; Justice EACL [A,B]
- R16: draft-das [B]; Governed Individuation [B]; "No One to Blame" [A]; Wu et al. [B]; draft-kroehl [B]; ACP [B]

Cluster totals from this coding: A 24, B 32, C 7, D 11, E 5, F 5, G 2, H 4 (all 78 rows coded at least once). The Section 2 legal-attribution trajectory split follows from this coding: R1–4 6, R5–10 2, R11–14 2, R15–16 1.

*Note on D by window:* R2 2 + R3 3 (Munich, Amazon, PAI) + R4 1 = 6 in R1–4; R5 1 + R7 1 = 2 in R5–10; R14 2 = 2 in R11–14; R15 1 = 1 in R15–16; total 11.

---

*All outputs are InterpretationArtifacts at Stage 01.*
*Layer 1 outputs are research-positioning artifacts — not legal opinions, patent opinions, prior-art findings, filing instructions, or authorization acts.*
*Proximity signals indicate architectural convergence only; they are not citations or IP claims.*
*No action authorized without RJ's explicit AuthorizationAct.*
*Save to: Reports/2026-10-05_Layer1_Run5_SCOPE-ALL.md*
