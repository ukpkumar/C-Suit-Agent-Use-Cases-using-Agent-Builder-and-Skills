# 4) How to Create Skills

A skill is a reusable package that makes outputs consistent.

## Skill package basics

- Use a folder with required `SKILL.md`.
- Include YAML front matter:
  - `name`
  - `description`
- Add task instructions below front matter.
- Optional: resource files and scripts.
- Zip the full folder and upload in Agent Builder.

## Two creation paths

1. **Describe tab generation**
   - Paste a skill prompt.
   - Review and refine on Configure tab.
2. **Upload zip**
   - Build skill locally.
   - Zip folder (max 50 MB).
   - Upload via **Skills > Add**.

## Example `SKILL.md`

```md
---
name: board-paper-summary
description: Turns a board paper into a one-page summary with decision, options, impact, risks, recommendation, and clarifications.
---
# Board paper summary
1. Identify title, sponsor, and decision type.
2. Extract options and recommendation.
3. Quote financial figures exactly with citations.
4. List key risks and mitigations.
5. List points to clarify.
6. Keep one-page format.
7. If missing, state "not stated in the pack".
```

Back to [Index](INDEX.md)
