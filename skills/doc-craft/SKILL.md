---
name: doc-craft
description: >
  Write, revise, and structure clear technical documentation in Markdown.
  Use when drafting or improving READMEs, developer guides, operating
  instructions, or the readability and organization of design documents.
---

# DocCraft

Write technical documents for human readers first: accurate, complete, concise, and easy to maintain.

## Writing Rules

- Use Traditional Chinese by default; preserve established project terminology and explicitly specified language conventions.
- Present the main rule or conclusion first, followed by conditions, exceptions, and follow-up actions.
- Prefer short sentences and focused list items; avoid packing unrelated conditions into one sentence.
- Use paragraphs for explanation, lists for rules, numbered steps for procedures, and tables only when comparisons or field mappings benefit from them.
- Use brief examples when they clarify a rule; examples supplement rather than replace complete requirements.
- Preserve necessary details and relationships. Do not oversimplify, fragment related content, or repeat full specifications merely to make a section self-contained.

## Markdown and Structure

- Keep heading levels logical without unnecessary jumps.
- Put code, commands, identifiers, paths, and filenames in backticks; use fenced blocks for longer examples.
- Prefer meaningful sections in existing documents over redundant files, empty outlines, or extra indexes.
- Reuse existing authoritative material through links or brief summaries instead of maintaining parallel explanations.
- Follow the project's current document names, link syntax, formatting, and generation conventions.
- When moving or renaming documents, update relevant references.
- If a document is generated from another source, edit the source and update the output through the established process; do not directly edit generated output.

## Workflow

1. **Read:** Identify the intended audience, document purpose, existing conventions, and relevant source material.
2. **Structure:** Choose the simplest readable organization; keep related information together.
3. **Write or revise:** Improve clarity without silently changing requirements, meaning, or established terminology.
4. **Check:** Review completeness, heading hierarchy, examples, links, and affected references. Run applicable existing formatters or linters when available; do not invent commands.
5. **Report:** Briefly state what changed and which checks were actually performed.

## Boundaries

- Do not invent technical facts, decisions, requirements, or missing context.
- If source material is ambiguous or contradictory, flag it; do not resolve specification authority or approve design decisions. That responsibility belongs to the project's specification-management process.
- Do not expand scope, restructure unrelated documents, or modify files when only analysis is requested.
- Never claim a check passed unless it actually ran.
