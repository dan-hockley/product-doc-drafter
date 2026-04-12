# Product Document Drafter

A multi-agent product management tool that turns rough ideas into strategically sound, solution focussed structured documents. Start chatting with Claude and it will help you break down a problem, explore solutions and eventually build out sharable documentation. 

Built for use with [Claude Code](https://claude.ai/code).

## Why this exists

Most AI writing tools will happily draft a PRD from a vague brief. This one won't. It pushes back.

**It challenges you as you go.** Every unsupported claim, missing baseline, and vague "we believe" gets called out. If you say "users want X" without data, it will ask what signal you have. If your problem statement is actually a solution in disguise, it will tell you. The conversation is the work: by the time you have a draft, you've pressure-tested your thinking.

**It knows your company.** Add your team's context once (products, strategy, competitors, tech stack, terminology) and the drafter uses it in every session. It asks better questions because it already knows what you're working with. No re-explaining your org every time.

**It gives you a team, not just a chatbot.** 14 specialist agents are available on demand: a critic to tear your doc apart, a strategist to challenge your priorities, a researcher to plan discovery, an architect to scope the build, a designer to check feasibility. Each one brings a distinct perspective.

**It scales with the initiative.** Start with a quick 1-Pager to get alignment. Expand to a full PRD as discovery progresses. Add an A/B test plan when you're ready to experiment. The system guides the progression.

**It produces real documents.** Not chat responses. Structured markdown files in a project folder, ready to share. Export to formatted Word docs for stakeholders who don't live in repos.

## How it works

1. You describe your initiative or drop in rough notes
2. The drafter asks questions, one at a time, challenging your thinking as you go
3. When the problem and solution are well-defined, it drafts the document
4. You review, iterate, and approve
5. Call in specialist agents for deeper analysis: competitive research, technical scoping, measurement frameworks, design feasibility

## Setup

1. Clone this repo and open it in Claude Code
2. Open `context.md` and follow the guide to add your company context. You can use Claude to build it from existing docs.
3. Start a session and describe your initiative

## Templates

| Template | When to use |
| --- | --- |
| 1-Pager | Default starting point for new initiatives |
| PRD | When the initiative is ready to expand beyond the 1-Pager |
| A/B Test Plan | When you need to design an experiment |
| Stakeholder Questions | When open questions need to be captured as a takeaway |

## Agent team

14 specialist agents live in `.claude/agents/`. Invoke them by name when you need them.

| Agent | Role | Output |
| --- | --- | --- |
| `critic` | Reviews completed documents for quality and rigour | Critique notes |
| `sr-principal-pm` | Senior strategic counsel - challenges direction, stress-tests prioritisation | Strategic counsel |
| `user-researcher` | Research plans, interview guides, desk research | Deliverable |
| `competitive-analyst` | Competitor landscape reports and feature benchmarks | Deliverable |
| `data-analyst` | Measurement frameworks, metric definitions, instrumentation requirements | Deliverable |
| `technical-pm` | Dependency maps, engineering questions, complexity assessments | Deliverable |
| `engineer-architect` | System architecture, stack choices, data models, infrastructure patterns | Deliverable |
| `product-designer` | Design feasibility, component coverage, design briefs, design direction | Both |
| `subscriptions-strategist` | Reviews for funnel logic, LTV, pricing, and subscription impact | Critique notes |
| `ux-advocate` | Reviews for usability, friction, accessibility risks | Critique notes |
| `legal-privacy-reviewer` | Reviews for GDPR, CCPA, data handling, compliance risks | Critique notes |
| `stakeholder-comms` | Takes approved PRDs and produces stakeholder summaries and briefings | Deliverable |
| `prototype-brief` | Produces a structured prompt for Lovable, v0, or similar AI prototyping tools | Prototype brief |
| `test-plan` | Produces a rigorous A/B test plan with hypothesis, metrics, sample size, and guardrails | Deliverable |

## File structure

Each initiative gets its own subfolder inside `projects/`:

```
projects/
  [initiative-slug]/
    [initiative-slug]-1pager.md
    [initiative-slug]-prd.md
    competitive-analysis.md
    source-docs/
    prototype/
      index.html
```

## Docx export

`md_to_docx.py` converts markdown to formatted Word docs (Arial, black text, 1.15 line height, no bookmarks). Each initiative can have a thin wrapper:

```python
from md_to_docx import convert
convert("initiative-slug/initiative-slug-1pager.md", "initiative-slug/initiative-slug-1pager.docx")
```
