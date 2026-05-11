# Section Rewrite Examples

These examples show rewrite patterns without source provenance or bibliographic detail.

## Abstract Opening

Before: `Cancer progression involves many transcriptional changes, and several studies have examined this process.`

After: `Which transcriptional changes precede metastatic transition remains unclear because most studies profile tumors after dissemination.`

Why it works: the rewrite replaces generic field background with a specific unresolved problem.

Pattern: `Generic field fact -> specific unresolved problem + reason prior work is insufficient.`

## Results Paragraph

Before: `We performed RNA-seq and found many genes changed. We then looked at pathway enrichment.`

After: `Treatment shifted the expression program toward inflammatory signaling, with the strongest increases in cytokine-response genes. Pathway analysis showed that this pattern was concentrated in the treated samples rather than the controls.`

Why it works: the rewrite states the finding first, then gives the evidence type.

Pattern: `Method chronology -> finding + comparison + evidence.`

## Methods Abstract

Before: `We developed a tool for image analysis and tested it on several datasets.`

After: `Segmenting densely packed cells remains difficult in low-contrast microscopy images. We developed CellMark, an image-analysis method that separates touching cells by combining boundary prediction with intensity-aware watershed refinement. Across three benchmark datasets, CellMark improved instance recovery while preserving cell-size estimates.`

Why it works: the rewrite names the unmet need, method, primary innovation, validation, and capability.

Pattern: `Tool exists -> unmet need + method name + innovation + validation + user value.`

## Introduction Gap

Before: `Many researchers have studied immune aging, but more work is needed.`

After: `Although immune aging has been linked to chronic inflammation, it remains unclear which early transcriptional changes precede the loss of vaccine responsiveness in older adults.`

Why it works: the rewrite replaces a generic gap with what is known, what remains unknown, and the consequence.

## Discussion Overclaim

Before: `These findings prove that this pathway controls disease progression and will transform treatment.`

After: `These findings support a role for this pathway in the model system tested here and motivate direct perturbation studies to determine whether it contributes to disease progression in vivo.`

Why it works: the rewrite preserves importance while restoring evidence boundaries.

Pattern: `Proof/transform language -> supported role + tested context + next evidence needed.`

## Figure Legend

Before: `Figure 3. Quantification of cells.`

After: `Figure 3. Treatment increases marker-positive cells. (A) Representative images of control and treated samples. (B) Quantification of marker-positive cells across the indicated conditions.`

Why it works: the rewrite names the comparison and maps the panels.

## Acknowledgement

Before: `We thank Sam for helping with everything.`

After: `We thank Sam for advice on experimental design and comments on an earlier manuscript draft.`

Why it works: the rewrite names concrete support without implying authorship eligibility.

## Sentence Base Clause

Before: `The implementation of the comparison of the normalized expression measurements across the treatment groups was performed to determine pathway activity differences.`

After: `We compared normalized expression across treatment groups to estimate pathway activity differences.`

Why it works: the rewrite recovers the actor and action, removes noun stacking, and preserves the scientific comparison.

Pattern: `Nominalization stack -> actor + verb + object + purpose.`

## Limitation Boundary

Before: `A limitation is that we only used one cohort, so the findings need more study.`

After: `Because the analysis used one cohort, the results support the association in this sampling frame but do not establish whether the same pattern generalizes across populations.`

Why it works: the rewrite turns a vague apology into a boundary on interpretation.

Pattern: `Weakness list -> design boundary + supported claim + unsupported stronger claim.`

## Reader-Logic Reorder

Before: `We collected samples, performed sequencing, filtered the data, and compared treated and untreated cells.`

After: `To test whether treatment changed cell-state composition, we compared single-cell profiles from treated and untreated samples after quality filtering. Treated samples showed an expanded inflammatory population, which motivated a focused analysis of cytokine-response genes.`

Why it works: the rewrite presents the question and finding rather than the order of work.

Pattern: `Work chronology -> question + minimal method + finding + next reason.`

## Hypothesis-Linked Result

Before: `We measured migration in the mutant cells and then compared the images.`

After: `If the pathway promotes migration, mutant cells should move less efficiently than controls. Consistent with this prediction, mutant cells covered a smaller area during the imaging interval, supporting a local role for the pathway in migration under these assay conditions.`

Why it works: the rewrite connects hypothesis, prediction, comparison, result, and evidence boundary.

Pattern: `Hypothesis -> prediction -> comparison -> result -> bounded local conclusion.`

## Thesis Conclusion

Before: `In conclusion, this thesis found several results and more work is needed.`

After: `Together, the three chapters show that early regulatory changes precede stable cell-state commitment in this model. The thesis contributes a staged view of this transition, while leaving open whether the same sequence occurs in primary tissue.`

Why it works: the rewrite synthesizes across chapters, states the contribution, and marks the evidence boundary.

Pattern: `Result list -> thesis-level answer + contribution + boundary.`

## Contribution Statement

Before: `A.B. helped with the project and C.D. supervised everything.`

After: `A.B. performed the image analysis and reviewed the manuscript. C.D. supervised the project and edited the manuscript.`

Why it works: the rewrite documents concrete roles instead of vague status.

Pattern: `Vague help/status -> concrete contribution verbs.`
