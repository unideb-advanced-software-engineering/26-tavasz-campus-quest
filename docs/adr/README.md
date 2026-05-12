# ADRs

Architecture Decision Records live here. Use this file as the routing layer for
architecture context.

Each ADR has YAML front matter with structured navigation metadata. Keep that
front matter and this README in sync when adding, retiring, or changing ADRs.

You can use [`adr-template.md`](./adr-template.md) to create new ADRs.

## Active ADRs

| ADR | Domain | Read when | Related |
| --- | --- | --- | --- |

## Proposed ADRs

| ADR | Domain | Read when | Related |
| --- | --- | --- | --- |

## Retired ADRs

| ADR | Superseded by | Use instead |
| --- | --- | --- |

## AI Navigation Rules

- Start from this README instead of scanning every ADR.
- Read the smallest cluster that matches the task, then follow `related_adrs`
  from the ADR front matter only when the change crosses boundaries.
- Treat `superseded` ADRs as historical context. Follow `superseded_by` before
  making current architecture claims.
- Use `related_docs` front matter to find conventions, specs, diagrams, and
  package docs that govern implementation details.
- When adding or retiring an ADR, update the ADR YAML front matter and this
  README in the same change.

## Lifecycle

- `active/`: currently accepted ADRs.
- `retired/`: superseded ADRs kept for historical context.
