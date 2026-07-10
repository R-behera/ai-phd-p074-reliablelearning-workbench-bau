# Unique Prototype Algorithm

## Algorithm

**BauTriangulatedDeepLearningInterpretabilityProbeMatrix** (`P074-Bau-DeepLearningInterpretability`)

## Professor Alignment

- Professor: David Bau
- Research area: Deep learning interpretability, generative models
- Focus terms: Deep learning interpretability, generative models

## Core Mechanism

This prototype prioritizes decision-support failures with calibration and subgroup reliability risk.

## Decision Rule

Rank seed cases by ml-specific priority score with Bau-aligned focus term 'Deep learning interpretability'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `ml` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to David Bau's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
