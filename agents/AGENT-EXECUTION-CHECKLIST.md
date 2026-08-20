# Agent Execution Checklist

## Before Editing
1. Confirm task owner node from AGENT-ROUTING-MATRIX.md.
2. Read that node markdown.
3. Run baseline checks relevant to touched files.

## During Editing
1. Keep changes inside owned surfaces first.
2. If crossing boundaries, note the dependency reason.
3. Preserve compatibility with existing script/module load order.

## After Editing
1. Re-run validations relevant to the change.
2. Smoke test interactive paths when touching desktop runtime.
3. Update lore guide or README when changing canon-facing behavior.

## Terminal Progression Guardrails
- New commands must not break existing commands.
- Artifact unlock conditions must be explicit.
- Checkpoint IDs should remain stable once published.

## Completion Gate
- No compile/runtime errors in touched files.
- Handoff written using AGENT-HANDOFF-TEMPLATE.md.
- Next node recommendation included.
