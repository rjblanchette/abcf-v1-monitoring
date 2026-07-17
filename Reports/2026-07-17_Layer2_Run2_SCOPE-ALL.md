# ABCF-v1 Corpus Analysis — Layer 2: IP Decision Node Mapping

DOCUMENT ID   : 2026-07-17_Layer2_Run2_SCOPE-ALL
LIFECYCLE     : Stage 01 — InterpretationArtifact
OUTPUT CLASS  : Structural Evaluation / Decision Node Map
AUTHORITY     : NOT_AUTHORIZED
RUN DATE      : 2026-07-17
PROMPT        : ABCF-v1_Corpus_Layer2_v1.0
CORPUS SCOPE  : ALL — Briefs Run 1–10 (2026-06-15 to 2026-07-17)
SUPERSEDES    : 2026-07-17_Layer2_Run1_SCOPE-ALL (Section 1 portfolio flags below resolved)

**This document does not contain legal opinions, prior art findings, or patentability assessments. It maps decision nodes and organizes corpus-derived facts for RJ and counsel's independent judgment. Filing-status facts in this run are drawn from the three project-knowledge documents RJ added (`UK_Refiling_Review_v2.md`, `ABCF-v1_IP_Status_2026-07-17.md`, `Publication_Control_Record.md`), which state they were verified against primary sources (WIPO RO/117 notices, UKIPO register, Zenodo records). This system has not independently re-verified those primary sources; it treats the three documents as the current record.**

---

## Section 1 — RJB IP portfolio context

### 1.1 UK filings — confirmed via UKIPO register

| GB Number | UKP Ref | Subject | Filed | Status |
|---|---|---|---|---|
| GB2605016.1 | UKP-01 | Institutional Rank | 08 Mar 2026 | Active |
| GB2605018.7 | UKP-02 | Controlled Rank Expansion | 08 Mar 2026 | Active |
| GB2605019.5 | UKP-03 | Governance Activation Interface | 08 Mar 2026 | Active |
| GB2605355.3 | UKP-04 | DOG (Declared-Origin Gate) | 12 Mar 2026 | Active |
| GB2605357.9 | UKP-05 | AWAP (Work Admissibility Packet) | 12 Mar 2026 | Active |
| GB2605360.3 | UKP-06 | IGA (Integrated Governance Architecture) | 12 Mar 2026 | Active |
| GB2609979.6 | UKP-10-RAC-01 | Residual Accountability Carrier | 28 Apr 2026 | Active — **KEEP decision made**, Paris/ePCT deadline 28 Apr 2027 |

Applicant consistent across all seven ("Robert John Blanchette"). Two probable title typos flagged for formality correction (GB2605016.1, GB2605018.7) — administrative, not substantive.

UKP-07-FTS, UKP-08-CVS, UKP-09-CMP: no filing numbers exist. Deferred, not drafting-ready.

### 1.2 PCT filings — all three withdrawn, refiling in progress

| Application | Filed | Status | Refiling window |
|---|---|---|---|
| PCT/CH2026/050009 (SPD) | 06 Mar 2026 | Withdrawn 07 Jul 2026 — non-payment | ~06 Mar 2027 |
| PCT/CH2026/050012 (SPD Continuation) | 19 Mar 2026 | Withdrawn 07 Jul 2026 — non-payment | ~19 Mar 2027 |
| PCT/CH2026/050013 (LID) | 19 Mar 2026 | Withdrawn 07 Jul 2026 — non-payment | ~19 Mar 2027 |

All three are independent first filings (no priority claim between them — corrects an earlier internal assumption). Publication suppression appears secured on the face of all three RO/117 notices; one confirmation item remains open (see Section 5, Node 6). No search fee paid, no ISR issued on any of the three.

### 1.3 Zenodo defensive publications — verified against Zenodo records

| Ref | Title | DOI | Published | Modified |
|---|---|---|---|---|
| P1 | Structural Limits of AI Accountability (SLT) | 10.5281/zenodo.18866882 | 04 Mar 2026 | 26 May 2026 (content of change unconfirmed) |
| P2 | TR-CNI-1.1: Causal Non-Interference | 10.5281/zenodo.20025045 | **04 May 2026** | 04 May 2026 |
| P3 | TR-LSPD-1.0 / TR-SA-1.1 | 10.5281/zenodo.19799074 | 26 Apr 2026 | — |
| P4 | Attribution, Surplus, and Governance (Economic Domain) | 10.5281/zenodo.20394642 | 25 May 2026 | — |
| P5 | Structural Indeterminacy and Legal Attribution | 10.5281/zenodo.19998537 | 03 May 2026 | 10 May 2026 |
| P6 | Creative Authorship and Structural Indeterminacy | 10.5281/zenodo.19998766 | 03 May 2026 | 10 May 2026 |
| P7 | Swiss Neutrality and National Coherence | 10.5281/zenodo.20596277 | 08 Jun 2026 | 09 Jun 2026 |
| P8 | Recognition Neutrality as Institutional Design | 10.5281/zenodo.20611099 | 09 Jun 2026 | — |

**Registry correction flag:** the project's canonical publication registry (used in Layer 2 Run 1 and in Tier 1 briefs) records P2's date as "March–April 2026." The verified Zenodo record states P2 published **04 May 2026**. This is a material correction — P2 is roughly five to eight weeks later than the canonical registry implies, which changes every priority-gap calculation involving P2 in Section 3 below. Recommend the canonical registry be corrected at source.

**P7 and P8 status clarification:** the IP-status document confirms these are political-theory/institutional-design publications **outside ABCF-v1's governance-IP scope** — not a gap in coverage, but a scope boundary. This reframes Section 4's earlier "P7/P8 not yet covered" framing from Run 1.

### 1.4 GitHub canonical

`rjblanchette/ABCF-v1`, `rjblanchette/ePCT`, and the monitoring repo are confirmed private (except the monitoring repo, which is public per project instructions — re-verify this distinction with RJ, as the IP-status document's private-repo confirmation does not explicitly carve out the public monitoring repo).

### 1.5 Key deadlines

| Date | Item |
|---|---|
| ~06 Mar 2027 | PCT/CH2026/050009 refiling window closes |
| ~19 Mar 2027 | PCT/CH2026/050012 and 050013 refiling windows close |
| **28 Apr 2027** | GB2609979.6 (RAC-01) Paris Convention / ePCT deadline |
| 04 May 2027 | US §102(b)(1) grace-period deadline for CNI content (filing decision on hold; deadline runs regardless) |

---

## Section 2 — Independent convergence risk register

The Run 1 register (all ~24 signals from Briefs 1–10) is unchanged in its facts and is not reproduced in full here — see the prior artifact for the complete table. This section restates only what changes now that live claim scope is known, and adds the risk dimension Run 1 could not assess: whether a signal sits in the same technical domain as an **active** filing, not just the published theory layer.

| Signal (from Run 1 register) | RJB pub(s) | Now mapped to live filing | Updated risk note |
|---|---|---|---|
| IETF EMILIA/PEDIGREE / WIMSE delegation-mapping cluster (Run 1→10, strongest convergence overall) | P1, P2, P3 | **GB2605355.3 (DOG)**, **GB2605357.9 (AWAP)**, and the PCT-02-LID refiling (governance-mediated execution / intercept-validate-gate) | This is now confirmed to sit in the same technical domain as three active or refiling-track claims (DOG, AWAP, LID governance kernel). The convergence line still lacks the identifiability-state precondition ABCF's claims turn on — but it is the corpus's highest-priority watch item precisely because it is closest to *filed* claim territory, not just published theory. |
| Tibebu Accountability Incompleteness / "Accountability Horizon" (Formal-depth, named parallel in P5) | P2, P5 | **GB2609979.6 (RAC-01)** — confirmed built directly on the Δ_AIT formula computed from Tibebu 2026's accountability residual | This is the corpus's most direct hit: RAC-01's claims are computed from the same formal result this external signal represents. RAC-01 is a **kept, active** filing with a hard 28 Apr 2027 deadline. This elevates the signal from "formal convergence with theory" to "formal convergence with an active claim's mathematical basis" — the single highest-priority item in this register. |
| Premise Governance / Jain et al. | P1, P2, P8 | GB2605019.5 (Governance Activation Interface) — plausible domain overlap, not confirmed | P8 is now understood to be outside ABCF-v1 IP scope (Section 1.3); the P1/P2 portion of this signal's relevance stands. |
| NIST AI Agent Standards Initiative / GSDC named-human-owner pattern | P1, P3 | GB2605016.1 (Institutional Rank), GB2605018.7 (Controlled Rank Expansion) — plausible domain overlap, not confirmed | Standards-body activity in the same conceptual space as two active UK filings' subject matter. Still identity-rooted, not identifiability-rooted, per the original brief language — the gap the filings are built to occupy. |
| AMI Labs / JEPA-class competitive bet | P3 | No direct filing mapping identified | Remains a competitive-positioning watch item, not a filing-adjacent risk. |

**Note on scope:** mapping proximity signals to specific claim numbers within each filing is outside what this system can do from monitoring-brief text alone (the briefs describe concepts, not claim language). The domain-level mappings above are this system's structural read for prioritization only — claim-level freedom-to-operate or novelty comparison is a task for counsel with the actual claim sets in hand.

---

## Section 3 — Publication sequencing observations (updated)

| Domain | RJB pub | Verified Zenodo date | Live filing in same domain | Filing date | External parallel (closest) | External date | Notes |
|---|---|---|---|---|---|---|---|
| Structural attribution impossibility | P5 | 03 May 2026 | GB2609979.6 (RAC-01) | 28 Apr 2026 | Tibebu AIT (arXiv:2604.07778) | 10 Apr 2026 | **RAC-01 filing (28 Apr) predates P5's publication (03 May) by 5 days, and both postdate the Tibebu external result (10 Apr) by 18 and 23 days respectively.** This is the sequencing fact most worth flagging to counsel — Tibebu's result was public before either the filing or the defensive publication it's connected to. |
| Causal non-interference | P2 | **04 May 2026 (corrected)** | None directly (PCT-03-CNI never filed — confirmed unfiled) | N/A | — | — | P2/TR-CNI-1.1 is now confirmed **prior art against RJB's own future UK/EPO filings** on the CNI-adjacent mechanisms it discloses (purge_Ψ, Identifiability Lattice, RAI-Γ, Audit Illusion detection, Fixed-Point Stability). This is a self-anticipation fact, not a third-party convergence risk — flagged in Section 5. |
| Named-integrator topology / delegation / execution gate | P3 | 26 Apr 2026 | GB2605355.3 (DOG), GB2605357.9 (AWAP), GB2605360.3 (IGA), PCT-02-LID refiling | 12 Mar 2026 (DOG/AWAP/IGA); 19 Mar 2026 (LID) | IETF DRP/DAAP/AIP → EMILIA/PEDIGREE → WIMSE cluster | First logged Jun 2026, still advancing 17 Jul 2026 | All four UK filings and the LID PCT predate P3's own Zenodo deposit by 6–7 weeks, and predate the first logged IETF convergence signal by roughly three months. Filing priority here looks comfortable on current information; the open question is whether the LID refiling (due ~19 Mar 2027) needs to move before the IETF track formalizes further — see Node 2. |
| Rank / institutional-rank architecture | P1 | 04 Mar 2026 | GB2605016.1 (UKP-01), GB2605018.7 (UKP-02) | 08 Mar 2026 | Tibebu AIT | 10 Apr 2026 | P1 predates both the filings (by 4 days) and the Tibebu result (by 37 days). Comfortable priority position. |
| Governance activation / execution interface | P1/P2 | 04 Mar 2026 / 04 May 2026 | GB2605019.5 (UKP-03) | 08 Mar 2026 | Verifiable Agentic Infra/DTF (arXiv:2605.15228) | ~May 2026 | Filing predates external item; P2's later-than-assumed date (04 May) does not affect this filing since it predates P2 as well. |
| Disownership / residual-carrier architecture (RAC-01 successor concept) | Not yet published | N/A — unfiled, undisclosed | **No filing exists** | N/A | None identified in corpus (P4/P5 general principle only, per IP-status doc §3.3) | N/A | Specific technical instantiation (AdmittedDomainQuantity, use-guard objects, RAT/Ledger structure) remains filable per the IP-status document's own analysis. The *general principle* is already disclosed via P4 (25 May 2026) and P5 (03 May 2026) — a claim drafted at that level of generality would now be self-anticipated. |
| Economic domain (attribution/surplus/governance) | P4 | 25 May 2026 | None identified | N/A | None found in corpus, Run 6–10 zero-convergence | N/A | No live filing and no external convergence — see Node 4 (unchanged from Run 1). |
| Legal attribution (general) / creative authorship | P5 / P6 | 03 May 2026 (both) | None identified | N/A | Oxford MLR piece; Munich/Google ruling; Amazon v. Perplexity; Thaler v. Perlmutter | Various, Run 2–3 window | Litigation-domain parallels, not competing publications — relevant to legal landscape only. |

---

## Section 4 — Defensive publication coverage assessment (updated)

**Covered by both defensive publication and active filing (dual protection posture):**
P1 → GB2605016.1, GB2605018.7. P3 → GB2605355.3, GB2605357.9, GB2605360.3, PCT-02-LID refiling. P5 → GB2609979.6 (RAC-01, via the Δ_AIT formula).

**Covered by defensive publication only, no corresponding filing (self-anticipation exposure for any future filing at that level of generality):**
P2 (TR-CNI-1.1) — confirmed no PCT-03-CNI filing was ever made. This publication now forecloses UK/EPO patent protection for purge_Ψ, the Identifiability Lattice, RAI-Γ, Audit Illusion detection, and Fixed-Point Stability as disclosed. A US-only §102(b)(1) grace-period filing remains theoretically available until **04 May 2027**, currently on hold. P4 (economic domain) and P5/P6 (legal/creative attribution, general principle only) — disclose general principles that would anticipate any future claim drafted at the same level of generality.

**Not yet covered by either publication or filing — implementation layer:**
The disownership/residual-carrier architecture (AdmittedDomainQuantity, the three use-guard prohibitions, Intake structural-completeness verification, topology-latency constraint L*, Minimum Monitoring Rate Condition) is fully drafted, unfiled, and undisclosed. The IP-status document identifies this as filable — it is more specific than what P4/P5 have already disclosed at the general-principle level. This is the clearest open coverage gap in the current portfolio.

**Outside ABCF-v1 IP scope (not a coverage gap):**
P7, P8 — political/institutional-design theory, confirmed by the IP-status document as having no governance-IP overlap.

---

## Section 5 — Corpus-derived decision nodes (updated)

**Node 1 — RAC-01 / Tibebu convergence (highest-priority node this run)**
- Information available: GB2609979.6 is a kept, active filing whose claims are computed directly from Tibebu 2026's accountability residual formula (Δ_AIT). The corpus's own monitoring record treats the Tibebu result as the single strongest formal-depth convergence found across all ten runs, and P5 itself names it as an independently-derived parallel.
- Information missing: Whether Tibebu's published formula (10 Apr 2026, predating both the RAC-01 filing and P5's publication) creates any prior-art exposure for RAC-01's specific claim language — a claim-level comparison this system cannot perform from monitoring-brief text.
- Time sensitivity: High — 28 Apr 2027 Paris Convention deadline is fixed and now less than 10 months out.
- Who decides: RJ + counsel.
- Blocking dependency: None upstream; this node should inform Q1 below directly.

**Node 2 — IETF standards-track line vs. DOG/AWAP/LID filings**
- Information available: The IETF EMILIA/PEDIGREE/WIMSE convergence line is confirmed to sit in the same technical domain as GB2605355.3, GB2605357.9, GB2605360.3, and the PCT-02-LID refiling (due ~19 Mar 2027). All four filings predate the standards-track line's first logged appearance by roughly three months, so priority looks comfortable on current information.
- Information missing: Whether the standards track has advanced far enough, or is likely to before the 19 Mar 2027 refiling deadline, to affect claim drafting for the new UK filing (e.g., whether to draft claims that anticipate the standards language, or avoid tracking it too closely per the novelty-exposure discipline already applied to Zenodo publications).
- Time sensitivity: Medium-high — tied to the 19 Mar 2027 refiling window, not immediate.
- Who decides: RJ + counsel, informed by continued Tier 1 monitoring.
- Blocking dependency: None identified.

**Node 3 — Disownership/residual-carrier architecture filing decision**
- Information available: Fully drafted, undisclosed, confirmed filable at the specific-instantiation level (general principle already disclosed via P4/P5). No external convergence signal in the corpus currently touches this specific architecture.
- Information missing: Filing budget/sequencing relative to the three PCT refilings and any new UK filing for SPD/LID.
- Time sensitivity: Low-medium — no external convergence pressure identified, but the general-principle disclosure via P4/P5 (already public since 25 May 2026) means the longer this waits, the more risk that an independent third party arrives at the specific instantiation on their own, even absent current evidence of that happening.
- Who decides: RJ + counsel.
- Blocking dependency: Competes for drafting/filing resources with Node 5 (SPD/LID refiling) — a portfolio-sequencing question.

**Node 4 — P4/P7/P8 zero-convergence / scope note (revised from Run 1)**
- Information available: P4 has five consecutive runs of zero external convergence and no corresponding filing. P7/P8 are now confirmed **outside ABCF-v1's governance-IP scope entirely** — Run 1's framing of these as an open "not yet covered" question no longer applies to P7/P8.
- Information missing: Whether P4's zero-convergence changes any filing calculus, given no filing currently exists in that domain.
- Time sensitivity: Low.
- Who decides: RJ + counsel, lower priority than Nodes 1–3.
- Blocking dependency: None.

**Node 5 — SPD/LID UK refiling shape and content**
- Information available: Three independent ~1-year refiling windows (no shared priority), so no single deadline forces simultaneous filing. Content questions (API/second-derivative-of-rank placement, LID Art. 34 Group III, merge-or-split of the two SPD filings) are now pure drafting/architecture decisions, not priority-driven ones.
- Information missing: None — the UK Refiling Review document identifies these as resolved to pure judgment calls.
- Time sensitivity: Medium — earliest window (~06 Mar 2027) is under 8 months out.
- Who decides: RJ + counsel (drafting), RJ (budget/sequencing).
- Blocking dependency: Shares drafting bandwidth with Node 3.

**Node 6 — Confirm ePCT non-publication outcome (administrative, not strategic)**
- Information available: Publication suppression appears secured on the face of all three RO/117 notices; not yet confirmed against the ePCT status page directly.
- Information missing: The explicit ePCT confirmation itself.
- Time sensitivity: Low but easy to close.
- Who decides: RJ or counsel, administrative check.
- Blocking dependency: None — worth closing simply because it is cheap to close.

**Node 7 — Corpus synthesis lag (carried from Run 1, unchanged)**
- Layer 1 remains at Run 2, unabsorbed on Briefs 6–10. Not resolved by this session's IP-data update. Still a process node, not a substance node.

---

## Section 6 — Questions for counsel

```
Q1 — RAC-01 / Tibebu formal convergence (Node 1)
Context: GB2609979.6's claims are computed from Tibebu 2026's Δ_AIT accountability-residual formula, published 10 Apr 2026 — before both the 28 Apr 2026 RAC-01 filing and the 03 May 2026 P5 publication that names Tibebu as an independent parallel.
Question: Does Tibebu's prior publication of the same formal result create any prior-art or inventorship exposure for RAC-01's specific claims, and does the 28 Apr 2027 Paris deadline need to be treated as a hard drafting-review checkpoint given this timing?
Time sensitivity: High
Blocking: None upstream — feeds directly into RAC-01 prosecution strategy

Q2 — IETF standards-track proximity to DOG/AWAP/LID (Node 2)
Context: An active IETF standards line (EMILIA/PEDIGREE/WIMSE) sits in the same technical domain as GB2605355.3, GB2605357.9, GB2605360.3, and the PCT-02-LID refiling (due ~19 Mar 2027), though it currently lacks the identifiability-state precondition those filings are built around.
Question: Should the new LID UK filing's claim drafting account for the standards-track language in any way (either to distinguish over it explicitly or to avoid the self-anticipation pattern already identified for the Zenodo publications), and is continued Tier 1 monitoring sufficient, or does this warrant a specific claims review before the 19 Mar 2027 window?
Time sensitivity: Medium-high
Blocking: Node 5 drafting

Q3 — Disownership/residual-carrier filing timing (Node 3)
Context: A fully-drafted, undisclosed architecture (AdmittedDomainQuantity, use-guard objects, RAT/Ledger structure) remains filable at the specific-instantiation level; its general principle has been public since 25 May 2026 via P4.
Question: Given no filing budget conflict has been resolved between this and the SPD/LID refilings, what filing sequence best manages the residual risk that a third party independently arrives at the specific instantiation, versus available drafting/filing resources?
Time sensitivity: Medium
Blocking: Competes with Node 5 for resources

Q4 — TR-CNI-1.1 self-anticipation and the US-only route (carried, now confirmed rather than hypothetical)
Context: PCT-03-CNI was never filed; TR-CNI-1.1 (published 04 May 2026) is confirmed prior art against RJB's own future UK/EPO claims on purge_Ψ, the Identifiability Lattice, RAI-Γ, Audit Illusion detection, and Fixed-Point Stability. The US §102(b)(1) grace-period route remains open until 04 May 2027 and is currently on hold.
Question: Should the US-only CNI filing decision be revisited now, given confirmed deadline math, or does it remain correctly deferred?
Time sensitivity: Medium (deadline is fixed, currently ~9.5 months out)
Blocking: None

Q5 — P4/P7/P8 posture (Node 4, lower priority — carried and narrowed from Run 1)
Context: P7/P8 are now confirmed outside ABCF-v1 IP scope. P4 has five consecutive runs of zero external convergence and no corresponding filing.
Question: Is any filing contemplated for P4-domain content, or does its zero-convergence status simply confirm no action is needed at this time?
Time sensitivity: Low
Blocking: None
```

---

## Section 7 — Summary brief for counsel

RJB operates a structured monitoring system (ABCF-v1) that runs periodic live searches against concepts drawn from an eight-part theoretical publication corpus (P1–P8, defensively published on Zenodo, March–June 2026), logging external "proximity" and "competitive" signals against that corpus. This report synthesizes ten monitoring runs (15 June–17 July 2026) against a now-confirmed patent portfolio: seven active UK filings (GB2605016.1 through GB2609979.6, filed March–April 2026), three PCT applications withdrawn 7 July 2026 for non-payment with publication suppression apparently secured and independent one-year refiling windows running through March 2027, and one Zenodo publication (TR-CNI-1.1) confirmed to have no corresponding filing at all.

The single most significant finding of this run is that the corpus's strongest formal-depth external convergence — an academic impossibility result (Tibebu, 2026) that RJB's own P5 publication names as an independently-derived parallel — is not just a theoretical proximity signal. GB2609979.6, a kept and active UK filing with a Paris Convention deadline of 28 April 2027, is built directly on a formula computed from that same external result. The external publication predates both the filing and RJB's own defensive publication of the connected theory by several weeks.

The second significant finding is that the corpus's most active convergence line — a live IETF standards-track effort building rooted-authorization and execution-gate architecture — sits in the same technical domain as four of RJB's filings (three UK, one PCT refiling), all of which currently predate the standards line's first logged appearance by roughly three months. Priority looks comfortable on current information, but the standards track continues to advance and one of the affected filings (PCT-02-LID) is not due for UK refiling until March 2027, leaving a window in which the external line could move further before RJB's claims are re-filed.

Separately, one already-published Zenodo report (TR-CNI-1.1) is confirmed to have no corresponding patent filing behind it; RJB's own team has flagged this as having foreclosed UK/EPO protection for the specific mechanisms it discloses, leaving only a time-limited US grace-period route (through 4 May 2027) currently on hold. A separate, fully-drafted implementation architecture (a residual-accountability "disownership" mechanism, distinct from the already-filed RAC-01) remains undisclosed and unfiled, and appears — on the corpus record and on RJB's own internal review — to remain available for filing at its specific technical level, though its general principle has already been disclosed via two other publications.

This document is a Stage 01 InterpretationArtifact produced by a structured monitoring system. It does not constitute legal advice, a prior art search, or a patentability assessment. All decisions remain with RJ Blanchette and qualified counsel.
