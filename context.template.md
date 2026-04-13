# Product Context

This file is where your company and team context lives. The drafter reads it at the start of every session and uses it to inform every document it helps you write.

Without context, the drafter works as a generic PM tool. With context, it becomes grounded in your reality: your products, your team, your strategy, your terminology, and your competitive landscape.

## The fastest way to build your context

You do not need to write this from scratch. Use Claude to build it for you:

1. Gather existing docs: strategy decks, org charts, product briefs, OKR docs, architecture diagrams, glossaries, onboarding materials
2. Drop them into this repo (or paste them into the conversation)
3. Ask Claude to read them and organize the information into the context skeleton below

Claude will extract the substance, strip the jargon, and file everything into the right sections. You review, correct, and fill gaps. This turns hours of writing into a conversation.

## What makes good context

**Write for durability.** Context should be factual information that stays true for months, not weeks. Company overview, product descriptions, team structure, strategic direction, competitive landscape, technology stack. Avoid status updates, sprint goals, or anything that will be stale next quarter. The more stable the information, the less maintenance this file needs.

**Write at a PM level of detail.** The drafter needs enough context to write informed product documents, challenge assumptions, and ask the right questions. That means: what the products are and who they serve, how the business model works, who the competitors are, what the team's priorities are, and what technology constraints exist. It does not mean architecture diagrams, database schemas, or line-level code details. Think about what a new PM would need in their first week to start contributing.

**Partial context is better than no context.** Start with whatever you have. A company overview and product list is enough to get value. Add depth over time as gaps surface during document drafting sessions.

## How to add your context

You have two options:

### Option 1: Write directly in context.md

Copy this template to `context.md` (if it doesn't already exist) and replace this guide with your own context. Write in plain markdown. Cover the topics listed in the skeleton below, in whatever depth you have. You can always add more later.

### Option 2: Create a separate context repo (recommended for teams)

If multiple people or tools share the same context, maintain it in a separate repo and compile it into this file. This keeps the source modular and version-controlled.

**How the compile approach works:**

1. Create a repo with organized markdown files (see the folder structure below)
2. Write a Python script that crawls all `.md` files and concatenates them into a single file
3. Use the `## FILE:{relative_path}` convention as a header for each file section
4. Copy the compiled output into `context.md` using the `/sync-context` command

**Recommended folder structure:**

```
your-context/
  company/           Company overview, mission, strategy, glossary
  products/          Per-product context: what it is, who it serves, key metrics
  teams/             Org structure, team members, ways of working
  goals/             OKRs, quarterly priorities, fiscal year structure
  tech/              Stack, platforms, integrations, experimentation tools
  process/           How work gets done, development stages, templates
  style/             Writing guidelines, design system, brand voice
  scripts/
    compile-context.py
```

**Compile script pattern:**

The compile script should:
- Crawl folders in priority order (company first, then strategy, products, teams, tech, process, style)
- Strip redundant whitespace and "last updated" lines
- Prefix each file with `## FILE:{relative_path}`
- Add a header with compilation date and file count

## Context skeleton

If you are writing directly in this file, use this skeleton as a starting point. Replace each prompt with your own content. Delete any sections that do not apply.

```markdown
# [Company Name] - Context

## Company overview
[What does the company do? What is the business model? Who are the customers?]

## Strategy
[What is the current strategic direction? What are the top priorities?]

## Glossary
[Internal terminology, acronyms, and tool names that the drafter should know.]

## Products
[For each product: what is it, who uses it, what are the key surfaces and metrics?]

## Team
[Who is on the product team? What are the key roles and responsibilities?
What cross-functional partners does the team work with?]

## Goals
[Current OKRs or priorities. Fiscal year structure if non-standard.]

## Technology
[Key platforms, tools, and infrastructure. What does the team build on?
What experimentation and analytics tools are in use?]

## Competitive landscape
[Who are the primary competitors? What is the company's positioning?
What are the key competitive dynamics?]

## Design system
[What design system is in use? What are the key components and conventions?]

## Brand guidelines
[Primary colors, typography, tone of voice for each product.]
```

## Context modes

The drafter supports two context modes, controlled by the `.context-mode` file in the repo root:

- **`compiled`** (default): reads `context.md`
- **`internal`**: reads all files directly from your context source directory

Use `/switch-context` to toggle between modes. Use `/sync-context` to update `context.md` from your context source.

When using `internal` mode, update the path in `.claude/commands/switch-context.md` to point to your context source directory.
