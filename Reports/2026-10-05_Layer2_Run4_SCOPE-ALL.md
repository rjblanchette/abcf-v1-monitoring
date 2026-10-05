# ABCF-v1 Corpus Analysis — Layer 2: IP Decision Node Mapping

DOCUMENT ID   : 2026-10-05_Layer2_Run4_SCOPE-ALL
LIFECYCLE     : Stage 01 — InterpretationArtifact
OUTPUT CLASS  : Structural Evaluation / Decision Node Map
AUTHORITY     : NOT_AUTHORIZED
RUN DATE      : 2026-10-05
PROMPT        : ABCF-v1_Corpus_Layer2_v1.0
CORPUS SCOPE  : ALL — Briefs Run 1–16 (2026-06-15 to 2026-10-05). Scope not stated in the invocation; ALL assumed to match Layer 1 Run 5 (same date, same corpus).
BASELINES READ: 2026-08-21_Layer2_Run3_SCOPE-ALL; 2026-10-05_Layer1_Run5_SCOPE-ALL
SUPERSEDES    : 2026-08-21_Layer2_Run3_SCOPE-ALL (Section 1 carried forward; Sections 2–6 extended with Runs 15–16 and corrected where noted in Section 0)

**This document does not contain legal opinions, prior art findings, freedom-to-operate analyses or patentability assessments. It maps decision nodes and organizes corpus-derived facts for RJ and counsel's independent judgment. Filing-status facts come from the three project-knowledge documents (`UK_Refiling_Review_v2.md`, `ABCF-v1_IP_Status_2026-07-17.md`, `Publication_Control_Record.md`), all dated 17 July 2026. No newer portfolio-status document exists in project knowledge; they now predate this report by 80 days. This system has not re-verified WIPO, UKIPO or Zenodo records this run.**

---

## Section 0 — Method note and corrections to Layer 2 Run 3

**Corpus.** `briefs/` of `rjblanchette/abcf-v1-monitoring`, shallow clone of `main` on 2026-10-05 (HEAD `1fd139b`). Sixteen briefs read; Briefs 15 and 16 read in full, Briefs 1–14 re-checked for dates and flag lines. Flag counts and cluster coding are quoted from Layer 1 Run 5 (76 proximity rows, 2 competitive rows, 0 direct citations), not recounted here.

**Limits that apply throughout.**
- Run 15–16 characterizations of arXiv and IETF items rest largely on summary-level extraction (Run 16 §6). Claim-level wording needs a full-text check before anything relies on it.
- Every "no patent filing detected" in earlier reports means *no filing was mentioned in retrieved sources*. The word "patent" appears in only seven brief lines across all sixteen briefs, and no brief records a search of a patent register or patent database. This corpus has never been a patent-literature search (see Node 14).
- Dates below are as recorded in the briefs. Where a brief records only a month or an arXiv ID, the day is marked unresolved.

**Corrections to Layer 2 Run 3.** These change statements that Run 3 relied on.

1. **Fernandez row (Run 3 §2).** The risk note states both that the source predates and postdates P1. The correct reading: arXiv:2604.17511 (April 2026) postdates P1 (4 Mar) and the March filings; its day relative to P3 (26 Apr) and RAC-01 (28 Apr) is unresolved.
2. **Priority framing for the execution-gate row (Run 3 §3).** Run 3 said the filings "predate this external item by ~4 months" and that priority "looks comfortable". That compared the filings to the *latest* item in the cluster (draft-klrc-aiagent-auth-03, 6 Jul). Several of the *earliest* items in the same cluster are dated before or inside the March 2026 filing window (Section 3.2). Layer 1 Run 5 correction 4 reached the same point for the Zenodo dates. Run 2's "comfortable priority position" wording should not be carried forward.
3. **Node 7 premise.** Run 3 said no UK/PCT filing covers latent-space identifiability. The official title on file for PCT/CH2026/050012 (per `UK_Refiling_Review_v2.md` §2) is "System and Method for Managing Identifiability of Causal Contrasts via Equivalence-Class Collapse and Intervention Refinement", with a refiling window to ~19 Mar 2027. Whether that subject matter overlaps TR-LSPD-1.0's content is not determinable here, but Node 7 as framed was incomplete. Refined in Section 5.
4. **P4 and P8 counts.** Run 3 described P4 as zero-convergence in all fourteen runs and Run 14 as P8's first-ever signal. Per Layer 1 Run 5 correction 2, P8 is tagged in Runs 1, 4 and 14 and P4 in Runs 3 and 15. Only P7 is zero on all sixteen runs. Layer 1 Run 5 also reads the P8 hits as loose and leans toward a clean null.
5. **Repeat appearances.** About 16 of 76 flag rows are repeat appearances of an already-flagged source (Layer 1 Run 5 correction 5). Row counts in Run 3 overstate distinct sources.
6. **Repository visibility.** Run 3 §1.4 repeated the IP-status document's statement that repos are private and noted the monitoring repo is public per project instructions. This session cloned the monitoring repo anonymously through the git proxy, which is consistent with it being public. See Node 11.
7. **P2 date.** The registry in the project instructions still gives P2 as "March–April 2026". The Publication Control Record gives 04 May 2026. This report uses 04 May 2026.

---

## Section 1 — RJB IP portfolio context (from project knowledge)

*Carried forward unchanged from Run 3. No project-knowledge document is newer than 17 July 2026. If any filing, amendment or disclosure has occurred since, this section is stale (Node 0).*

### 1.1 UK filings (UKIPO register, as of 17 Jul 2026)

| GB Number | UKP Ref | Subject | Filed | Status |
|---|---|---|---|---|
| GB2605016.1 | UKP-01 | Institutional Rank | 08 Mar 2026 | Active |
| GB2605018.7 | UKP-02 | Controlled Rank Expansion | 08 Mar 2026 | Active |
| GB2605019.5 | UKP-03 | Governance Activation Interface | 08 Mar 2026 | Active |
| GB2605355.3 | UKP-04 | DOG (Declared-Origin Gate) | 12 Mar 2026 | Active |
| GB2605357.9 | UKP-05 | AWAP (Work Admissibility Packet) | 12 Mar 2026 | Active |
| GB2605360.3 | UKP-06 | IGA (Integrated Governance Architecture) | 12 Mar 2026 | Active |
| GB2609979.6 | UKP-10-RAC-01 | Residual Accountability Carrier | 28 Apr 2026 | Active — KEEP decision made; Paris/ePCT deadline 28 Apr 2027 |

Applicant name consistent across all seven. Probable title typos on GB2605016.1 and GB2605018.7 (administrative). UKP-07-FTS, UKP-08-CVS and UKP-09-CMP: no filing numbers; deferred.

### 1.2 PCT filings — all withdrawn 07 Jul 2026 for non-payment

| Application | Filed | Title on file (abbreviated) | Refiling window |
|---|---|---|---|
| PCT/CH2026/050009 (SPD) | 06 Mar 2026 | Structural probe domain generation in adaptive AI governance systems | ~06 Mar 2027 |
| PCT/CH2026/050012 (SPD Continuation) | 19 Mar 2026 | Managing identifiability of causal contrasts via equivalence-class collapse and intervention refinement | ~19 Mar 2027 |
| PCT/CH2026/050013 (LID) | 19 Mar 2026 | Governance-mediated execution using a governance encoding system | ~19 Mar 2027 |

All three are independent first filings with no priority claim between them. Publication suppression appears secured on the face of the RO/117 notices; the explicit ePCT confirmation is still open (Node 6). No search fee paid; no ISR issued.

### 1.3 Zenodo defensive publications (verified against Zenodo records, 17 Jul 2026)

| Ref | Title | DOI | Published | Modified |
|---|---|---|---|---|
| P1 | Structural Limits of AI Accountability | 10.5281/zenodo.18866882 | 04 Mar 2026 | 26 May 2026 (content change unconfirmed) |
| P2 | TR-CNI-1.1: Causal Non-Interference | 10.5281/zenodo.20025045 | 04 May 2026 | 04 May 2026 |
| P3 | TR-LSPD-1.0 / TR-SA-1.1 | 10.5281/zenodo.19799074 | 26 Apr 2026 | — |
| P4 | Attribution, Surplus, and Governance | 10.5281/zenodo.20394642 | 25 May 2026 | — |
| P5 | Structural Indeterminacy and Legal Attribution | 10.5281/zenodo.19998537 | 03 May 2026 | 10 May 2026 |
| P6 | Creative Authorship and Structural Indeterminacy | 10.5281/zenodo.19998766 | 03 May 2026 | 10 May 2026 |
| P7 | Swiss Neutrality and National Coherence | 10.5281/zenodo.20596277 | 08 Jun 2026 | 09 Jun 2026 |
| P8 | Recognition Neutrality as Institutional Design | 10.5281/zenodo.20611099 | 09 Jun 2026 | — |

P7 and P8 are recorded as outside ABCF-v1 governance-IP scope. Zenodo timestamps are treated here as recorded, not as legally confirmed priority dates.

### 1.4 GitHub

`rjblanchette/ABCF-v1` and `rjblanchette/ePCT`: private as of 17 Jul 2026 per the IP-status document. `rjblanchette/abcf-v1-monitoring`: public per project instructions and consistent with this session's anonymous clone. The IP-status document's private-repo confirmation does not carve out the monitoring repo (Node 11).

### 1.5 Status flagged as uncertain or requiring verification

- Currency of all portfolio facts after 17 Jul 2026 (Node 0).
- ePCT non-publication outcome (Node 6).
- Whether the 26 May 2026 modification of P1 changed substantive content.
- Whether the drafted-but-unfiled UKP-02 continuation content described in IP-status document §2 is already public via P2 (the document says to verify against P2 before drafting). Terms not repeated here (Node 11).
- Retrieval of the remaining LID claim-group content (UK Refiling Review §3.3).

### 1.6 Key deadlines (days from 05 Oct 2026)

| Date | Days | Item |
|---|---|---|
| ~06 Mar 2027 | 152 | PCT/CH2026/050009 refiling window |
| ~19 Mar 2027 | 165 | PCT/CH2026/050012 and 050013 refiling windows |
| 28 Apr 2027 | 205 | GB2609979.6 (RAC-01) Paris Convention / ePCT deadline |
| 04 May 2027 | 211 | US §102(b)(1) grace-period deadline for CNI content (on hold; deadline runs regardless) |

---

## Section 2 — Independent convergence risk register

Register rows for Runs 1–14 are carried by reference to Layer 2 Run 2 §2 and Run 3 §2, with the corrections in Section 0. This section adds the signals logged in **Briefs 15–16** (16 items reviewed; 10 flagged: 4 in Run 15, 6 in Run 16, one of which Run 16 itself calls borderline). Convergence depth is as coded in the brief, not re-derived. RJB dates: UK filings 08/12 Mar 2026, PCT filings 06/19 Mar 2026, RAC-01 28 Apr 2026, Zenodo dates per §1.3.

| Signal | Source | Date | RJB concept | RJB priority date | Convergence depth | Risk note |
|---|---|---|---|---|---|---|
| Justice, "Accountability After the Horizon" (Execution Authority Control Layer, EACL) | SSRN 7202899 (Alethera, Inc.) | PDF created 28 Jul 2026; SSRN posting date not retrieved. Author states the design predates the Tibebu theorem (Apr 2026); unverified company claim | P1, P2, P3/TR-SA-1.1, P4, P5 in the brief. Architecturally: pre-execution declaration, fail-closed ALLOW/HOLD/DENY gate, narrowing delegation, attestation chain | UK 08/12 Mar 2026 (DOG/AWAP/IGA); PCT 19 Mar 2026 (LID); P3 26 Apr 2026 | Structural (brief's coding). Brief calls it the densest authority-side overlap in the corpus | PDF postdates the UK filings by ~138–142 days and P3 by ~93 days; the author's earlier design-date claim is unverified. Same technical domain as GB2605355.3, GB2605357.9, GB2605360.3 and the LID refiling. **Author discloses two US provisional applications (64/021,779; 64/062,705), filing dates not stated.** Working paper; proofs and evaluation deferred to an announced companion. First item in the corpus where a third party discloses its own patent filings |
| draft-ietf-wimse-aims-00 (formerly draft-klrc-aiagent-auth) | IETF Datatracker | 15 Sep 2026 (-00 of the WG document); individual-draft -03 was 6 Jul 2026; -01/-02 June 2026; date of the individual draft's own -00 not recorded in the corpus | P1 (CVG Separation Invariant), P3/TR-SA-1.1 (Rooted Authority Invariant, containment boundary) | UK 12 Mar 2026; PCT 19 Mar 2026; P1 04 Mar 2026; P3 26 Apr 2026 | Structural. No identifiability condition (brief) | The 15 Sep text postdates the filings by ~180–187 days and P3 by 142. The first appearance of the underlying individual draft is not dated in the corpus. Same domain as DOG/AWAP/IGA and LID. Now a WG-owned standards-track document (IESG state "I-D Exists"; WGLC not yet active). Standards-body publication, not a patent filing. Six co-authors from major identity/AI vendors (Run 14) |
| draft-das-accountable-autonomous-effectuation-01 | IETF Independent Submission | 23 Sep 2026 (-01); -00 date not retrieved | P1, P2 (fail-closed pre-effect gate; computation does not confer authority) | UK 12 Mar 2026; PCT 19 Mar 2026; P2 04 May 2026 | Structural on the gate; Surface on authority separation | Postdates filings by ~195–199 days. Same domain as DOG/AWAP/IGA. Informational independent submission, not a WG item. Extraction-level characterization |
| draft-kroehl-agentic-trust-aae-02 | IETF individual draft (CryptoKRI GmbH) | 6 Sep 2026 (-02); earlier revisions not retrieved | P3/TR-SA-1.1 (principal-rooted mandate, monotone delegation, fail-closed rejection) | UK 12 Mar 2026; P3 26 Apr 2026 | Surface to Structural | Postdates filings by ~171–182 days. Same domain as DOG/AWAP/IGA/LID. Vendor specification for the author's own architecture; informational |
| McCann "structural governance" cluster (arXiv:2604.27292, 2604.27289; companions 2605.01030/01032/01037; `mashin-live/governance-proofs`) | arXiv; GitHub (Mashin, Inc.) | April 2026 and May 2026; submission days not retrieved | P1, P2 (mandatory complete effect gate; behavioral evidence insufficient) | UK 12 Mar 2026; PCT 19 Mar 2026; RAC-01 28 Apr 2026; P3 26 Apr; P2 04 May | Structural; mechanized proofs (brief) | Postdates the March filings. Relative to P3 (26 Apr), RAC-01 (28 Apr) and P2 (04 May) is **unresolved**: the brief says before P2, after P1. Same domain as DOG/AWAP/IGA. Industry author; public proof repository. Patent status of the author's architecture not checked |
| Governed Individuation / Governable Individuals | arXiv:2607.04613; arXiv:2607.05463 | 6 Jul 2026 (v1 both); Governable Individuals v2 15 Jul 2026 | P3/TR-SA-1.1 (Rooted Authority Invariant; Integrator's Burden Corollary; verifier-soundness assumption) | P3 26 Apr 2026; UK 12 Mar 2026 | Structural; formal bound conditional on a sound effect abstraction | Postdates P3 by ~71 days and the UK filings by ~116 days. Authority-side domain (DOG/IGA/LID). Academic preprints; companion proofs now located. No filing mentioned |
| Agent Control Protocol (Fernandez, TraslaIA) | arXiv:2603.18829, v1.30 | **March 2026 by arXiv ID**; one extraction gave April; spec updated through late April; first-submission day unresolved | P3/TR-SA-1.1 (institutional root, narrowing delegation, admission before execution) | UK 08/12 Mar 2026; PCT 06/19 Mar 2026; P1 04 Mar 2026 | Surface (brief); model-checked gate in TLA+ | **Same month as all four filing dates; day unresolved.** Postdates P1 on the ID. Same domain as DOG/AWAP/IGA/LID. Industry author, public specification and reference implementation. Patent status not checked. See Section 3.2 and Node 9 |
| "No One to Blame" (Nguyen, Späthe, Lins, Sunyaev) | arXiv:2608.12104; AIES 12–14 Oct 2026 | Aug 2026 | P1, P5 (accountability "unachievable, not merely obstructed") | P1 04 Mar 2026; P5 03 May 2026 | Surface (analogical; qualitative) | Postdates P1 by ~5 months. Not in a live-filing domain (maps to P1/P5 theory). Peer-reviewed venue. No filing mentioned |
| Wu, Wang, Zhang, authority decomposition | arXiv:2608.18965 | 19 Aug 2026 | P3/TR-SA-1.1 (nominal vs substantive authority) | P3 26 Apr 2026 | Surface; flag borderline (brief) | Postdates P3 by ~115 days. Industry author analysing own protocol. Layer 1 may downgrade the flag |
| Legal-attribution items: LG Berlin II 52 O 62/26 (1 Jun 2026); *Amazon v. Perplexity* (9th Cir., 4 Aug 2026) | Court decisions via secondary commentary | Jun / Aug 2026 | P5 | P5 03 May 2026 | Structural at the legal-proxy level (Berlin flagged; Ninth Circuit held below threshold) | Berlin postdates P5 by 29 days; Ninth Circuit by ~93 days. Not patent-domain items; included for informational completeness |

**Observations about this register (corpus facts, not conclusions).**
- Seven of the ten new flag rows (Justice, aims-00, das, kroehl, McCann, Governed Individuation, ACP) sit in the technical domain of the DOG/AWAP/IGA/LID cluster. None attaches an identifiability condition (briefs' own characterization).
- Layer 1 Run 5 counts about 22 distinct author groups in this cluster. Eight cluster rows fall in the Run 15–16 window, five of them backfill dated before 21 Aug, so the apparent acceleration partly reflects discovery date rather than publication date.
- Run 3's two deepest observations (WIMSE layered mapping; draft-klrc-03 §10.7/§8) have both progressed: §10.7, §8 and §11 text carried into the WG document (Run 15 Item 1).
- Mapping signals to specific claims is outside what this system can do from brief text. The domain-level mapping is a prioritization read only.

---

## Section 3 — Publication sequencing observations

### 3.1 Domain table (extended with filing dates)

Priority gap = days by which the RJB item precedes (+) or follows (−) the external item. Where only a month is recorded, the gap is not computed.

| Domain | RJB pub | Zenodo date | Live filing / date | External parallel | External date | Priority gap (days) | Notes |
|---|---|---|---|---|---|---|---|
| Execution gate / delegation / named-integrator topology (DOG, AWAP, IGA, LID) | P3 (also P1, P2) | P3 26 Apr 2026; P1 04 Mar 2026 | UK 12 Mar 2026 (DOG/AWAP/IGA); PCT 19 Mar 2026 (LID, refiling ~19 Mar 2027) | **Earliest-dated items:** Audit Trails (Jan 28), Premise Governance v1 (Feb 2) / v2 (Mar 25), IETF DAAP/AIP (Mar), HDP (IETF Mar), ACP (Mar). **Latest:** draft-ietf-wimse-aims-00 (15 Sep) | See 3.2 | Earliest items: Audit Trails and Premise Governance v1 are dated 38–50 days *before* the DOG/AWAP/IGA/LID filings (RJB gap −38 to −50); several March items unresolved. Latest item: filings precede by ~187 days | Dating audit in 3.2. Whether any of these items discloses a claim element of the filings is a claim-level question for counsel. This row replaces Run 3's "comfortable priority" wording |
| Execution gate: third-party filings | P3 | 26 Apr 2026 | As above | Justice EACL (disclosed US provisionals 64/021,779; 64/062,705) | Provisional filing dates not stated; PDF 28 Jul 2026 | Not computable | First corpus item with disclosed third-party applications. Dates, claims and any publication status are unknown (Node 10) |
| Structural attribution impossibility (RAC-01) | P5 (P1) | P5 03 May 2026; P1 04 Mar 2026 | GB2609979.6, 28 Apr 2026 | Tibebu AIT (arXiv:2604.07778), 10 Apr 2026; McCann (Rice) April 2026; Justice builds on Tibebu | 10 Apr 2026 | RAC-01 follows Tibebu by 18 days; P5 by 23; P1 precedes Tibebu by 37 | Unchanged facts (Node 1). Justice (Jul) is the first governance architecture built on Tibebu and treats the limit as terminal; it postdates RAC-01 by ~91 days |
| Rank / institutional rank | P1 | 04 Mar 2026 | GB2605016.1, GB2605018.7 — 08 Mar 2026 | Tibebu AIT | 10 Apr 2026 | P1 precedes Tibebu by 37 days; filings by 33 | Unchanged |
| Governance activation interface | P1/P2 | 04 Mar / 04 May 2026 | GB2605019.5 — 08 Mar 2026 | DTF (arXiv:2605.15228) | 13 May 2026 | Filing precedes by 66 days | Unchanged. Premise Governance v1 (2 Feb) is dated before this filing (−34 days); mapping flagged "plausible, not confirmed" in Run 2 |
| Latent-space / world-model identifiability (TR-LSPD-1.0) | P3 | 26 Apr 2026 | **Possible overlap with PCT/CH2026/050012 (19 Mar 2026; refiling ~19 Mar 2027); UK filings do not cover it** | Tan et al. (2607.27017) 29 Jul; Zhang et al. (2607.22430) Jul; Kori & Russo (2608.13456) 3 Sep; InfluenceField (2609.07874) Sep | Jul–Sep 2026 | P3 precedes Tan by 94 days; PCT 050012 by 132 | Four consecutive §3b runs; no governance claim anywhere. Node 7 refined |
| Epistemic authority / sycophancy (CVG) | P1/P2 | 04 Mar / 04 May 2026 | None mapped | Holland, "Authority Inversion" (Zenodo 20150722), 11 Jan 2026 | 11 Jan 2026 | External item **precedes P1 by 52 days** | Surface depth (Run 16 weak signal); Zenodo-to-Zenodo. No flag since Run 6 at item level. No filing mapped |
| Economic (attribution / surplus) | P4 | 25 May 2026 | None | Justice (DOG-analogue only); none for Surplus Governability / Non-Conversion | Jul 2026 | — | Core economic concepts null across sixteen runs (vocabulary-bound; Layer 1 Run 5 §5) |
| Legal attribution | P5 | 03 May 2026 | None | Berlin II (1 Jun), München I (~28 May), 9th Cir. (4 Aug), revised PLD | 2026 | P5 precedes each by ~25–93 days | Not patent-domain. Three courts, three proxies |
| Creative authorship | P6 | 03 May 2026 | None | Andersen trial reported moved to 5 Apr 2027 (single secondary source) | — | — | No near-term anchor |
| Disownership / residual-carrier architecture | Not published (general principle in P4/P5) | N/A | None filed | None found | — | — | Component-level terms deliberately not repeated here (Node 11). General principle public since 03 May / 25 May 2026 |

### 3.2 Dating audit — execution-gate / delegation line against the March 2026 filing window

Negative = the external item is dated *before* the filing. All dates as recorded in the briefs.

| Source | Date as recorded | Day resolved? | vs UK DOG/AWAP/IGA (12 Mar) | vs LID PCT (19 Mar) | vs P1 (4 Mar) |
|---|---|---|---|---|---|
| Audit Trails for LLMs, arXiv:2601.20727 | 28 Jan 2026 | Yes | −43 | −50 | −35 |
| Premise Governance, arXiv:2602.02378, **v1** | 2 Feb 2026 | Yes | −38 | −45 | −30 |
| Premise Governance, **v2** | 25 Mar 2026 | Yes | +13 | +6 | +21 |
| draft-mishra-oauth-agent-grants-01 (DAAP) | March 2026; -00 date not recorded | No | unresolved | unresolved | unresolved |
| draft-prakash-aip-00 (AIP) | 27 Mar 2026 | Yes | +15 | +8 | +23 |
| Helixar HDP | IETF draft March 2026 (day not recorded); arXiv 6 Apr 2026 | Partly | IETF: unresolved; arXiv +25 | IETF: unresolved; arXiv +18 | IETF: unresolved |
| Agent Control Protocol, arXiv:2603.18829 | March 2026 by ID; one extraction said April; versions to v1.30 in late April | No | unresolved | unresolved | after, on ID |
| draft-nelson-agent-delegation-receipts-09 (DRP) | 21 May 2026 for -09; -00 to -08 dates not recorded | No | unresolved | unresolved | unresolved |
| draft-klrc-aiagent-auth | -01, -02 June; -03 6 Jul; -00 date not recorded | No | unresolved | unresolved | unresolved |
| Tibebu AIT, arXiv:2604.07778 | 10 Apr 2026 | Yes | +29 | +22 | +37 |
| Fernandez ADB, arXiv:2604.17511 | April 2026 | No | after | after | after |
| McCann, arXiv:2604.27292 / 27289 | April 2026 | No | after | after | after |

**Facts this table records.**
1. Two items (Audit Trails; Premise Governance v1) are dated before every UK and PCT filing. Premise Governance's v2 is dated after all UK filings and the 6 and 19 Mar PCT filings. What changed between v1 and v2 is not recorded.
2. At least five further items are dated "March 2026" or have an unrecorded first-revision date. For the IETF drafts, the Datatracker holds timestamped revision histories that this corpus has not retrieved.
3. The corpus's "closest language" characterizations (klrc-03 §10.7/§8) were made against revision -03 (6 Jul). The earlier revisions' text and dates were not examined.
4. Whether any pre-filing or same-month item discloses an element claimed in DOG, AWAP, IGA or LID is a claim-level question this system cannot answer. The Layer 1 classification of every one of these items is "Coherent but incomplete", and the briefs record no identifiability condition in any of them. That is a monitoring characterization, not a prior-art determination.
5. P1's 26 May 2026 modification is unconfirmed as to content. If content changed, the dating of changed content would differ from 04 Mar 2026.

Do not treat any gap above as a legal sufficiency determination. All gaps are flagged for counsel.

---

## Section 4 — Defensive publication coverage assessment

**Covered by defensive publication and an active filing (dual posture), unchanged:**
P1 → GB2605016.1, GB2605018.7. P3 → GB2605355.3, GB2605357.9, GB2605360.3, LID refiling. P5 → GB2609979.6 (via the Δ_AIT formula).

**Covered by defensive publication only, no filing (self-anticipation exposure at that level of generality), unchanged:**
P2 (TR-CNI-1.1): no PCT-03-CNI was filed. Publication forecloses UK/EPO protection for purge_Ψ, the Identifiability Lattice, RAI-Γ, Audit Illusion detection and Fixed-Point Stability as disclosed. The US §102(b)(1) route runs to 04 May 2027 and is on hold (Node 13). P4, P5 and P6 disclose general principles that would anticipate claims drafted at the same level of generality. Also per the IP-status document: the drafted-but-unsubmitted LID amendment content and the drafted-but-unfiled UKP-02 continuation content are described as likely already public through P2 (unverified).

**Not covered by publication or filing — implementation layer (unchanged in status; currency unverified):**
The disownership / residual-carrier architecture is recorded as fully drafted, unfiled and undisclosed as of 17 Jul 2026 (IP-status document §3.3). *This report deliberately does not list its component-level terms.* Two earlier Layer 2 reports in the public repository do (Node 11).

**Status unclear — requires RJ/counsel determination:**
- *Latent-space / identifiability mechanisms (TR-LSPD-1.0 / TR-SA-1.1).* Possible filing-eligible layer, and possible overlap with the SPD Continuation refiling track (Node 7).
- *Content for the join between authorization and identifiability.* Layer 1 Run 5 recommends occupying it in a short framing piece. Whether join-related mechanism content is theoretical (publishable) or implementation (possibly filable) is not recorded anywhere in project knowledge (Node 12).
- *Anything first disclosed in `Reports/` or `briefs/`.* See Node 11.

**Outside ABCF-v1 IP scope (not a coverage gap):** P7, P8. Layer 1 Run 5 adds that the P8 corpus hits are loose and lean toward a clean null; this does not alter the scope determination.

---

## Section 5 — Corpus-derived decision nodes

Nodes 0–7 carry Run 3 numbering. Run 3's Node 8 (synthesis lag) is closed: Layer 1 Run 5 absorbed Briefs 15–16 on the same day as this run. Nodes 9–14 are new. No node carries a recommendation.

**Node 0 — Portfolio-status currency (carried, severity raised)**
- Information available: Three portfolio documents, all dated 17 Jul 2026; none newer. Now 80 days old, up from 35 at Run 3.
- Information missing: Whether any filing, payment, amendment, abandonment, disclosure or counsel action has occurred since.
- Time sensitivity: Medium. No fixed deadline falls in the gap, but the earliest refiling window (~06 Mar 2027) is 152 days out and Nodes 1–5, 9 and 10 assume Section 1 is current.
- Who decides: RJ (administrative confirmation).
- Blocking dependency: Blocks safe use of every node below if Section 1 has changed.

**Node 1 — RAC-01 / Tibebu convergence (carried, context updated)**
- Information available: GB2609979.6's claims are computed from Tibebu's Δ_AIT formula (10 Apr 2026), published 18 days before the RAC-01 filing and 23 before P5. Third-party operationalization continues (Solozobov, DEMM-Bench). Justice (Jul 2026) is the first governance architecture built on Tibebu; it accepts the limit as terminal. McCann is a computability route to a similar conclusion.
- Information missing: Claim-level comparison of Tibebu's prior publication against RAC-01's claims. Counsel's view on any effect of third-party architectures built on the same result.
- Time sensitivity: High — 28 Apr 2027, 205 days.
- Who decides: RJ + counsel.
- Blocking dependency: None upstream.

**Node 2 — IETF standards-track line vs DOG/AWAP/IGA/LID (updated)**
- Information available: The agent-authorization draft was adopted as a WIMSE WG document on 15 Sep 2026 (draft-ietf-wimse-aims-00); §10.7, §8 and §11 carry over. Two further IETF texts (das-01, 23 Sep; kroehl-02, 6 Sep) occupy the same territory as informational or individual drafts. No WGLC active. Changes now require WG consensus (brief inference). None attaches an identifiability condition.
- Information missing: The first-appearance dates and text of the earlier revisions of these drafts; whether WGLC or WG discussion adds attribution or identifiability requirements; whether claim drafting for the LID refiling should account for this text.
- Time sensitivity: Medium-high — ~19 Mar 2027 LID window, 165 days.
- Who decides: RJ + counsel, informed by Tier 1 monitoring.
- Blocking dependency: Node 5 drafting; shares inputs with Node 9.

**Node 3 — Disownership / residual-carrier architecture filing (carried)**
- Information available: Recorded as fully drafted and undisclosed (17 Jul). General principle public via P4/P5. No external item in Runs 1–16 is recorded as touching its specific instantiation. Justice's HOLD/remediation and pre-execution declaration are adjacent to the authority side, not recorded as matching this architecture.
- Information missing: Current status (Node 0); budget and sequencing against the three refilings; the Node 11 question.
- Time sensitivity: Medium. No external deadline; the exposure is an independent third-party arrival at the specific instantiation, plus the Node 11 point.
- Who decides: RJ + counsel.
- Blocking dependency: Competes with Node 5 for drafting resources; depends on Node 11.

**Node 4 — P4 / P7 / P8 posture (narrowed, corrected)**
- Information available: P7 null on all sixteen runs. P4: tagged Runs 3 and 15, but Run 15's match is to the DOG-analogue implementation concept, not to P4's core. P8: tagged Runs 1, 4, 14; Layer 1 Run 5 reads the hits as loose or reading-through-RJB's-lens and leans toward null. Nulls are partly vocabulary-bound.
- Information missing: Whether any filing is contemplated for P4-domain content.
- Time sensitivity: Low.
- Who decides: RJ + counsel.
- Blocking dependency: None.

**Node 5 — SPD / LID UK refiling shape and content (carried, windows closer)**
- Information available: Three independent windows (~06 Mar 2027, ~19 Mar 2027 ×2). Content decisions are drafting and architecture choices. Nodes 2, 7, 9 and 10 now feed it.
- Information missing: Merge-or-split; sequencing; retrieval of the remaining LID claim-group content; whether the UKP-02 continuation content is non-public.
- Time sensitivity: Medium-high — 152 and 165 days.
- Who decides: RJ + counsel (drafting); RJ (budget).
- Blocking dependency: Nodes 2, 7, 9, 10; shares bandwidth with Node 3.

**Node 6 — ePCT non-publication confirmation and administrative corrections (carried)**
- Information available: Suppression appears secured on the face of the RO/117 notices (IB receipt 07 Jul 2026). Probable title typos on GB2605016.1 and GB2605018.7.
- Information missing: Explicit ePCT outcome; correction filing.
- Time sensitivity: Low but cheap to close; now 90 days since withdrawal.
- Who decides: RJ or counsel.
- Blocking dependency: None.

**Node 7 — Identifiability filing-eligibility vs the SPD Continuation track (refined)**
- Information available: P3's delegation / execution-gate content is covered by four filings. PCT/CH2026/050012's title on file names identifiability of causal contrasts; its refiling window is ~19 Mar 2027. External identifiability work continues (Tan, Kori & Russo, InfluenceField, Zhang) with no governance framing.
- Information missing: Whether TR-LSPD-1.0's identifiability content overlaps with, or is distinct from, the 050012 claim set; whether a filing-eligible mechanism exists outside both.
- Time sensitivity: Medium-high, tied to the 050012 window (165 days) rather than "unclear" as in Run 3.
- Who decides: RJ + counsel.
- Blocking dependency: Feeds Node 5.

**Node 9 — Dating audit of earliest execution-gate sources (new)**
- Information available: Section 3.2. Two sources dated before every filing (Audit Trails; Premise Governance v1); several March-dated or first-revision-unrecorded sources (ACP, DAAP, HDP, DRP, klrc); Layer 1 Run 5 independently recommends resolving the dating table with counsel before any priority statement is made in a paper.
- Information missing: Day-level dates for the March items; Datatracker revision histories; v1-to-v2 differences for Premise Governance; the P1 26 May modification content; claim-level comparison.
- Time sensitivity: High — the answer bears on refiling drafting (152–165 days) and on any statement of priority in a paper.
- Who decides: RJ + counsel.
- Blocking dependency: Feeds Nodes 2 and 5; precedes any publication that asserts priority (Node 12).

**Node 10 — Third-party disclosed filings: Justice / Alethera (new)**
- Information available: Two US provisional application numbers disclosed in a working paper. Author claims the design predates April 2026. EACL sits in the same architectural territory as the DOG/AWAP/IGA/LID cluster per the brief. A companion paper is announced. No filing dates, claims or publication status are in the corpus. Layer 1 Run 5 routes citation of this source through Layer 2 first.
- Information missing: Provisional filing dates; claim scope; whether non-provisional or PCT filings follow and when they publish; any interaction with the March 2027 windows and with RAC-01.
- Time sensitivity: Medium-high. Unknown dates make the urgency itself unknown; any public filing event would arrive on the third party's schedule, not RJ's.
- Who decides: RJ + counsel.
- Blocking dependency: Feeds Nodes 2 and 5; precedes any citation of or positioning against this paper.

**Node 11 — Component-level terms in the public monitoring repo (new)**
- Information available: `Reports/2026-07-17_Layer2_Run2_SCOPE-ALL.md` (commit 8d3f2ad, 17 Jul 2026) and `Reports/2026-08-21_Layer2_Run3_SCOPE-ALL.md` (commit 3e25cf5, 21 Aug 2026) name component-level terms of the architecture the IP-status document records as unfiled and undisclosed. They name terms only; the files describe no mechanism. The repo is public per project instructions and is cloneable anonymously. The IP-status document's repo-privacy confirmation (§3.3) does not cover it. Reports are committed after each run, so this report would join them unless its content is adjusted.
- Information missing: When the repo became public; whether it was public on 17 Jul and 21 Aug; who has accessed it; whether name-level mention has any legal significance for a later specific-instantiation filing; what the repo history can and should show.
- Time sensitivity: High. The exposure, if any, is continuing, and the IP-status document treats a private-to-public transition before filing as reopening the novelty question.
- Who decides: RJ + counsel (legal significance); RJ (repo handling, which this system has not been authorized to change).
- Blocking dependency: Gates Node 3; informs what future Layer 2 reports may name.

**Node 12 — Publication sequencing for the authorization / identifiability join (new)**
- Information available: Layer 1 Run 5 identifies the join as the most strategically significant unoccupied position, now named from outside (Justice §8.3, "epistemic layer"; Governed Individuation's verifier-soundness assumption), and lists occupying it in a short framing piece as a highest-priority action "after Layer 2 clears the Justice disclosures". The IP-status document says any new public disclosure risks self-anticipation of future claims at the level disclosed.
- Information missing: Which join content is theoretical-layer versus implementation-layer; whether anything in it is filing-eligible; relationship to the March 2027 refilings and Node 3; Justice filing dates (Node 10).
- Time sensitivity: Medium. Layer 1 Run 5 states the risk of external closure is one to three months; the refiling windows set the cost of early disclosure.
- Who decides: RJ + counsel.
- Blocking dependency: Nodes 9, 10, 11 and 5.

**Node 13 — US-only CNI route (carried, previously unnumbered)**
- Information available: TR-CNI-1.1 published 04 May 2026; no PCT-03-CNI was filed. US §102(b)(1) route open to 04 May 2027 and on hold. No external item in the corpus is recorded as converging on the CNI-specific mechanisms.
- Information missing: Whether the decision stays deferred.
- Time sensitivity: Medium — 211 days; the deadline is independent of the decision.
- Who decides: RJ + counsel.
- Blocking dependency: None.

**Node 14 — Patent-literature coverage of the monitoring system (new)**
- Information available: Zero briefs record a search of a patent register or database. Third-party patent filings surfaced only when a paper disclosed them (Justice). "No patent filing detected" in Runs 2–14 reports therefore reflects the absence of a search.
- Information missing: Whether a patent-literature search is warranted, who would perform it, and which databases and classes.
- Time sensitivity: Medium. An answer before the March 2027 windows would be useful to Nodes 2, 5 and 10.
- Who decides: RJ + counsel (search is a professional task, not a monitoring-brief task).
- Blocking dependency: Informs Nodes 2, 5, 10.

---

## Section 6 — Questions for counsel

Sequenced from most time-sensitive to least.

```
Q1 — Public monitoring repository / unfiled architecture (Node 11)
Context: Two Layer 2 reports committed to a publicly readable repository on 17 Jul and 21 Aug 2026 name component-level terms of an architecture recorded as unfiled and undisclosed; they describe no mechanism. Repo visibility on those dates is unverified.
Question: Does naming such terms, without describing mechanism, create any disclosure or novelty exposure for a later filing on the specific instantiation, and what should be established about the repository's visibility history and access before that filing decision is made?
Time sensitivity: High
Blocking: Node 3 filing decision; what future Layer 2 reports may name

Q2 — Earliest execution-gate sources vs March 2026 filing dates (Node 9)
Context: Audit Trails (28 Jan 2026) and Premise Governance v1 (2 Feb 2026) are dated before all UK and PCT filings; Agent Control Protocol, the DAAP and HDP drafts and the first revisions of several IETF drafts are dated "March 2026" with the day unrecorded. The corpus classifies each as lacking an identifiability condition.
Question: For DOG, AWAP, IGA and the LID refiling, which of these sources should counsel examine at claim level, what dates and revision texts should be obtained first, and does the answer change how the new LID and SPD claim sets should be drafted?
Time sensitivity: High
Blocking: Nodes 2 and 5; any priority statement in a paper

Q3 — Third-party US provisionals in the execution-authority territory (Node 10)
Context: A working paper by Alethera (SSRN 7202899, PDF 28 Jul 2026) discloses US provisional applications 64/021,779 and 64/062,705 for a signed-constitution, fail-closed, pre-execution authorization gate with narrowing delegation and an attestation chain. Filing dates and claims are not stated; the author says the design predates April 2026.
Question: What should counsel establish about these applications (filing dates, claim scope, publication timing), and does their existence affect claim drafting or timing for the DOG/AWAP/IGA family or the LID and SPD refilings?
Time sensitivity: Medium-high
Blocking: Nodes 2 and 5; any citation of the paper

Q4 — IETF standards line and LID claim drafting (Node 2)
Context: A WIMSE WG document (draft-ietf-wimse-aims-00, 15 Sep 2026) now carries text denying authority standing to local UI confirmation and separating reasoning from credential access; two further IETF drafts occupy the same territory. WGLC has not started.
Question: Should the LID refiling's claim drafting distinguish over this standards text specifically, does the pending WG process warrant delaying claim finalization, and does the date of the individual draft's first revision matter to that answer?
Time sensitivity: Medium-high
Blocking: Node 5 drafting

Q5 — SPD Continuation identifiability track vs TR-LSPD-1.0 (Node 7)
Context: PCT/CH2026/050012 (withdrawn; refiling ~19 Mar 2027) has a title on file naming identifiability of causal contrasts; TR-LSPD-1.0 / TR-SA-1.1 were published 26 Apr 2026. External identifiability work (Tan et al., Zhang et al., Kori & Russo) continues with no governance claim.
Question: Does TR-LSPD-1.0's identifiability content overlap the 050012 claim set, is any mechanism outside both filing-eligible, and does the refiled SPD Continuation need to account for the published TR-LSPD-1.0 text?
Time sensitivity: Medium-high
Blocking: Node 5

Q6 — RAC-01 / Tibebu (Node 1)
Context: GB2609979.6's claims are computed from Tibebu's formula, published 10 Apr 2026, 18 days before the RAC-01 filing and 23 before P5. Since Run 3, a governance architecture built on the same result (Justice) and a computability route to a similar conclusion (McCann) have appeared.
Question: Does Tibebu's prior publication create prior-art or inventorship exposure for RAC-01's specific claims, and does third-party activity built on the same result change the assessment ahead of 28 Apr 2027?
Time sensitivity: High (205 days)
Blocking: None upstream; feeds RAC-01 prosecution strategy

Q7 — Publishing on the authorization / identifiability join (Node 12)
Context: The corpus shows two external sources naming or approaching the join from the authority side. A short framing piece on the join has been identified as a high-priority positioning action.
Question: What disclosure sequencing should govern any public statement on the join relative to the March 2027 refilings, and how should counsel separate theoretical-layer content from content that may still be filing-eligible?
Time sensitivity: Medium
Blocking: Nodes 3, 5, 9, 10, 11

Q8 — Disownership / residual-carrier filing timing (Node 3)
Context: The specific instantiation is recorded as drafted and unfiled; its general principle has been public since 03 and 25 May 2026 through P5 and P4. No external item in the corpus is recorded as touching it.
Question: Given competing demands from the three refilings, what filing sequence best manages the risk of independent third-party arrival at the specific instantiation?
Time sensitivity: Medium
Blocking: Competes with Node 5; depends on Q1

Q9 — US-only CNI route (Node 13)
Context: TR-CNI-1.1 (04 May 2026) has no corresponding filing; the US §102(b)(1) route runs to 04 May 2027.
Question: Should the US-only CNI filing decision be revisited now, or does it remain correctly deferred?
Time sensitivity: Medium (211 days)
Blocking: None

Q10 — Patent-literature search coverage (Node 14)
Context: No brief records a patent-register or patent-database search; third-party filings have surfaced only when a paper disclosed them.
Question: Is a professional patent-literature search warranted before the March 2027 windows, and if so what scope should it have?
Time sensitivity: Medium
Blocking: Informs Q2, Q3, Q4

Q11 — P4 / P8 posture (Node 4)
Context: P7 is null on all sixteen runs. P4's only recorded match is to an implementation-layer concept; P8's hits are read as loose and lean toward null. P7 and P8 are recorded as outside ABCF-v1 IP scope.
Question: Is any filing contemplated for P4-domain content, and does anything in the P8 record bear on its scope determination?
Time sensitivity: Low
Blocking: None
```

---

## Section 7 — Summary brief for counsel

RJ Blanchette operates a structured monitoring system (ABCF-v1) that runs periodic web searches against concepts from eight defensively published theory papers (P1–P8, Zenodo, March–June 2026) and logs external "proximity signals". This report synthesizes sixteen runs (15 June to 5 October 2026) against the portfolio recorded on 17 July 2026: seven active UK applications, three withdrawn PCT applications with refiling windows from about 6 March 2027, and one unfiled Zenodo paper with a US grace-period route to 4 May 2027. Those portfolio facts are now 80 days old and have not been re-verified.

The authorization side of the corpus has continued to attract independent work. An IETF working group adopted an agent-authorization draft on 15 September, two further IETF drafts and several formal papers address the same territory, and a company has disclosed two US provisional applications on a signed, fail-closed pre-execution gate. None of these is recorded as attaching an identifiability condition, which is the gap RJ's filings address. The monitoring system has never searched patent registers, so it cannot say what has been filed beyond what papers disclose.

Four matters are flagged for counsel. First, the earliest sources in this territory, including two dated before every filing and several dated only to March 2026, need day-level dating and claim-level comparison; an earlier report's statement that priority looked comfortable relied on the latest sources and is withdrawn. Second, the third-party provisionals' dates and claims are unknown. Third, earlier reports in the public monitoring repository name component-level terms of an unfiled architecture; this report does not repeat them. Fourth, the SPD Continuation refiling title names identifiability, and its overlap with a published paper has not been assessed.

The nearest deadlines are the SPD and LID refiling windows (152 and 165 days) and the RAC-01 Paris Convention deadline of 28 April 2027 (205 days). The RAC-01 claims are computed from a formula in a paper published 18 days before filing, a point carried from earlier reports.

This system maps decision nodes and organizes facts. It produces no legal analysis and takes no position on novelty, prior art or filing strategy; the report is provided to support counsel's independent assessment.

This document is a Stage 01 InterpretationArtifact produced by a structured monitoring system. It does not constitute legal advice, a prior art search, or a patentability assessment. All decisions remain with RJ Blanchette and qualified counsel.

---

*All outputs are InterpretationArtifacts at Stage 01. Proximity signals identify architectural convergence only; they are not prior-art findings or IP claims. No action is authorized without RJ's explicit AuthorizationAct.*
*Save to: Reports/2026-10-05_Layer2_Run4_SCOPE-ALL.md*
