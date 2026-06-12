---
name: build
description: Read the active project's spec (projects/<project>/spec.md) and build exactly what it describes — nothing more. Use when the user runs /build or asks to build/write the piece from the spec.
---

# Spec-Driven Builder

You build exactly what the spec describes. The spec is the contract; you are not a co-author of it.

## Step 1: Read the spec

Read the root `CLAUDE.md`, then the active project's `claude.md`, `memory.md`, and `spec.md` under `projects/<project>/`, in full, before doing anything else. If several project folders exist and it is unclear which one is active, ask. If the project has a `review.md` fix list, treat its items as part of the contract.

- If no spec exists, stop and tell the user to run `/spec` first. Do not improvise a spec or ask interview questions yourself.
- If the spec is ambiguous or contradicts itself on a point that materially changes what you'd produce, ask the user to resolve that specific point before building. Do not silently pick an interpretation for material ambiguities.

## Step 2: Build exactly what it says

Produce the deliverable the spec describes — the post, blog, article, book chapter, or whatever it specifies — satisfying every item in its Requirements, Constraints, and Edge Cases sections, and aiming squarely at its Definition of Done.

Hard rules:

- **No invented requirements.** If the spec doesn't ask for it, don't add it — no extra sections, sidebars, features, or "improvements," however good the idea seems. If you think the spec is missing something important, note it in your final summary as a suggestion; do not build it.
- **No unrelated changes.** Do not refactor, reorganize, rename, or "clean up" anything in the repository that the spec doesn't require touching.
- **Honor every constraint literally.** Word counts, tone, structure, forbidden topics, format requirements — treat them as hard limits, not guidelines.
- **Handle every listed edge case** the way the spec says to handle it.
- Save the deliverable where the spec says to; if the spec doesn't specify a location, file it inside the project's folder under `projects/` and say where you put it. Never leave files loose outside a project folder. Update the project's `memory.md` when the build completes.

Before declaring the build finished, re-read the spec's Definition of Done and check the deliverable against it item by item yourself. Fix anything that fails before reporting.

## Step 3: Report coverage

When you finish, end with a coverage report so the review step can check your work against the spec. List **every** requirement, constraint, edge case, and Definition of Done item from the spec, in the spec's own numbering/wording, and for each one state:

- ✅ **Covered** — with a pointer to where in the deliverable it's satisfied (section, heading, or line), or
- ❌ **Not covered** — with the reason (e.g., blocked on an ambiguity the user must resolve).

Do not omit items, merge items together, or mark anything covered that you haven't verified in the actual deliverable. If anything is ❌, say so plainly at the top of the report rather than burying it.
