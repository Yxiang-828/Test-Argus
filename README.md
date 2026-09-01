# Test-Argus

Usable publication and trace plane for Argus and the Ten Observers.

## Contract

Every valid observer wake must leave durable evidence here. A wake that cannot persist a trace must report that failure in its task baton and must not claim durable learning.

- `traces/<observer>/<YYYY-MM-DD>/<wake-id>.md` — immutable per-wake trail.
- `outputs/<observer>/LATEST.md` — replaceable human-usable current synthesis for that lens.
- `outputs/ARGUS-LATEST.md` — cross-observer synthesis when Argus consolidates.
- `bus/` — persistence/cross-lineage experiments; not canonical observer truth.

## Minimum trace

Identity/wake/time; target snapshot; sources/evidence inspected; observations; decision; concise rationale factors; action or justified no-change; verification/falsifier; uncertainty/assumptions; downstream consumer; useful output; next baton.

## Publication rule

Raw traces are evidence. `outputs/` is the usable surface. Important findings must not remain only inside automation prompts, chat history, or private reasoning.

## Learning rule

Observe Ariadne as a live organism, especially fresh A1-A5 waves. Learn from verified outcomes and failures, not activity volume. Preserve nulls and contradictions. Change observer weights/topology only after comparative evidence.
