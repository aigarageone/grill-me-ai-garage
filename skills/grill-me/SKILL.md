---
name: grill-me
description: Stress-test a plan, decision, or idea, or interview the user for a personal portrait.
disable-model-invocation: true
---

Choose the skill based on what the user wants to discuss.

- Use [grilling](../grilling/SKILL.md) to stress-test a plan, decision, or idea.
- Use [grill-me-portrait](../grill-me-portrait/SKILL.md) for a personal portrait covering work, income sources, goals, and blockers. Use this for explicit portrait requests and standalone requests such as «прожар мене».

Use the current conversation to resolve an unspecified subject. If the subject is still unclear, ask which interview the user wants.

Call the Skill tool with the selected skill's name when available. If the agent has no Skill tool, read and follow the linked `SKILL.md` relative to this file. If the selected skill is missing, tell the user which skill to install.
