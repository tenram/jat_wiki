# Anthropic Agent Skills

> Sources: Anthropic, Unknown date
> Raw: [anthropics/skills](../../raw/claude-code-ecosystem/anthropics-skills.md)

## Overview

Anthropic's own reference repository for "Agent Skills": folders containing a `SKILL.md` (YAML frontmatter with `name`/`description`, plus instructions, examples, guidelines) that Claude loads dynamically for specialized tasks, rather than keeping all capability in the base system prompt.

## Structure

`./skills` holds example skills grouped by Creative & Design, Development & Technical, Enterprise & Communication, and Document Skills (PDF/DOCX/PPTX/XLSX). `./spec` defines the Agent Skills specification itself; `./template` provides a starter skill. Installable in Claude Code via `/plugin marketplace add anthropics/skills`, and usable in Claude.ai (paid plans) or the Claude API.

Licensing is split: most example skills are Apache 2.0; the document skills are source-available rather than open source, shared as reference implementations only, with an explicit disclaimer that Claude's actual behavior may differ from the reference code.

This is the canonical spec that third-party skill projects (academic-research-skills, ui-ux-pro-max-skill, article-writing-skills) build on top of.

## See Also

- [Academic Research Skills](academic-research-skills.md)
- [UI UX Pro Max Skill](ui-ux-pro-max-skill.md)
- [article-writing-skills](article-writing-skills.md)
