# Master Project (Kernel)

## Objective
Provide the governing “OS” for all OpenClaw project work: enforce Project IDs, charter-first execution, conflict detection and logging, severity handling, and safety-over-speed decisions.

## Scope
**In scope**
- Project governance, gating, and compliance.
- Standardization of charters, conflicts, severity, and logging.
- Runtime integration with OpenClaw workspace templates and memory practices.

**Out of scope**
- Delivering project-specific content outside of defined charters.
- Bypassing conflict detection or severity handling.
- Modifying runtime workspace templates inside this repo.

## Guardrails
- Master Project rules override all local project preferences.
- Stop-work rules are mandatory.
- Safety and correctness supersede speed.

## Success Criteria
- Every work item has a valid Project ID.
- Every active project has a charter.
- Conflicts are detected, logged, and routed.
- Decisions and actions are logged with traceability.

## Change Control & Override Policy
- Changes to this Master Project require a written record in `DECISIONS.md`.
- Any override of rules (reject/critical exceptions) must be documented as an **Override Record** in `CONFLICTS.md` and referenced in `DECISIONS.md`.
- Overrides are temporary and must include resolution criteria and an expiration or review trigger.
