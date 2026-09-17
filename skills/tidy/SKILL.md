---
name: tidy
description: Refine implemented code around architecture, business rules, and root causes while preserving established agreements.
---

# Tidy

Rework the current implementation into a coherent part of the system. Make the changes warranted by these principles:

- **Preserve established agreements.** Honor agreed requirements, design decisions, and accepted tradeoffs. Refactoring does not reopen settled decisions. Revisit them only when new evidence or changed conditions materially affect their basis; surface the conflict before departing from the agreement.
- **Business semantics govern behavior.** Express domain rules and invariants directly. Preserve intended behavior and contracts; accidental behavior introduced by the implementation is not a requirement.
- **Architecture governs ownership.** Put behavior where its responsibility belongs. Keep dependencies and sources of truth coherent. Reconsider a boundary when it causes the problem.
- **Fix causes at their source.** Resolve the faulty rule, assumption, state model, or interaction. Avoid special cases, duplicated checks, silent fallbacks, and compensating logic that merely conceal the defect. Keep exceptions that represent real business requirements.
- **Prefer the simplest complete design.** Remove redundant paths, obsolete scaffolding, and unnecessary indirection. Let actual requirements justify abstractions and compatibility logic.
- **Keep scope proportional.** Address the current work and the causes it touches. Preserve unrelated changes and explicit constraints. Leave sound code alone; avoid speculative redesign.
- **Judge correctness by outcomes.** Ground confidence in intended behavior, domain invariants, and relevant regression evidence. Passing checks alone does not establish a coherent design.
