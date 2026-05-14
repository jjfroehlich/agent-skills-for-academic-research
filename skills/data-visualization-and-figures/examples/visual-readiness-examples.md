# Visual Readiness Examples

Use these examples when the user needs a concrete pattern for final figure critique.

## Hidden n and uncertainty

Input: A bar chart shows mean response for control and treated groups with `p=0.04`, but the underlying sample size is five biological replicates per group.

Output pattern:

```text
Primary risk: the bar chart hides the small sample size and distribution shape.
Recommended change: show each biological replicate as a point, add a median or mean with an uncertainty interval, and state the independent unit in the legend.
Interpretation boundary: keep the p-value secondary to the effect estimate and spread; do not imply a precise treatment effect from a small sample.
```

## Final-size multi-panel check

Input: A six-panel figure works at full screen but becomes unreadable at one-column width.

Output pattern:

```text
Must fix before export: panel labels, axis text, and inset labels must remain readable at final size.
Likely revision: split secondary panels into supplement, align remaining panels to one reading order, and move methods detail from the figure into the legend.
Technical check: verify line weights, color contrast, raster resolution, and vector text after export.
```
