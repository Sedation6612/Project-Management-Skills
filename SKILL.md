---
name: project-management-skills
description: A governed operating system for OpenClaw with charter-first work, conflict detection, severity handling, and runtime memory integration.
---

# Project Management Skills

## Trigger Conditions
Use this skill whenever:
- The request involves project work, planning, delivery, or changes that can impact scope, safety, or governance.
- A Project ID is required or missing.
- Conflicts, uncertainty, or policy violations are possible.
- You must coordinate memory/continuity across sessions.

## Quickstart Checklist
1. Identify or request the **Project ID**.
2. Confirm a **charter** exists in `CHARTERS.md`.
3. Load caches: `PROJECTS.md`, `CONFLICTS.md`, `CHARTERS.md`, `DECISIONS.md`, `LOG.md`.
4. Run the **Conflict Detection Checklist**.
5. Proceed only if gates pass; otherwise log conflict and stop.
6. Execute the governed workflow in `WORKFLOW.md`.
7. Log outcomes in `LOG.md`, decisions in `DECISIONS.md`.
8. Update runtime workspace files per `RUNTIME_INTEGRATION.md`.

## The 9 Setup Commandments (Stop-Work Rules)
**C1 Lock project isolation:** every unit of work belongs to exactly one Project ID.
**C2 Master Project as OS/kernel governs all projects.**
**C3 Charter first:** no charter, no work.
**C4 No Project ID, no work:** missing ID = stop.
**C5 Conflict detection:** run gates; conflicts can block.
**C6 Conflicts become logs:** every conflict is recorded.
**C7 Conflicts routed to messenger:** provide manual copy/paste payload.
**C8 Severity defined up front:** info, warn, block, reject, critical.
**C9 Kill fast-but-wrong:** if uncertain, add checks or record unknowns—never guess.

## Core References
- Workflow: [WORKFLOW.md](WORKFLOW.md)
- Runtime integration: [RUNTIME_INTEGRATION.md](RUNTIME_INTEGRATION.md)

## Safety & Trust Warning
Safety and correctness override speed. If uncertain, **stop**, document unknowns, and escalate or request clarification rather than guessing.
