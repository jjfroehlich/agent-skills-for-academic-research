# Decision Criteria Examples

Use these examples when the user needs research strategy rather than execution details.

## Project triage

Input: Three project ideas compete for one six-month slot.

Output pattern:

```text
Rank by decision value, not excitement alone.
Compare: novelty, feasibility, dependence on unavailable resources, decisive early test, publication path, and downside if the first test fails.
Recommendation: choose the project with the clearest cheap falsification test unless the highest-risk project has uniquely high strategic value.
```

## Kill criteria

Input: The lab wants to keep pursuing a mechanism after ambiguous pilot data.

Output pattern:

```text
Define the stop rule before the next experiment.
Continue if: the perturbation changes the predicted readout in the expected direction in the right cell state.
Pivot if: the phenotype appears only under a narrow artifact-prone condition.
Stop if: two orthogonal perturbations fail to move the readout despite adequate assay sensitivity.
```
