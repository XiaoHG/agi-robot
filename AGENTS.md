# Desktop Entertainment Robot Project

This file is the entry point for Codex sessions working in this repository.

## Session startup protocol

Before making changes:

1. Read `.codex/START-HERE.md`.
2. Read `.codex/state/current-status.md` and `.codex/state/next-actions.md`.
3. Read the relevant files under `.codex/knowledge/`, `.codex/decisions/`, and `.codex/plans/` for the requested task.
4. Inspect the actual repository and verify that the recorded state is still true.

After making changes:

1. Update `.codex/state/current-status.md` with verified progress and blockers.
2. Update `.codex/state/next-actions.md` with concrete next actions.
3. Record durable technical facts in `.codex/knowledge/` and important choices in `.codex/decisions/`.
4. Append a concise entry to `.codex/sessions/` for substantial work.

Do not treat memory files as authoritative over the filesystem. Resolve conflicts in favor of observed repository facts, then update the memory.

## Project scope

This is a desktop entertainment robot development project. The proposal currently lives at `proposal/robot-proposal.docx`. Source code, hardware notes, firmware, application software, tests, and deployment material may be added over time.
