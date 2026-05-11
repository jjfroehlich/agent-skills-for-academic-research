# Agent Skills for Scientific Work

This repository contains reusable agent skills for scientific work, with an emphasis on life-science research workflows. Each skill is a self-contained folder with a `SKILL.md` entry point plus supporting references, checklists, and examples.

The skills are exported from a private workbench after provenance sanitization. Public skill files do not include private source notes, bibliographies, citation maps, raw source URLs, or workbench-only resource metadata.

## Skills

| Skill | Use it for |
| --- | --- |
| `career-development` | Advisor and lab choice, PhD/postdoc applications, faculty searches, CVs, cover letters, interviews, negotiation, and career transitions. |
| `data-visualization-and-figures` | Scientific plots, tables, heatmaps, microscopy panels, multi-panel figures, graphical abstracts, legends, color, layout, typography, and publication readiness. |
| `grant-writing` | Grant and fellowship planning, specific aims, significance/innovation/approach sections, feasibility, risk plans, budgets, and reviewer-facing narratives. |
| `literature-reading-and-synthesis` | Active paper reading, claim extraction, figure unpacking, literature tracking, and synthesis matrices. |
| `mentoring-management-and-lab-culture` | Mentoring, lab handbooks, onboarding, PI leadership systems, lab culture, IDPs, feedback scripts, and conflict diagnosis. |
| `publishing-and-peer-review` | Journal submissions, cover letters, editor inquiries, peer-review reports, reviewer ethics, resubmission plans, and response-to-reviewers letters. |
| `research-strategy-and-project-design` | Choosing research problems, triaging project ideas, generating hypotheses, comparing experiment strategies, and setting risk or kill criteria. |
| `scientific-communication` | Talks, slide decks, posters, chalk talks, elevator pitches, research stories, audience explanations, and Q&A plans. |
| `scientific-feedback` | Orchestrated feedback across manuscripts, figures, slides, posters, grants, research plans, paper notes, mentoring documents, and lab artifacts. |
| `scientific-writing` | Manuscripts, thesis sections, abstracts, introductions, results, discussions, figure legends, section flow, claim calibration, and publication-ready prose. |

## Repository Layout

```text
skills/
  <skill-name>/
    SKILL.md
    references/
    checklists/
    examples/
```

`SKILL.md` is the entry point. It defines when the skill should trigger, how the agent should work, which reference files to open, and what output formats to use. Reference files are playbooks. Checklists and examples support common review and drafting tasks.

## Use

Copy one or more folders from `skills/` into your agent's skill directory, or point your agent runtime at this repository if it supports loading skills from a local folder.

For Codex-style skill loading, each skill folder can be installed independently. The folder name and the `name` field in `SKILL.md` are lowercase kebab-case and should stay unchanged.

## Notes

- These skills provide workflow guidance, review structure, and writing or design heuristics. They do not replace expert scientific, statistical, legal, medical, safety, or funding-agency review.
- For data visualization, inspect the actual figure before making exact layout, palette, microscopy/image-quality, or graphical-abstract composition claims.
- For publishing, grants, and journal formatting, check current venue or funder instructions before relying on any technical requirement.

## License

No license has been declared yet.
