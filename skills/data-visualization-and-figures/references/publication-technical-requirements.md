# Publication Technical Requirements

Use this when a figure is headed to a journal, preprint, poster, slide deck, grant, report, or public-facing scientific output.

## Use this when...

- The user asks if a figure is ready for submission, presentation, or export.
- The figure may fail because of final size, file type, font, line weight, resolution, raster/vector choice, or venue constraints.
- The target medium changes the design recommendation.

## The job of this topic

Catch medium and export failures that can make an otherwise strong figure unreadable, noncompliant, or misleading at final delivery size.

## Default workflow

1. Ask for target medium and venue if size, file type, color mode, accessibility, or export constraints matter.
2. Check final physical or pixel dimensions before judging text size and line weight.
3. Verify labels, legends, symbols, annotations, scale bars, and image details at final reduction or projection size.
4. Choose raster output for image data and vector output for plots/diagrams when the venue permits.
5. Check resolution, embedded fonts, transparency, color mode, and panel assembly requirements when known.
6. State assumptions when venue specifications are missing; do not invent current journal rules.

## Decision rules

- Manuscript figures need final column/page width testing.
- Posters need distance readability and stronger hierarchy than manuscripts.
- Slides need fewer simultaneous claims and larger labels.
- Raster image panels should not be repeatedly resampled or enlarged beyond useful resolution.
- Vector charts and diagrams should preserve editable text/lines unless the venue requires flattening.
- Manual edits must be reproducible or documented enough not to break future revision.
- Current journal instructions override generic style preferences.

## Variants and edge cases

- Composite figures: confirm that labels, legends, scale bars, and annotations remain tied to the correct panel.
- Preprints: optimize for screen readability and downloadable PDF use.
- Grants: prioritize review readability and explanatory captions over journal-specific file minutiae unless required.
- Unknown venue: return a generic readiness pass and list the venue checks still needed.

## Anti-patterns

- Reviewing at zoomed-in size only.
- Using software defaults for font size or line width without final-size testing.
- Ignoring color mode, resolution, transparency, or font embedding until submission.
- Treating posters, slides, and manuscripts as interchangeable.
- Guessing exact venue requirements from memory.

## Diagnostic questions

- What is the final display size?
- What venue requirements are known?
- Which elements become illegible when reduced or projected?
- Are fonts embedded, labels readable, and line weights visible?
- Does the figure work in print, screen, and projection contexts as needed?

## Output patterns / mini-templates

```text
Readiness status: <ready/needs revision/blocked>.
Known constraints: <venue/medium specs supplied>.
Must fix before export: <items>.
Assumptions: <unknown specs to verify>.
```

## Examples

- `Manuscript panel that looks fine full-screen`: test at single-column width before accepting labels and line weights.
- `Slide made from a manuscript figure`: split into fewer panels and enlarge the key comparison.

## When not to apply this

Do not let technical export checks replace chart-choice, uncertainty, accessibility, or image-evidence critique.
