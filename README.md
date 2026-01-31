# Project Management Skills (Markdown-Only)

This repository provides **Project Management Skills**, a **Markdown-only skill** that implements a governed “Operating System” for OpenClaw: mandatory Project IDs, a Master Project (kernel), charter-first workflow, conflict detection + logging, severity levels, and safety-over-speed execution. It also **integrates with OpenClaw runtime workspace files** by instructing OpenClaw how to read/write them at boot and when learning or remembering. This repo does not include BOOT/AGENTS/SOUL/TOOLS/HEARTBEAT; it instructs OpenClaw how to update them in its workspace.

## Contents
- [SKILL.md](SKILL.md) — Skill entry point with triggers, quickstart, commandments, and safety rules.
- [WORKFLOW.md](WORKFLOW.md) — Canonical governed workflow gates.
- [MASTER.md](MASTER.md) — Master Project (kernel) definition and override policy.
- [DEFINITIONS.md](DEFINITIONS.md) — Canonical definitions for governance terms.
- [SEVERITY.md](SEVERITY.md) — Severity ladder with required actions and mappings.
- [PROJECTS.md](PROJECTS.md) — Project registry cache (updated by OpenClaw).
- [CHARTERS.md](CHARTERS.md) — All project charters live here (cache).
- [CONFLICTS.md](CONFLICTS.md) — Conflict inbox + archive (cache).
- [ROUTING.md](ROUTING.md) — Manual messenger payload template.
- [DECISIONS.md](DECISIONS.md) — Append-only decision log (cache).
- [LOG.md](LOG.md) — Append-only activity log (cache).
- [TEMPLATES.md](TEMPLATES.md) — Copy/paste templates for intake, charter, conflicts, and more.
- [RUNTIME_INTEGRATION.md](RUNTIME_INTEGRATION.md) — How OpenClaw must read/write workspace templates and memory files at runtime.
