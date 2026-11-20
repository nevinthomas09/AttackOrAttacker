# Decision rules

Decision rules for the experiments in *Attack or Attacker: A Leakage-Controlled Evaluation of Neural and
Neuro-Symbolic Detection of Unseen Network Attacks*. Each file states its hypotheses, metrics, thresholds and the
consequence of every outcome for the paper, and was fixed before the experiments it governs. Later changes are
recorded as dated amendments at the end of each file.

| File | Covers | Fixed on |
|---|---|---|
| `DECISIONS_TIER2.md` | H1–H5: rule axioms, label axioms, reproduction of Hindy et al., anomaly baselines, CORAL | 03/10/2026 |
| `DECISIONS_TIER3.md` | H6–H7: size-matched control, logic vs rule-derived data; checks F1–F5; Amendment 1: axiom-weight check (05/10/2026) | 04/10/2026 |
| `DECISIONS_TIER4.md` | H8–H10: matched weights, benign rule points, rule data in gradient boosting; F6–F7 | 14/10/2026 |
| `DECISIONS_TIER5.md` | H11–H13: knowledge-guided networks on CSE-CIC-IDS2018; review changes and Amendment 1 (15/10/2026) | 15/10/2026 |

Shared definitions (primary metric, seeds, operating point, category drop, validity guard) are in
`DECISIONS_TIER2.md` and apply to every later tier unless a file says otherwise.

The host-recognition analysis, the first rule experiments and the 0.1% operating point were not pre-registered.
