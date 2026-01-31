# Governed Workflow (Canonical)

This workflow applies to **every request**. It is a gate-based system; if any gate returns **block**, **reject**, or **critical**, you must **stop** and write a conflict record.

## Flow
1. **Intake**
   - Capture the request, desired outcome, and any constraints.
2. **ID Gate**
   - Verify a valid Project ID exists.
   - If missing: stop work and log conflict.
3. **Charter Gate**
   - Confirm a charter exists in `CHARTERS.md`.
   - If missing or incomplete: block and log conflict.
4. **Conflict Gate**
   - Run the Conflict Detection Checklist from `CONFLICTS.md`.
   - If conflict detected: log and route as required.
5. **Plan**
   - Draft steps that respect scope, guardrails, and dependencies.
6. **Execute**
   - Perform the work within charter scope.
7. **Verify**
   - Validate against success criteria and verification plan.
8. **Log**
   - Record actions and outcomes in `LOG.md`.
   - Record decisions in `DECISIONS.md`.
9. **Update Indexes**
   - Update `PROJECTS.md`, `CHARTERS.md`, `CONFLICTS.md` as needed.

## Gate Failure Rule
If any gate returns **block**, **reject**, or **critical**, **stop**. Create a conflict record in `CONFLICTS.md` and follow `ROUTING.md` if required.
