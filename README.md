# AI Skills

Agent skills by [leonmarq](https://github.com/leonmarq), installable with the [`skills` CLI](https://skills.sh/docs/cli).

## Install

```bash
# Choose from all skills
npx skills add leonmarq/ai-skills

# Install one skill for all your projects
npx skills add leonmarq/ai-skills --skill pilot -g
```

## Skills

| Skill | What it does |
| --- | --- |
| [`pilot`](skills/pilot/SKILL.md) | Builds one variant end to end and checks in before building the rest. For tasks that span several file formats, providers or integrations. |

## Add a skill

Create `skills/<name>/SKILL.md`, with `name` matching the folder:

```markdown
---
name: my-skill
description: Do X for Y projects. Use when the user asks about X or mentions Y.
---

Instructions go here.
```

Check that it is found:

```bash
npx skills add . --list
```
