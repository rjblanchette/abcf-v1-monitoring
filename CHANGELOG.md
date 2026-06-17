# Changelog — abcf-v1-monitoring

All prompt and structural changes to the monitoring system. Versions follow `vMAJOR.MINOR`
(MAJOR = structural change to output format or analytical framework; MINOR = additions).
Each prompt also carries its own change-from note in its header; this file is the consolidated view.

---

## 2026-06-17

### Tier 1 — Monitoring Prompt v1.5 → **v2.0** (MAJOR)
- Removed §8 run-output item "Suggested searches for next run."
- Next-Tier-1 search-vector guidance is now generated solely by Tier 2 Layer 1 §8 (corpus-wide view), eliminating the redundant per-run single-run suggestion list and the divergence risk of two sections producing the same artifact.
- §8 items renumbered (10 → 9); cross-reference pointer added; §10 item count and brief-header template version updated.
- No change to search vectors (§3 / §3a / §3b), ABCF components (§4), item format (§5), prioritization (§6), epistemic rules (§7), or the RJB Publication Proximity machinery (§9).

### Tier 2 — Corpus Layer 1 v1.0 → **v1.1** (MINOR)
- §8 reframed as the sole authoritative source of next-Tier-1 search-vector guidance.
- Added per-query new-vs-refinement tagging and P-ref / weak-signal attribution; added cadence note.
- No change to analytical framework or any other section.

### Docs
- `README.md` and `PROJECT_INSTRUCTIONS.md` version pointers aligned to Tier 1 v2.0 / Layer 1 v1.1.
- `README_CHANGES.md` (prompt-update working artifact) retired in favour of this `CHANGELOG.md`.

---

## 2026-06-16

### Tier 1 — Monitoring Prompt v1.4 → **v1.5** (MINOR)
- Added §3b (World-Model / Predictive-Architecture Search Vector): JEPA-class architectures, world-model self-governance claims, the predictive-success-as-governance thesis.
- Renamed §8 standards summary to "Standards and Architecture Body Status Summary" (added §3b coverage).
- Added JEPA-class governance-gap proximity triggers and the `[COMPETITIVE SIGNAL — JEPA-CLASS BET]` flag to §9.

### Tier 1 — Monitoring Prompt v1.3 → **v1.4** (MINOR)
- *Change note not verified in this pass — backfill from the v1.4 file header.*

---

## 2026-06-15

### Tier 1 — Monitoring Prompt v1.2 → **v1.3** (MINOR)
- Added §3a (Standards Body Search Vector): dedicated primary-source monitoring for ISO SC 42, IEEE, EU AI Act implementing acts, NIST, IETF, W3C, OECD, Council of Europe.

### Tier 1 — Monitoring Prompt **v1.2**
- Baseline version in use at Run 1 (2026-06-15). *Earlier history, if any, to be backfilled from the v1.2 file header.*

### Tier 2 — Corpus Layer 1 **v1.0**, Corpus Layer 2 **v1.0**
- Initial corpus-analysis prompts: Layer 1 (research positioning), Layer 2 (IP decision node mapping).

---

*Entries marked for backfill are flagged rather than reconstructed, to avoid asserting version history that was not verified against the source file.*
