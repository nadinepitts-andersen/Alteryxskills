---
name: alteryx-designer-help
description: Answer questions about using Alteryx Designer, including how a tool works, which tool fits a task, what a setting does, and why a workflow or run failed. Use for how-to questions, tool explanations, configuration guidance, and error troubleshooting. Do not use to build, edit, or run workflows; that belongs to the alteryx-designer skill.
---

# Alteryx Designer Help

Use this skill to explain Alteryx Designer and help the user get unstuck. Answer from what the user shows you: the error text, the tool configuration, the workflow description, or the Designer version. Do not guess at settings you have not seen.

## Answering a How-To Question

1. Restate the goal in one sentence so the user can correct a misreading.
2. Name the tool or setting that fits, and say why it fits.
3. Give the steps in Designer order: which tool to drag in, which fields to set, and what the output should look like.
4. Note one common mistake for that tool.

## Troubleshooting an Error

1. Ask for the exact error message, the tool it points to, and the Designer version if it is not known. Do not start from a generic cause.
2. Explain what the message means in plain language.
3. List likely causes in order of how often they occur, and say how to check each one.
4. Suggest the smallest change to try first. Do not recommend rewriting the workflow unless the smaller checks fail.

## Boundaries

- If the user asks you to change, build, or run a workflow, switch to the `alteryx-designer` skill.
- If the user asks about finding existing workflows or data sources, use `alteryx-asset-discovery`.
- If you are not sure which Designer version or setting applies, say so and ask. Do not present an uncertain answer as fact.
