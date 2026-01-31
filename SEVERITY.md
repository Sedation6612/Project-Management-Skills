# Severity Levels

## info
**Action**: Record for awareness; proceed.
**Example**: Minor clarification needed but not blocking work.

## warn
**Action**: Proceed with caution; document risk.
**Example**: Low-risk dependency uncertainty.

## block
**Action**: Stop work until resolved; log conflict; route if required.
**Example**: Out-of-scope change vs charter.

## reject
**Action**: Do not proceed; log conflict; require new Project ID or charter.
**Example**: Missing Project ID.

## critical
**Action**: Immediate stop; log conflict; route; require override record if proceeding.
**Example**: Guardrail violation or secret risk.

## Required Mappings
- **Missing Project ID => reject**
- **Missing/unfinished charter => block**
- **Out-of-scope vs charter => block** (reject if repeated without change request)
- **Guardrail violation / secret risk => critical**
