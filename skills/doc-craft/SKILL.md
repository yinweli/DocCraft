---
name: doc-craft
description: >
  Use when writing, revising, or restructuring human-facing Markdown documentation:
  READMEs, developer guides, operating instructions, or the readability of design
  documents (撰寫、改寫、整理文件、README、說明、操作手冊、設計文件).
  Not for deciding or approving specifications, code comments, or commit messages.
---

# DocCraft

Write technical documents for human readers first: accurate, complete, concise, and easy to maintain.

## Writing Rules

- Language: when editing an existing document, keep its language. For a new document, follow the project's stated language convention, then the language of its existing documentation; if neither exists, use Traditional Chinese. Preserve established terminology.
- Present the main rule or conclusion first, followed by conditions, exceptions, and follow-up actions.
- Prefer short sentences and focused list items; avoid packing unrelated conditions into one sentence.
- Use paragraphs for explanation, lists for rules, numbered steps for procedures, and tables only when comparisons or field mappings benefit from them.
- Use brief examples when they clarify a rule; examples supplement rather than replace complete requirements.
- Preserve necessary details and relationships. Do not oversimplify, fragment related content, or repeat full specifications merely to make a section self-contained.

## Markdown and Structure

- Put code, commands, identifiers, paths, and filenames in backticks; use fenced blocks for longer examples.
- Prefer meaningful sections in existing documents over redundant files, empty outlines, or extra indexes.
- Reuse existing authoritative material through links or brief summaries instead of maintaining parallel explanations.
- Follow the project's current document names, link syntax, formatting, and generation conventions.
- If a document is generated from another source, edit the source and update the output through the established process; do not directly edit generated output.

## Reading Scope

- Read the target document, the files it directly links to, and any files the user names.
- When the text you are revising states commands, versions, or default values, confirm them in the file that defines them (for example `package.json` or a config file).
- Search the repository for references only when moving or renaming a document, then update those references.

## Workflow

1. **Read:** Identify the intended audience, document purpose, and existing conventions within the reading scope.
2. **Structure:** Choose the simplest readable organization; keep related information together.
3. **Write or revise:** Improve clarity without silently changing requirements, meaning, or established terminology.
4. **Check:** Review completeness, heading hierarchy, examples, and the links you touched.
5. **Report:** Briefly state what changed and list only the checks that actually ran.

## Boundaries

- Do not invent technical facts, decisions, requirements, or missing context.
- If source material is ambiguous or contradictory, flag it; do not resolve specification authority or approve design decisions. That responsibility belongs to the project's specification-management process.
- Do not expand scope, restructure unrelated documents, or modify files when only analysis is requested.
