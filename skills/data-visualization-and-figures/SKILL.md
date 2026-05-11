---
name: data-visualization-and-figures
description: Review, redesign, or plan scientific plots, tables, heatmaps, microscopy/image panels, multi-panel figures, graphical abstracts, legends, posters, slides, and manuscript figures when the user needs chart choice, uncertainty display, color accessibility, image annotation, layout, typography, or publication-readiness advice.
---

# Data Visualization And Figures

## Purpose

Help the agent make scientific figures honest, readable, accessible, and ready for their medium by matching the visual form to the evidence and reader task.

## Use this skill when

- The user asks for figure critique, chart choice, plot redesign, table redesign, graphical abstract planning, or publication-ready figure checks.
- The artifact includes distributions, p-values, effect sizes, intervals, small samples, repeated experiments, heatmaps, networks, genomic views, set intersections, or dense multi-panel displays.
- The request involves microscopy, photographs, image overlays, scale bars, insets, channels, annotations, layout, labels, typography, color, accessibility, posters, slides, or manuscript export.

## Do not use this skill when

- The task is only plotting-library syntax, package errors, or data-frame debugging.
- The user wants statistical analysis design with no visual artifact or visual decision.
- The request is prose-only writing feedback with no figure, table, diagram, or visual-output concern.

## Core workflow

1. Name the figure job: comparison, distribution, relationship, composition, process/overview, exact lookup, image evidence, or publication export.
2. Identify missing context that changes the recommendation: data type, `n`, independent unit, audience, medium, venue constraints, legend, or actual figure/image.
3. Inspect the actual figure before making exact layout, palette, microscopy, or graphical-abstract claims; if it is unavailable, state the recommendation as conditional.
4. Route to the narrowest reference file, then diagnose the highest-risk failure before polishing style.
5. Return recommendations as `problem -> fix -> rationale -> priority`, with assumptions and unresolved checks separated from confirmed findings.

## Reference routing

- Open `references/chart-selection.md` for chart family, raw-pattern visibility, bar/line alternatives, tables, and ordinary plot selection.
- Open `references/statistics-and-uncertainty.md` for effect sizes, intervals, p-values, replicate structure, overplotting, outliers, and small-n displays.
- Open `references/color-and-accessibility.md` for palettes, grayscale/color-vision checks, redundant encodings, and semantic color use.
- Open `references/specialized-figures.md` for heatmaps, networks, genome tracks, set intersections, temporal/dense data, matrices, and 3D displays.
- Open `references/biological-images.md` for microscopy, image panels, scale bars, channels, insets, annotations, and image-analysis workflow reporting.
- Open `references/layout-and-typography.md` for multi-panel hierarchy, labels, legends, axes, callouts, salience, spacing, typography, and final-size readability.
- Open `references/conceptual-figures.md` for graphical abstracts, overview figures, mechanism diagrams, pathways, neural-circuit diagrams, arrows, and schematic grammar.
- Open `references/publication-technical-requirements.md` for manuscript, poster, slide, preprint, raster/vector, font, resolution, color-mode, and venue-specific checks.

## Output formats

- `Figure critique`: prioritized findings in the order evidence-job mismatch, hidden data, statistical ambiguity, accessibility/color, layout/labels, export risk, and visual-review needs.
- `Redesign plan`: recommended form, encodings, layout changes, caveats, and required context.
- `Publication-readiness pass`: ready/needs revision/blocked status with must-fix items and venue assumptions.
- `Before/after guidance`: concise contrast between the current design and the stronger alternative.

## Quick checklist

- Does the visual form match the scientific task and data structure?
- Are raw observations, sample size, spread, uncertainty, independent units, and outliers visible when they affect interpretation?
- Does color encode meaning accessibly, with redundant cues where needed?
- Are image scale, channel identity, annotations, and analysis workflow clear when images support the claim?
- Do layout, labels, axes, typography, and export settings work at final size?

## Common pitfalls

- Recommending a prettier chart before naming the figure job.
- Hiding continuous or small-n data behind mean-only bars or lines.
- Treating p values, stars, or summary statistics as the visual evidence.
- Using diverging heatmap colors without a meaningful midpoint.
- Inferring image scale, channel meaning, palette accuracy, or exact layout quality without inspecting the actual figure.
- Guessing current journal requirements instead of asking for or checking the venue instructions.

## Quality bar

- Give specific, executable figure advice, not taste-level comments.
- Separate confirmed visual findings from conditional guidance and missing context.
- Treat accessibility, uncertainty, replicate structure, and final-size legibility as core checks.
- Keep provenance, source names, and extraction notes out of user-facing responses.
