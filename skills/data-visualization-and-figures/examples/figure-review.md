# Figure Review Examples

Use these as patterns for actionable, non-provenance figure feedback.

## Weak feedback

```text
This plot is cluttered. Use nicer colors and make the labels bigger.
```

Why it fails: it gives taste-level advice without naming the data task, the misleading element, or the specific revision.

## Strong feedback

```text
Main job: compare distributions across the three treatment groups.
Top priority: the current bar chart hides sample size and spread -> replace it with jittered points plus a median and interval -> this lets readers see whether the treatment difference is driven by all observations or one outlier.
Accessibility/readability check: keep the palette muted, label groups directly, and test the final column-width version.
Missing context: state the independent unit and `n` per group in the caption.
```

Why it works: it names the job, identifies the failure, gives a concrete redesign, and explains the rationale.

## Common transformations

- Mean-only bar chart with continuous small-n data -> points plus interval, box/dot plot, or paired display.
- P-value-focused result -> effect estimate plus uncertainty interval, with p-value secondary.
- Red/green fluorescence merge -> accessible channel colors, single-channel panels if needed, and explicit channel legend.
- Dense multi-panel figure -> one reading order, aligned panels, direct labels, and secondary material moved to caption or supplement.
- Heatmap with arbitrary diverging palette -> palette chosen from data semantics and a labeled color scale.
- Network hairball -> filtered subnetwork, adjacency matrix, grouped layout, or supplemental interactive view.

## Bad assistant traps

- Giving plotting-code advice when the user asked for design critique.
- Saying "make it cleaner" without specifying what to remove.
- Treating accessibility as optional polish.
- Inferring image scale, channel identity, replicate structure, exact palette performance, or layout quality without the actual figure.
- Guessing venue specifications instead of stating assumptions and required checks.
