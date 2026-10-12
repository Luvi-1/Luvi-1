# Lavi

**Software engineering · Applied AI**

I’m building software and AI projects, with a current focus on reproducible machine-learning research.

## Featured project

### [Sport Signal](https://github.com/Luvi-1/sport-signal)

A sports analytics research project with two complementary tracks:

- **Outcome forecasting:** pre-event probabilities for soccer, baseball, American football, and tennis, evaluated on chronological holdouts
- **Tactical workbench:** five-sport analysis with seven reviewed aggregate model views, available through a local, read-only interface

The project connects historical data, availability-aware features, sport-specific models, and auditable evaluation. Its documentation includes negative results and the limits of retrospective analysis.

| Area | What to inspect |
| :--- | :--- |
| **Data & features** | Source-hashed snapshots, strict validation, and information-availability boundaries |
| **Evaluation** | Chronological development folds, separate calibration periods, and held-out comparisons against prior and Elo baselines |
| **Engineering** | Reproduction scripts, a guarded prediction CLI, leakage regression tests, and model cards |

[Project overview](https://github.com/Luvi-1/sport-signal) · [Local workbench](https://github.com/Luvi-1/sport-signal/blob/main/docs/tactical/WORKBENCH.md) · [Results](https://github.com/Luvi-1/sport-signal/blob/main/reports/v2/RESULTS.md) · [Reproduce the benchmark](https://github.com/Luvi-1/sport-signal/blob/main/docs/v2/REPRODUCE.md) · [Architecture & deployment gaps](https://github.com/Luvi-1/sport-signal/blob/main/docs/deployment.md)

## Current project stack

Python · NumPy · pandas · scikit-learn · JavaScript · GitHub Actions

## Development transparency

Sport Signal was developed with substantial AI assistance and is an ongoing learning project. The repository records its methodology, validation, data rights, limitations, and [authorship context](https://github.com/Luvi-1/sport-signal/blob/main/docs/APPLICATION_NOTE.md).
