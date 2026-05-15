# Merkabit Research — Master Results Registry (public)

Every numerical result cited in any **published** Merkabit paper traces to one row in `merkabit_results_registry.xlsx`.

**Last updated:** May 2026 (v9-public)
**Active result rows:** 354 across 42 distinct paper IDs

## What this is

A single spreadsheet auditing every quantitative claim in the Merkabit research programme: predictions vs measurements, computational verification numbers, hardware-confirmed observables, and theorem-rigorous results. Each row links a number to (a) the paper section that cites it, (b) the script that produced it, and (c) the dataset it ran against.

## File contents

`merkabit_results_registry.xlsx` — five sheets:

| Sheet | Purpose |
|-------|---------|
| **Results Registry** | Every cited number, columns: Result ID, Description, Value, Uncertainty, Paper, Section, Script, Dataset (Zenodo), Date, Status |
| **Dataset Provenance** | Zenodo DOIs, file counts, measurement types, and analysis applicability for every external dataset used |
| **Scripts Directory** | Analysis scripts that produce cited results, organised by dataset, with output numbers and repo location |
| **Submission Checklist** | Pre-submission audit items per paper |
| **Key Findings** | Narrative summaries of headline results |

## Status conventions

| Status | Meaning |
|--------|---------|
| `CONFIRMED` | Verified — derivation rigorous, simulation matches prediction, or hardware-validated |
| `HEDGED` | Result holds with caveats noted in the cited section |
| `PARTIAL` | Mixed result — some predictions confirmed, others ambiguous (often hardware noise) |
| `PENDING` | Pre-registered prediction awaiting hardware data |
| `OPEN` | Conjectural; cited but not yet provable |

## Coverage by paper

Papers 2–41 (excluding Paper 42), plus the Companion paper (CP), 24-cell geometric foundations (GF), and Meditation analysis (MED-P1).

## ID prefixes

| Prefix | Topic |
|--------|-------|
| `P<N>-XX` | Paper N |
| `CP-XX` | Companion paper (alpha=4/3 driven coherent systems) |
| `GF-XX` | Geometric Foundations / 24-cell investigation |
| `MED-P1-XX` | Meditation analysis (Paper 1 / Phase 1 deep dive) |

## What's not in this public registry

To protect unpublished hardware protocols and theory in development, this public version excludes:

- **Paper 42** (Matter Generator) — theoretical synthesis still in private development
- **Three-generations IBM hardware test** (3GEN-HW) — protocol details for an in-progress hardware validation of Paper 29's commutator predictions
- **Audit-trail rows** marked SUPERSEDED in the master registry (these document version drift and aren't useful for external readers)

The full master registry is maintained privately at `selinaserephina-star/Results_Registry`.

## Companion repos

Most cited scripts live in https://github.com/SelinaAliens (one repo per paper). The Scripts Directory sheet's `Location` column names the repo per script.

| Paper | Public repo |
|-------|-------------|
| Base | [The_Merkabit](https://github.com/SelinaAliens/The_Merkabit) |
| 3 | [The_Rotation_Gap_Is_Not_An_Error](https://github.com/SelinaAliens/The_Rotation_Gap_Is_Not_An_Error) |
| 4 | [enzymes_5_gates_merkabit](https://github.com/SelinaAliens/enzymes_5_gates_merkabit) |
| 5 | [merkabit_results-fusion_ignition](https://github.com/SelinaAliens/merkabit_results-fusion_ignition) |
| 6 | [merkabit_geometric_operator](https://github.com/SelinaAliens/merkabit_geometric_operator) |
| 7 | [Riemann_Zeroes](https://github.com/SelinaAliens/Riemann_Zeroes) |
| 8 | [Klein_quartic_merkabit](https://github.com/SelinaAliens/Klein_quartic_merkabit) |
| 9 | [yang_mills_Merkabit](https://github.com/SelinaAliens/yang_mills_Merkabit) |
| 11 | [standard_model_merkabit](https://github.com/SelinaAliens/standard_model_merkabit) |
| 12 | [w_boson_as_alegbraic_inversion](https://github.com/SelinaAliens/w_boson_as_alegbraic_inversion) |
| 13 | [gauge_group_merkabit](https://github.com/SelinaAliens/gauge_group_merkabit) |
| 14 | [Matter_is_fano](https://github.com/SelinaAliens/Matter_is_fano) |
| 15 | [rotation_gap_is_flat](https://github.com/SelinaAliens/rotation_gap_is_flat) |
| 16 | [Yang-Mills_Spectral-Resonance](https://github.com/SelinaAliens/Yang-Mills_Spectral-Resonance) |
| 17 | [plasma_is_the_weak_force](https://github.com/SelinaAliens/plasma_is_the_weak_force) |
| 20 / 22 | [Merkabit_architecture_gravity_cosmological_constant](https://github.com/SelinaAliens/Merkabit_architecture_gravity_cosmological_constant) |
| 27 | [Black_holes_holography_membrane](https://github.com/SelinaAliens/Black_holes_holography_membrane) |
| 29 | [three_generations_merkabit](https://github.com/SelinaAliens/three_generations_merkabit) |
| 32 | [tesseract_quantum_implementation](https://github.com/SelinaAliens/tesseract_quantum_implementation) |
| 33 | [pentachoric_verification](https://github.com/SelinaAliens/pentachoric_verification) |
| 35 | [closure_forces_the_clock](https://github.com/SelinaAliens/closure_forces_the_clock) |
| 37, 38, 40 | [Riemanns_alignment](https://github.com/SelinaAliens/Riemanns_alignment) |
| 39 | [genesis_sequence_merkabit](https://github.com/SelinaAliens/genesis_sequence_merkabit) |
| 41 | [Riemanns_resolution](https://github.com/SelinaAliens/Riemanns_resolution) |
| Companion | [merkabit-companion-analysis](https://github.com/SelinaAliens/merkabit-companion-analysis) |
| Entanglement | [entanglement_4-3](https://github.com/SelinaAliens/entanglement_4-3) |

## How to cite

Stenberg, S. (2026). *Merkabit Research — Master Results Registry*. GitHub. https://github.com/SelinaAliens/Merkabit_results_registry

The registry indexes results across 30+ papers; for individual claim citations please cite the specific paper named in the `Paper` column. Paper Zenodo DOIs are listed in the [companion papers index](https://github.com/SelinaAliens/The_Merkabit).

## License

MIT License — see `LICENSE` file.

---

Selina Stenberg with Claude (Anthropic, Opus 4.7).
