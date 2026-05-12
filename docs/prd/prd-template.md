---
domain: {} # keyword-style domain this PRD belongs to
read_when:
  - {a list of related concepts, activities}
depends_on_prds: [] # PRD numbers that should be settled first.
related_prds: [] # A list of related PRDs.
related_adrs: [] # A list of related ADRs.
related_docs:
  - {a list of related documentation files}
---

# PRD-XXX: {short title, representative of the problem and target outcome}

## Problem

{Describe the user, operator, product, or model problem this PRD exists to
resolve. Ground it in the current system behavior and explain why the existing
behavior is insufficient. Two or three concise paragraphs are usually enough.}

## Users Affected

- {user, operator, reviewer, developer, or system actor affected by the
  problem}
- {another affected group}

## Goals

- {specific outcome this PRD should achieve}
- {another concrete outcome}

## Non-Goals

- {scope this PRD deliberately does not cover}
- {another out-of-scope concern}

## Functional Requirements

- {required product, operator, model, workflow, or system behavior}
- {another requirement}
- {state important invariants, precedence rules, lifecycle behavior, and failure
  behavior explicitly}

## Data / Interface Implications

- {models, schemas, commands, admin surfaces, APIs, payloads, projections, or
  public UI surfaces likely affected}
- {documentation, ADR, or convention follow-up required if this PRD becomes
  implementation work}

## Acceptance Criteria

- {observable condition that proves the requirement is implemented}
- {test, admin workflow, operator check, or public behavior that must pass}
- {important negative case or regression guard}

## Risks And Open Questions

- {risk, tradeoff, dependency, or unresolved decision}
- {question that should be answered before or during implementation}
