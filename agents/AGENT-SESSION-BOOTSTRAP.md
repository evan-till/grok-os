# Agent Session Bootstrap

## Goal
Use this file at the start of a new session to immediately activate the node model in this codebase.

## Quick Start
1. Read agents/AGENT-ROUTING-MATRIX.md.
2. Select the primary node based on the task type.
3. Read that node's markdown file.
4. Run baseline validation before edits.
5. Make focused edits in owned surfaces first.

## Baseline Validation Commands
- pnpm -r test
- pnpm -r build
- Search for runtime errors in docs/js and docs/index.html when touching frontend behavior.

## Frontend Runtime Smoke Checklist
1. Open docs/index.html.
2. Verify window controls work: close, minimize, maximize, drag.
3. Verify terminal opens and accepts input.
4. Verify artifact commands: artifacts, collect, checkpoints.
5. Verify no dead-end states requiring forced refresh.

## Session Constraints
- Preserve multi-instance framing as real operation.
- Keep contradictory evidence intentional and traceable.
- Do not remove collectible progression hooks unless replacing them.

## Deliverable Minimum
- Files changed list.
- What behavior changed.
- Risks and regression areas.
- Suggested next node to continue work.
