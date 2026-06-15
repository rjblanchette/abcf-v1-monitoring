# ABCF-v1 Governance Monitoring Brief — Search and Lens Prompt
**Version:** 1.3
**Last revised:** 15 June 2026
**Change from v1.2:** Added §3a (Standards Body Search Vector) — dedicated primary-source monitoring for ISO TC 42, IEEE P2863, EU AI Act implementing acts, NIST AI RMF updates, IETF AI-relevant drafts, and W3C credentials/identity work. No other changes.

---

## 1. Frame

You are producing an AI governance monitoring brief using the ABCF-v1 lens.

Assume you have no prior knowledge of ABCF-v1. Use the working definition below.

**ABCF-v1 working definition:**
ABCF-v1 is a proposed formal governance architecture for AI systems. It is built around rooted human authorization, structural causal identifiability, and explicit containment boundaries.

Its core claim is that causal attribution in AI-assisted decisions can become structurally indeterminate above a computable threshold, not merely difficult. ABCF-v1 does not claim to solve that unsolvable attribution class. It governs below that threshold by asking what can still be bounded, authorized, audited, contained, or withheld.

**Core ABCF ideas:**

1. **Rooted human authorization:** AI systems should not generate their own governance authority. Authority must originate from an identifiable human or institution through an explicit authorization act.

2. **Structural causal identifiability:** Governance must distinguish between decisions where causal contribution can be meaningfully traced and decisions where attribution becomes structurally indeterminate.

3. **Containment boundaries:** Interpretation must not become authority. Pattern recognition must not become mandate. Drafts, outputs, metrics, or model behavior must not become governance instruments without explicit authorization.

4. **Execution / admissibility boundaries:** AI outputs should pass through explicit checks before being treated as usable, reliable, relied upon, or authorized.

5. **Human decision autonomy:** AI governance should preserve the human capacity to decide, not replace it through overconfidence, distortion, hidden persuasion, or false authority.

---

## 2. Search Task

Search current and recent sources for AI governance developments relevant to ABCF-v1 or any of its architectural components.

Search broadly across:
- major news outlets
- government and regulator publications
- standards bodies (see §3a for dedicated standards search vector)
- court and litigation updates
- academic papers and preprints
- AI lab technical blogs
- AI safety and governance organizations
- audit, assurance, compliance, and certification materials
- public procurement and institutional adoption materials
- patent or IP databases where relevant

---

## 3. Search Themes

- AI governance frameworks
- AI accountability
- AI auditability
- AI assurance
- AI safety cases
- AI liability
- AI decision provenance
- causal attribution in AI systems
- structural causal models and AI governance
- AI-assisted decision-making
- human authorization in AI governance
- human oversight
- non-delegation of authority to AI
- behavioral governance of AI systems
- AI persuasion, manipulation, sycophancy, epistemic drift, or behavioral distortion
- model monitoring and runtime enforcement
- AI constitutionalism / constitutional AI
- high-risk AI systems
- AI standards, certification, and conformity assessment
- AI compliance regimes

---

## 3a. Standards Body Search Vector

Run a dedicated search pass against the following bodies and instruments each run. Prioritize primary sources (working group outputs, published standards, draft texts, official meeting reports) over secondary commentary.

**Fetch or search the following primary sources directly where accessible:**

### ISO / IEC JTC 1 / SC 42 — Artificial Intelligence
- ISO 42001:2023 (AI Management Systems) — monitor for amendments, corrigenda, or sector-specific guidance documents
- ISO/IEC 42005 (AI system impact assessment) — publication status
- ISO/IEC 42006 (AI auditing) — publication status and working draft updates
- ISO/IEC TR 42108 (AI governance implications) — status
- Search: `site:iso.org "42001" OR "42005" OR "42006" OR "SC 42" AI governance 2026`

### IEEE Standards Association
- IEEE P2863 — Recommended Practice for Organizational Governance of Artificial Intelligence
- IEEE P3119 — Standard for the Procurement of Artificial Intelligence
- IEEE P2894 — Guide for an Architectural Framework for Explainable Artificial Intelligence
- Search: `site:standards.ieee.org "P2863" OR "P3119" OR "P2894" AI governance 2026`

### EU AI Act — Implementing Acts and Delegated Regulations
- Article 9 risk management system implementing acts
- Article 10 data governance implementing acts
- Article 17 quality management implementing acts
- Article 40 harmonised standards (CEN/CENELEC mandated work)
- Article 72 general-purpose AI model transparency implementing acts
- Search: `EU AI Act implementing act delegated regulation 2026 site:eur-lex.europa.eu`
- Search: `CEN CENELEC AI Act harmonised standard mandate 2026`

### NIST — AI Risk Management Framework
- NIST AI RMF 1.0 updates, sector profiles, or companion documents published 2026
- NIST AI 100-series publications
- NIST CAISI (Consortium for AI Safety and Infrastructure) — pre-deployment evaluation criteria
- Search: `site:nist.gov AI RMF 2026` and `NIST CAISI pre-deployment evaluation 2026`

### IETF — AI-relevant Internet Drafts
- draft-helixar-hdp-agentic-delegation (HDP) — status update
- IETF AIMS (AI Model Safety) working group — any new drafts
- Any new Internet-Drafts addressing AI agent identity, delegation, or authorization
- Search: `site:datatracker.ietf.org AI agent delegation authorization 2026`

### W3C — Credentials and Identity
- Verifiable Credentials Working Group — AI agent credential specifications
- Decentralized Identifier (DID) Working Group — AI agent identity
- Search: `site:w3.org AI agent identity credential authorization 2026`

### OECD — AI Policy Observatory
- OECD AI Principles implementation updates
- OECD.AI policy tools relevant to accountability and attribution
- Search: `site:oecd.ai accountability attribution governance 2026`

### Council of Europe — AI Convention
- Framework Convention on Artificial Intelligence (CETS 225) — ratification status, implementing guidance
- Search: `Council of Europe AI Convention CETS 225 ratification 2026`

**Standards body search output format:**

For each standards body item found, produce a Part A / Part B entry using the standard item format (§5), with the following addition to Part A:

- Field 10: **Standards status** — Draft / Published / Under revision / Withdrawn / Pending adoption

Prioritize standards items that:
- Introduce or modify human oversight, authorization, or accountability requirements
- Establish conformity assessment or certification criteria
- Address causal attribution, explainability, or audit trail requirements
- Create or modify liability or responsibility allocation frameworks
- Reference or interact with EU AI Act implementation obligations

Deprioritize:
- Standards that address only technical performance metrics without governance implications
- Republication of existing standards without substantive change
- Commentary on standards without primary source citation

---

## 4. ABCF-Related Components to Watch For

- explicit human authorization
- authorization acts
- named accountable human integrators
- governance authority
- institutional authorization
- causal identifiability
- causal non-identifiability
- attribution indeterminacy
- accountability gaps
- accountability incompleteness
- provenance chains
- decision traceability
- model audit trails
- containment boundaries
- human-in-the-loop limits
- human oversight failure
- execution gates
- admissibility checks
- runtime governance
- behavioral monitoring
- decision autonomy
- epistemic calibration
- uncertainty disclosure
- option-space preservation
- asymmetric framing
- selective evidence presentation

---

## 5. Item Format

For each relevant item, provide Part A and Part B.

### PART A — News item summary

1. Title
2. Source
3. Publication date
4. Link
5. Jurisdiction / institution
6. One-sentence factual summary
7. Why it was selected — **include any RJB Publication Proximity flags here (see §9)**
8. Relevant ABCF component(s)
9. Relevance level:
   - Direct relevance
   - Indirect relevance
   - Background relevance
   - Watchlist only
10. **Standards status** *(standards body items only)*: Draft / Published / Under revision / Withdrawn / Pending adoption

### PART B — ABCF lens analysis

Evaluate the item through three categories:

**1. Coherence:**
Does the item make sense within the ABCF frame? Does it involve attribution, authorization, containment, admissibility, provenance, decision autonomy, or governance boundaries?

**2. Alignment:**
Does the item support or move toward ABCF-compatible governance? Examples:
- clearer human authorization
- stronger provenance
- meaningful auditability
- explicit execution gates
- real intervention authority
- recognition of attribution limits
- preservation of human decision autonomy

**3. Infringement / tension:**
Does the item violate, bypass, or weaken ABCF principles? Examples:
- liability assigned without real causal visibility
- ceremonial human oversight
- AI-generated outputs treated as authority
- risk classification used as a substitute for actual containment
- accountability shifted to the nearest human rather than the authorized actor
- opacity hidden behind compliance language
- metrics treated as governance authority
- outputs treated as reliable without admissibility checks

For each item, produce:

- **ABCF coherence:** High / Medium / Low
- **ABCF alignment:** Strong / Partial / Weak / None
- **Infringement or tension:** High / Medium / Low / None
- **Structural analysis:** Explain the reasoning briefly.
- **Known facts:** Only what the source directly supports.
- **Inferences:** Reasonable interpretation, clearly marked.
- **Unknowns:** What cannot be determined from the available source.
- **ABCF classification:** Choose one:
  - Coherent and aligned
  - Coherent but incomplete
  - Coherent problem signal
  - Misaligned / infringement risk
  - Background only
  - Not materially relevant

---

## 6. Prioritization

**Prioritize items involving:**
- new law, regulation, guidance, enforcement, or litigation
- new or revised standards with governance, accountability, or authorization implications
- AI accountability failures
- auditability or assurance mechanisms
- causal attribution problems
- human oversight failures
- AI decision provenance
- institutional authorization of AI use
- runtime monitoring or output gating
- standards or certification regimes
- technical findings affecting traceability, identifiability, or representation stability

**Exclude or deprioritize:**
- generic AI product launches
- hype pieces
- investment news unless governance-relevant
- speculative commentary without institutional, legal, or technical substance
- AI safety content that does not connect to governance structure, accountability, authorization, or decision autonomy
- standards performance metrics without governance implications

---

## 7. Epistemic Rules

- Separate facts from interpretation.
- Do not claim that an item validates ABCF-v1 unless the source directly supports that.
- When no source explicitly mentions ABCF-v1, say: "ABCF is not mentioned in the source; relevance is architectural."
- If relevance is analogical, say "analogical relevance."
- If relevance is speculative, say "speculative relevance."
- If a source is promotional, label it.
- If an item is policy-relevant but not architecture-relevant, say so.
- Prefer primary sources over commentary.
- For standards items: cite the standard number and version, not commentary about the standard.
- Include links for every item.
- Include publication dates.
- Do not omit uncertainty.
- Do not treat regulatory visibility, media coverage, adoption, or institutional language as proof of ABCF alignment.

---

## 8. Run Outputs

End the brief with:

**1. Summary matrix**
Columns: Item | Coherence | Alignment | Infringement / tension | ABCF classification

**2.** Top 3 structurally relevant items this run

**3.** Strongest ABCF-aligned signal

**4.** Strongest ABCF problem signal

**5.** Weak signals worth monitoring

**6.** Suggested searches for next run

**7.** Coverage gaps or source limitations

**8.** Standards body status summary *(new in v1.3)*
For each body in §3a: one line on what was found, what was not found, and what to watch.

**9.** RJB Publication Proximity Report *(see §9 for format)*

---

## 9. RJB Publication Proximity Check

The following eight publications have been deposited by the brief's author (Robert J. Blanchette) on Zenodo and constitute the reference corpus against which proximity is assessed. They are not expected to appear in retrieved sources; all proximity assessments are architectural or analogical unless a source explicitly names the work.

**For each item retrieved in this brief, run a secondary proximity pass after Part B.** Assess whether the item:

- **(a)** names, cites, or directly references any of the eight publications below, or
- **(b)** independently arrives at a structurally convergent claim, terminology, or formal object from the concept lists below.

**Flag format:**
- If (a): add `[DIRECT CITATION — RJB PUBLICATION: {short title}]` to Part A, field 7.
- If (b): add `[PROXIMITY SIGNAL — RJB PUBLICATION]` to Part A, field 7, and name the specific convergent concept(s).

**At the end of the brief,** produce:

> **RJB PUBLICATION PROXIMITY REPORT — {run date}**
> Table of all triggered items with matched concept(s) and a one-line structural note.
> If none triggered: "No proximity signals detected this run."

---

### 9.1 P1 — Structural Limits of AI Accountability

**Title:** Structural Limits of AI Accountability: Institutional Rank and the Geometry of Governance
**DOI:** 10.5281/zenodo.18866882
**Date:** March 4, 2026

**Concepts to match:**

- **Structural Indeterminacy (SI):** attribution failure arising from rank deficiency in the admissible intervention space — defined as a property of the triple (C, A, τ). Ontological limit, not epistemic.
- **Structural Limit Theorem (SLT):** forced-use causal contrasts are non-identifiable from rollout-only evidence in dynamic adaptive endogenous-use systems.
- **Institutional Rank (R_I):** rank of the Jacobian of the admissible intervention mapping; measures causal experimentation capacity.
- **Institutional Rank Theorem:** rank(DΨ_A₀) < dim(Θ) ⟹ ∃τ structurally indeterminate.
- **Admissible intervention set (A₀):** institutionally permitted interventions; determines attribution geometry.
- **Forced-use contrast (τ):** marginal causal contribution of AI use conditional on availability.
- **Rollout-only evidence:** cannot sever endogenous AI use from institutional state.
- **Governance–Identifiability Composition Theorem:** controlled rank expansion restores identifiability without collapsing authority boundaries.
- **Attribution Regime:** the pair (A, τ).
- **Bounded Probe Episode / Probe Expansion (ΔA):** temporary authority-governed expansion of A₀.
- **Authority Activation (Leadership Artifact / ΛLA):** interventions executable only through explicit authorization act.
- **Contraction Guarantee:** A₀ must be restored after probe; failure = authority leakage.
- **Probe Execution Log (PEL):** record enabling reconstruction of effective admissible set.
- **Structural Probe Domain (SPD):** generates candidate probe expansions; cannot activate them.
- **Audit Illusion:** audit that does not expand intervention set; appearance of accountability without identifiability change.
- **Accountability–Authority Tradeoff:** higher attribution capacity requires greater intervention authority.
- **Authority / Information / Operational Bottleneck:** three structural sources of low institutional rank.
- **AI Governance Theorem:** attribution feasible iff baseline rank sufficient OR controlled probe expansion available.
- **"AI governance is a problem of controlled causal geometry"**
- **AWAP (AI-Assisted Work Admissibility Packet):** provenance and human mandate documentation for AI-assisted work.

---

### 9.2 P2 — TR-CNI-1.1: Causal Non-Interference

**Title:** Causal Non-Interference: Formal Definition and Core Theorems
**DOI:** 10.5281/zenodo.20025045
**Date:** March–April 2026

**Concepts to match:**

- **Causal Non-Interference (CNI):** extends classical non-interference (Goguen–Meseguer 1982) by replacing administrative security levels with identifiability states derived from causal structure.
- **Identifiability States (Ψ / Γ):** computed from rank of admissible intervention mapping, not assigned by policy. "The level is ontological, not administrative."
- **Strict CNI:** K(e) ∈ {REFUSE, HALT} for all Ψ-state events.
- **Rooted Admissibility Invariant (RAI-Γ):** K(e) = AUTHORIZE ⟹ id_state(e) ∈ Γ ∧ auth(e) ≤ ρ; sufficient for strict CNI.
- **Causal Purge function (purge_Ψ):** CNI requires obs(purge_Ψ(σ)) = obs(σ).
- **Identifiability Lattice L = (Ψ, Γ_local, Γ_dual, Γ_integrated):** four-level lattice; bottom = Ψ, top = Γ_integrated.
- **Deployment Safety Criterion:** safe(strategy) ⟺ id_state(e) ≥ min_level(strategy).
- **Lattice–deployment correspondence:** shadow = Ψ; canary = Γ_local; A/B = Γ_dual; interleaved = Γ_integrated.
- **Audit Illusion as CNI Violation:** rollout-only data treated as causal evidence = Ψ-state misclassification; a theorem, not an observation.
- **CVG Separation Invariant:** VALID ≢ MANDATE; theorem from strict CNI, not architectural convention.
- **SLT-CNI Correspondence:** strict CNI non-trivially binding ⟺ Structural Indeterminacy holds under A₀.
- **Probe Stability Threshold (Δθ_max):** largest ball around θ̄ preserving kernel containment; bounds tolerable actor-adaptation drift.
- **Visibility Function:** V(ΔA, t) = ℓ(ΔA) · (1 − e^(−λ(t − t_s))).
- **Probe-Induced Drift (δθ):** θ(t) − θ̄; actor adaptation during probe.
- **Probe Stability Violation (PSV):** rank drop in DΨ_probe(θ(t)) below design-time baseline → HALT or Structurally Compromised.
- **Bridge Proposition:** ‖δθ‖ < Δθ_max ∀t ⟺ kernel containment holds throughout probe episode.
- **Asymmetry of identifiability:** observation cannot promote Ψ → Γ; only governed probe expansion can.
- **Monotone Governance:** A ⊆ A' ⟹ Ψ(A', τ) ⊆ Ψ(A, τ).

---

### 9.3 P3 — TR-LSPD-1.0 + TR-SA-1.1: Latent-Space Extensions

**Title:** Formal Extensions to Structural Probe Domain and Authority-Safety Theory for Latent-Space Predictive Architectures
**DOI:** 10.5281/zenodo.19799074
**Date:** April 26, 2026

**TR-LSPD-1.0 concepts to match:**

- **Latent-Space Structural Limit Theorem (L-SLT):** extends SLT to latent embedding spaces via Clarke Generalized Jacobian (∂_C).
- **Representation Indeterminacy (RI):** observable Jacobian full-rank but latent Jacobian rank-deficient due to Abstraction Collapse.
- **Abstraction Collapse:** encoder hides contrast-relevant causal directions in single latent dimension.
- **Latent SPD (L-SPD):** detects RI invisible to observable SPD.
- **Fail-Closed Deployment Corollary:** defaults to non-deployment if ker(∂_C Ψ^L_A₀) ⊄ ker(∂_C T^L).
- **Semantic Anchoring of Latent Probes:** latent intervention admissible only if observable intervention do(X = α) exists such that the latent–observable diagram commutes via Π.
- **Anchoring Identifiability Problem:** open problem; Π must be formally proved for Path B restoration.
- **Causal State Space (C) as Hausdorff quotient:** causal states must be topologically separable.
- **Representation Drift:** RI may be non-stationary; dynamic rank monitoring required.
- **Latent Residual (z) as CNI Witness:** z constitutes CNI condition when ρ_z1, ρ_z2 yield identical latent observations but different causal contrasts.
- **JEPA-class governance gap:** predictive success ≢ structural identifiability in governance regime.
- **Clarke Generalized Jacobian (∂_C):** handles non-smoothness of neural encoders.

**TR-SA-1.1 concepts to match:**

- **Nominal vs. Substantive Authority:** nominal = structural reference; substantive = nominal + L-SLT kernel condition satisfied under H's probe set.
- **Rooted Authority Invariant (RAI):** execution requires path in Γ from named human integrator H to executing node, every edge a valid substantive delegation.
- **Named-Integrator Topology:** G = (H, A, GAI, Γ); unique named human integrator; all authority from H.
- **Governance Activation Interface (GAI):** enforces that all authority injection originates from H.
- **Integrated Authority-Safety Theorem:** agent cannot exceed B_i iff (a) topological connectivity (Maffeis–Mitchell–Taly 2010) AND (b) geometric identifiability along every path from H to agent.
- **RI-Opacity Failure:** substantive → nominal authority degradation when agent undergoes RI; triggers Legitimacy Hold.
- **Lateral RI Propagation:** RI through coupling Ξ_ij; requires Quarantine.
- **Composability Fail-Closed Corollary:** non-deployment if any agent has only nominal authority.
- **Integrator's Burden Corollary:** capability expansion without H's probe set expansion = RAI violation; halt until Rank Expansion Proof provided.
- **Reduction to Maffeis–Mitchell–Taly 2010:** no RI → geometric identifiability trivially satisfied → MMT result recovered.
- **Silent Directions:** agent world model directions crossing B_i invisible to H's probe set.
- **Coupling Inspectability:** Clarke Jacobian of Ξ_ij must be computable by H.

---

### 9.4 P4 — Attribution, Surplus, and Governance (Economic Domain)

**Title:** Attribution, Surplus, and Governance: Extending Structural Indeterminacy to the Economic Domain
**DOI:** 10.5281/zenodo.20394642
**Date:** 2026

**Concepts to match:**

- **Surplus Governability Condition:** surplus is governable only where attribution is resolvable; ungovernable surplus is structural, not distributional.
- **Non-Conversion Principle:** detected surplus cannot legitimately acquire economic standing through accumulation or metric visibility alone. Surplus visibility ≢ surplus authority.
- **Attribution Prior Condition (economic domain):** attribution resolution required before surplus can be allocated, taxed, or governed.
- **Structural Indeterminacy → economic ungovernability:** any system generating surplus under attribution indeterminacy produces structurally ungovernable surplus absent an attribution prior condition.
- **Convergence with Magnifica Humanitas (Leo XIV, 2026):** convergence across independent derivational paths treated as epistemological evidence of necessity.
- **Declared-Origin Gate (DOG) declaration and Conception Event Anchor log:** used as provenance instruments in the paper's own supplementary record.
- **"Fourth paper in a series extending the Structural Limit Theorem to specific governance domains"**

---

### 9.5 P5 — Structural Indeterminacy and the Limits of Legal Attribution

**Title:** Structural Indeterminacy and the Limits of Legal Attribution in AI Systems
**DOI:** 10.5281/zenodo.19998537
**Date:** 2026

**Concepts to match:**

- **Translation between formal impossibility and legal-facing governance failure:** maps SLT / AIT results onto legal proceedings record.
- **Three legal domains:** criminal risk assessment, algorithmic discrimination, AI-assisted medical decision-making — all instances of structural indeterminacy, not transparency failure.
- **"These are not failures of transparency, documentation, or oversight design. They are instances of structural indeterminacy."**
- **Accountability Incompleteness Theorem (Tibebu 2026):** independently derived parallel result; SLT–Tibebu as two-stage impossibility.
- **Compound autonomy threshold:** computable threshold above which single-locus accountability frameworks structurally fail.
- **"Governance architecture whose organizing principle is the refusal to form authority where attribution cannot be structurally supported"**
- **Attribution-prior governance:** concrete instantiation of the required architecture class.
- **Admissible observation regime:** legal proceedings operate within constrained observation regimes that cannot resolve structural indeterminacy.

---

### 9.6 P6 — Creative Authorship and Structural Indeterminacy

**Title:** Creative Authorship and Structural Indeterminacy: Attribution-Prior Governance in AI-Assisted Art Production
**DOI:** 10.5281/zenodo.19998766
**Date:** 2026

**Concepts to match:**

- **Creative authorship as a fourth candidate domain:** SLT extended to creative authorship disputes; relevant causal variable is upstream of any observable data.
- **"Output inspection, generation logs, percentage-of-AI-involvement metrics, and stylistic analysis all operate on the surface of the problem without reaching the causal question."**
- **Mapping to AIT Axiom 1 (Attributability) failure.**
- **Mapping to L-SLT / Representation Indeterminacy.**
- **Systemic Discipline for Cognitive Architecture (SDCA v2.0):** attribution-prior governance instantiation in the creative domain.
- **Minimum definition of art adequate to the governance problem.**
- **Current industry approaches address the wrong causal variable.**
- **Gate architecture encoding the correct causal variable.**

---

### 9.7 P7 — Swiss Neutrality and the Architecture of National Coherence

**Title:** Swiss Neutrality and the Architecture of National Coherence
**DOI:** 10.5281/zenodo.20596277
**Date:** 2026

**Concepts to match:**

- **Recognition neutrality:** governance discipline preventing constitutional authority from attaching prematurely to contested causal explanations under structural indeterminacy.
- **Four functions of neutrality:** survival → federal → active → recognition neutrality.
- **Constitutional authority attaching prematurely to disputed explanations:** the structural failure recognition neutrality prevents.
- **1992 EEA referendum as illustrative case.**
- **"Observable conditions widely recognized while causal structures producing them remain contested"**
- **Neutrality as an evolving architecture of national coherence.**

---

### 9.8 P8 — Recognition Neutrality as Institutional Design (REA/CLP)

**Title:** Recognition Neutrality as Institutional Design: The Recognition–Explanation–Authorization Framework
**DOI:** 10.5281/zenodo.20611099
**Date:** 2026

**Concepts to match:**

- **Recognition–Explanation–Authorization (REA) framework:** reading discipline enforcing recognition precedes explanation precedes authorization.
- **Civic Legibility Packet (CLP):** three-compartment instrument: (1) observable conditions, (2) competing explanatory frameworks, (3) decision object.
- **Invariants maintaining compartment separation.**
- **Four structural limits of REA/CLP:** converge on requirement for a governing constitutional field.
- **Governing constitutional field:** holds classification authority, integrity conditions, maintenance protocols, symmetry enforcement.
- **"The instrument is necessary. It is not sufficient."**
- **Swiss democratic practice test cases:** EEA referendum 1992; AVS 13th pension vote 2024.
- **Recognition precedes explanation precedes authorization:** sequencing invariant; analogue of ABCF admissibility precondition sequence.
- **"Constitutional authority attaching prematurely to contested causal explanations"**

---

### 9.9 Proximity Matching Guidance

**Trigger a `[PROXIMITY SIGNAL]` if a retrieved item:**

- Uses "structural indeterminacy" in a causal attribution context
- Distinguishes between epistemic and ontological attribution failure
- Names "institutional rank" or "intervention geometry" in a governance context
- Treats audit activity as insufficient to establish causal attribution, beyond the standard "audits aren't enough" policy observation
- Distinguishes nominal from substantive authority or oversight
- Names an identifiability condition as a precondition for human authorization
- Treats AI output admissibility as a function of causal identifiability, not merely transparency or explainability
- Names "representation indeterminacy" or an analogous latent-space attribution gap
- Names "probe" as a bounded, authority-governed intervention for identifiability restoration, not merely a test or evaluation
- Names "rooted authority" or "named human integrator" as a structural (not merely procedural) governance requirement
- Uses "fail-closed" as a deployment gate grounded in identifiability rather than performance metrics
- Treats AI sycophancy or epistemic drift as a structural governance failure of the authority boundary, not merely a UX or alignment problem
- Applies the Clarke Generalized Jacobian or analogous non-smooth analysis to latent-space governance problems
- Names a "latent residual" or analogous object as a causal non-identifiability witness
- Argues that surplus from AI systems is structurally ungovernable absent attribution resolution
- Applies the Accountability Incompleteness Theorem (Tibebu 2026) or the SLT–Tibebu two-stage impossibility to legal, economic, or creative governance problems
- Proposes a sequenced recognition → explanation → authorization discipline for public or institutional decision-making
- Names "recognition neutrality" or an analogous restraint principle preventing premature authority attachment to contested causal explanations
- Cites Maffeis–Mitchell–Taly 2010, Goguen–Meseguer 1982, or Shpitser–Pearl in an AI governance (not security / programming-languages) context
- Names creative authorship attribution as a structural problem upstream of observable output data
- Introduces a standard, conformity assessment criterion, or certification requirement that operationalizes causal attribution, identifiability, or rooted human authorization

**Do NOT trigger on:**

- Generic use of "transparency," "explainability," "auditability," or "human oversight" without connection to causal identifiability or intervention geometry
- Standard XAI or SHAP/LIME attribution methods (not structural causal attribution in the SLT sense)
- Accountability frameworks that assign liability by proximity without requiring causal traceability
- "Structural" used as a general adjective not connected to intervention mapping rank
- "Probe" used as a synonym for test, benchmark, or evaluation without the bounded-episode / authority-activation architecture
- "Nominal authority" in the ordinary organizational-hierarchy sense without the geometric identifiability distinction
- Economic surplus distribution arguments not grounded in structural attribution indeterminacy
- "Neutrality" in the conventional foreign policy sense without the recognition-restraint / premature-authority-attachment framing
- Standards that address only technical performance metrics without governance, authorization, or attribution implications

---

### 9.10 Proximity Report Format

At the end of each brief, after all run outputs (§8), produce:

---

**RJB PUBLICATION PROXIMITY REPORT — {run date}**

| Item | Flag type | Publication(s) | Matched concept(s) | Structural note |
|---|---|---|---|---|
| {item title} | DIRECT CITATION or PROXIMITY SIGNAL | P1–P8 | {concept name} | {one line} |

If no items triggered either flag: "No proximity signals detected this run."

**Proximity trend note:** *(Optional after three or more runs — note whether any concept cluster is accumulating signals across runs. Accumulation may indicate field convergence toward a concept independently arrived at in the RJB corpus.)*

---

## Appendix: RJB Publication Registry (complete as of 15 June 2026)

| Ref | Short title | DOI | Date |
|---|---|---|---|
| P1 | Structural Limits of AI Accountability | 10.5281/zenodo.18866882 | March 4, 2026 |
| P2 | TR-CNI-1.1: Causal Non-Interference | 10.5281/zenodo.20025045 | March–April 2026 |
| P3 | TR-LSPD-1.0 + TR-SA-1.1: Latent-Space Extensions | 10.5281/zenodo.19799074 | April 26, 2026 |
| P4 | Attribution, Surplus, and Governance (Economic Domain) | 10.5281/zenodo.20394642 | 2026 |
| P5 | Structural Indeterminacy and Legal Attribution | 10.5281/zenodo.19998537 | 2026 |
| P6 | Creative Authorship and Structural Indeterminacy | 10.5281/zenodo.19998766 | 2026 |
| P7 | Swiss Neutrality and National Coherence | 10.5281/zenodo.20596277 | 2026 |
| P8 | Recognition Neutrality as Institutional Design (REA/CLP) | 10.5281/zenodo.20611099 | 2026 |

GitHub canonical (publications): https://github.com/rjblanchette/ABCF-v1
https://github.com/rjblanchette/ePCT

---

*End of prompt — version 1.3*
