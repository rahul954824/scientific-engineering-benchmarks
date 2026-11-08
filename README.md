# Scientific & Engineering Agent Challenges

An independent portfolio of **conceptual benchmark briefs** for evaluating AI agents on scientific computing and engineering decision-making.

These briefs are original, generalized exercises inspired by broad problem-solving patterns across chemical, civil, process, pharmaceutical and reactor engineering. They are not the source project's task specifications, datasets, reference implementations, or tests.

## What the challenges assess

A strong agent should be able to:
- translate an engineering scenario into a defensible mathematical model;
- identify parameters from imperfect measurements and explain assumptions;
- account for measurement uncertainty and model limitations;
- predict behavior beyond the observed operating points;
- compare feasible designs against explicit safety or performance constraints;
- produce reproducible code and communicate limitations.

## Challenge catalogue

| # | Challenge | Area | Core capability |
|---|---|---|---|
| 01 | Pipeline Transient Protection | Hydraulic engineering | Transient modelling and valve strategy |
| 02 | Gas Absorption Capacity Planning | Separation processes | Mass-transfer modelling and constrained design |
| 03 | Adsorption Unit Performance | Separation processes | Breakthrough prediction and model selection |
| 04 | Ground Improvement Planning | Geotechnical engineering | Consolidation modelling and schedule design |
| 05 | Reactive Separation Screening | Chemical engineering | Phase equilibrium and feasibility analysis |
| 06 | Catalyst Health and Operating Policy | Reaction engineering | Deactivation estimation and safe operation |
| 07 | Reactor Control-Rod Scenario Analysis | Reactor physics | Transient response and uncertainty-aware limits |
| 08 | Process Controller Tuning | Process control | System identification and robust tuning |
| 09 | Bioreactor Throughput Planning | Bioprocess engineering | Inhibition, oxygen limits and dynamic response |
| 10 | Freeze-Drying Cycle Planning | Pharmaceutical engineering | Heat/mass transfer and process constraints |
| 11 | Synthesis Loop Operating Envelope | Reaction engineering | Model reconciliation and operating-envelope prediction |
| 12 | Membrane Separation Optimization | Separation processes | Coupled transport and design optimization |

Each challenge folder contains a high-level brief and suggested evaluation dimensions. These are **portfolio concepts**, not complete executable benchmark specifications. No source-project data, hidden tests, reference answers, or proprietary implementation details are included.

## Suggested evaluation dimensions

1. **Scientific correctness:** equations, units, boundary conditions and physical interpretation.
2. **Identification quality:** treatment of noisy, biased, missing or correlated observations.
3. **Uncertainty reasoning:** distinction between point estimates, uncertainty and model discrepancy.
4. **Prediction:** sensible extrapolation and explicit limits on validity.
5. **Decision quality:** feasibility, safety margins, objective trade-offs and sensitivity.
6. **Software quality:** reproducibility, input validation, numerical stability and clear outputs.
7. **Communication:** assumptions, evidence, caveats and actionable conclusions.

## Repository status

This repository currently provides conceptual challenge briefs only. It does not claim that the tasks have been implemented, independently validated, or run through an automated grader. Future additions should include fully specified inputs/outputs, independently generated cases, reference calculations, and tests before being described as executable benchmarks.

## Provenance and scope

Created as an independent portfolio. The task titles and briefs here are generalized and newly written; they do not reproduce another project's task files. Do not infer access to or authorship of any third-party benchmark implementation from this repository.
