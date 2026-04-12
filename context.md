# Product Context

This file is where your company and team context lives. The drafter reads it at the start of every session and uses it to inform every document it helps you write.

Without context, the drafter works as a generic PM tool. With context, it becomes grounded in your reality: your products, your team, your strategy, your terminology, and your competitive landscape.

## How to add your context

You have two options:

### Option 1: Write directly in this file

Replace this guide with your own context. Write in plain markdown. Cover the topics listed in the skeleton below, in whatever depth you have. Partial context is better than no context. You can always add more later.

### Option 2: Create a separate context repo (recommended for teams)

If multiple people or tools share the same context, maintain it in a separate repo and compile it into this file. This keeps the source modular and version-controlled.

**How the compile approach works:**

1. Create a repo with organized markdown files (see the folder structure below)
2. Write a Python script that crawls all `.md` files and concatenates them into a single file
3. Use the `## FILE:{relative_path}` convention as a header for each file section
4. Copy the compiled output into this file using the `/sync-context` command

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

- **`compiled`** (default): reads this file
- **`internal`**: reads all files directly from your context source directory

Use `/switch-context` to toggle between modes. Use `/sync-context` to update this file from your context source.

When using `internal` mode, update the path in `.claude/commands/switch-context.md` to point to your context source directory.
