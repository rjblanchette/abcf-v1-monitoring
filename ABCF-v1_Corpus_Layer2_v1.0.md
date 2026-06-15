# ABCF-v1 Corpus Analysis — Layer 2: IP Decision Node Mapping
**Version:** 1.0
**Last revised:** 15 June 2026

---

## 1. Purpose

This prompt analyses the accumulated ABCF-v1 monitoring brief corpus to produce a structured IP decision node brief. It answers the question: *what does the corpus show about priority positions, independent convergence risks, and publication sequencing considerations that require a decision?*

**This prompt produces a structured question set and decision node map for counsel and RJ's review. It does not produce legal opinions, freedom-to-operate analyses, or patentability assessments. All outputs are InterpretationArtifacts requiring RJ's explicit AuthorizationAct before any decision is made.**

---

## 2. Input

**Corpus location:** `briefs/` directory of `rjblanchette/abcf-v1-monitoring`

**Scope instruction (required):**
```
RUN SCOPE: ALL
```
or
```
RUN SCOPE: YYYY-MM-DD to YYYY-MM-DD
```

Load all briefs matching the scope. Apply the same date-scoping rules as Layer 1.

---

## 3. Epistemic rules

- Separate what the corpus records (facts) from what it may imply for IP strategy (inferences).
- Do not assess patentability, novelty, or freedom-to-operate. Those are legal determinations reserved for qualified counsel.
- Do not treat proximity signals as prior art findings. They are architectural convergence indicators. Prior art determination is a legal judgment.
- Do not treat Zenodo timestamps as legally confirmed priority dates without counsel verification.
- Mark every inference clearly. Mark every open legal question as a question for counsel, not a conclusion.
- Do not recommend specific filing strategies. Map the decision nodes and the information available at each node; let RJ and counsel make the decisions.
- All outputs are InterpretationArtifacts at Stage 01.

---

## 4. Analysis structure

Produce the following sections in order.

---

### Section 1 — RJB IP portfolio context (from project knowledge)

Summarize the current IP portfolio status as recorded in project knowledge (memories, prior session context). Include:

- UK patent applications: filing numbers, titles, status notes
- PCT filings: filing numbers, titles, status notes
- Zenodo defensive publications: P1–P8 with DOIs and dates
- GitHub canonical: URL
- Any known pending decisions (e.g. abandonment considerations, PCT deadlines)

**Note any portfolio items whose status is flagged as uncertain or requiring verification.** Do not assert status that is not confirmed in available context.

---

### Section 2 — Independent convergence risk register

For each proximity signal recorded across the corpus, assess the convergence risk to RJB IP:

| Signal | Source | Date | RJB concept | RJB priority date | Convergence depth | Risk note |
|---|---|---|---|---|---|---|

**Convergence depth:**
- *Surface* — similar language, different technical claim
- *Structural* — similar architectural claim, different formal apparatus
- *Formal* — same or closely analogous formal object, proof structure, or claim element

**Risk note guidance (factual only — do not assess legal implications):**
- State whether the source predates or postdates the relevant RJB Zenodo deposit
- State whether the source is in the same technical domain as any live UK or PCT application
- State whether the source has been published, submitted to a standards body, or filed as a patent
- Do not conclude whether this constitutes prior art or affects patentability

---

### Section 3 — Publication sequencing observations

For each domain covered by the corpus, note:

- Whether any external item has been published in a peer-reviewed venue that addresses concepts in that domain
- Whether the corresponding RJB publication (P1–P8) predates or postdates that external item by Zenodo timestamp
- Whether any RJB domain has no corresponding Zenodo deposit yet (implementation layer concepts that may still be patentable)

**Format as a table:**

| Domain | RJB pub (P-ref) | Zenodo date | External parallel | External date | Priority gap (days) | Notes |
|---|---|---|---|---|---|---|

Do not assess whether the priority gap is legally sufficient. Flag gaps for counsel review.

---

### Section 4 — Defensive publication coverage assessment

Assess which RJB concepts are currently covered by Zenodo defensive publication (P1–P8) and which are not:

**Covered:** List concepts with confirmed Zenodo DOI and date.

**Not yet covered:** List concepts that appear in project knowledge as part of the ABCF-v1 architecture but have no Zenodo deposit. Flag each as:
- *Implementation layer* — may still be patentable; defensive publication may close patent window
- *Theoretical layer* — defensive publication appropriate; patent protection not available
- *Status unclear* — requires counsel determination before any publication decision

**Do not recommend whether to publish or file.** Map the coverage and flag the decision nodes.

---

### Section 5 — Corpus-derived decision nodes

List every decision visible in the corpus that has a time dimension or a sequencing dependency. For each:

- **Decision node:** what needs to be decided
- **Information available:** what the corpus provides that is relevant
- **Information missing:** what would need to be verified or obtained before deciding
- **Time sensitivity:** is there a known deadline or window that applies?
- **Who decides:** RJ alone / RJ + counsel / RJ + counsel + other
- **Blocking dependency:** does this decision block or depend on another?

Format as a structured list, not a table (some nodes require more prose than a table allows).

**Do not recommend a decision at any node.** Map the nodes only.

---

### Section 6 — Questions for counsel

Produce a structured question list formatted for transmission to patent counsel. Questions should be:

- Specific and grounded in corpus observations
- Framed to elicit legal judgment, not confirm RJ's assumptions
- Sequenced from most time-sensitive to least

**Format:**
```
Q[N] — [Domain / filing reference]
Context: [one sentence of factual context from the corpus]
Question: [the legal question for counsel]
Time sensitivity: [high / medium / low]
Blocking: [what this question blocks, if anything]
```

---

### Section 7 — Summary brief for counsel

Produce a 300–500 word plain-language summary suitable for transmitting to patent counsel alongside the full Layer 2 report. It should:

- Describe the monitoring system and what the corpus represents
- Summarize the independent convergence signals found
- Identify the most time-sensitive decision nodes
- State clearly that the report does not contain legal analysis and is provided to support counsel's independent assessment

Close with: **"This document is a Stage 01 InterpretationArtifact produced by a structured monitoring system. It does not constitute legal advice, a prior art search, or a patentability assessment. All decisions remain with RJ Blanchette and qualified counsel."**

---

*End of Layer 2 prompt — version 1.0*
