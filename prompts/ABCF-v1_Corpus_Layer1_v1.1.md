# ABCF-v1 Corpus Analysis — Layer 1: Research Positioning
**Version:** 1.1
**Last revised:** 17 June 2026
**Change from v1.0:** §8 (Recommended search vectors for next Tier 1 run) is now the **sole authoritative source** of next-Tier-1 search vector guidance. The Tier 1 monitoring prompt's per-run "Suggested searches for next run" output has been retired (see Tier 1 monitoring prompt v2.0). Framing and a cadence note added to §8. No change to analytical framework, epistemic rules, or any other section.

---

## 1. Purpose

This prompt analyses the accumulated ABCF-v1 monitoring brief corpus to produce a research positioning report. It answers the question: *what does the corpus show about where the field is going, where ABCF-v1 sits relative to it, and what research and publication opportunities are visible?*

This is a research strategy tool, not a legal tool. Layer 2 handles IP decision nodes.

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

Load all briefs matching the scope. If a brief filename does not include a date, treat it as undated and include it in ALL scope runs but exclude it from date-bounded runs.

---

## 3. Epistemic rules

- Separate facts (what the briefs record) from interpretation (what the pattern may mean).
- Do not claim field convergence unless at least two independent sources in the corpus arrive at structurally similar claims without citing each other or the RJB corpus.
- Do not treat proximity signals as citations. They are architectural convergence indicators only.
- Do not treat ABCF classification labels as validated peer assessments. They are analytical framings applied by the monitoring system.
- Mark all trend claims as inferences. Mark all structural gap claims as assessments, not facts.
- All outputs are InterpretationArtifacts at Stage 01. RJ's explicit AuthorizationAct is required before any output is used to make a research or publication decision.

---

## 4. Analysis structure

Produce the following sections in order.

---

### Section 1 — Corpus inventory

List all briefs included in this run with:
- Filename
- Run date
- Item count
- Proximity signal count
- ABCF classification distribution (count per category)

---

### Section 2 — Concept cluster map

Identify which ABCF/RJB concepts have appeared across multiple briefs. For each concept cluster:

- **Concept name** (using RJB terminology from the publication registry)
- **Appearances:** count of items across briefs that triggered this concept
- **Source diversity:** how many distinct independent sources (not citing each other) arrived at convergent claims
- **Trajectory:** stable / increasing / decreasing across the date range
- **Gap assessment:** what the field has arrived at vs. what the RJB corpus adds that the field has not reached

Format as a table followed by brief prose analysis of the top three clusters by source diversity.

---

### Section 3 — Field convergence assessment

For each concept cluster with source diversity ≥ 2:

- **Convergence type:** Choose one:
  - *Independent parallel* — multiple sources arrive at structurally similar claims without citing each other
  - *Sequential elaboration* — later sources build on earlier ones in the corpus
  - *Analogical approach* — sources address a related but distinct problem using similar framing
- **Convergence depth:** Surface (same language, different meaning) / Structural (same architectural claim) / Formal (same formal object or proof strategy)
- **RJB priority position:** Does the RJB corpus predate the converging sources? By how much? Is the priority date clearly established by Zenodo timestamp?
- **Remaining gap:** What does the RJB corpus provide that none of the converging sources have reached?

---

### Section 4 — Citation and framing opportunities

For each item across the corpus classified as "Coherent and aligned" or "Coherent but incomplete":

Assess whether it provides:

- **Citation support:** Can it be cited in a future RJB paper to ground a claim that the field recognizes the problem ABCF addresses?
- **Framing anchor:** Can it be used to frame the gap that ABCF fills ("existing approaches do X but not Y")?
- **Positioning contrast:** Can it be used to distinguish ABCF from an adjacent approach ("unlike X, ABCF does not merely...but...")?

Produce a short table:

| Item | Publication / source | Use type | Notes |
|---|---|---|---|

---

### Section 5 — Domain coverage assessment

Assess coverage across the eight RJB publication domains:

| Domain | P-ref | Items in corpus | Concept hits | Gap |
|---|---|---|---|---|
| Core causal governance / SLT | P1 | | | |
| Causal Non-Interference / CNI | P2 | | | |
| Latent-space extensions (L-SLT, RI, SA) | P3 | | | |
| Economic domain | P4 | | | |
| Legal attribution | P5 | | | |
| Creative authorship | P6 | | | |
| Swiss neutrality / recognition neutrality | P7 | | | |
| REA / Civic Legibility Packet | P8 | | | |

For domains with zero or low coverage: identify whether this reflects absence of field activity or a search vector gap. Recommend targeted search terms for the next Tier 1 run.

---

### Section 6 — Weak signal watch list

List all items across the corpus flagged as "Watchlist only" or appearing in the "Weak signals" section of any brief. For each:

- Has the signal strengthened, weakened, or held steady across runs?
- Has it yet triggered a proximity flag?
- Does it warrant promotion to a monitored concept cluster?

---

### Section 7 — Research positioning summary

Produce a 400–600 word synthesis answering:

1. Where is the field moving relative to ABCF-v1's theoretical positions?
2. Which RJB concepts are most at risk of independent field convergence in the next 1–3 months?
3. Which RJB concepts remain structurally ahead of the field with no visible convergence?
4. What are the two or three highest-priority research actions visible from the corpus?

Close with: **"This is a Stage 01 InterpretationArtifact. No action should be taken on these assessments without RJ's explicit review and AuthorizationAct."**

---

### Section 8 — Recommended search vectors for next Tier 1 run

**This section is the sole authoritative source of next-Tier-1 search vector guidance.** As of Tier 1 monitoring prompt v2.0, individual Tier 1 briefs no longer emit a per-run "Suggested searches for next run" list. Next-run vector guidance is generated *here*, from the corpus-wide view — domain coverage gaps across all briefs in scope plus the §6 weak signal watch list — rather than from any single run's narrower vantage.

Based on the domain coverage assessment (Section 5), the weak signal watch list (Section 6), and the field convergence assessment (Section 3), provide 8–12 targeted search queries for the next Tier 1 monitoring run. For each query:

- Flag whether it is a **new vector** or a **refinement** of an existing standing vector (Tier 1 prompt §3 / §3a / §3b).
- Note which RJB domain (P1–P8) or weak signal it is intended to surface.

**Cadence note:** Tier 1 runs more frequently than Layer 1. Between Layer 1 passes, Tier 1 runs operate on the standing prompt vectors (§3 / §3a / §3b) alone — this is by design, as the standing vectors are the primary engine and these recommendations are a refinement layer. These recommended vectors therefore refresh on the Layer 1 cadence. If Tier 1 cadence materially outpaces Layer 1, run Layer 1 to refresh next-run guidance.

---

*End of Layer 1 prompt — version 1.1*
