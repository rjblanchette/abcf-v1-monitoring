# ABCF-v1 Monitoring System — Claude Project Instructions

## Repo
`rjblanchette/abcf-v1-monitoring`

## System overview

This project implements a two-tier AI governance monitoring system for ABCF-v1 research.

**Tier 1** produces dated monitoring briefs via live web search.
**Tier 2** analyses the accumulated brief corpus for research positioning (Layer 1) and IP decision node mapping (Layer 2).

All prompts are versioned knowledge files in `prompts/`. All briefs are stored in `briefs/` with the naming convention `YYYY-MM-DD_Brief_RunN.md`.

---

## How to invoke each prompt

### Tier 1 — Run a monitoring brief

Say: **"Run the monitoring prompt"** or **"Run Tier 1"**

Claude loads `prompts/ABCF-v1_Monitoring_Prompt_v1.2.md` (or the highest version present), executes all search vectors, and produces a full brief. Save the output to `briefs/` with the correct filename before closing the session.

### Tier 2, Layer 1 — Research positioning analysis

Say: **"Run Layer 1"** followed by a scope instruction:

```
RUN SCOPE: ALL
```
or
```
RUN SCOPE: 2026-06-01 to 2026-07-31
```

Claude loads `prompts/ABCF-v1_Corpus_Layer1_vX.X.md` (highest version), identifies all briefs in `briefs/` matching the scope, and produces a research positioning report.

### Tier 2, Layer 2 — IP decision node mapping

Say: **"Run Layer 2"** followed by a scope instruction:

```
RUN SCOPE: ALL
```
or
```
RUN SCOPE: 2026-06-01 to 2026-07-31
```

Claude loads `prompts/ABCF-v1_Corpus_Layer2_vX.X.md` (highest version), identifies all briefs in `briefs/` matching the scope, and produces an IP decision node brief formatted for counsel.

### Running both Tier 2 layers

Say: **"Run Layer 1 and Layer 2"** with a scope instruction. Claude runs them sequentially and produces both outputs in a single session.

---

## Versioning convention

Prompts follow semantic versioning: `vMAJOR.MINOR`

- MAJOR increment: structural change to output format or analytical framework
- MINOR increment: additions (new publications, new search themes, refined trigger criteria)

Always load the highest version of each prompt present in `prompts/`.

---

## Epistemic rules that apply in all sessions

- All Claude outputs in this project are InterpretationArtifacts at Stage 01 unless RJ explicitly advances them.
- Layer 2 outputs are structured question sets for counsel. They are not legal opinions and must not be treated as such.
- Proximity signals identify architectural convergence. They do not constitute IP claims.
- No output from this system authorizes any filing, publication, or legal decision without RJ's explicit AuthorizationAct.

---

## RJB publication registry (canonical)

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
