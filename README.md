# abcf-v1-monitoring

ABCF-v1 AI Governance Monitoring System — two-tier research and IP tracking tool.

---

## Structure

```
abcf-v1-monitoring/
│
├── PROJECT_INSTRUCTIONS.md          ← Claude Project instructions
├── README.md                        ← this file
│
├── prompts/
│   ├── ABCF-v1_Monitoring_Prompt_v1.2.md     ← Tier 1: live search brief
│   ├── ABCF-v1_Corpus_Layer1_v1.0.md         ← Tier 2: research positioning
│   └── ABCF-v1_Corpus_Layer2_v1.0.md         ← Tier 2: IP decision nodes
│
└── briefs/
    └── YYYY-MM-DD_Brief_RunN.md               ← saved Tier 1 outputs
```

---

## How to use

### Run a Tier 1 monitoring brief

Open the Claude Project. Say: **"Run the monitoring prompt"**

Claude executes live searches and produces a dated brief. Save the output as `briefs/YYYY-MM-DD_Brief_RunN.md` before closing the session.

### Run Tier 2 corpus analysis

Open the Claude Project. Say: **"Run Layer 1"** or **"Run Layer 2"** or **"Run Layer 1 and Layer 2"**

Follow with a scope instruction:

```
RUN SCOPE: ALL
```
or
```
RUN SCOPE: 2026-06-01 to 2026-07-31
```

Claude loads the relevant prompt from `prompts/` and analyses all briefs in `briefs/` matching the scope.

---

## Tier summary

| Tier | Prompt | Purpose | Input | Output |
|---|---|---|---|---|
| 1 | Monitoring_Prompt_v1.2 | Live AI governance surveillance | Web search | Dated brief (.md) |
| 2 / Layer 1 | Corpus_Layer1_v1.0 | Research positioning | Brief corpus | Positioning report |
| 2 / Layer 2 | Corpus_Layer2_v1.0 | IP decision node mapping | Brief corpus | Counsel brief |

---

## Versioning

Prompts follow `vMAJOR.MINOR` convention.
- MAJOR: structural change to output format or analytical framework
- MINOR: additions (publications, search themes, trigger criteria)

Always load the highest version present in `prompts/`.

---

## Related repositories

- **ABCF-v1 publications canonical:** https://github.com/rjblanchette/ABCF-v1
- **Zenodo deposit:** https://doi.org/10.5281/zenodo.19799074

---

## Publication registry

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
