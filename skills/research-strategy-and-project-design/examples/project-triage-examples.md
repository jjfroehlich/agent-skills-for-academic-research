# Project Triage Examples

## Project Comparison Table

Use this when the user asks which project to pursue or how to rank several ideas.

| Candidate project | Feasibility | Expected knowledge gain | Decisive uncertainty | Cheapest kill test | Timeline | Stage fit | Recommendation |
|---|---|---|---|---|---|---|---|
| New assay for a proposed mechanism | Medium | High | Does the assay detect the relevant signal above noise? | Small positive/negative-control pilot | 2-4 weeks | Good if assay support exists | Test before committing |
| Large dataset collection | Low | Medium | Is the expected effect visible in existing data? | Analyze public or pilot data first | 1-2 weeks for first check | Risky for early trainee | Delay unless signal appears |
| Incremental follow-up | High | Low | Does it answer a question anyone cares about? | One-paragraph claim and audience test | 1 week | Good only as training | Narrow or drop |

## Cheap Decisive Test Families

- Literature kill search: look for a recent result that already falsifies, solves, or trivializes the premise.
- Existing-data analysis: test whether the signal is even plausible before collecting new data.
- Online or small pilot: estimate noise, recruitment, effect size, or feasibility.
- Counterexample search: find cases that would break the proposed mechanism or model.
- Feared control: run the control that would most damage the preferred interpretation.
- Baseline comparison: check whether a simple alternative matches the proposed complex approach.

## Example Response Shape

```text
Recommendation: Run a one-week kill test before committing.

Why: The idea has high potential payoff, but the core premise depends on a necessary condition that has not been checked.

Decisive uncertainty: Whether the signal is detectable above the current noise floor.

Cheapest test: Reanalyze existing pilot data with a simple baseline and one feared negative control.

Continue if: The signal appears in the expected direction and the control rules out the obvious confound.

Stop or pivot if: The baseline explains the pattern or the control shows the signal is an artifact.
```

## Stuck-Project Example

If a project has become a default commitment, ask the user to write the best plausible title or claim it is becoming. If that output would not justify the remaining time, recommend a dated stop/go review and a cheaper alternative branch.

## Hypothesis Example

If the user says an observation "doesn't fit," do not immediately explain it away. Write the contradiction, list hidden assumptions, generate two or three candidate explanations, and select the prediction that best separates them.
