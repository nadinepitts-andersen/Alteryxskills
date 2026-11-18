# Alteryx Designer Help

A Claude Code plugin that answers how-to questions about Alteryx Designer and helps troubleshoot errors. It does not build or run workflows; use the `alteryx` plugin's `alteryx-designer` skill for that.

## Contents

| Path | Purpose |
|------|---------|
| `.claude-plugin/plugin.json` | Plugin manifest |
| `skills/alteryx-designer-help/SKILL.md` | Guidance for how-to answers and error troubleshooting |
| `commands/alteryx-help.md` | `/alteryx-help <question>` |
| `commands/alteryx-troubleshoot.md` | `/alteryx-troubleshoot <error or symptom>` |

## Usage

```text
/alteryx-help which tool joins two tables on a key that has different names?
/alteryx-troubleshoot Error: Field 'Amount' not found in Select tool
```
