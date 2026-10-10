# Session: 2026-10-10 - initialize project memory

## Intent

Create a durable Codex project structure for restoring project state across sessions.

## Evidence inspected

- Repository root inventory.
- `proposal/robot-proposal.docx` exists.
- No source, test, firmware, CAD, or deployment tree was present at initialization.

## Changes made

- Added root `AGENTS.md` with startup and shutdown protocols.
- Added `.codex/START-HERE.md` and project metadata.
- Added state, knowledge, decision, plan, session, and template directories.
- Added initial status, next actions, and open questions.

## Verification

- Confirmed all expected memory files are present after creation.

## Decisions and updated knowledge

- Repository facts outrank memory files; memory must be refreshed after meaningful changes.
- Stable knowledge, decisions, plans, and session logs are stored separately.

## Blockers

- Proposal requirements and target architecture have not yet been structured.

## Next actions

- Extract the proposal into `.codex/knowledge/requirements.md`.
