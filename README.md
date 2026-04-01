# Product Document Drafter

A multi-agent system for turning rough product ideas into structured documents. Built for use with Claude Code.

## What it does

You bring rough notes. The system identifies the right template, asks probing questions, challenges weak reasoning, and helps you write a properly structured product document.

It is not a template filler. It pushes back on vague problem statements, unsupported claims, and solutions in search of a problem.

## Setup

1. Clone this repo and open it in Claude Code
2. Create a `context.md` file in the repo root describing your role, team, product portfolio, and working assumptions. The system reads this before every session.
3. Start a session and describe your initiative. The system will take it from there.

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

Use lowercase-hyphenated slugs.

## Agent team

12 specialist agents live in `.claude/agents/`. Invoke them by name when you need them.

| Agent | Role | Output |
| --- | --- | --- |
| `critic` | Reviews completed documents for quality and rigour | Critique notes |
| `sr-principal-pm` | Senior strategic counsel - challenges direction, stress-tests prioritisation | Strategic counsel |
| `user-researcher` | Research plans, interview guides, desk research | Deliverable |
| `competitive-analyst` | Competitor landscape reports and feature benchmarks | Deliverable |
| `data-analyst` | Measurement frameworks, metric definitions, instrumentation requirements | Deliverable |
| `technical-pm` | Dependency maps, engineering questions, complexity assessments | Deliverable |
| `subscriptions-strategist` | Reviews for funnel logic, LTV, pricing, and subscription impact | Critique notes |
| `ux-advocate` | Reviews for usability, friction, accessibility risks | Critique notes |
| `legal-privacy-reviewer` | Reviews for GDPR, CCPA, data handling, compliance risks | Critique notes |
| `stakeholder-comms` | Takes approved PRDs and produces stakeholder summaries and briefings | Deliverable |
| `prototype-brief` | Produces a structured prompt for Lovable, v0, or similar AI prototyping tools | Prototype brief |
| `test-plan` | Produces a rigorous A/B test plan with hypothesis, metrics, sample size, and guardrails | Deliverable |

## Other files

- `templates/` - all document templates live here
- `md_to_docx.py` - converts markdown files to .docx with consistent formatting (Arial, black text, 1.15 line height, no bookmarks)

## Docx generation

Each initiative can have a thin `generate_docx.py` wrapper:

```python
from md_to_docx import convert
convert("initiative-slug/initiative-slug-1pager.md", "initiative-slug/initiative-slug-1pager.docx")
```

Run with `python3 [initiative]/generate_docx.py`.
