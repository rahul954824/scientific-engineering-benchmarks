# Benchmark Design Methodology

## Purpose

The challenge briefs in this repository are starting points for evaluating scientific and engineering reasoning in AI agents. A brief becomes an executable benchmark only after its assumptions, inputs, outputs, scoring rules and test cases are specified.

## A consistent task lifecycle

1. **Define the decision.** State the engineering question, decision variables, operating limits and objective.
2. **Describe the system.** Specify governing equations, units, boundary conditions, constitutive relationships and valid operating range.
3. **Design observations.** Provide realistic synthetic or openly licensed measurements with documented noise, bias, missingness and sampling behavior.
4. **Specify identification.** Define parameter bounds, objective function, weighting, robust-loss choices and required diagnostics.
5. **Quantify uncertainty.** State the uncertainty method and how it propagates into predictions and decisions.
6. **Evaluate predictions.** Include cases outside the calibration points but within a declared validity envelope.
7. **Score decisions.** Check constraints, safety margins, objective value and sensitivity to uncertainty.
8. **Test software behavior.** Validate parsing, units, edge cases, numerical stability, deterministic output and resource limits.

## Fairness and validation

- Publish a complete, unambiguous input/output contract.
- Generate held-out cases independently from public examples.
- Use at least one independent reference calculation for critical numerical outputs.
- Test plausible incorrect approaches, not just formatting mistakes.
- Set tolerances based on numerical conditioning and engineering significance.
- Separate scientific correctness from software-interface compliance.
- Record known limitations and avoid claims unsupported by evidence.

## Recommended scoring dimensions

| Dimension | What to inspect |
|---|---|
| Model formulation | Correct governing model, assumptions and units |
| Parameter estimation | Identifiability, residuals and treatment of data quality |
| Uncertainty | Appropriate uncertainty estimates and propagation |
| Prediction | Accuracy on held-out operating conditions |
| Decision | Constraint satisfaction and objective quality |
| Robustness | Sensitivity, edge cases and numerical stability |
| Reproducibility | Deterministic execution and documented dependencies |
| Explanation | Traceable reasoning, assumptions and limitations |

## Current maturity

The repository contains conceptual briefs only. No hidden datasets, reference solutions, automatic graders, or validation results are included. Do not describe these briefs as completed or validated benchmarks until those components exist and have been independently checked.
