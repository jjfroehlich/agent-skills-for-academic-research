# Artifact Routing

Use this when a feedback request could involve more than one specialist lens or when the artifact type is ambiguous.

## Use this when...

- The user says "review this," "critique this," "sanity-check this," or "give feedback" without naming the exact kind of feedback.
- The artifact combines writing, figures, presentation, publication, funding, strategy, literature, or lab-management concerns.
- You need to decide whether to use this orchestrator or hand off to one narrower domain lens.

## The job of this topic

Route the artifact to the fewest domain lenses that explain the main feedback risks, then integrate those lenses into one revision path.

## Default workflow

1. Identify the artifact: manuscript, figure, slide deck, poster, grant, proposal, paper note, research plan, lab document, or mixed package.
2. Identify the destination: journal, funder, talk, committee, lab meeting, collaborator, mentor, trainee, public audience, or internal decision.
3. Select primary and secondary lenses; do not apply every lens just because it is available.
4. State the chosen lenses in the response before detailed critique.
5. Produce one integrated priority list rather than separate disconnected reviews.

## Decision rules

- Manuscript or thesis prose: apply the scientific-writing lens first; add figure, publishing, or strategy lenses only if the artifact needs them.
- Slides, talks, posters, and pitches: apply the scientific-communication lens first; add figure and writing lenses for visuals or wording.
- Plots, tables, microscopy, graphical abstracts, or figure packages: apply the data-visualization-and-figures lens first.
- Submission packages, peer-review reports, editorial decisions, and response letters: apply the publishing-and-peer-review lens.
- Grants, fellowships, specific aims, and funding narratives: apply the grant-writing lens.
- Paper notes, journal-club prep, synthesis matrices, and reading workflows: apply the literature-reading-and-synthesis lens.
- Project ideas, research plans, hypotheses, stop/go decisions, and decisive tests: apply the research-strategy-and-project-design lens.
- Lab handbooks, mentoring compacts, feedback scripts, IDPs, conflict notes, and culture documents: apply the mentoring-management-and-lab-culture lens.

## Variants and edge cases

- A manuscript with figures needs writing plus figure lenses, but publication-process advice only if submission or review is part of the ask.
- A grant with aims, figures, and feasibility needs grant-writing as primary, with writing, figures, and research-strategy as secondary lenses.
- A poster needs scientific-communication as primary; use data visualization only for figure readability or evidence display.
- A trainee feedback script about a manuscript may need mentoring-management for the relationship and scientific-writing for the artifact.

## Anti-patterns

- Applying all lenses and overwhelming the user.
- Treating a mixed artifact as a single-domain task when the main risk crosses domains.
- Routing based on file type only, ignoring audience and destination.
- Claiming that another skill was called when you only applied its lens manually.

## Diagnostic questions

- What is the artifact and where is it going?
- What kind of feedback did the user ask for: content, structure, strategy, visual design, readiness, tone, or process?
- Which issue would make the artifact fail if left unfixed?
- Which specialist lens would change the top priority?
- Is a narrower domain skill sufficient?

## Output patterns / mini-templates

```text
Scope: <artifact, audience, destination>.
Selected lenses: <primary lens>, <secondary lens if needed>.
Why these lenses: <one-line routing rationale>.
Priority order: <blocking issue -> major revision -> secondary polish>.
```

## Examples

- "Review my results section and Figure 3" -> scientific-writing plus data-visualization-and-figures.
- "Is my specific aims page compelling?" -> grant-writing plus scientific-writing.
- "Critique this poster before the conference" -> scientific-communication plus data-visualization-and-figures.

## When not to apply this

Do not use the orchestrator when the user asks a narrow, single-domain task and the correct domain skill is obvious.
