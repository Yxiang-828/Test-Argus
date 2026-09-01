# Argus persistence policy

Owner correction, 2026-09-01.

The safety boundary is approval-triggering authority, not GitHub as a category.

## Allowed without asking the owner
- Read public or already-connected approval-free sources.
- Write to the public owner-controlled repository `Yxiang-828/Test-Argus` when the connector performs the write without approval, OAuth, login, connection, permission elevation, or confirmation.
- Use Test-Argus as the durable spillway for scheduled Argus lineages: immutable traces, research archives, compact durable priors, source portfolios, and designated current syntheses.
- Prefer append-only per-run/per-topic files when concurrent writers may exist.

## Forbidden unattended
- Any operation that can surface user/admin approval, confirmation, OAuth, login/connection, installation, permission elevation, purchase, send/post/message, destructive action, or private-repository access gate.
- Writes to private/project repositories merely because GitHub is connected.
- Treating an approval-gated surface as equivalent to the public Test-Argus plane.

## Memory pressure rule
Task prompts are hot batons, not archives. Keep only current hypotheses, unresolved targets, strongest corrections, and pointers. Offload stable lower-priority detail and provenance to Test-Argus before baton growth crowds out current reasoning.

## Provenance
Test-Argus persistence is external durable memory, not ChatGPT native/saved memory. Never claim native-memory persistence from a Test-Argus write.
