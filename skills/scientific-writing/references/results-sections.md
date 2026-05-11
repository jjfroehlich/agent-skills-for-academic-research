# Results Sections

Use this when the user is revising results text, figure callouts, finding-first paragraphs, subsection order, or text that drifts into discussion.

## The job of this topic

Results sections present what was found and how the evidence supports it. They should orient the reader to the question, state the finding, provide necessary evidence, and reserve broad interpretation for the discussion.

## Default workflow

1. Identify the result, hypothesis, prediction, or figure each paragraph is supposed to convey.
2. Put the finding or question near the paragraph opening.
3. Name the comparison, direction, magnitude or qualitative pattern, system, evidence type, sample or replicate context, and figure/table location when available.
4. Build each result unit as question or prediction, minimal approach, result, detail or robustness, and local conclusion.
5. Include only methodological detail needed to interpret the result; leave reproducibility detail in Methods.
6. Report null or negative results when they test the question, but do not make them the main emphasis unless they are the paper's point.
7. Remove broad implications, speculation, limitations, or future work unless used as brief local signposting.
8. Check that figure references appear near the relevant claim and in a useful order.

## Decision rules

- If the paragraph starts with method chronology, revise toward finding-first structure.
- If the result is vague, add direction, comparator, effect size, sample context, or qualitative pattern from the supplied material.
- If the paragraph interprets why the finding matters, move that reasoning to the discussion or shorten it to a transition.
- If a figure is cited without explaining what panel supports, add panel-specific orientation.
- If multiple results compete in one paragraph, split by finding or combine under a stronger topic sentence.
- If a result paragraph begins with method chronology, recover the tested question and move method detail after that orientation.
- If a statistical result lacks direction or comparator, add the missing comparison from the supplied material or flag it as needed.
- If the paragraph contains only technique names, recover the tested question and the finding each technique supports.
- If the paragraph cites a figure before telling the reader what to look for, add a finding or orientation phrase before the citation.
- If a result was expected from a hypothesis or prediction, show that link explicitly before reporting the evidence.
- If a paragraph contains values without a takeaway, add a local conclusion that does not drift into broad discussion.

## Variants and edge cases

- Exploratory results can be presented as patterns without causal language.
- Negative or null results still need the tested comparison and interpretation boundary.
- Complex multi-panel figures may need a short orientation sentence before the finding.
- Methods-heavy results should keep reproducibility detail in methods and use results text for what the method showed.

## Anti-patterns

- "We next performed..." repeated as the main paragraph structure.
- Hiding the finding after a long method setup.
- Reporting only statistical significance without biological direction or meaning.
- Using causal verbs when the design supports association only.
- Discussing limitations in every result paragraph instead of reserving them for synthesis.

## Diagnostic questions

- What is the finding in this paragraph?
- What question, hypothesis, or prediction does it answer?
- What comparison or condition produced it?
- Which figure, table, or evidence supports it?
- Are direction, magnitude or pattern, uncertainty, and sample context clear enough from the supplied material?
- Does the paragraph state enough detail to understand the result without overloading the reader?
- Which sentences belong in the discussion instead?

## Output patterns / mini-templates

- Results paragraph: `To test/ask [question], we [minimal method]. [Finding] was [direction/pattern] in [condition]. This pattern was supported by [evidence/figure], indicating [local interpretation only if needed].`
- Hypothesis-linked result: `If [hypothesis], we expected [prediction]. In [comparison], [result direction/pattern] was observed ([evidence/figure]), supporting/refining/not supporting [local claim].`
- Results edit note: `Move [broad implication] to Discussion; keep [finding + evidence] in Results.`
- Figure-linked unit: `[Finding]. In Fig. [panel], [visual/evidence type] shows [comparison or pattern]. [Robustness/control/detail] supports [local conclusion].`
- Null-result unit: `We tested whether [question]. [Comparison] did not show [expected change] under [conditions], indicating that [bounded conclusion] rather than [unsupported stronger claim].`
- Numeric-support prompt: `Add direction, comparator, estimate or magnitude, uncertainty/statistical support, and figure/table reference if supplied.`

## Examples

Before: `We performed imaging and then quantified marker expression.`

After: `Marker expression increased after treatment, with the largest change in the late-stage cells shown in Fig. 2B.`

Before: `RNA-seq was performed, and several genes were differentially expressed. Pathway analysis was then conducted.`

After: `Treatment shifted the transcriptional response toward inflammatory signaling. Differential expression analysis identified increased cytokine-response genes in treated samples, and pathway enrichment concentrated these changes in interferon-associated programs.`

## When not to apply this

Do not use results guidance to write the broader conclusion, limitations, or field implications; route those to `discussions.md`.
