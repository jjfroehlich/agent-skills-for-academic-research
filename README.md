<p align="center">
  <img src="./images/agent-skills-for-scientific-work_banner.jpg" width="900" alt="Title banner" />
</p>

# Agent Skills for Academic Research

Experimental, agent skills for academic research workflows. These skills are meant to improve AI agents by giving topic-specific guidance. Completely experimental and untested. Please get in contact if you have feedback.

## Skills

| Skill | Use it for |
| --- | --- |
| `career-development` | Advisor and lab choice, PhD/postdoc applications, faculty searches, CVs, cover letters, interviews, negotiation, and career transitions. |
| `data-visualization-and-figures` | Scientific plots, tables, heatmaps, microscopy panels, multi-panel figures, graphical abstracts, color, layout, typography, and publication readiness. |
| `grant-writing` | Grant and fellowship planning, specific aims, significance/innovation/approach sections, feasibility, risk plans, budgets, and reviewer-facing narratives. |
| `literature-reading-and-synthesis` | Active paper reading, claim extraction, figure unpacking, literature tracking, and synthesis matrices. |
| `mentoring-management-and-lab-culture` | Mentoring, lab handbooks, onboarding, PI leadership systems, lab culture, IDPs, feedback scripts, and conflict diagnosis. |
| `publishing-and-peer-review` | Journal submissions, cover letters, editor inquiries, peer-review reports, reviewer ethics, resubmission plans, and response-to-reviewers letters. |
| `research-strategy-and-project-design` | Choosing research problems, triaging project ideas, generating hypotheses, comparing experiment strategies, and setting risk or kill criteria. |
| `scientific-communication` | Talks, slide decks, posters, chalk talks, elevator pitches, research stories, audience explanations, and Q&A plans. |
| `scientific-feedback` | Orchestrated feedback across manuscripts, figures, slides, posters, grants, research plans, paper notes, mentoring documents, and lab artifacts. |
| `scientific-writing` | Manuscripts, thesis sections, abstracts, introductions, results, discussions, figure legends, section flow, claim calibration, and publication-ready prose. |

## How to Install

Give your agent the repository link and tell it to install it. For example `Please install the skills at https://github.com/jjfroehlich/agent-skills-for-academic-research`. Alternatively, copy one or more folders from `skills/` into your agent's skill directory. Skills are portable across different agent systems.

## How to Use 

The skills should be triggered automatically in the right conditions. 
Just ask for advice on anything that is related to the above topics.

## Limitations
- These skills are experimental and I am unsure if they are useful, useless or even harmful. 
- Skills were built in a private workbench based on public resources and private notes.
- Do not replace expert scientific, statistical, legal, medical, safety, or funding-agency review.

## Repository Layout

Each skill is a self-contained folder with a `SKILL.md` entry point plus supporting references, checklists, and examples. 

```text
skills/
  <skill-name>/
    SKILL.md
    references/
    checklists/
    examples/
```

`SKILL.md` defines when the skill should trigger, how the agent should work, which reference files to open, and what output formats to use. Reference files are playbooks. Checklists and examples support common review, drafting, planning, and critique tasks.

## License

MIT. See [LICENSE](./LICENSE).
