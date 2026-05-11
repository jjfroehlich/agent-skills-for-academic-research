# Color And Accessibility

Use this for palette choice, colorblind accessibility, grayscale robustness, fluorescence channels, heatmap colors, categorical legends, contrast, and color-as-emphasis decisions.

## Use this when...

- The figure uses color to encode category, magnitude, deviation, channel identity, annotation, or emphasis.
- The user asks whether a palette is accessible, publication-safe, or misleading.
- Color appears decorative, inconsistent across panels, or overloaded with too many meanings.

## The job of this topic

Make color serve meaning without becoming the only way to read the figure.

## Default workflow

1. Identify what color encodes: category, ordered magnitude, deviation from a midpoint, cyclic value, channel, or highlight.
2. Choose palette type from the variable, not aesthetics.
3. Check luminance contrast, grayscale readability, and common color-vision deficiencies.
4. Add redundant encodings such as position, direct labels, shape, line style, order, or annotations where color carries decisions.
5. Keep semantic colors consistent across panels and the manuscript.
6. Inspect the actual figure before making exact palette or contrast claims; without the figure, state the check the user must perform.

## Decision rules

- Sequential palettes fit ordered one-direction magnitude.
- Diverging palettes fit values around a meaningful midpoint such as zero, baseline, or control.
- Categorical palettes fit unordered groups; limit hue count or split into panels when categories grow.
- Cyclic palettes fit wraparound variables.
- Avoid rainbow or jet-style maps for ordered quantitative data.
- Use color for important distinction or emphasis; avoid saturated color on backgrounds, decoration, or secondary marks.
- Do not rely on hue alone for essential interpretation.

## Variants and edge cases

- Heatmaps: pair palette advice with scale, clipping, clustering, missing-value, and legend checks in `specialized-figures.md`.
- Fluorescence overlays: label each channel and biological target; consider single-channel panels plus merge when channel-specific signal matters.
- Posters and talks: projection and distance can weaken contrast, so test the intended medium.
- Print or PDF compression: check grayscale, low-resolution previews, and whether thin colored lines survive.

## Anti-patterns

- Meaning encoded only by red/green, blue/purple, or other hue pairs.
- Diverging color scale for all-positive data with no meaningful midpoint.
- Rainbow maps that create artificial boundaries.
- Saturated colors competing with the main signal.
- Legends far from marks when direct labels would work.

## Diagnostic questions

- What does color mean in this figure?
- What remains understandable in grayscale?
- Which distinction must survive color-vision deficiency?
- Does the palette imply order, midpoint, or categories correctly?
- Are labels close enough that readers do not have to memorize colors?

## Output patterns / mini-templates

```text
Color role: <category/magnitude/deviation/channel/emphasis>.
Palette issue: <problem>.
Fix: <palette type and redundant cue>.
Check: <grayscale/color-vision/final-medium test>.
Do not claim: <exact color/contrast result unless figure was inspected>.
```

## Examples

- `Red/green fluorescence overlay`: use an accessible channel pairing or single-channel panels, and label each channel and target.
- `All-positive heatmap with blue-white-red`: use a sequential palette unless white represents a real baseline.

## When not to apply this

Do not spend the answer on palette style if the primary problem is chart choice, missing uncertainty, or missing image scale.
